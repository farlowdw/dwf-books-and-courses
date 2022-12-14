---
title: Nand to Tetris
hide_title: false
sidebar_label: Overview
description: Introduction to Nand to Tetris
draft: false
tags: [NandToTetris]
keywords: [tbd]
image: https://github.com/farlowdw.png
hide_table_of_contents: false
toc_min_heading_level: 2
toc_max_heading_level: 5
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import VideoContent from '@site/src/components/VideoContent';

## Overview

## Tips and tricks

On a Mac, an `.sh` file accepts the `-h` flag for help. For example, 

```bash
~/Desktop/nand2tetris/tools/HardwareSimulator.sh -h
```

returns the following:

```
Usage:
    HardwareSimulator.sh             Starts the Hardware Simulator in
                                     interactive mode.
    HardwareSimulator.sh FILE.tst    Starts the Hardware Simulator and runs the
                                     FILE.tst test script.  The success/failure
                                     message is printed to the command console.
```

## Software

### macOS

Go to the [software page](https://www.nand2tetris.org/software) and click the [download the Nand2tetris Software Suite](https://drive.google.com/open?id=1xZzcMIUETv3u3sdpM_oTJSTetpVee3KZ) Version 2.6 link. The [Setup Guide for Apple MacOS](https://drive.google.com/file/d/1QDYIvriWBS_ARntfmZ5E856OEPpE4j1F/view) will be helpful. Below are details concerning my experience.

I already had Java installed from previous use (confirmed via `java -version`). I did as instructed and moved the extracted files from the `.zip` folder to my Desktop, but the goal in using something like 

```bash
~/Desktop/nand2tetris/tools/HardwareSimulator.sh
```

is longer possible because the `.sh` file is not executable. To resolve this issue, we can [make each `.sh` file executable](https://askubuntu.com/a/229592/958617) by issuing the following command from within the `tools` directory:

```bash title="~/Desktop/nand2tetris/tools"
chmod +x *.sh
```

Now each `.sh` file should be executable and something like

```bash
~/Desktop/nand2tetris/tools/HardwareSimulator.sh
```

should now run. It is possible you could get an error about [the Times font no longer being available](https://stackoverflow.com/a/68609803/5209533), but you can [download and install it](https://www.freebestfonts.com/timr45w-font) without issue.

### Compiling `.jack` files

Unlike the simulators, which feature an interactive user interface, the Jack Compiler is a terminal-oriented application. In order to run it, you must supply the name of the file or folder that you wish to compile. For example, suppose you wish to compile all `.jack` files stored in the folder `projects/09/Square` (that's a folder called `Square`, located in the `09` folder, which is located in the `projects` folder). To do so, open a Terminal window and type:

```bash
JackCompiler.sh ~/Desktop/nand2tetris/projects/09/Square
```

This results in either a successful compilation of the `.jack` files in `Square`, or some compilation errors.

### About the software

The Nand2tetris Software Suite consists of two directories: *projects*, and *tools*.

#### `projects` folder

The `projects` directory is divided into 14 project directories named `00`, `01`, ..., `13` (of which project `00` is relevant only to learners who take the course in Coursera, and project `13` is open-ended). These directories contain files that you have to modify and complete as you work on various nand2tetris projects.

#### `tools` folder

The `tools` directory contains the nand2tetris software tools. It's a collection of programs and files that will be explained as you follow the various projects.

#### Software reference

The remainder of this section should be used as reference; there is no need to read what follows until you will be asked to use a particular software tool.

The `.bat` and `.sh` files are batch and script files, used to invoke the nand2tetris software tools. These files are explained in detail below.

The `bin` directory contains the code of the nand2tetris software tools. It consists of several subdirectories containing Java class files and supporting files.

The `builtInChips` and the `builtInVMCode` directories contain files that are used by the supplied Hardware Simulator and VM Emulator, respectively.

The `OS` directory contains a compiled version of the Jack operating system.

### Software tool descriptions and tutorials

The Nand to tetris Software Suite features the following software tools:

| Tool | Description | Test Scripts |
| :-- | :-- | :-- |
| Hardware Simulator | Simulates and tests logic gates and chips implemented in the HDL (Hardware Description Language) described in the book. Used in hardware construction projects. -> [Tutorial](https://www.nand2tetris.org/_files/ugd/44046b_bfd91435260748439493a60a8044ade6.pdf) | [Simulating a Xor gate](https://www.nand2tetris.org/software?lightbox=dataItem-ja8c9qhk); [Running a test script](https://www.nand2tetris.org/software?lightbox=dataItem-ja8c9qhl); [Simulating the topmost Computer chip](https://www.nand2tetris.org/software?lightbox=dataItem-ja8c9qhl1) |
| CPU Emulator | Emulates the operation of the Hack computer system. Used to test and run programs written in the Hack machine language, in both its binary and assembly versions. -> [Tutorial](https://www.nand2tetris.org/_files/ugd/44046b_f63aba2611944e82974c9c5d5a3821fe.pdf) | [Running a machine language program that draws a rectangle on the computer screen](https://www.nand2tetris.org/software?lightbox=dataItem-j9cwy0cn) |
| VM Emulator | Emulates the operation of our virtual machine (similar to Java's JVM); used to run and test programs written in the VM language (similar to Java's Bytcode). -> [Tutorial](https://www.nand2tetris.org/_files/ugd/44046b_b74d071ee4b74279b211acede232ced9.pdf) | [Running a VM program](https://www.nand2tetris.org/software?lightbox=dataItem-j9d33lz0) |
| Assembler | Translates programs from the Hack assembly language to Hack binary code. The resulting code can be executed directly on the Computer chip (in the hardware simulator), or emulated on the supplied CPU Emulator (much faster and more convenient). -> [Tutorial](https://www.nand2tetris.org/_files/ugd/44046b_759f4f811ad14e12ac45bc60dd679fa3.pdf) | [Translating](https://www.nand2tetris.org/software?lightbox=dataItem-j9d3e5jd); [Using a compare file](https://www.nand2tetris.org/software?lightbox=dataItem-j9d3e5je) |
| Compiler | Translates programs written in Jack (a simple, Java-like object-based language) into VM code. The resulting code can run on the supplied VM Emulator. Alternatively, the VM code can be translated further by the supplied VM translatorinto Hack assembly code that can then be executed on the supplied CPU Emulator. | (A GUI-less, command-level program) |
| Operating system | Two OS implementations are supplied: (i) a collection of eight .vm class files, written originally in Jack (just like Unix is written in C), and (ii) a faster implementation of all the OS services, embedded in the supplied VM Emulator. | (GUI-less) |
| Text Comparer | This utility checks if two input text files are identical, up to white space differences. Used in various projects. In Unix use `diff` instead. | (A GUI-less, command-level program) |

### Test script illustrations

#### Hardware simulator

##### Simulating a XOR gate

<p align='center'>
  <img width='800px' src={require('@site/static/img/books/nand-to-tetris/test-scripts/hs-f1.gif').default} />
</p>

##### Running a test script

<p align='center'>
  <img width='800px' src={require('@site/static/img/books/nand-to-tetris/test-scripts/hs-f2.gif').default} />
</p>

##### Simulating the topmost Computer chip

<p align='center'>
  <img width='800px' src={require('@site/static/img/books/nand-to-tetris/test-scripts/hs-f3.gif').default} />
</p>

#### CPU Emulator

##### Running a machine language program that draws a rectangle on the computer screen

<p align='center'>
  <img width='800px' src={require('@site/static/img/books/nand-to-tetris/test-scripts/cpuem-f1.gif').default} />
</p>

#### VM Emulator

##### Running a VM program

<p align='center'>
  <img width='800px' src={require('@site/static/img/books/nand-to-tetris/test-scripts/vmem-f1.gif').default} />
</p>

#### Assembler

##### Translating

<p align='center'>
  <img width='800px' src={require('@site/static/img/books/nand-to-tetris/test-scripts/ass-f1.gif').default} />
</p>

##### Using a compare file

<p align='center'>
  <img width='800px' src={require('@site/static/img/books/nand-to-tetris/test-scripts/ass-f2.gif').default} />
</p>

## Demos

### Hardware Simulator: First Look

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/FW6Z_Xp2v-c'
  ]}
>

First look at the Nand to Tetris hardware simulator. This demo illustrates how to load a chip specification (HDL file / program), and how to evaluate the chip by changing the values of its input pins and observing the resulting values of its output pins. Two kinds of chips are illustrates: a chip that operates on 1-bit inputs, and another chip that operates on 16-bit inputs (also known as "buses").

</VideoContent>

### HDL-Based Chip Simulation

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/iSNfqzJUWW4'
  ]}
>

Illustrates how to edit, load, and interact with a chip specification (HDL file / program), using the Nand to Tetris hardware simulator. Also demonstrates how to use chip-parts that were not yet implemented, using built-in chips in their stead.

</VideoContent>

### Script-Based Chip Simulation

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/d0X0dMMUt1U'
  ]}
>

Illustrates how to test a chip specification (HDL program / file) in the Nand to Tetris hardware simulator, using a test script. In particular, we show two cases: testing a well-written HDL program, and testing / debugging an HDL program that has a bug. Also illustrates working with script (.tst), output (.out), and compare (.cmp) files.

</VideoContent>

### Clock Demo

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/VFXPGIw_Odo'
  ]}
