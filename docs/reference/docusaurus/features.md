---
title: Documentation Features and Capabilities
sidebar_label: Features
description: Explores some of the features of Docusaurus in a visual manner
last_update: 
  date: '03 Jul 2022'
  author: Daniel Farlow
tags: [Docusaurus]
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import ImageSwitcher from '@site/src/components/ImageSwitcher';
import PartialExample from '@site/docs/_Partials/_markdown-partial-example.md';
import ExportCustomToolbar from '@site/src/components/CustomToolbar';
import VideoContent from '@site/src/components/VideoContent';
import ReactPlayer from 'react-player';
import AcUnitIcon from '@mui/icons-material/AcUnit';
import { orange } from '@mui/material/colors';
import Pseudocode from '@site/src/components/Pseudocode';

import sampleTextStyle from '!!raw-loader!@site/src/components/_PseudocodesSamples/_test-text-style.tex';
import sampleTestAtoms from '!!raw-loader!@site/src/components/_PseudocodesSamples/_test-atoms.tex';
import sampleTestControlBlocks from '!!raw-loader!@site/src/components/_PseudocodesSamples/_test-control-blocks.tex';
import sampleTestStatementsAndComments from '!!raw-loader!@site/src/components/_PseudocodesSamples/_test-statements-and-comments.tex';
import sampleQuicksort from '!!raw-loader!@site/src/components/_PseudocodesSamples/_test-quicksort.tex';

## Math

See the [KaTeX](./katex) reference below to understand the full scope of what math can be typeset, but the very basics appear immediately below.

### Inline math

Inline math like $\sin(x^2)$ can be easily typset by `$\sin(x^2)$`.

### Display math

**Input:**

```latex
$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a};\quad \{x \mid ax^2+bx+c = 0 \}
$$
```

**Output:**

$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a};\quad \{x \mid ax^2+bx+c = 0 \}
$$

### Math Macros

Math macros like

```js title="docusaurus.config.js"
const macros = {
	'\\x': 'x+1',
};
```

can be defined so that something like `$\x$` can be used as a shortcut for $\x$.


## Code Blocks

### Syntax highlighting

Syntax highlighting is supported for various languages. Docusaurus comes with some [common languages](https://github.com/FormidableLabs/prism-react-renderer/blob/master/src/vendor/prism/includeLangs.js) supported out of the box, but this site supports syntax highlighting for several more languages:

<details><summary> Supported Languages</summary>

The keys for providing code blocks in the implied language are provided below:

- `apacheconf`
- `applescript`
- `asciidoc`
- `aspnet`
- `awk`
- `bash`
- `basic`
- `c`
- `clojure`
- `cpp`
- `csharp`
- `css`
- `csv`
- `django`
- `docker`
- `editorconfig`
- `ejs`
- `elixir`
- `erlang`
- `excel-formula`
- `flow`
- `fortran`
- `git`
- `go`
- `go-module`
- `graphql`
- `handlebars`
- `http`
- `java`
- `javadoclike`
- `javascript`
- `js-extras`
- `jsdoc`
- `json`
- `jsonp`
- `jsx`
- `latex`
- `less`
- `lisp`
- `log`
- `lua`
- `makefile`
- `markdown`
- `markup`
- `markup-templating`
- `mermaid`
- `mongodb`
- `nginx`
- `perl`
- `php`
- `php-extras`
- `phpdoc`
- `plsql`
- `powerquery`
- `powershell`
- `pug`
- `python`
- `r`
- `regex`
- `ruby`
- `rust`
- `sas`
- `sass`
- `scheme`
- `scss`
- `shell-session`
- `sql`
- `systemd`
- `toml`
- `tsx`
- `turtle`
- `typescript`
- `vim`
- `visual-basic`
- `wasm`
- `wiki`
- `wolfram`
- `yaml`

</details>

### Titled code blocks

Code blocks can optionally have titles at the top of the code block (usually the file name for where the code is located):

```jsx title="/src/someFile.jsx"
function HelloCodeTitle(props) {
	return <h1>Hello, {props.name}</h1>;
}
```

### Line highlighting

#### Highlighting with comments

You can use comments with `highlight-next-line`, `highlight-start`, and `highlight-end` to select which lines are highlighted.

**Input:**

````md
```js
function HighlightSomeText(highlight) {
	if (highlight) {
		// highlight-next-line
		return 'This text is highlighted!';
	}

	return 'Nothing highlighted';
}

function HighlightMoreText(highlight) {
	// highlight-start
	if (highlight) {
		return 'This range is highlighted!';
	}
	// highlight-end

	return 'Nothing highlighted';
}
```
````

**Output:**

```js
function HighlightSomeText(highlight) {
	if (highlight) {
		// highlight-next-line
		return 'This text is highlighted!';
	}

	return 'Nothing highlighted';
}

function HighlightMoreText(highlight) {
	// highlight-start
	if (highlight) {
		return 'This range is highlighted!';
	}
	// highlight-end

	return 'Nothing highlighted';
}
```

#### Highlighting with metadata string

You can also specify highlighted line ranges within the language meta string (leave a space after the language). To highlight multiple lines, separate the line numbers by commas or use the range syntax to select a chunk of lines. This feature uses the parse-number-range library and you can find [more syntax](https://www.npmjs.com/package/parse-numeric-range) on their project details.

**Input:**

````md
```jsx {1,4-6,11}
import React from 'react';

function MyComponent(props) {
	if (props.isBar) {
		return <div>Bar</div>;
	}

	return <div>Foo</div>;
}

export default MyComponent;
```
````

**Output:**

```jsx {1,4-6,11}
import React from 'react';

function MyComponent(props) {
	if (props.isBar) {
		return <div>Bar</div>;
	}

	return <div>Foo</div>;
}

export default MyComponent;
```

#### Error blocks

You can also highlight error blocks by using [magic comments](https://docusaurus.io/docs/markdown-features/code-blocks#custom-magic-comments). For example, in JavaScript, trying to access properties on `null` will error.

```js
const name = null;
// highlight-error-next-line
console.log(name.toUpperCase());
// Uncaught TypeError: Cannot read properties of null (reading 'toUpperCase')
```

### Line numbering

You can enable line numbering for your code block by using the `showLineNumbers` key within the language meta string (just don't forget to add space directly before the key).

**Input:**

````md
```jsx {1,4-6,11} showLineNumbers
import React from 'react';

function MyComponent(props) {
	if (props.isBar) {
		return <div>Bar</div>;
	}

	return <div>Foo</div>;
}

export default MyComponent;
```
````

**Output:**

```jsx {1,4-6,11} showLineNumbers
import React from 'react';

function MyComponent(props) {
	if (props.isBar) {
		return <div>Bar</div>;
	}

	return <div>Foo</div>;
}

export default MyComponent;
```

### Multi-language support code blocks

As the [Docusaurus docs note](https://docusaurus.io/docs/markdown-features/code-blocks#multi-language-support-code-blocks), with MDX, you can easily create interactive components within your documentation (e.g., to display code in multiple programming languages and switch between them using a tabs component).

Instead of implementing a dedicated component for multi-language support code blocks, a general-purpose `<Tabs>` component in the classic theme so that you can use it for other non-code scenarios as well. The following example is how you can have multi-language code tabs in your docs. Note that the empty lines above and below each language block are _intentional_. This is a current limitation of MDX: you have to leave empty lines around Markdown syntax for the MDX parser to know that it's Markdown syntax and not JSX.

**Input:**

````jsx
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
<TabItem value="js" label="JavaScript">

```js
function helloWorld() {
  console.log('Hello, world!');
}
```

</TabItem>
<TabItem value="py" label="Python">

```py
def hello_world():
  print("Hello, world!")
```

</TabItem>
<TabItem value="java" label="Java">

```java
class HelloWorld {
  public static void main(String args[]) {
    System.out.println("Hello, World");
  }
}
```

</TabItem>
</Tabs>
````

**Output:**

```mdx-code-block
<BrowserWindow>
<Tabs>
<TabItem value="js" label="JavaScript">
```

```js
function helloWorld() {
	console.log('Hello, world!');
}
```

```mdx-code-block
</TabItem>
<TabItem value="py" label="Python">
```

```py
def hello_world():
  print("Hello, world!")
```

```mdx-code-block
</TabItem>
<TabItem value="java" label="Java">
```

```java
class HelloWorld {
  public static void main(String args[]) {
    System.out.println("Hello, World");
  }
}
```

```mdx-code-block
</TabItem>
</Tabs>
</BrowserWindow>
```

#### Default tab

As noted in the [Docusaurus docs](https://docusaurus.io/docs/markdown-features/tabs#displaying-a-default-tab), the first tab is displayed by default, and to override this behavior, you can specify a default tab by adding `default` to one of the tab items. You can also set the `defaultValue` prop of the `Tabs` component to the label value of your choice.

Docusaurus will throw an error if a `defaultValue` is provided for the `Tabs` but it refers to a non-existing value. If you want none of the tabs to be shown by default, use `defaultValue={null}`:

<Tabs defaultValue={null}>
<TabItem value="js" label="JavaScript">

```js
function helloWorld() {
	console.log('Hello, world!');
}
```

</TabItem>
<TabItem value="py" label="Python">

```py
def hello_world():
  print("Hello, world!")
```

</TabItem>
</Tabs>

But you can add the `default` to a tab other than the first one (usually the default) if desired:

<Tabs>
<TabItem value="js" label="JavaScript">

```js
function helloWorld() {
	console.log('Hello, world!');
}
```

</TabItem>
<TabItem value="py" label="Python" default>

```py
def hello_world():
  print("Hello, world!")
```

</TabItem>
</Tabs>

#### Syncing tab choices

You may want choices of the same kind of tabs to sync with each other. For example, you might want to provide different instructions for users on Windows vs users on macOS, and you want to change all OS-specific instructions tabs in one click. To achieve that, you can give all related tabs the same `groupId` prop. Note that doing this will persist the choice in `localStorage` and all `<Tab>` instances with the same `groupId` will update automatically when the value of one of them is changed. Note that group IDs are globally namespaced.

**Input:**

```jsx
// highlight-next-line
<Tabs groupId="operating-systems">
  <TabItem value="win" label="Windows">Use Ctrl + C to copy.</TabItem>
  <TabItem value="mac" label="macOS">Use Command + C to copy.</TabItem>
</Tabs>

// highlight-next-line
<Tabs groupId="operating-systems">
  <TabItem value="win" label="Windows">Use Ctrl + V to paste.</TabItem>
  <TabItem value="mac" label="macOS">Use Command + V to paste.</TabItem>
</Tabs>
```

**Output:**

```mdx-code-block
<BrowserWindow>
  <Tabs groupId="operating-systems">
    <TabItem value="win" label="Windows">Use Ctrl + C to copy.</TabItem>
    <TabItem value="mac" label="macOS">Use Command + C to copy.</TabItem>
  </Tabs>

  <Tabs groupId="operating-systems">
    <TabItem value="win" label="Windows">Use Ctrl + V to paste.</TabItem>
    <TabItem value="mac" label="macOS">Use Command + V to paste.</TabItem>
  </Tabs>
</BrowserWindow>
```

For all tab groups that have the same `groupId`, the possible values do not need to be the same. If one tab group is chosen a value that does not exist in another tab group with the same `groupId`, the tab group with the missing value won't change its tab. You can see that from the following example. Try to select Linux, and the above tab groups don't change.

```jsx
<Tabs groupId="operating-systems">
	<TabItem value="win" label="Windows">
		I am Windows.
	</TabItem>
	<TabItem value="mac" label="macOS">
		I am macOS.
	</TabItem>
	<TabItem value="linux" label="Linux">
		I am Linux.
	</TabItem>
</Tabs>
```

```mdx-code-block
<BrowserWindow>
  <Tabs groupId="operating-systems">
    <TabItem value="win" label="Windows">I am Windows.</TabItem>
    <TabItem value="mac" label="macOS">I am macOS.</TabItem>
    <TabItem value="linux" label="Linux">I am Linux.</TabItem>
  </Tabs>
</BrowserWindow>
```

---

Tab choices with different group IDs will not interfere with each other:

```jsx
// highlight-next-line
<Tabs groupId="operating-systems">
  <TabItem value="win" label="Windows">Windows in windows.</TabItem>
  <TabItem value="mac" label="macOS">macOS is macOS.</TabItem>
</Tabs>

// highlight-next-line
<Tabs groupId="non-mac-operating-systems">
  <TabItem value="win" label="Windows">Windows is windows.</TabItem>
  <TabItem value="unix" label="Unix">Unix is unix.</TabItem>
</Tabs>
```

```mdx-code-block
<BrowserWindow>
  <Tabs groupId="operating-systems">
    <TabItem value="win" label="Windows">Windows in windows.</TabItem>
    <TabItem value="mac" label="macOS">macOS is macOS.</TabItem>
  </Tabs>

  <Tabs groupId="non-mac-operating-systems">
    <TabItem value="win" label="Windows">Windows is windows.</TabItem>
    <TabItem value="unix" label="Unix">Unix is unix.</TabItem>
  </Tabs>
</BrowserWindow>
```

## Algorithm Pseudocode

Pseudocode similar to that found in CLRS can be typeset.

### Test text style

<Pseudocode
	content={sampleTextStyle}
	algID="text-style"
	options={{ lineNumber: true }}
/>

### Test atoms

<Pseudocode
	content={sampleTestAtoms}
	algID="atoms"
	options={{ lineNumber: true, captionCount: 1 }}
/>

### Test control blocks

<Pseudocode
	content={sampleTestControlBlocks}
	algID="control-blocks"
	options={{ lineNumber: true, captionCount: 2 }}
/>

### Test statements and comments

<Pseudocode
	content={sampleTestStatementsAndComments}
	algID="statements-and-comments"
	options={{ lineNumber: true, captionCount: 3 }}
/>

### Quicksort

<Pseudocode
	content={sampleQuicksort}
	algID="quicksort"
	options={{ lineNumber: true, captionCount: 4 }}
/>

## Admonitions

The following "admonitions" can help highlight different elements of the page.

:::note

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::

:::tip

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::

:::info

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::

:::caution

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::

:::danger

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::

## Video Content

### Single Video

A video can be embedded as part of an admonition:

<VideoContent type="note" videoUrls={['https://www.youtube.com/embed/XV-u_Ow47s0']}>

The content in this guide may be helpful. Wow this is not good. But some more wrap.

</VideoContent>

### Multiple Videos

More than one video can be embedded as part of an admonition:

<VideoContent type="caution" title="something cool and something nice" videoUrls={["https://www.youtube.com/embed/cN9c_JyvL1A", "https://www.youtube.com/embed/XV-u_Ow47s0"]}>

This content in this guide is also available in video format. We know $f(x)=\sin(x)$.

</VideoContent>

### Watch Video Directly

Videos can be embedded in the page for viewing _outside of admonitions_:

<div className="player-wrapper">
	<ReactPlayer
		width="100%"
		height="100%"
		className="react-player"
		controls={true}
		playing={false}
		loop={false}
		volume={1}
		muted={false}
		url="https://www.youtube.com/watch?v=8aGhZQkoFbQ"
	/>
</div>

## Images

Centered image:

<p align="center">
	<img width="200px" src="/img/experiment.png" />
</p>

## Block Content

Content can be highlighted on a single line:

> Single line

Or multiple lines:

> Line 1
>
> Line 2
>
> Line 3

## Material-UI

Content/components from other frameworks can be used such as the `DataGrid` component from Material-UI:

<ExportCustomToolbar />

## Icons

Icons can be used: <AcUnitIcon className='material-icon' sx={{ color: orange[500] }} />

## Partials

Partials from other files can be used.

<PartialExample name="time and space complexity" />

## Dark Mode and Light Mode Dependence

Items can be made to appear or disappear based on light or dark mode selection (such as the image below):

<ImageSwitcher
	lightImageSrc="https://picsum.photos/300"
	darkImageSrc="https://picsum.photos/300"
/>