>

Illustrates how the clock comes to play when simulating sequential (time-dependent) chips in the Nand to Tetris hardware simulator. In particular, illustrates how to advance the clock interactively, and using a test-script. These operations realize a sequence of cycles, to which the sequential chips respond according to their specifications.

</VideoContent>

### Register Demo

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/URds-xtD5A0'
  ]}
>

Illustrates how a Register chip operates on the Nand to Tetris hardware simulator. Shows how the register maintains its value (state) over time, and how we can load the register with a new value. In particular, shows how it takes a complete cycle before the register commits to its new value.

</VideoContent>

### Program Counter Demo

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/PECRzxWh1Ho'
  ]}
>

This video illustrates how to have a program counter.

</VideoContent>

### RAM Demo

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/-99WGl31dcA'
  ]}
>

Illustrates how a RAM (Random Access Memory) chip operates on the Nand to Tetris hardware simulator. In particular, shows how to read data from, and write data into, the Hack computer's RAM chip.

</VideoContent>

### CPU Emulator Demo

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/8XieZhHNFVY'
  ]}
>

Illustrates the CPU emulator, which enables loading and executing programs written in the Hack machine language. The emulator allows loading either symbolic (assembly) code or binary code. In the former case, it translated the assembly instructions to binary instructions, on the fly.

</VideoContent>

### CPU Emulator Demo: Executing a simple graphics program

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/20CHjI8M2gU'
  ]}
>

Illustrates how to execute a graphics program on the CPU emulator. The program, stored in a file named Rectangle.asm, is written in the Hack assembly language.  It is designed to draw a rectangle on the computer's screen, as this demo illustrates.

</VideoContent>

### CPU Emulator Demo: Executing Pong

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/NMG-7e7d_jE'
  ]}
>

The Nand to Tetris CPU emulator can execute any program written in the Hack machine language. Such programs are typically written in a high level language (like Jack) and then compiled into machine language. One such program is a version of the classical video game Pong. This demo illustrates how the Nand to Tetris CPU emulator executed the compiled Pong program.

</VideoContent>

### Screen Chip Demo

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/Z-Wl9MEeChk'
  ]}
>

Illustrates working with the Screen chip in the Nand to Tetris hardware simulator. The screen device of the Hack computer is realized as a memory chip, called Screen, that has 8K 16-bit registers. The Screen chip continuously refreshes a 2D screen device consisting of 256 rows of 512 black-and-white pixels each. The demo shows how this screen device can be manipulated by entering various values into the Screen memory chip.

</VideoContent>

### Keyboard Chip Demo

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/XLH2wRjtiHA'
  ]}
>

This video gives a demonstration of what a keyboard chip is.

</VideoContent>

### ROM Demo

<VideoContent 
  type="note" 
  videoUrls={[
    'https://www.youtube.com/embed/7rXFuyiCHi8'
  ]}
>

Illustrates the ROM chip of the Hack computer, which serves as the computer's instruction memory, i.e. the storage device that contains the presently executing program. In particular, shows how to load a program into the ROM, and how to inspect the ROM's contents using both symbolic and binary representations.

</VideoContent>

## Reference Links

- [Extended course syllabus](https://drive.google.com/file/d/1EWCOVIcg0-dX0XtL3KwNyra6jzMogXLL/view): Directly from the Nand to Tetris site.
- [Nand2Tetris Questions and Answers Forum](http://nand2tetris-questions-and-answers-forum.52.s1.nabble.com/)
- [Cool Stuff](https://www.nand2tetris.org/copy-of-talks): Cool projects and resources related to Nand to Tetris.

### Coursera

- [Build a Modern Computer from First Principles: From Nand to Tetris (Project-Centered Course)](https://www.coursera.org/learn/build-a-computer)
- [Build a Modern Computer from First Principles: Nand to Tetris Part II (project-centered course)](https://www.coursera.org/learn/nand2tetris2)

### Project files

- [Project 1: Boolean Logic](https://drive.google.com/file/d/1MY1buFHo_Wx5DPrKhCNSA2cm5ltwFJzM/view)
- [Project 2: Boolean Arithmetic](https://drive.google.com/file/d/1ie9s3GjM2TrvL7PrEZJ00gEwezgNLOBm/view)
- [Project 3: Sequential Logic](https://drive.google.com/file/d/1boFooygPrxMX-AxzogFYIZ-8QsZiDz96/view)
- [Project 4: Machine Language](https://drive.google.com/file/d/1HxjPmIZkFHl-BVW3qoz8eD9dqEuEyuBI/view)
- [Project 5: Computer Architecture](https://drive.google.com/file/d/1nEptWuRpFF9zmqlKYq6s1UfDB_dd16vx/view)
- [Project 6: Assembler](https://drive.google.com/file/d/1uKGRMnL-gqk9DsgeN50z0EpHoSMWe6F5/view)
- [Project 7: VM I: Stack Arithmetic](https://drive.google.com/file/d/19fe1PeGnggDHymu4LlVY08KmDdhMVRpm/view)
- [Project 8: VM II: Program Control](https://drive.google.com/file/d/1lBsaO5XKLkUgrGY6g6vLMsiZo6rWxlYJ/view)
- [Project 9: High-Level Language](https://drive.google.com/file/d/1rbHGZV8AK4UalmdJyivgt0fpPiD1Q6Vk/view)
- [Project 10: Compiler I: Syntax Analysis](https://drive.google.com/file/d/1ujgcS7GoI-zu56FxhfkTAvEgZ6JT7Dxl/view)
- [Project 11: Compiler II: Code Generation](https://drive.google.com/file/d/1DfGKr0fuJcCvlIPABNSg7fsLfFFqRLex/view)
- [Project 12: Operating System](https://drive.google.com/file/d/137PiYjt4CAZ3ROWiD0DJ8XMUbMM0_VHR/view)

### Syllabi




