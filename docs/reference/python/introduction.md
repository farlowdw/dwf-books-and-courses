---
title: Python Language Notes (Overview)
hide_title: false
sidebar_label: Overview
description: Details about the Python language
draft: false
tags: [Learning Resources]
keywords: [learning]
image: https://github.com/farlowdw.png
hide_table_of_contents: false
toc_min_heading_level: 2
toc_max_heading_level: 5
---


import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

## Quick Reference Links

- [Index of Python Enhancement Proposals (PEPs)](https://www.python.org/dev/peps/)
- [The Python Module Index](https://docs.python.org/3/py-modindex.html)
- [The Python Standard Library](https://docs.python.org/3/library/)
- [Python Package Index](https://pypi.org/)
- [Python Time Complexity Wiki](https://wiki.python.org/moin/TimeComplexity)
- [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
- [Python ZTM Cheatsheet](https://github.com/aneagoie/ztm-python-cheat-sheet)
- [Python Monthly](https://zerotomastery.io/blog/?&utm_medium=coursecontent#monthly)
- [Python 2.7x vs Python 3.x: Key Differences (short)](https://www.geeksforgeeks.org/important-differences-between-python-2-x-and-python-3-x-with-examples/)
- [Python 2.7x vs Python 3.x: Key Differences (long)](https://sebastianraschka.com/Articles/2014_python_2_3_key_diff.html)
- [Functional Programming](https://github.com/farlowdw/python-learnings/blob/master/functional-programming.md)
- [Iteration and Generators](https://github.com/farlowdw/python-learnings/blob/master/iteration-and-generators.md)
- [Hash Maps](https://github.com/farlowdw/python-learnings/blob/master/hash-maps.md)
- [Object-oriented programming (OOP)](https://github.com/farlowdw/python-learnings/blob/master/oop.md)

## External modules

A listing of frequently used external Python modules (list updated as needed):

| Module | Description |
| :-- | :-- |
| [`tbd`](link) | desc |

## Standard library modules

A listing of frequently used standard library Python modules (list updated as needed):

| Module | Description |
| :-- | :-- |
| **Data Structures and Algorithms** | |
| [`collections`](https://docs.python.org/3/library/collections.html#module-collections) | Container datatypes |
| [`functools`](https://docs.python.org/3/library/functools.html#module-functools) | Higher-order functions and operations on callable objects |
| [`itertools`](https://docs.python.org/3/library/itertools.html#module-itertools) | Functions creating iterators for efficient looping |
| [`copy`](https://docs.python.org/3/library/copy.html#module-copy) | Shallow and deep copy operations |
| [`json`](https://docs.python.org/3/library/json.html#module-json) | Encode and decode the JSON format |
| [`json.tool`](https://docs.python.org/3/library/json.html#module-json.tool) | A command line to validate and pretty-print JSON |
| [`heapq`](https://docs.python.org/3/library/heapq.html#module-heapq) | Heap queue algorithm (a.k.a. priority queue) |
| [`queue`](https://docs.python.org/3/library/queue.html#module-queue) | A synchronized queue class |
| [`graphlib`](https://docs.python.org/3/library/graphlib.html#module-graphlib) | Functionality to operate with graph-like structures |
| [`re`](https://docs.python.org/3/library/re.html#module-re) | Regular expression operations |
| [`string`](https://docs.python.org/3/library/string.html#module-string) | Common string operations |
| [`cmath`](https://docs.python.org/3/library/cmath.html#module-cmath) | Mathematical functions for complex numbers |
| [`math`](https://docs.python.org/3/library/math.html#module-math) | Mathematical functions (sin() etc.) |
| [`random`](https://docs.python.org/3/library/random.html#module-random) | Generate pseudo-random numbers with various common distributions |
| [`statistics`](https://docs.python.org/3/library/statistics.html#module-statistics) | Mathematical statistics functions |
| **Dates and Times** | |
| [`calendar`](https://docs.python.org/3/library/calendar.html#module-calendar) | Functions for working with calendars, including some emulation of the Unix cal program |
| [`datetime`](https://docs.python.org/3/library/datetime.html#module-datetime) | Basic date and time types |
| **Debugging and Testing** | |
| [`difflib`](https://docs.python.org/3/library/difflib.html#module-difflib) | Helpers for computing differences between objects |
| [`inspect`](https://docs.python.org/3/library/inspect.html#module-inspect) | Extract information and source code from live objects |
| [`logging`](https://docs.python.org/3/library/logging.html#module-logging) | Flexible event logging system for applications |
| [`pdb`](https://docs.python.org/3/library/pdb.html#module-pdb) | The Python debugger for interactive interpreters |
| [`time`](https://docs.python.org/3/library/time.html#module-time) | Time access and conversions |
| [`timeit`](https://docs.python.org/3/library/timeit.html#module-timeit) | Measure the execution time of small code snippets |
| [`unittest`](https://docs.python.org/3/library/unittest.html#module-unittest) | Unit testing framework for Python |
| [`unittest.mock`](https://docs.python.org/3/library/unittest.mock.html#module-unittest.mock) | Mock object library |
| [`warnings`](https://docs.python.org/3/library/warnings.html#module-warnings) | Issue warning messages and control their disposition |
| **Documentation** | |
| [`doctest`](https://docs.python.org/3/library/doctest.html#module-doctest) | Test pieces of code within docstrings |
| [`pydoc`](https://docs.python.org/3/library/pydoc.html#module-pydoc) | Documentation generator and online help system |
| [`types`](https://docs.python.org/3/library/types.html#module-types) | Names for built-in types |
| [`typing`](https://docs.python.org/3/library/typing.html#module-typing) | Support for type hints (see :pep:`484`) |
| **Encoding and Decoding** | |
| [`base64`](https://docs.python.org/3/library/base64.html#module-base64) | RFC 3548: Base16, Base32, Base64 Data Encodings; Base85 and Ascii85 |
| [`hashlib`](https://docs.python.org/3/library/hashlib.html#module-hashlib) | Secure hash and message digest algorithms |
| [`uuid`](https://docs.python.org/3/library/uuid.html#module-uuid) | UUID objects (universally unique identifiers) according to RFC 4122 |
| **File Manipulation and Input/Output** | |
| [`asyncio`](https://docs.python.org/3/library/asyncio.html#module-asyncio) | Asynchronous I/O |
| [`csv`](https://docs.python.org/3/library/csv.html#module-csv) | Write and read tabular data to and from delimited files |
| [`io`](https://docs.python.org/3/library/io.html#module-io) | Core tools for working with streams |
| [`os`](https://docs.python.org/3/library/os.html#module-os) | Miscellaneous operating system interfaces |
| [`pathlib`](https://docs.python.org/3/library/pathlib.html#module-pathlib) | Object-oriented filesystem paths |
| [`sys`](https://docs.python.org/3/library/sys.html#module-sys) | Access system-specific parameters and functions |
| [`sysconfig`](https://docs.python.org/3/library/sysconfig.html#module-sysconfig) | Python's configuration information |
| [`tempfile`](https://docs.python.org/3/library/tempfile.html#module-tempfile) | Generate temporary files and directories |
| [`textwrap`](https://docs.python.org/3/library/textwrap.html#module-textwrap) | Text wrapping and filling |
| **Reference** | |
| [`__main__`](https://docs.python.org/3/library/__main__.html#module-__main__) | The environment where the top-level script is run |
| [`dataclasses`](https://docs.python.org/3/library/dataclasses.html#module-dataclasses) | Generate special methods on user-defined classes |
| [`email`](https://docs.python.org/3/library/email.html#module-email) | Package supporting the parsing, manipulating, and generating email messages |
| [`glob`](https://docs.python.org/3/library/glob.html#module-glob) | Unix shell style pathname pattern expansion |
| [`keyword`](https://docs.python.org/3/library/keyword.html#module-keyword) | Test whether a string is a keyword in Python |
| [`venv`](https://docs.python.org/3/library/venv.html#module-venv) | Creation of virtual environments |

## Complete standard library module index

| Module | Description |
| :-- | :-- |
| **-** | |
| [`__future__`](https://docs.python.org/3/library/__future__.html#module-__future__) | Future statement definitions |
| [`__main__`](https://docs.python.org/3/library/__main__.html#module-__main__) | The environment where the top-level script is run |
| [`_thread`](https://docs.python.org/3/library/_thread.html#module-_thread) | Low-level threading API |
| **A** | |
| [`abc`](https://docs.python.org/3/library/abc.html#module-abc) | Abstract base classes according to :pep:`3119` |
| [`aifc`](https://docs.python.org/3/library/aifc.html#module-aifc) | Read and write audio files in AIFF or AIFC format |
| [`argparse`](https://docs.python.org/3/library/argparse.html#module-argparse) | Command-line option and argument parsing library |
| [`array`](https://docs.python.org/3/library/array.html#module-array) | Space efficient arrays of uniformly typed numeric values |
| [`ast`](https://docs.python.org/3/library/ast.html#module-ast) | Abstract Syntax Tree classes and manipulation |
| [`asynchat`](https://docs.python.org/3/library/asynchat.html#module-asynchat) | Support for asynchronous command/response protocols |
| [`asyncio`](https://docs.python.org/3/library/asyncio.html#module-asyncio) | Asynchronous I/O |
| [`asyncore`](https://docs.python.org/3/library/asyncore.html#module-asyncore) | A base class for developing asynchronous socket handling services |
| [`atexit`](https://docs.python.org/3/library/atexit.html#module-atexit) | Register and execute cleanup functions |
| [`audioop`](https://docs.python.org/3/library/audioop.html#module-audioop) | Manipulate raw audio data |
| **B** | |
| [`base64`](https://docs.python.org/3/library/base64.html#module-base64) | RFC 3548: Base16, Base32, Base64 Data Encodings; Base85 and Ascii85 |
| [`bdb`](https://docs.python.org/3/library/bdb.html#module-bdb) | Debugger framework |
| [`binascii`](https://docs.python.org/3/library/binascii.html#module-binascii) | Tools for converting between binary and various ASCII-encoded binary representations |
| [`binhex`](https://docs.python.org/3/library/binhex.html#module-binhex) | Encode and decode files in binhex4 format |
| [`bisect`](https://docs.python.org/3/library/bisect.html#module-bisect) | Array bisection algorithms for binary searching |
| [`builtins`](https://docs.python.org/3/library/builtins.html#module-builtins) | The module that provides the built-in namespace |
| [`bz2`](https://docs.python.org/3/library/bz2.html#module-bz2) | Interfaces for bzip2 compression and decompression |
| **C** | |
| [`calendar`](https://docs.python.org/3/library/calendar.html#module-calendar) | Functions for working with calendars, including some emulation of the Unix cal program |
| [`cgi`](https://docs.python.org/3/library/cgi.html#module-cgi) | Helpers for running Python scripts via the Common Gateway Interface |
| [`cgitb`](https://docs.python.org/3/library/cgitb.html#module-cgitb) | Configurable traceback handler for CGI scripts |
| [`chunk`](https://docs.python.org/3/library/chunk.html#module-chunk) | Module to read IFF chunks |
| [`cmath`](https://docs.python.org/3/library/cmath.html#module-cmath) | Mathematical functions for complex numbers |
| [`cmd`](https://docs.python.org/3/library/cmd.html#module-cmd) | Build line-oriented command interpreters |
| [`code`](https://docs.python.org/3/library/code.html#module-code) | Facilities to implement read-eval-print loops |
| [`codecs`](https://docs.python.org/3/library/codecs.html#module-codecs) | Encode and decode data and streams |
| [`codeop`](https://docs.python.org/3/library/codeop.html#module-codeop) | Compile (possibly incomplete) Python code |
| [`collections`](https://docs.python.org/3/library/collections.html#module-collections) | Container datatypes |
| [`collections.abc`](https://docs.python.org/3/library/collections.abc.html#module-collections.abc) | Abstract base classes for containers |
| [`colorsys`](https://docs.python.org/3/library/colorsys.html#module-colorsys) | Conversion functions between RGB and other color systems |
| [`compileall`](https://docs.python.org/3/library/compileall.html#module-compileall) | Tools for byte-compiling all Python source files in a directory tree |
| `concurrent` | |
| [`concurrent.futures`](https://docs.python.org/3/library/concurrent.futures.html#module-concurrent.futures) | Execute computations concurrently using threads or processes |
| [`configparser`](https://docs.python.org/3/library/configparser.html#module-configparser) | Configuration file parser |
| [`contextlib`](https://docs.python.org/3/library/contextlib.html#module-contextlib) | Utilities for with-statement contexts |
| [`contextvars`](https://docs.python.org/3/library/contextvars.html#module-contextvars) | Context Variables |
| [`copy`](https://docs.python.org/3/library/copy.html#module-copy) | Shallow and deep copy operations |
| [`copyreg`](https://docs.python.org/3/library/copyreg.html#module-copyreg) | Register pickle support functions |
| [`cProfile`](https://docs.python.org/3/library/profile.html#module-cProfile) | |
| [`crypt`](https://docs.python.org/3/library/crypt.html#module-crypt) (Unix) | The `crypt()` function used to check Unix passwords |
| [`csv`](https://docs.python.org/3/library/csv.html#module-csv) | Write and read tabular data to and from delimited files |
| [`ctypes`](https://docs.python.org/3/library/ctypes.html#module-ctypes) | A foreign function library for Python |
| [`curses`](https://docs.python.org/3/library/curses.html#module-curses) (Unix) | An interface to the curses library, providing portable terminal handling |
| [`curses.ascii`](https://docs.python.org/3/library/curses.ascii.html#module-curses.ascii) | Constants and set-membership functions for ASCII characters |
| [`curses.panel`](https://docs.python.org/3/library/curses.panel.html#module-curses.panel) | A panel stack extension that adds depth to curses windows |
| [`curses.textpad`](https://docs.python.org/3/library/curses.html#module-curses.textpad) | Emacs-like input editing in a curses window |
| **D** | |
| [`dataclasses`](https://docs.python.org/3/library/dataclasses.html#module-dataclasses) | Generate special methods on user-defined classes |
| [`datetime`](https://docs.python.org/3/library/datetime.html#module-datetime) | Basic date and time types |
| [`dbm`](https://docs.python.org/3/library/dbm.html#module-dbm) | Interfaces to various Unix "database" formats |
| [`dbm.dumb`](https://docs.python.org/3/library/dbm.html#module-dbm.dumb) | Portable implementation of the simple DBM interface |
| [`dbm.gnu`](https://docs.python.org/3/library/dbm.html#module-dbm.gnu) (Unix) | GNU's reinterpretation of dbm |
| [`dbm.ndbm`](https://docs.python.org/3/library/dbm.html#module-dbm.ndbm) (Unix) | The standard "database" interface, based on ndbm |
| [`decimal`](https://docs.python.org/3/library/decimal.html#module-decimal) | Implementation of the General Decimal Arithmetic Specification |
| [`difflib`](https://docs.python.org/3/library/difflib.html#module-difflib) | Helpers for computing differences between objects |
| [`dis`](https://docs.python.org/3/library/dis.html#module-dis) | Disassembler for Python bytecode |
| [`distutils`](https://docs.python.org/3/library/distutils.html#module-distutils) | Support for building and installing Python modules into an existing Python installation |
| [`distutils.archive_util`](https://docs.python.org/3/distutils/apiref.html#module-distutils.archive_util) | Utility functions for creating archive files (tarballs, zip files, ...) |
| [`distutils.bcppcompiler`](https://docs.python.org/3/distutils/apiref.html#module-distutils.bcppcompiler) |  |
| [`distutils.ccompiler`](https://docs.python.org/3/distutils/apiref.html#module-distutils.ccompiler) | Abstract CCompiler class |
| [`distutils.cmd`](https://docs.python.org/3/distutils/apiref.html#module-distutils.cmd) | Provides the abstract base class :class:`~distutils.cmd.Command`. This class is subclassed by the modules in the distutils.command subpackage. |
| [`distutils.command`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command) | Contains one module for each standard Distutils command |
| [`distutils.command.bdist`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.bdist) | Build a binary installer for a package |
| [`distutils.command.bdist_dumb`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.bdist_dumb) | Build a "dumb" installer - a simple archive of files |
| [`distutils.command.bdist_msi`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.bdist_msi) | Build a binary distribution as a Windows MSI file |
| [`distutils.command.bdist_packager`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.bdist_packager) | Abstract base class for packagers |
| [`distutils.command.bdist_rpm`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.bdist_rpm) | Build a binary distribution as a Redhat RPM and SRPM |
| [`distutils.command.bdist_wininst`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.bdist_wininst) | Build a Windows installer |
| [`distutils.command.build`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.build) | Build all files of a package |
| [`distutils.command.build_clib`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.build_clib) | Build any C libraries in a package |
| [`distutils.command.build_ext`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.build_ext) | Build any extensions in a package |
| [`distutils.command.build_py`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.build_py) | Build the .py/.pyc files of a package |
| [`distutils.command.build_scripts`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.build_scripts) | Build the scripts of a package |
| [`distutils.command.check`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.check) | Check the meta-data of a package |
| [`distutils.command.clean`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.clean) | Clean a package build area |
| [`distutils.command.config`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.config) | Perform package configuration |
| [`distutils.command.install`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.install) | Install a package |
| [`distutils.command.install_data`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.install_data) | Install data files from a package |
| [`distutils.command.install_headers`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.install_headers) | Install C/C++ header files from a package |
| [`distutils.command.install_lib`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.install_lib) | Install library files from a package |
| [`distutils.command.install_scripts`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.install_scripts) | Install script files from a package |
| [`distutils.command.register`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.register) | Register a module with the Python Package Index |
| [`distutils.command.sdist`](https://docs.python.org/3/distutils/apiref.html#module-distutils.command.sdist) | Build a source distribution |
| [`distutils.core`](https://docs.python.org/3/distutils/apiref.html#module-distutils.core) | The core Distutils functionality |
| [`distutils.cygwinccompiler`](https://docs.python.org/3/distutils/apiref.html#module-distutils.cygwinccompiler) |  |
| [`distutils.debug`](https://docs.python.org/3/distutils/apiref.html#module-distutils.debug) | Provides the debug flag for distutils |
| [`distutils.dep_util`](https://docs.python.org/3/distutils/apiref.html#module-distutils.dep_util) | Utility functions for simple dependency checking |
| [`distutils.dir_util`](https://docs.python.org/3/distutils/apiref.html#module-distutils.dir_util) | Utility functions for operating on directories and directory trees |
| [`distutils.dist`](https://docs.python.org/3/distutils/apiref.html#module-distutils.dist) | Provides the Distribution class, which represents the module distribution being built/installed/distributed |
| [`distutils.errors`](https://docs.python.org/3/distutils/apiref.html#module-distutils.errors) | Provides standard distutils exceptions |
| [`distutils.extension`](https://docs.python.org/3/distutils/apiref.html#module-distutils.extension) | Provides the Extension class, used to describe C/C++ extension modules in setup scripts |
| [`distutils.fancy_getopt`](https://docs.python.org/3/distutils/apiref.html#module-distutils.fancy_getopt) | Additional getopt functionality |
| [`distutils.file_util`](https://docs.python.org/3/distutils/apiref.html#module-distutils.file_util) | Utility functions for operating on single files |
| [`distutils.filelist`](https://docs.python.org/3/distutils/apiref.html#module-distutils.filelist) | The FileList class, used for poking about the file system and building lists of files. |
| [`distutils.log`](https://docs.python.org/3/distutils/apiref.html#module-distutils.log) | A simple logging mechanism, :pep:`282`-style |
| [`distutils.msvccompiler`](https://docs.python.org/3/distutils/apiref.html#module-distutils.msvccompiler) | Microsoft Compiler |
| [`distutils.spawn`](https://docs.python.org/3/distutils/apiref.html#module-distutils.spawn) | Provides the spawn() function |
| [`distutils.sysconfig`](https://docs.python.org/3/distutils/apiref.html#module-distutils.sysconfig) | Low-level access to configuration information of the Python interpreter |
| [`distutils.text_file`](https://docs.python.org/3/distutils/apiref.html#module-distutils.text_file) | Provides the TextFile class, a simple interface to text files |
| [`distutils.unixccompiler`](https://docs.python.org/3/distutils/apiref.html#module-distutils.unixccompiler) | UNIX C Compiler |
| [`distutils.util`](https://docs.python.org/3/distutils/apiref.html#module-distutils.util) | Miscellaneous other utility functions |
| [`distutils.version`](https://docs.python.org/3/distutils/apiref.html#module-distutils.version) | Implements classes that represent module version numbers |
| [`doctest`](https://docs.python.org/3/library/doctest.html#module-doctest) | Test pieces of code within docstrings |
| **E** | |
| [`email`](https://docs.python.org/3/library/email.html#module-email) | Package supporting the parsing, manipulating, and generating email messages |
| [`email.charset`](https://docs.python.org/3/library/email.charset.html#module-email.charset) | Character Sets |
| [`email.contentmanager`](https://docs.python.org/3/library/email.contentmanager.html#module-email.contentmanager) | Storing and Retrieving Content from MIME Parts |
| [`email.encoders`](https://docs.python.org/3/library/email.encoders.html#module-email.encoders) | Encoders for email message payloads |
| [`email.errors`](https://docs.python.org/3/library/email.errors.html#module-email.errors) | The exception classes used by the email package |
| [`email.generator`](https://docs.python.org/3/library/email.generator.html#module-email.generator) | Generate flat text email messages from a message structure |
| [`email.header`](https://docs.python.org/3/library/email.header.html#module-email.header) | Representing non-ASCII headers |
| [`email.headerregistry`](https://docs.python.org/3/library/email.headerregistry.html#module-email.headerregistry) | Automatic Parsing of headers based on the field name |
| [`email.iterators`](https://docs.python.org/3/library/email.iterators.html#module-email.iterators) | Iterate over a message object tree |
| [`email.message`](https://docs.python.org/3/library/email.message.html#module-email.message) | The base class representing email messages |
| [`email.mime`](https://docs.python.org/3/library/email.mime.html#module-email.mime) | Build MIME messages |
| [`email.parser`](https://docs.python.org/3/library/email.parser.html#module-email.parser) | Parse flat text email messages to produce a message object structure |
| [`email.policy`](https://docs.python.org/3/library/email.policy.html#module-email.policy) | Controlling the parsing and generating of messages |
| [`email.utils`](https://docs.python.org/3/library/email.utils.html#module-email.utils) | Miscellaneous email package utilities |
| encodings | |
| [`encodings.idna`](https://docs.python.org/3/library/codecs.html#module-encodings.idna) | Internationalized Domain Names implementation |
| [`encodings.mbcs`](https://docs.python.org/3/library/codecs.html#module-encodings.mbcs) | Windows ANSI codepage |
| [`encodings.utf_8_sig`](https://docs.python.org/3/library/codecs.html#module-encodings.utf_8_sig) | UTF-8 codec with BOM signature |
| [`ensurepip`](https://docs.python.org/3/library/ensurepip.html#module-ensurepip) | Bootstrapping the "pip" installer into an existing Python installation or virtual environment |
| [`enum`](https://docs.python.org/3/library/enum.html#module-enum) | Implementation of an enumeration class |
| [`errno`](https://docs.python.org/3/library/errno.html#module-errno) | Standard errno system symbols |
| **F** | |
| [`faulthandler`](https://docs.python.org/3/library/faulthandler.html#module-faulthandler) | Dump the Python traceback |
| [`fcntl`](https://docs.python.org/3/library/fcntl.html#module-fcntl) (Unix) | The `fcntl()` and `ioctl()` system calls |
| [`filecmp`](https://docs.python.org/3/library/filecmp.html#module-filecmp) | Compare files efficiently |
| [`fileinput`](https://docs.python.org/3/library/fileinput.html#module-fileinput) | Loop over standard input or a list of files |
| [`fnmatch`](https://docs.python.org/3/library/fnmatch.html#module-fnmatch) | Unix shell style filename pattern matching |
| [`formatter`](https://docs.python.org/3/library/formatter.html#module-formatter) | Deprecated: Generic output formatter and device interface |
| [`fractions`](https://docs.python.org/3/library/fractions.html#module-fractions) | Rational numbers |
| [`ftplib`](https://docs.python.org/3/library/ftplib.html#module-ftplib) | FTP protocol client (requires sockets) |
| [`functools`](https://docs.python.org/3/library/functools.html#module-functools) | Higher-order functions and operations on callable objects |
| **G** | |
| [`gc`](https://docs.python.org/3/library/gc.html#module-gc) | Interface to the cycle-detecting garbage collector |
| [`getopt`](https://docs.python.org/3/library/getopt.html#module-getopt) | Portable parser for command line options; support both short and long option names |
| [`getpass`](https://docs.python.org/3/library/getpass.html#module-getpass) | Portable reading of passwords and retrieval of the userid |
| [`gettext`](https://docs.python.org/3/library/gettext.html#module-gettext) | Multilingual internationalization services |
| [`glob`](https://docs.python.org/3/library/glob.html#module-glob) | Unix shell style pathname pattern expansion |
| [`graphlib`](https://docs.python.org/3/library/graphlib.html#module-graphlib) | Functionality to operate with graph-like structures |
| [`grp`](https://docs.python.org/3/library/grp.html#module-grp) (Unix) | The group database (getgrnam() and friends) |
| [`gzip`](https://docs.python.org/3/library/gzip.html#module-gzip) | Interfaces for gzip compression and decompression using file objects |
| **H** | |
| [`hashlib`](https://docs.python.org/3/library/hashlib.html#module-hashlib) | Secure hash and message digest algorithms |
| [`heapq`](https://docs.python.org/3/library/heapq.html#module-heapq) | Heap queue algorithm (a.k.a. priority queue) |
| [`hmac`](https://docs.python.org/3/library/hmac.html#module-hmac) | Keyed-Hashing for Message Authentication (HMAC) implementation |
| [`html`](https://docs.python.org/3/library/html.html#module-html) | Helpers for manipulating HTML |
| [`html.entities`](https://docs.python.org/3/library/html.entities.html#module-html.entities) | Definitions of HTML general entities |
| [`html.parser`](https://docs.python.org/3/library/html.parser.html#module-html.parser) | A simple parser that can handle HTML and XHTML |
| [`http`](https://docs.python.org/3/library/http.html#module-http) | HTTP status codes and messages |
| [`http.client`](https://docs.python.org/3/library/http.client.html#module-http.client) | HTTP and HTTPS protocol client (requires sockets) |
| [`http.cookiejar`](https://docs.python.org/3/library/http.cookiejar.html#module-http.cookiejar) | Classes for automatic handling of HTTP cookies |
| [`http.cookies`](https://docs.python.org/3/library/http.cookies.html#module-http.cookies) | Support for HTTP state management (cookies) |
| [`http.server`](https://docs.python.org/3/library/http.server.html#module-http.server) | HTTP server and request handlers |
| **I** | |
| [`imaplib`](https://docs.python.org/3/library/imaplib.html#module-imaplib) | IMAP4 protocol client (requires sockets) |
| [`imghdr`](https://docs.python.org/3/library/imghdr.html#module-imghdr) | Determine the type of image contained in a file or byte stream |
| [`imp`](https://docs.python.org/3/library/imp.html#module-imp) | Deprecated: Access the implementation of the import statement |
| [`importlib`](https://docs.python.org/3/library/importlib.html#module-importlib) | The implementation of the import machinery |
| [`importlib.abc`](https://docs.python.org/3/library/importlib.html#module-importlib.abc) | Abstract base classes related to import |
| [`importlib.machinery`](https://docs.python.org/3/library/importlib.html#module-importlib.machinery) | Importers and path hooks |
| [`importlib.metadata`](https://docs.python.org/3/library/importlib.metadata.html#module-importlib.metadata) | The implementation of the importlib metadata |
| [`importlib.resources`](https://docs.python.org/3/library/importlib.html#module-importlib.resources) | Package resource reading, opening, and access |
| [`importlib.util`](https://docs.python.org/3/library/importlib.html#module-importlib.util) | Utility code for importers |
| [`inspect`](https://docs.python.org/3/library/inspect.html#module-inspect) | Extract information and source code from live objects |
| [`io`](https://docs.python.org/3/library/io.html#module-io) | Core tools for working with streams |
| [`ipaddress`](https://docs.python.org/3/library/ipaddress.html#module-ipaddress) | IPv4/IPv6 manipulation library |
| [`itertools`](https://docs.python.org/3/library/itertools.html#module-itertools) | Functions creating iterators for efficient looping |
| **J** | |
| [`json`](https://docs.python.org/3/library/json.html#module-json) | Encode and decode the JSON format |
| [`json.tool`](https://docs.python.org/3/library/json.html#module-json.tool) | A command line to validate and pretty-print JSON |
| **K** | |
| [`keyword`](https://docs.python.org/3/library/keyword.html#module-keyword) | Test whether a string is a keyword in Python |
| **L** | |
| [`lib2to3`](https://docs.python.org/3/library/2to3.html#module-lib2to3) | The 2to3 library |
| [`linecache`](https://docs.python.org/3/library/linecache.html#module-linecache) | Provides random access to individual lines from text files |
| [`locale`](https://docs.python.org/3/library/locale.html#module-locale) | Internationalization services |
| [`logging`](https://docs.python.org/3/library/logging.html#module-logging) | Flexible event logging system for applications |
| [`logging.config`](https://docs.python.org/3/library/logging.config.html#module-logging.config) | Configuration of the logging module |
| [`logging.handlers`](https://docs.python.org/3/library/logging.handlers.html#module-logging.handlers) | Handlers for the logging module |
| [`lzma`](https://docs.python.org/3/library/lzma.html#module-lzma) | A Python wrapper for the liblzma compression library |
| **M** | |
| [`mailbox`](https://docs.python.org/3/library/mailbox.html#module-mailbox) | Manipulate mailboxes in various formats |
| [`mailcap`](https://docs.python.org/3/library/mailcap.html#module-mailcap) | Mailcap file handling |
| [`marshal`](https://docs.python.org/3/library/marshal.html#module-marshal) | Convert Python objects to streams of bytes and back (with different constraints) |
| [`math`](https://docs.python.org/3/library/math.html#module-math) | Mathematical functions (sin() etc.) |
| [`mimetypes`](https://docs.python.org/3/library/mimetypes.html#module-mimetypes) | Mapping of filename extensions to MIME types |
| [`mmap`](https://docs.python.org/3/library/mmap.html#module-mmap) | Interface to memory-mapped files for Unix and Windows |
| [`modulefinder`](https://docs.python.org/3/library/modulefinder.html#module-modulefinder) | Find modules used by a script |
| [`msilib`](https://docs.python.org/3/library/msilib.html#module-msilib) (Windows) | Creation of Microsoft Installer files, and CAB files |
| [`msvcrt`](https://docs.python.org/3/library/msvcrt.html#module-msvcrt) (Windows) | Miscellaneous useful routines from the MS VC++ runtime |
| [`multiprocessing`](https://docs.python.org/3/library/multiprocessing.html#module-multiprocessing) | Process-based parallelism |
| [`multiprocessing.connection`](https://docs.python.org/3/library/multiprocessing.html#module-multiprocessing.connection) | API for dealing with sockets |
| [`multiprocessing.dummy`](https://docs.python.org/3/library/multiprocessing.html#module-multiprocessing.dummy) | Dumb wrapper around threading |
| [`multiprocessing.managers`](https://docs.python.org/3/library/multiprocessing.html#module-multiprocessing.managers) | Share data between process with shared objects |
| [`multiprocessing.pool`](https://docs.python.org/3/library/multiprocessing.html#module-multiprocessing.pool) | Create pools of processes |
| [`multiprocessing.shared_memory`](https://docs.python.org/3/library/multiprocessing.shared_memory.html#module-multiprocessing.shared_memory) | Provides shared memory for direct access across processes |
| [`multiprocessing.sharedctypes`](https://docs.python.org/3/library/multiprocessing.html#module-multiprocessing.sharedctypes) | Allocate ctypes objects from shared memory |
| **N** | |
| [`netrc`](https://docs.python.org/3/library/netrc.html#module-netrc) | Loading of .netrc files |
| [`nis`](https://docs.python.org/3/library/nis.html#module-nis) (Unix) | Interface to Sun's NIS (Yellow Pages) library |
| [`nntplib`](https://docs.python.org/3/library/nntplib.html#module-nntplib) | NNTP protocol client (requires sockets) |
| [`numbers`](https://docs.python.org/3/library/numbers.html#module-numbers) | Numeric abstract base classes (Complex, Real, Integral, etc.) |
| **O** | |
| [`operator`](https://docs.python.org/3/library/operator.html#module-operator) | Functions corresponding to the standard operators |
| [`optparse`](https://docs.python.org/3/library/optparse.html#module-optparse) | Deprecated: Command-line option parsing library |
| [`os`](https://docs.python.org/3/library/os.html#module-os) | Miscellaneous operating system interfaces |
| [`os.path`](https://docs.python.org/3/library/os.path.html#module-os.path) | Operations on pathnames |
| [`ossaudiodev`](https://docs.python.org/3/library/ossaudiodev.html#module-ossaudiodev) | (Linux, FreeBSD) Access to OSS-compatible audio devices |
| **P** | |
| [`parser`](https://docs.python.org/3/library/parser.html#module-parser) | Access parse trees for Python source code |
| [`pathlib`](https://docs.python.org/3/library/pathlib.html#module-pathlib) | Object-oriented filesystem paths |
| [`pdb`](https://docs.python.org/3/library/pdb.html#module-pdb) | The Python debugger for interactive interpreters |
| [`pickle`](https://docs.python.org/3/library/pickle.html#module-pickle) | Convert Python objects to streams of bytes and back |
| [`pickletools`](https://docs.python.org/3/library/pickletools.html#module-pickletools) | Contains extensive comments about the pickle protocols and pickle-machine opcodes, as well as some useful functions |
| [`pipes`](https://docs.python.org/3/library/pipes.html#module-pipes) (Unix) | A Python interface to Unix shell pipelines |
| [`pkgutil`](https://docs.python.org/3/library/pkgutil.html#module-pkgutil) | Utilities for the import system |
| [`platform`](https://docs.python.org/3/library/platform.html#module-platform) | Retrieves as much platform identifying data as possible |
| [`plistlib`](https://docs.python.org/3/library/plistlib.html#module-plistlib) | Generate and parse Apple plist files |
| [`poplib`](https://docs.python.org/3/library/poplib.html#module-poplib) | POP3 protocol client (requires sockets) |
| [`posix`](https://docs.python.org/3/library/posix.html#module-posix) (Unix) | The most common POSIX system calls (normally used via module os) |
| [`pprint`](https://docs.python.org/3/library/pprint.html#module-pprint) | Data pretty printer |
| [`profile`](https://docs.python.org/3/library/profile.html#module-profile) | Python source profiler |
| [`pstats`](https://docs.python.org/3/library/profile.html#module-pstats) | Statistics object for use with the profiler |
| [`pty`](https://docs.python.org/3/library/pty.html#module-pty) (Linux) | Pseudo-Terminal Handling for Linux |
| [`pwd`](https://docs.python.org/3/library/pwd.html#module-pwd) (Unix) | The password database (getpwnam() and friends) |
| [`py_compile`](https://docs.python.org/3/library/py_compile.html#module-py_compile) | Generate byte-code files from Python source files |
| [`pyclbr`](https://docs.python.org/3/library/pyclbr.html#module-pyclbr) | Supports information extraction for a Python module browser |
| [`pydoc`](https://docs.python.org/3/library/pydoc.html#module-pydoc) | Documentation generator and online help system |
| **Q** | |
| [`queue`](https://docs.python.org/3/library/queue.html#module-queue) | A synchronized queue class |
| [`quopri`](https://docs.python.org/3/library/quopri.html#module-quopri) | Encode and decode files using the MIME quoted-printable encoding |
| **R** | |
| [`random`](https://docs.python.org/3/library/random.html#module-random) | Generate pseudo-random numbers with various common distributions |
| [`re`](https://docs.python.org/3/library/re.html#module-re) | Regular expression operations |
| [`readline`](https://docs.python.org/3/library/readline.html#module-readline) (Unix) | GNU readline support for Python |
| [`reprlib`](https://docs.python.org/3/library/reprlib.html#module-reprlib) | Alternate repr() implementation with size limits |
| [`resource`](https://docs.python.org/3/library/resource.html#module-resource) (Unix) | An interface to provide resource usage information on the current process |
| [`rlcompleter`](https://docs.python.org/3/library/rlcompleter.html#module-rlcompleter) | Python identifier completion, suitable for the GNU readline library |
| [`runpy`](https://docs.python.org/3/library/runpy.html#module-runpy) | Locate and run Python modules without importing them first |
| **S** | |
| [`sched`](https://docs.python.org/3/library/sched.html#module-sched) | General purpose event scheduler |
| [`secrets`](https://docs.python.org/3/library/secrets.html#module-secrets) | Generate secure random numbers for managing secrets |
| [`select`](https://docs.python.org/3/library/select.html#module-select) | Wait for I/O completion on multiple streams |
| [`selectors`](https://docs.python.org/3/library/selectors.html#module-selectors) | High-level I/O multiplexing |
| [`shelve`](https://docs.python.org/3/library/shelve.html#module-shelve) | Python object persistence |
| [`shlex`](https://docs.python.org/3/library/shlex.html#module-shlex) | Simple lexical analysis for Unix shell-like languages |
| [`shutil`](https://docs.python.org/3/library/shutil.html#module-shutil) | High-level file operations, including copying |
| [`signal`](https://docs.python.org/3/library/signal.html#module-signal) | Set handlers for asynchronous events |
| [`site`](https://docs.python.org/3/library/site.html#module-site) | Module responsible for site-specific configuration |
| [`smtpd`](https://docs.python.org/3/library/smtpd.html#module-smtpd) | A SMTP server implementation in Python |
| [`smtplib`](https://docs.python.org/3/library/smtplib.html#module-smtplib) | SMTP protocol client (requires sockets) |
| [`sndhdr`](https://docs.python.org/3/library/sndhdr.html#module-sndhdr) | Determine type of a sound file |
| [`socket`](https://docs.python.org/3/library/socket.html#module-socket) | Low-level networking interface |
| [`socketserver`](https://docs.python.org/3/library/socketserver.html#module-socketserver) | A framework for network servers |
| [`spwd`](https://docs.python.org/3/library/spwd.html#module-spwd) (Unix) | The shadow password database (getspnam() and friends) |
| [`sqlite3`](https://docs.python.org/3/library/sqlite3.html#module-sqlite3) | A DB-API 2.0 implementation using SQLite 3.x |
| [`ssl`](https://docs.python.org/3/library/ssl.html#module-ssl) | TLS/SSL wrapper for socket objects |
| [`stat`](https://docs.python.org/3/library/stat.html#module-stat) | Utilities for interpreting the results of os.stat(), os.lstat() and os.fstat() |
| [`statistics`](https://docs.python.org/3/library/statistics.html#module-statistics) | Mathematical statistics functions |
| [`string`](https://docs.python.org/3/library/string.html#module-string) | Common string operations |
| [`stringprep`](https://docs.python.org/3/library/stringprep.html#module-stringprep) | String preparation, as per RFC 3453 |
| [`struct`](https://docs.python.org/3/library/struct.html#module-struct) | Interpret bytes as packed binary data |
| [`subprocess`](https://docs.python.org/3/library/subprocess.html#module-subprocess) | Subprocess management |
| [`sunau`](https://docs.python.org/3/library/sunau.html#module-sunau) | Provide an interface to the Sun AU sound format |
| [`symbol`](https://docs.python.org/3/library/symbol.html#module-symbol) | Constants representing internal nodes of the parse tree |
| [`symtable`](https://docs.python.org/3/library/symtable.html#module-symtable) | Interface to the compiler's internal symbol tables |
| [`sys`](https://docs.python.org/3/library/sys.html#module-sys) | Access system-specific parameters and functions |
| [`sysconfig`](https://docs.python.org/3/library/sysconfig.html#module-sysconfig) | Python's configuration information |
| [`syslog`](https://docs.python.org/3/library/syslog.html#module-syslog) (Unix) | An interface to the Unix syslog library routines |
| **T** | |
| [`tabnanny`](https://docs.python.org/3/library/tabnanny.html#module-tabnanny) | Tool for detecting white space related problems in Python source files in a directory tree |
| [`tarfile`](https://docs.python.org/3/library/tarfile.html#module-tarfile) | Read and write tar-format archive files |
| [`telnetlib`](https://docs.python.org/3/library/telnetlib.html#module-telnetlib) | Telnet client class |
| [`tempfile`](https://docs.python.org/3/library/tempfile.html#module-tempfile) | Generate temporary files and directories |
| [`termios`](https://docs.python.org/3/library/termios.html#module-termios) (Unix) | POSIX style tty control |
| [`test`](https://docs.python.org/3/library/test.html#module-test) | Regression tests package containing the testing suite for Python |
| [`test.support`](https://docs.python.org/3/library/test.html#module-test.support) | Support for Python's regression test suite |
| [`test.support.bytecode_helper`](https://docs.python.org/3/library/test.html#module-test.support.bytecode_helper) | Support tools for testing correct bytecode generation |
| [`test.support.script_helper`](https://docs.python.org/3/library/test.html#module-test.support.script_helper) | Support for Python's script execution tests |
| [`test.support.socket_helper`](https://docs.python.org/3/library/test.html#module-test.support.socket_helper) | Support for socket tests |
| [`textwrap`](https://docs.python.org/3/library/textwrap.html#module-textwrap) | Text wrapping and filling |
| [`threading`](https://docs.python.org/3/library/threading.html#module-threading) | Thread-based parallelism |
| [`time`](https://docs.python.org/3/library/time.html#module-time) | Time access and conversions |
| [`timeit`](https://docs.python.org/3/library/timeit.html#module-timeit) | Measure the execution time of small code snippets |
| [`tkinter`](https://docs.python.org/3/library/tkinter.html#module-tkinter) | Interface to Tcl/Tk for graphical user interfaces |
| [`tkinter.colorchooser`](https://docs.python.org/3/library/tkinter.colorchooser.html#module-tkinter.colorchooser) (Tk) | Color choosing dialog |
| [`tkinter.commondialog`](https://docs.python.org/3/library/dialog.html#module-tkinter.commondialog) (Tk) | Tkinter base class for dialogs |
| [`tkinter.dnd`](https://docs.python.org/3/library/tkinter.dnd.html#module-tkinter.dnd) (Tk) | Tkinter drag-and-drop interface |
| [`tkinter.filedialog`](https://docs.python.org/3/library/dialog.html#module-tkinter.filedialog) (Tk) | Dialog classes for file selection |
| [`tkinter.font`](https://docs.python.org/3/library/tkinter.font.html#module-tkinter.font) (Tk) | Tkinter font-wrapping class |
| [`tkinter.messagebox`](https://docs.python.org/3/library/tkinter.messagebox.html#module-tkinter.messagebox) (Tk) | Various types of alert dialogs |
| [`tkinter.scrolledtext`](https://docs.python.org/3/library/tkinter.scrolledtext.html#module-tkinter.scrolledtext) (Tk) | Text widget with a vertical scroll bar |
| [`tkinter.simpledialog`](https://docs.python.org/3/library/dialog.html#module-tkinter.simpledialog) (Tk) | Simple dialog windows |
| [`tkinter.tix`](https://docs.python.org/3/library/tkinter.tix.html#module-tkinter.tix) | Tk Extension Widgets for Tkinter |
| [`tkinter.ttk`](https://docs.python.org/3/library/tkinter.ttk.html#module-tkinter.ttk) | Tk themed widget set |
| [`token`](https://docs.python.org/3/library/token.html#module-token) | Constants representing terminal nodes of the parse tree |
| [`tokenize`](https://docs.python.org/3/library/tokenize.html#module-tokenize) | Lexical scanner for Python source code |
| [`trace`](https://docs.python.org/3/library/trace.html#module-trace) | Trace or track Python statement execution |
| [`traceback`](https://docs.python.org/3/library/traceback.html#module-traceback) | Print or retrieve a stack traceback |
| [`tracemalloc`](https://docs.python.org/3/library/tracemalloc.html#module-tracemalloc) | Trace memory allocations |
| [`tty`](https://docs.python.org/3/library/tty.html#module-tty) (Unix) | Utility functions that perform common terminal control operations |
| [`turtle`](https://docs.python.org/3/library/turtle.html#module-turtle) | An educational framework for simple graphics applications |
| [`turtledemo`](https://docs.python.org/3/library/turtle.html#module-turtledemo) | A viewer for example turtle scripts |
| [`types`](https://docs.python.org/3/library/types.html#module-types) | Names for built-in types |
| [`typing`](https://docs.python.org/3/library/typing.html#module-typing) | Support for type hints (see :pep:`484`) |
| **U** | |
| [`unicodedata`](https://docs.python.org/3/library/unicodedata.html#module-unicodedata) | Access the Unicode Database |
| [`unittest`](https://docs.python.org/3/library/unittest.html#module-unittest) | Unit testing framework for Python |
| [`unittest.mock`](https://docs.python.org/3/library/unittest.mock.html#module-unittest.mock) | Mock object library |
| [`urllib`](https://docs.python.org/3/library/urllib.html#module-urllib) | |
| [`urllib.error`](https://docs.python.org/3/library/urllib.error.html#module-urllib.error) | Exception classes raised by urllib.request |
| [`urllib.parse`](https://docs.python.org/3/library/urllib.parse.html#module-urllib.parse) | Parse URLs into or assemble them from components |
| [`urllib.request`](https://docs.python.org/3/library/urllib.request.html#module-urllib.request) | Extensible library for opening URLs |
| [`urllib.response`](https://docs.python.org/3/library/urllib.request.html#module-urllib.response) | Response classes used by urllib |
| [`urllib.robotparser`](https://docs.python.org/3/library/urllib.robotparser.html#module-urllib.robotparser) | Load a robots.txt file and answer questions about fetchability of other URLs |
| [`uu`](https://docs.python.org/3/library/uu.html#module-uu) | Encode and decode files in uuencode format |
| [`uuid`](https://docs.python.org/3/library/uuid.html#module-uuid) | UUID objects (universally unique identifiers) according to RFC 4122 |
| **V** | |
| [`venv`](https://docs.python.org/3/library/venv.html#module-venv) | Creation of virtual environments |
| **W** | |
| [`warnings`](https://docs.python.org/3/library/warnings.html#module-warnings) | Issue warning messages and control their disposition |
| [`wave`](https://docs.python.org/3/library/wave.html#module-wave) | Provide an interface to the WAV sound format |
| [`weakref`](https://docs.python.org/3/library/weakref.html#module-weakref) | Support for weak references and weak dictionaries |
| [`webbrowser`](https://docs.python.org/3/library/webbrowser.html#module-webbrowser) | Easy-to-use controller for Web browsers |
| [`winreg`](https://docs.python.org/3/library/winreg.html#module-winreg) (Windows) | Routines and objects for manipulating the Windows registry |
| [`winsound`](https://docs.python.org/3/library/winsound.html#module-winsound) (Windows) | Access to the sound-playing machinery for Windows |
| [`wsgiref`](https://docs.python.org/3/library/wsgiref.html#module-wsgiref) | WSGI Utilities and Reference Implementation |
| [`wsgiref.handlers`](https://docs.python.org/3/library/wsgiref.html#module-wsgiref.handlers) | WSGI server/gateway base classes |
| [`wsgiref.headers`](https://docs.python.org/3/library/wsgiref.html#module-wsgiref.headers) | WSGI response header tools |
| [`wsgiref.simple_server`](https://docs.python.org/3/library/wsgiref.html#module-wsgiref.simple_server) | A simple WSGI HTTP server |
| [`wsgiref.util`](https://docs.python.org/3/library/wsgiref.html#module-wsgiref.util) | WSGI environment utilities |
| [`wsgiref.validate`](https://docs.python.org/3/library/wsgiref.html#module-wsgiref.validate) | WSGI conformance checker |
| **X** | |
| [`xdrlib`](https://docs.python.org/3/library/xdrlib.html#module-xdrlib) | Encoders and decoders for the External Data Representation (XDR) |
| [`xml`](https://docs.python.org/3/library/xml.html#module-xml) | Package containing XML processing modules |
| [`xml.dom`](https://docs.python.org/3/library/xml.dom.html#module-xml.dom) | Document Object Model API for Python |
| [`xml.dom.minidom`](https://docs.python.org/3/library/xml.dom.minidom.html#module-xml.dom.minidom) | Minimal Document Object Model (DOM) implementation |
| [`xml.dom.pulldom`](https://docs.python.org/3/library/xml.dom.pulldom.html#module-xml.dom.pulldom) | Support for building partial DOM trees from SAX events |
| [`xml.etree.ElementTree`](https://docs.python.org/3/library/xml.etree.elementtree.html#module-xml.etree.ElementTree) | Implementation of the ElementTree API |
| [`xml.parsers.expat`](https://docs.python.org/3/library/pyexpat.html#module-xml.parsers.expat) | An interface to the Expat non-validating XML parser |
| [`xml.parsers.expat.errors`](https://docs.python.org/3/library/pyexpat.html#module-xml.parsers.expat.errors) | | 
| [`xml.parsers.expat.model`](https://docs.python.org/3/library/pyexpat.html#module-xml.parsers.expat.model) | | 
| [`xml.sax`](https://docs.python.org/3/library/xml.sax.html#module-xml.sax) | Package containing SAX2 base classes and convenience functions |
| [`xml.sax.handler`](https://docs.python.org/3/library/xml.sax.handler.html#module-xml.sax.handler) | Base classes for SAX event handlers |
| [`xml.sax.saxutils`](https://docs.python.org/3/library/xml.sax.utils.html#module-xml.sax.saxutils) | Convenience functions and classes for use with SAX |
| [`xml.sax.xmlreader`](https://docs.python.org/3/library/xml.sax.reader.html#module-xml.sax.xmlreader) | Interface which SAX-compliant XML parsers must implement |
| `xmlrpc` | | 
| [`xmlrpc.client`](https://docs.python.org/3/library/xmlrpc.client.html#module-xmlrpc.client) | XML-RPC client access |
| [`xmlrpc.server`](https://docs.python.org/3/library/xmlrpc.server.html#module-xmlrpc.server) | Basic XML-RPC server implementations |
| **Z** | |
| [`zipapp`](https://docs.python.org/3/library/zipapp.html#module-zipapp) | Manage executable Python zip archives |
| [`zipfile`](https://docs.python.org/3/library/zipfile.html#module-zipfile) | Read and write ZIP-format archive files |
| [`zipimport`](https://docs.python.org/3/library/zipimport.html#module-zipimport) | Support for importing Python modules from ZIP archives |
| [`zlib`](https://docs.python.org/3/library/zlib.html#module-zlib) | Low-level interface to compression and decompression routines compatible with gzip |
| [`zoneinfo`](https://docs.python.org/3/library/zoneinfo.html#module-zoneinfo) | IANA time zone support |

## W3 general reference links with descriptions

### Built-in functions 

| Function | Description |
| --: | :-- |
| [`abs()`](https://www.w3schools.com/python/ref_func_abs.asp) | Returns the absolute value of a number |
| [`all()`](https://www.w3schools.com/python/ref_func_all.asp) | Returns True if all items in an iterable object are true |
| [`any()`](https://www.w3schools.com/python/ref_func_any.asp) | Returns True if any item in an iterable object is true |
| [`ascii()`](https://www.w3schools.com/python/ref_func_ascii.asp) | Returns a readable version of an object. Replaces none-ascii characters with escape character |
| [`bin()`](https://www.w3schools.com/python/ref_func_bin.asp) | Returns the binary version of a number |
| [`bool()`](https://www.w3schools.com/python/ref_func_bool.asp) | Returns the boolean value of the specified object |
| [`bytearray()`](https://www.w3schools.com/python/ref_func_bytearray.asp) | Returns an array of bytes |
| [`bytes()`](https://www.w3schools.com/python/ref_func_bytes.asp) | Returns a bytes object |
| [`callable()`](https://www.w3schools.com/python/ref_func_callable.asp) | Returns True if the specified object is callable, otherwise False |
| [`chr()`](https://www.w3schools.com/python/ref_func_chr.asp) | Returns a character from the specified Unicode code. |
| `classmethod()` | Converts a method into a class method |
| [`compile()`](https://www.w3schools.com/python/ref_func_compile.asp) | Returns the specified source as an object, ready to be executed |
| [`complex()`](https://www.w3schools.com/python/ref_func_complex.asp) | Returns a complex number |
| [`delattr()`](https://www.w3schools.com/python/ref_func_delattr.asp) | Deletes the specified attribute (property or method) from the specified object |
| [`dict()`](https://www.w3schools.com/python/ref_func_dict.asp) | Returns a dictionary (Array) |
| [`dir()`](https://www.w3schools.com/python/ref_func_dir.asp) | Returns a list of the specified object's properties and methods |
| [`divmod()`](https://www.w3schools.com/python/ref_func_divmod.asp) | Returns the quotient and the remainder when argument1 is divided by argument2 |
| [`enumerate()`](https://www.w3schools.com/python/ref_func_enumerate.asp) | Takes a collection (e.g. a tuple) and returns it as an enumerate object |
| [`eval()`](https://www.w3schools.com/python/ref_func_eval.asp) | Evaluates and executes an expression |
| [`exec()`](https://www.w3schools.com/python/ref_func_exec.asp) | Executes the specified code (or object) |
| [`filter()`](https://www.w3schools.com/python/ref_func_filter.asp) | Use a filter function to exclude items in an iterable object |
| [`float()`](https://www.w3schools.com/python/ref_func_float.asp) | Returns a floating point number |
| [`format()`](https://www.w3schools.com/python/ref_func_format.asp) | Formats a specified value |
| [`frozenset()`](https://www.w3schools.com/python/ref_func_frozenset.asp) | Returns a frozenset object |
| [`getattr()`](https://www.w3schools.com/python/ref_func_getattr.asp) | Returns the value of the specified attribute (property or method) |
| [`globals()`](https://www.w3schools.com/python/ref_func_globals.asp) | Returns the current global symbol table as a dictionary |
| [`hasattr()`](https://www.w3schools.com/python/ref_func_hasattr.asp) | Returns True if the specified object has the specified attribute (property/method) |
| `hash()` | Returns the hash value of a specified object |
| `help()` | Executes the built-in help system |
| [`hex()`](https://www.w3schools.com/python/ref_func_hex.asp) | Converts a number into a hexadecimal value |
| [`id()`](https://www.w3schools.com/python/ref_func_id.asp) | Returns the id of an object |
| [`input()`](https://www.w3schools.com/python/ref_func_input.asp) | Allowing user input |
| [`int()`](https://www.w3schools.com/python/ref_func_int.asp) | Returns an integer number |
| [`isinstance()`](https://www.w3schools.com/python/ref_func_isinstance.asp) | Returns True if a specified object is an instance of a specified object |
| [`issubclass()`](https://www.w3schools.com/python/ref_func_issubclass.asp) | Returns True if a specified class is a subclass of a specified object |
| [`iter()`](https://www.w3schools.com/python/ref_func_iter.asp) | Returns an iterator object |
| [`len()`](https://www.w3schools.com/python/ref_func_len.asp) | Returns the length of an object |
| [`list()`](https://www.w3schools.com/python/ref_func_list.asp) | Returns a list |
| [`locals()`](https://www.w3schools.com/python/ref_func_locals.asp) | Returns an updated dictionary of the current local symbol table |
| [`map()`](https://www.w3schools.com/python/ref_func_map.asp) | Returns the specified iterator with the specified function applied to each item |
| [`max()`](https://www.w3schools.com/python/ref_func_max.asp) | Returns the largest item in an iterable |
| [`memoryview()`](https://www.w3schools.com/python/ref_func_memoryview.asp) | Returns a memory view object |
| [`min()`](https://www.w3schools.com/python/ref_func_min.asp) | Returns the smallest item in an iterable |
| [`next()`](https://www.w3schools.com/python/ref_func_next.asp) | Returns the next item in an iterable |
| [`object()`](https://www.w3schools.com/python/ref_func_object.asp) | Returns a new object |
| [`oct()`](https://www.w3schools.com/python/ref_func_oct.asp) | Converts a number into an octal |
| [`open()`](https://www.w3schools.com/python/ref_func_open.asp) | Opens a file and returns a file object |
| [`ord()`](https://www.w3schools.com/python/ref_func_ord.asp) | Convert an integer representing the Unicode of the specified character |
| [`pow()`](https://www.w3schools.com/python/ref_func_pow.asp) | Returns the value of x to the power of y |
| [`print()`](https://www.w3schools.com/python/ref_func_print.asp) | Prints to the standard output device |
| `property()` | Gets, sets, deletes a property |
| [`range()`](https://www.w3schools.com/python/ref_func_range.asp) | Returns a sequence of numbers, starting from 0 and increments by 1 (by default) |
| `repr()` | Returns a readable version of an object |
| [`reversed()`](https://www.w3schools.com/python/ref_func_reversed.asp) | Returns a reversed iterator |
| [`round()`](https://www.w3schools.com/python/ref_func_round.asp) | Rounds a numbers |
| [`set()`](https://www.w3schools.com/python/ref_func_set.asp) | Returns a new set object |
| [`setattr()`](https://www.w3schools.com/python/ref_func_setattr.asp) | Sets an attribute (property/method) of an object |
| [`slice()`](https://www.w3schools.com/python/ref_func_slice.asp) | Returns a slice object |
| [`sorted()`](https://www.w3schools.com/python/ref_func_sorted.asp) | Returns a sorted list |
| `@staticmethod()` | Converts a method into a static method |
| [`str()`](https://www.w3schools.com/python/ref_func_str.asp) | Returns a string object |
| [`sum()`](https://www.w3schools.com/python/ref_func_sum.asp) | Sums the items of an iterator |
| [`super()`](https://www.w3schools.com/python/ref_func_super.asp) | Returns an object that represents the parent class |
| [`tuple()`](https://www.w3schools.com/python/ref_func_tuple.asp) | Returns a tuple |
| [`type()`](https://www.w3schools.com/python/ref_func_type.asp) | Returns the type of an object |
| [`vars()`](https://www.w3schools.com/python/ref_func_vars.asp) | Returns the __dict__ property of an object |
| [`zip()`](https://www.w3schools.com/python/ref_func_zip.asp) | Returns an iterator, from two or more iterators |

### String methods

| Method | Description |
| --: | :-- |
| [`capitalize()`](https://www.w3schools.com/python/ref_string_capitalize.asp) | Converts the first character to upper case |
| [`casefold()`](https://www.w3schools.com/python/ref_string_casefold.asp) | Converts string into lower case |
| [`center()`](https://www.w3schools.com/python/ref_string_center.asp) | Returns a centered string |
| [`count()`](https://www.w3schools.com/python/ref_string_count.asp) | Returns the number of times a specified value occurs in a string |
| [`encode()`](https://www.w3schools.com/python/ref_string_encode.asp) | Returns an encoded version of the string |
| [`endswith()`](https://www.w3schools.com/python/ref_string_endswith.asp) | Returns true if the string ends with the specified value |
| [`expandtabs()`](https://www.w3schools.com/python/ref_string_expandtabs.asp) | Sets the tab size of the string |
| [`find()`](https://www.w3schools.com/python/ref_string_find.asp) | Searches the string for a specified value and returns the position of where it was found |
| [`format()`](https://www.w3schools.com/python/ref_string_format.asp) | Formats specified values in a string |
| `format_map()` | Formats specified values in a string |
| [`index()`](https://www.w3schools.com/python/ref_string_index.asp) | Searches the string for a specified value and returns the position of where it was found |
| [`isalnum()`](https://www.w3schools.com/python/ref_string_isalnum.asp) | Returns True if all characters in the string are alphanumeric |
| [`isalpha()`](https://www.w3schools.com/python/ref_string_isalpha.asp) | Returns True if all characters in the string are in the alphabet |
| [`isdecimal()`](https://www.w3schools.com/python/ref_string_isdecimal.asp) | Returns True if all characters in the string are decimals |
| [`isdigit()`](https://www.w3schools.com/python/ref_string_isdigit.asp) | Returns True if all characters in the string are digits |
| [`isidentifier()`](https://www.w3schools.com/python/ref_string_isidentifier.asp) | Returns True if the string is an identifier |
| [`islower()`](https://www.w3schools.com/python/ref_string_islower.asp) | Returns True if all characters in the string are lower case |
| [`isnumeric()`](https://www.w3schools.com/python/ref_string_isnumeric.asp) | Returns True if all characters in the string are numeric |
| [`isprintable()`](https://www.w3schools.com/python/ref_string_isprintable.asp) | Returns True if all characters in the string are printable |
| [`isspace()`](https://www.w3schools.com/python/ref_string_isspace.asp) | Returns True if all characters in the string are whitespaces |
| [`istitle()`](https://www.w3schools.com/python/ref_string_istitle.asp) | Returns True if the string follows the rules of a title |
| [`isupper()`](https://www.w3schools.com/python/ref_string_isupper.asp) | Returns True if all characters in the string are upper case |
| [`join()`](https://www.w3schools.com/python/ref_string_join.asp) | Joins the elements of an iterable to the end of the string |
| [`ljust()`](https://www.w3schools.com/python/ref_string_ljust.asp) | Returns a left justified version of the string |
| [`lower()`](https://www.w3schools.com/python/ref_string_lower.asp) | Converts a string into lower case |
| [`lstrip()`](https://www.w3schools.com/python/ref_string_lstrip.asp) | Returns a left trim version of the string |
| [`maketrans()`](https://www.w3schools.com/python/ref_string_maketrans.asp) | Returns a translation table to be used in translations |
| [`partition()`](https://www.w3schools.com/python/ref_string_partition.asp) | Returns a tuple where the string is parted into three parts |
| [`replace()`](https://www.w3schools.com/python/ref_string_replace.asp) | Returns a string where a specified value is replaced with a specified value |
| [`rfind()`](https://www.w3schools.com/python/ref_string_rfind.asp) | Searches the string for a specified value and returns the last position of where it was found |
| [`rindex()`](https://www.w3schools.com/python/ref_string_rindex.asp) | Searches the string for a specified value and returns the last position of where it was found |
| [`rjust()`](https://www.w3schools.com/python/ref_string_rjust.asp) | Returns a right justified version of the string |
| [`rpartition()`](https://www.w3schools.com/python/ref_string_rpartition.asp) | Returns a tuple where the string is parted into three parts |
| [`rsplit()`](https://www.w3schools.com/python/ref_string_rsplit.asp) | Splits the string at the specified separator, and returns a list |
| [`rstrip()`](https://www.w3schools.com/python/ref_string_rstrip.asp) | Returns a right trim version of the string |
| [`split()`](https://www.w3schools.com/python/ref_string_split.asp) | Splits the string at the specified separator, and returns a list |
| [`splitlines()`](https://www.w3schools.com/python/ref_string_splitlines.asp) | Splits the string at line breaks and returns a list |
| [`startswith()`](https://www.w3schools.com/python/ref_string_startswith.asp) | Returns true if the string starts with the specified value |
| [`strip()`](https://www.w3schools.com/python/ref_string_strip.asp) | Returns a trimmed version of the string |
| [`swapcase()`](https://www.w3schools.com/python/ref_string_swapcase.asp) | Swaps cases, lower case becomes upper case and vice versa |
| [`title()`](https://www.w3schools.com/python/ref_string_title.asp) | Converts the first character of each word to upper case |
| [`translate()`](https://www.w3schools.com/python/ref_string_translate.asp) | Returns a translated string |
| [`upper()`](https://www.w3schools.com/python/ref_string_upper.asp) | Converts a string into upper case |
| [`zfill()`](https://www.w3schools.com/python/ref_string_zfill.asp) | Fills the string with a specified number of 0 values at the beginning |

### List methods

| Method | Description |
| --: | :-- |
| [`append()`](https://www.w3schools.com/python/ref_list_append.asp) | Adds an element at the end of the list |
| [`clear()`](https://www.w3schools.com/python/ref_list_clear.asp) | Removes all the elements from the list |
| [`copy()`](https://www.w3schools.com/python/ref_list_copy.asp) | Returns a copy of the list |
| [`count()`](https://www.w3schools.com/python/ref_list_count.asp) | Returns the number of elements with the specified value |
| [`extend()`](https://www.w3schools.com/python/ref_list_extend.asp) | Add the elements of a list (or any iterable), to the end of the current list |
| [`index()`](https://www.w3schools.com/python/ref_list_index.asp) | Returns the index of the first element with the specified value |
| [`insert()`](https://www.w3schools.com/python/ref_list_insert.asp) | Adds an element at the specified position |
| [`pop()`](https://www.w3schools.com/python/ref_list_pop.asp) | Removes the element at the specified position |
| [`remove()`](https://www.w3schools.com/python/ref_list_remove.asp) | Removes the first item with the specified value |
| [`reverse()`](https://www.w3schools.com/python/ref_list_reverse.asp) | Reverses the order of the list |
| [`sort()`](https://www.w3schools.com/python/ref_list_sort.asp) | Sorts the list |

### Dictionary methods

| Method | Description |
| --: | :-- |
| [`clear()`](https://www.w3schools.com/python/ref_dictionary_clear.asp) | Removes all the elements from the dictionary |
| [`copy()`](https://www.w3schools.com/python/ref_dictionary_copy.asp) | Returns a copy of the dictionary |
| [`fromkeys()`](https://www.w3schools.com/python/ref_dictionary_fromkeys.asp) | Returns a dictionary with the specified keys and value |
| [`get()`](https://www.w3schools.com/python/ref_dictionary_get.asp) | Returns the value of the specified key |
| [`items()`](https://www.w3schools.com/python/ref_dictionary_items.asp) | Returns a list containing a tuple for each key value pair |
| [`keys()`](https://www.w3schools.com/python/ref_dictionary_keys.asp) | Returns a list containing the dictionary's keys |
| [`pop()`](https://www.w3schools.com/python/ref_dictionary_pop.asp) | Removes the element with the specified key |
| [`popitem()`](https://www.w3schools.com/python/ref_dictionary_popitem.asp) | Removes the last inserted key-value pair |
| [`setdefault()`](https://www.w3schools.com/python/ref_dictionary_setdefault.asp) | Returns the value of the specified key. If the key does not exist: insert the key, with the specified value |
| [`update()`](https://www.w3schools.com/python/ref_dictionary_update.asp) | Updates the dictionary with the specified key-value pairs |
| [`values()`](https://www.w3schools.com/python/ref_dictionary_values.asp) | Returns a list of all the values in the dictionary |

### Tuple methods

| Method | Description |
| --: | :-- |
| [`count()`](https://www.w3schools.com/python/ref_tuple_count.asp) | Returns the number of times a specified value occurs in a tuple |
| [`index()`](https://www.w3schools.com/python/ref_tuple_index.asp) | Searches the tuple for a specified value and returns the position of where it was found |

### Set methods

| Method | Description |
| --: | :-- |
| [`add()`](https://www.w3schools.com/python/ref_set_add.asp) | Adds an element to the set |
| [`clear()`](https://www.w3schools.com/python/ref_set_clear.asp) | Removes all the elements from the set |
| [`copy()`](https://www.w3schools.com/python/ref_set_copy.asp) | Returns a copy of the set |
| [`difference()`](https://www.w3schools.com/python/ref_set_difference.asp) | Returns a set containing the difference between two or more sets |
| [`difference_update()`](https://www.w3schools.com/python/ref_set_difference_update.asp) | Removes the items in this set that are also included in another, specified set |
| [`discard()`](https://www.w3schools.com/python/ref_set_discard.asp) | Remove the specified item |
| [`intersection()`](https://www.w3schools.com/python/ref_set_intersection.asp) | Returns a set, that is the intersection of two other sets |
| [`intersection_update()`](https://www.w3schools.com/python/ref_set_intersection_update.asp) | Removes the items in this set that are not present in other, specified set(s) |
| [`isdisjoint()`](https://www.w3schools.com/python/ref_set_isdisjoint.asp) | Returns whether two sets have a intersection or not |
| [`issubset()`](https://www.w3schools.com/python/ref_set_issubset.asp) | Returns whether another set contains this set or not |
| [`issuperset()`](https://www.w3schools.com/python/ref_set_issuperset.asp) | Returns whether this set contains another set or not |
| [`pop()`](https://www.w3schools.com/python/ref_set_pop.asp) | Removes an element from the set |
| [`remove()`](https://www.w3schools.com/python/ref_set_remove.asp) | Removes the specified element |
| [`symmetric_difference()`](https://www.w3schools.com/python/ref_set_symmetric_difference.asp) | Returns a set with the symmetric differences of two sets |
| [`symmetric_difference_update()`](https://www.w3schools.com/python/ref_set_symmetric_difference_update.asp) | inserts the symmetric differences from this set and another |
| [`union()`](https://www.w3schools.com/python/ref_set_union.asp) | Return a set containing the union of sets |
| [`update()`](https://www.w3schools.com/python/ref_set_update.asp) | Update the set with another set, or any other iterable |

### File methods

| Method | Description |
| --: | :-- |
| [`close()`](https://www.w3schools.com/python/ref_file_close.asp) | Closes the file |
| `detach()` | Returns the separated raw stream from the buffer |
| [`fileno()`](https://www.w3schools.com/python/ref_file_fileno.asp) | Returns a number that represents the stream, from the operating system's perspective |
| [`flush()`](https://www.w3schools.com/python/ref_file_flush.asp) | Flushes the internal buffer |
| [`isatty()`](https://www.w3schools.com/python/ref_file_isatty.asp) | Returns whether the file stream is interactive or not |
| [`read()`](https://www.w3schools.com/python/ref_file_read.asp) | Returns the file content |
| [`readable()`](https://www.w3schools.com/python/ref_file_readable.asp) | Returns whether the file stream can be read or not |
| [`readline()`](https://www.w3schools.com/python/ref_file_readline.asp) | Returns one line from the file |
| [`readlines()`](https://www.w3schools.com/python/ref_file_readlines.asp) | Returns a list of lines from the file |
| [`seek()`](https://www.w3schools.com/python/ref_file_seek.asp) | Change the file position |
| [`seekable()`](https://www.w3schools.com/python/ref_file_seekable.asp) | Returns whether the file allows us to change the file position |
| [`tell()`](https://www.w3schools.com/python/ref_file_tell.asp) | Returns the current file position |
| [`truncate()`](https://www.w3schools.com/python/ref_file_truncate.asp) | Resizes the file to a specified size |
| [`writable()`](https://www.w3schools.com/python/ref_file_writable.asp) | Returns whether the file can be written to or not |
| [`write()`](https://www.w3schools.com/python/ref_file_write.asp) | Writes the specified string to the file |
| [`writelines()`](https://www.w3schools.com/python/ref_file_writelines.asp) | Writes a list of strings to the file |

### Keywords

| Keyword | Description |
| --: | :-- |
| [`and`](https://www.w3schools.com/python/ref_keyword_and.asp) | A logical operator |
| [`as`](https://www.w3schools.com/python/ref_keyword_as.asp) | To create an alias |
| [`assert`](https://www.w3schools.com/python/ref_keyword_assert.asp) | For debugging |
| [`break`](https://www.w3schools.com/python/ref_keyword_break.asp) | To break out of a loop |
| [`class`](https://www.w3schools.com/python/ref_keyword_class.asp) | To define a class |
| [`continue`](https://www.w3schools.com/python/ref_keyword_continue.asp) | To continue to the next iteration of a loop |
| [`def`](https://www.w3schools.com/python/ref_keyword_def.asp) | To define a function |
| [`del`](https://www.w3schools.com/python/ref_keyword_del.asp) | To delete an object |
| [`elif`](https://www.w3schools.com/python/ref_keyword_elif.asp) | Used in conditional statements, same as else if |
| [`else`](https://www.w3schools.com/python/ref_keyword_else.asp) | Used in conditional statements |
| [`except`](https://www.w3schools.com/python/ref_keyword_except.asp) | Used with exceptions, what to do when an exception occurs |
| [`False`](https://www.w3schools.com/python/ref_keyword_false.asp) | Boolean value, result of comparison operations |
| [`finally`](https://www.w3schools.com/python/ref_keyword_finally.asp) | Used with exceptions, a block of code that will be executed no matter if there is an exception or not |
| [`for`](https://www.w3schools.com/python/ref_keyword_for.asp) | To create a for loop |
| [`from`](https://www.w3schools.com/python/ref_keyword_from.asp) | To import specific parts of a module |
| [`global`](https://www.w3schools.com/python/ref_keyword_global.asp) | To declare a global variable |
| [`if`](https://www.w3schools.com/python/ref_keyword_if.asp) | To make a conditional statement |
| [`import`](https://www.w3schools.com/python/ref_keyword_import.asp) | To import a module |
| [`in`](https://www.w3schools.com/python/ref_keyword_in.asp) | To check if a value is present in a list, tuple, etc. |
| [`is`](https://www.w3schools.com/python/ref_keyword_is.asp) | To test if two variables are equal |
| [`lambda`](https://www.w3schools.com/python/ref_keyword_lambda.asp) | To create an anonymous function |
| [`None`](https://www.w3schools.com/python/ref_keyword_none.asp) | Represents a null value |
| [`nonlocal`](https://www.w3schools.com/python/ref_keyword_nonlocal.asp) | To declare a non-local variable |
| [`not`](https://www.w3schools.com/python/ref_keyword_not.asp) | A logical operator |
| [`or`](https://www.w3schools.com/python/ref_keyword_or.asp) | A logical operator |
| [`pass`](https://www.w3schools.com/python/ref_keyword_pass.asp) | A null statement, a statement that will do nothing |
| [`raise`](https://www.w3schools.com/python/ref_keyword_raise.asp) | To raise an exception |
| [`return`](https://www.w3schools.com/python/ref_keyword_return.asp) | To exit a function and return a value |
| [`True`](https://www.w3schools.com/python/ref_keyword_true.asp) | Boolean value, result of comparison operations |
| [`try`](https://www.w3schools.com/python/ref_keyword_try.asp) | To make a try...except statement |
| [`while`](https://www.w3schools.com/python/ref_keyword_while.asp) | To create a while loop |
| `with` | Used to simplify exception handling |
| `yield` | To end a function, returns a generator |

### Exceptions

| Exception | Description |
| --: | :-- |
| `ArithmeticError` | Raised when an error occurs in numeric calculations |
| `AssertionError` | Raised when an assert statement fails |
| `AttributeError` | Raised when attribute reference or assignment fails |
| `Exception` | Base class for all exceptions |
| `EOFError` | Raised when the input() method hits an "end of file" condition (EOF) |
| `FloatingPointError` | Raised when a floating point calculation fails |
| `GeneratorExit` | Raised when a generator is closed (with the close() method) |
| `ImportError` | Raised when an imported module does not exist |
| `IndentationError` | Raised when indendation is not correct |
| `IndexError` | Raised when an index of a sequence does not exist |
| `KeyError` | Raised when a key does not exist in a dictionary |
| `KeyboardInterrupt` | Raised when the user presses Ctrl+c, Ctrl+z or Delete |
| `LookupError` | Raised when errors raised cant be found |
| `MemoryError` | Raised when a program runs out of memory |
| `NameError` | Raised when a variable does not exist |
| `NotImplementedError` | Raised when an abstract method requires an inherited class to override the method |
| `OSError` | Raised when a system related operation causes an error |
| `OverflowError` | Raised when the result of a numeric calculation is too large |
| `ReferenceError` | Raised when a weak reference object does not exist |
| `RuntimeError` | Raised when an error occurs that do not belong to any specific expections |
| `StopIteration` | Raised when the next() method of an iterator has no further values |
| `SyntaxError` | Raised when a syntax error occurs |
| `TabError` | Raised when indentation consists of tabs or spaces |
| `SystemError` | Raised when a system error occurs |
| `SystemExit` | Raised when the sys.exit() function is called |
| `TypeError` | Raised when two different types are combined |
| `UnboundLocalError` | Raised when a local variable is referenced before assignment |
| `UnicodeError` | Raised when a unicode problem occurs |
| `UnicodeEncodeError` | Raised when a unicode encoding problem occurs |
| `UnicodeDecodeError` | Raised when a unicode decoding problem occurs |
| `UnicodeTranslateError` | Raised when a unicode translation problem occurs |
| `ValueError` | Raised when there is a wrong value in a specified data type |
| `ZeroDivisionError` | Raised when the second operator in a division is zero |

### Glossary

| Feature | Description |
| --: | :-- |
| [Indentation](https://www.w3schools.com/python/gloss_python_indentation.asp) | Indentation refers to the spaces at the beginning of a code line |
| [Comments](https://www.w3schools.com/python/gloss_python_comments.asp) | Comments are code lines that will not be executed |
| [Multi Line Comments](https://www.w3schools.com/python/gloss_python_multi_line_comments.asp) | How to insert comments on multiple lines |
| [Creating Variables](https://www.w3schools.com/python/gloss_python_creating_variables.asp) | Variables are containers for storing data values |
| [Variable Names](https://www.w3schools.com/python/gloss_python_variable_names.asp) | How to name your variables |
| [Assign Values to Multiple Variables](https://www.w3schools.com/python/gloss_python_assign_value_to_multiple_variables.asp) | How to assign values to multiple variables |
| [Output Variables](https://www.w3schools.com/python/gloss_python_variable_output.asp) | Use the print statement to output variables |
| [String Concatenation](https://www.w3schools.com/python/gloss_python_string_concatenation.asp) | How to combine strings |
| [Global Variables](https://www.w3schools.com/python/gloss_python_global_variables.asp) | Global variables are variables that belongs to the global scope |
| [Built-In Data Types](https://www.w3schools.com/python/gloss_python_built-in_data_types.asp) | Python has a set of built-in data types |
| [Getting Data Type](https://www.w3schools.com/python/gloss_python_getting_data_type.asp) | How to get the data type of an object |
| [Setting Data Type](https://www.w3schools.com/python/gloss_python_setting_data_type.asp) | How to set the data type of an object |
| [Numbers](https://www.w3schools.com/python/gloss_python_numbers.asp) | There are three numeric types in Python |
| [Int](https://www.w3schools.com/python/gloss_python_int.asp) | The integer number type |
| [Float](https://www.w3schools.com/python/gloss_python_float.asp) | The floating number type |
| [Complex](https://www.w3schools.com/python/gloss_python_complex.asp) | The complex number type |
| [Type Conversion](https://www.w3schools.com/python/gloss_python_type_conversion.asp) | How to convert from one number type to another |
| [Random Number](https://www.w3schools.com/python/gloss_python_random_number.asp) | How to create a random number |
| [Specify a Variable Type](https://www.w3schools.com/python/gloss_python_specify_variable_type.asp) | How to specify a certain data type for a variable |
| [String Literals](https://www.w3schools.com/python/gloss_python_string_literals.asp) | How to create string literals |
| [Assigning a String to a Variable](https://www.w3schools.com/python/gloss_python_assign_string_variable.asp) | How to assign a string value to a variable |
| [Multiline Strings](https://www.w3schools.com/python/gloss_python_multi_line_strings.asp) | How to create a multi line string |
| [Strings are Arrays](https://www.w3schools.com/python/gloss_python_strings_are_arrays.asp) | Strings in Python are arrays of bytes representing Unicode characters |
| [Slicing a String](https://www.w3schools.com/python/gloss_python_string_slice.asp) | How to slice a string |
| [Negative Indexing on a String](https://www.w3schools.com/python/gloss_python_string_negative_indexing.asp) | How to use negative indexing when accessing a string |
| [String Length](https://www.w3schools.com/python/gloss_python_string_length.asp) | How to get the length of a string |
| [Check In String](https://www.w3schools.com/python/gloss_python_check_string.asp) | How to check if a string contains a specified phrase |
| [Format String](https://www.w3schools.com/python/gloss_python_string_format.asp) | How to combine two strings |
| [Escape Characters](https://www.w3schools.com/python/gloss_python_escape_characters.asp) | How to use escape characters |
| [Boolean Values](https://www.w3schools.com/python/gloss_python_boolean_values.asp) | True or False |
| [Evaluate Booleans](https://www.w3schools.com/python/gloss_python_evaluate_boolean_values.asp) | Evaluate a value or statement and return either True or False |
| [Return Boolean Value](https://www.w3schools.com/python/gloss_python_return_boolean.asp) | Functions that return a Boolean value |
| [Operators](https://www.w3schools.com/python/gloss_python_operators.asp) | Use operator to perform operations in Python |
| [Arithmetic Operators](https://www.w3schools.com/python/gloss_python_arithmetic_operators.asp) | Arithmetic operator are used to perform common mathematical operations |
| [Assignment Operators](https://www.w3schools.com/python/gloss_python_assignment_operators.asp) | Assignment operators are use to assign values to variables |
| [Comparison Operators](https://www.w3schools.com/python/gloss_python_comparison_operators.asp) | Comparison operators are used to compare two values |
| [Logical Operators](https://www.w3schools.com/python/gloss_python_logical_operators.asp) | Logical operators are used to combine conditional statements |
| [Identity Operators](https://www.w3schools.com/python/gloss_python_identity_operators.asp) | Identity operators are used to see if two objects are in fact the same object |
| [Membership Operators](https://www.w3schools.com/python/gloss_python_membership_operators.asp) | Membership operators are used to test is a sequence is present in an object |
| [Bitwise Operators](https://www.w3schools.com/python/gloss_python_bitwise_operators.asp) | Bitwise operators are used to compare (binary) numbers |
| [Lists](https://www.w3schools.com/python/gloss_python_lists.asp) | A list is an ordered, and changeable, collection |
| [Access List Items](https://www.w3schools.com/python/gloss_python_access_list_items.asp) | How to access items in a list |
| [Change List Item](https://www.w3schools.com/python/gloss_python_change_list_item.asp) | How to change the value of a list item |
| [Loop Through List Items](https://www.w3schools.com/python/gloss_python_loop_list_items.asp) | How to loop through the items in a list |
| [List Comprehension](https://www.w3schools.com/python/gloss_python_list_comprehension.asp) | How use a list comprehensive |
| [Check if List Item Exists](https://www.w3schools.com/python/gloss_python_check_if_list_item_exists.asp) | How to check if a specified item is present in a list |
| [List Length](https://www.w3schools.com/python/gloss_python_list_length.asp) | How to determine the length of a list |
| [Add List Items](https://www.w3schools.com/python/gloss_python_add_list_items.asp) | How to add items to a list |
| [Remove List Items](https://www.w3schools.com/python/gloss_python_remove_list_items.asp) | How to remove list items |
| [Copy a List](https://www.w3schools.com/python/gloss_python_copy_list.asp) | How to copy a list |
| [Join Two Lists](https://www.w3schools.com/python/gloss_python_join_lists.asp) | How to join two lists |
| [Tuple](https://www.w3schools.com/python/gloss_python_tuple.asp) | A tuple is an ordered, and unchangeable, collection |
| [Access Tuple Items](https://www.w3schools.com/python/gloss_python_access_tuple_items.asp) | How to access items in a tuple |
| [Change Tuple Item](https://www.w3schools.com/python/gloss_python_change_tuple_item.asp) | How to change the value of a tuple item |
| [Loop List Items](https://www.w3schools.com/python/gloss_python_loop_tuple_items.asp) | How to loop through the items in a tuple |
| [Check if Tuple Item Exists](https://www.w3schools.com/python/gloss_python_check_if_tuple_item_exists.asp) | How to check if a specified item is present in a tuple |
| [Tuple Length](https://www.w3schools.com/python/gloss_python_tuple_length.asp) | How to determine the length of a tuple |
| [Tuple With One Item](https://www.w3schools.com/python/gloss_python_tuple_one_item.asp) | How to create a tuple with only one item |
| [Remove Tuple Items](https://www.w3schools.com/python/gloss_python_remove_tuple_items.asp) | How to remove tuple items |
| [Join Two Tuples](https://www.w3schools.com/python/gloss_python_join_tuple.asp) | How to join two tuples |
| [Set](https://www.w3schools.com/python/gloss_python_set.asp) | A set is an unordered, and unchangeable, collection |
| [Access Set Items](https://www.w3schools.com/python/gloss_python_access_set_items.asp) | How to access items in a set |
| [Add Set Items](https://www.w3schools.com/python/gloss_python_add_set_items.asp) | How to add items to a set |
| [Loop Set Items](https://www.w3schools.com/python/gloss_python_loop_set_items.asp) | DETTE KAPITTELET MANGLER |
| [Check if Set Item Exists](https://www.w3schools.com/python/gloss_python_check_if_set_item_exists.asp) | DETTE KAPITTELET MANGLER |
| [Set Length](https://www.w3schools.com/python/gloss_python_set_length.asp) | How to determine the length of a set |
| [Remove Set Items](https://www.w3schools.com/python/gloss_python_remove_set_items.asp) | How to remove set items |
| [Join Two Sets](https://www.w3schools.com/python/gloss_python_join_sets.asp) | How to join two sets |
| [Dictionary](https://www.w3schools.com/python/gloss_python_dictionary.asp) | A dictionary is an unordered, and changeable, collection |
| [Access Dictionary Items](https://www.w3schools.com/python/gloss_python_access_dictionary_items.asp) | How to access items in a dictionary |
| [Change Dictionary Item](https://www.w3schools.com/python/gloss_python_change_dictionary_item.asp) | How to change the value of a dictionary item |
| [Loop Dictionary Items](https://www.w3schools.com/python/gloss_python_loop_dictionary_items.asp) | How to loop through the items in a tuple |
| [Check if Dictionary Item Exists](https://www.w3schools.com/python/gloss_python_check_if_dictionary_item_exists.asp) | How to check if a specified item is present in a dictionary |
| [Dictionary Length](https://www.w3schools.com/python/gloss_python_dictionary_length.asp) | How to determine the length of a dictionary |
| [Add Dictionary Item](https://www.w3schools.com/python/gloss_python_dictionary_add_item.asp) | How to add an item to a dictionary |
| [Remove Dictionary Items](https://www.w3schools.com/python/gloss_python_remove_dictionary_items.asp) | How to remove dictionary items |
| [Copy Dictionary](https://www.w3schools.com/python/gloss_python_copy_dictionary.asp) | How to copy a dictionary |
| [Nested Dictionaries](https://www.w3schools.com/python/gloss_python_nested_dictionaries.asp) | A dictionary within a dictionary |
| [If Statement](https://www.w3schools.com/python/gloss_python_if_statement.asp) | How to write an if statement |
| [If Indentation](https://www.w3schools.com/python/gloss_python_if_indentation.asp) | If statemnts in Python relies on indentation (whitespace at the beginning of a line) |
| [Elif](https://www.w3schools.com/python/gloss_python_elif.asp) | elif is the same as "else if" in other programming languages |
| [Else](https://www.w3schools.com/python/gloss_python_else.asp) | How to write an if...else statement |
| [Shorthand If](https://www.w3schools.com/python/gloss_python_if_shorthand.asp) | How to write an if statement in one line |
| [Shorthand If Else](https://www.w3schools.com/python/gloss_python_if_else_shorthand.asp) | How to write an if...else statement in one line |
| [If AND](https://www.w3schools.com/python/gloss_python_if_and.asp) | Use the and keyword to combine if statements |
| [If OR](https://www.w3schools.com/python/gloss_python_if_or.asp) | Use the or keyword to combine if statements |
| [Nested If](https://www.w3schools.com/python/gloss_python_if_nested.asp) | How to write an if statement inside an if statement |
| [The pass Keyword in If](https://www.w3schools.com/python/gloss_python_if_pass.asp) | Use the pass keyword inside empty if statements |
| [While](https://www.w3schools.com/python/gloss_python_while.asp) | How to write a while loop |
| [While Break](https://www.w3schools.com/python/gloss_python_while_break.asp) | How to break a while loop |
| [While Continue](https://www.w3schools.com/python/gloss_python_while_continue.asp) | How to stop the current iteration and continue wit the next |
| [While Else](https://www.w3schools.com/python/gloss_python_while_else.asp) | How to use an else statement in a while loop |
| [For](https://www.w3schools.com/python/gloss_python_for.asp) | How to write a for loop |
| [Loop Through a String](https://www.w3schools.com/python/gloss_python_for_string.asp) | How to loop through a string |
| [For Break](https://www.w3schools.com/python/gloss_python_for_break.asp) | How to break a for loop |
| [For Continue](https://www.w3schools.com/python/gloss_python_for_continue.asp) | How to stop the current iteration and continue wit the next |
| [Looping Through a rangee](https://www.w3schools.com/python/gloss_python_for_range.asp) | How to loop through a range of values |
| [For Else](https://www.w3schools.com/python/gloss_python_for_else.asp) | How to use an else statement in a for loop |
| [Nested Loops](https://www.w3schools.com/python/gloss_python_for_nested.asp) | How to write a loop inside a loop |
| [For pass](https://www.w3schools.com/python/gloss_python_for_pass.asp) | Use the pass keyword inside empty for loops |
| [Function](https://www.w3schools.com/python/gloss_python_function.asp) | How to create a function in Python |
| [Call a Function](https://www.w3schools.com/python/gloss_python_function_call.asp) | How to call a function in Python |
| [Function Arguments](https://www.w3schools.com/python/gloss_python_function_arguments.asp) | How to use arguments in a function |
| [*args](https://www.w3schools.com/python/gloss_python_function_arbitrary_arguments.asp) | To deal with an unknown number of arguments in a function, use the * symbol before the parameter name |
| [Keyword Arguments](https://www.w3schools.com/python/gloss_python_function_keyword_arguments.asp) | How to use keyword arguments in a function |
| [*kwargs](https://www.w3schools.com/python/gloss_python_function_arbitrary_keyword_arguments.asp) | To deal with an unknown number of keyword arguments in a function, use the * symbol before the parameter name |
| [Default Parameter Value](https://www.w3schools.com/python/gloss_python_function_default_parameter.asp) | How to use a default parameter value |
| [Passing a List as an Argument](https://www.w3schools.com/python/gloss_python_function_passing_list.asp) | How to pass a list as an argument |
| [Function Return Value](https://www.w3schools.com/python/gloss_python_function_return_value.asp) | How to return a value from a function |
| [The pass Statement i Functions](https://www.w3schools.com/python/gloss_python_function_pass.asp) | Use the pass statement in empty functions |
| [Function Recursion](https://www.w3schools.com/python/gloss_python_function_recursion.asp) | Functions that can call itself is called recursive functions |
| [Lambda Function](https://www.w3schools.com/python/gloss_python_lambda.asp) | How to create anonymous functions in Python |
| [Why Use Lambda Functions](https://www.w3schools.com/python/gloss_python_lambda_why.asp) | Learn when to use a lambda function or not |
| [Array](https://www.w3schools.com/python/gloss_python_array.asp) | Lists can be used as Arrays |
| [What is an Array](https://www.w3schools.com/python/gloss_python_arrray_what_is.asp) | Arrays are variables that can hold more than one value |
| [Access Arrays](https://www.w3schools.com/python/gloss_python_array_access.asp) | How to access array items |
| [Array Length](https://www.w3schools.com/python/gloss_python_array_length.asp) | How to get the length of an array |
| [Looping Array Elements](https://www.w3schools.com/python/gloss_python_array_loop.asp) | How to loop through array elements |
| [Add Array Element](https://www.w3schools.com/python/gloss_python_array_add.asp) | How to add elements from an array |
| [Remove Array Element](https://www.w3schools.com/python/gloss_python_array_remove.asp) | How to remove elements from an array |
| [Array Methods](https://www.w3schools.com/python/gloss_python_array_methods.asp) | Python has a set of Array/Lists methods |
| [Class](https://www.w3schools.com/python/gloss_python_class.asp) | A class is like an object constructor |
| [Create Class](https://www.w3schools.com/python/gloss_python_class_create.asp) | How to create a class |
| [The Class __init__() Function](https://www.w3schools.com/python/gloss_python_class_init.asp) | The __init__() function is executed when the class is initiated |
| [Object Methods](https://www.w3schools.com/python/gloss_python_object_methods.asp) | Methods in objects are functions that belongs to the object |
| [self](https://www.w3schools.com/python/gloss_python_self.asp) | The self parameter refers to the current instance of the class |
| [Modify Object Properties](https://www.w3schools.com/python/gloss_python_object_modify_properties.asp) | How to modify properties of an object |
| [Delete Object Properties](https://www.w3schools.com/python/gloss_python_object_delete_properties.asp) | How to modify properties of an object |
| [Delete Object](https://www.w3schools.com/python/gloss_python_object_delete.asp) | How to delete an object |
| [Class pass Statement](https://www.w3schools.com/python/gloss_python_class_pass.asp) | Use the pass statement in empty classes |
| [Create Parent Class](https://www.w3schools.com/python/gloss_python_parent_class.asp) | How to create a parent class |
| [Create Child Class](https://www.w3schools.com/python/gloss_python_child_class.asp) | How to create a child class |
| [Create the __init__() Function](https://www.w3schools.com/python/gloss_python_create_init.asp) | How to create the __init__() function |
| [super Function](https://www.w3schools.com/python/gloss_python_super.asp) | The super() function make the child class inherit the parent class |
| [Add Class Properties](https://www.w3schools.com/python/gloss_python_class_add_properties.asp) | How to add a property to a class |
| [Add Class Methods](https://www.w3schools.com/python/gloss_python_class_add_methods.asp) | How to add a method to a class |
| [Iterators](https://www.w3schools.com/python/gloss_python_iterators.asp) | An iterator is an object that contains a countable number of values |
| [Iterator vs Iterable](https://www.w3schools.com/python/gloss_python_iterator_vs_iterable.asp) | What is the difference between an iterator and an iterable |
| [Loop Through an Iterator](https://www.w3schools.com/python/gloss_python_iterator_loop.asp) | How to loop through the elements of an iterator |
| [Create an Iterator](https://www.w3schools.com/python/gloss_python_iterator_create.asp) | How to create an iterator |
| [StopIteration](https://www.w3schools.com/python/gloss_python_iterator_stop.asp) | How to stop an iterator |
| [Global Scope](https://www.w3schools.com/python/gloss_python_global_scope.asp) | When does a variable belong to the global scope? |
| [Global Keyword](https://www.w3schools.com/python/gloss_python_global_keyword.asp) | The global keyword makes the variable global |
| [Create a Module](https://www.w3schools.com/python/gloss_python_module_create.asp) | How to create a module |
| [Variables in Modules](https://www.w3schools.com/python/gloss_python_module_variables.asp) | How to use variables in a module |
| [Renaming a Module](https://www.w3schools.com/python/gloss_python_module_rename.asp) | How to rename a module |
| [Built-in Modules](https://www.w3schools.com/python/gloss_python_module_built-in.asp) | How to import built-in modules |
| [Using the dir() Function](https://www.w3schools.com/python/gloss_python_module_dir.asp) | List all variable names and function names in a module |
| [Import From Module](https://www.w3schools.com/python/gloss_python_module_import_from.asp) | How to import only parts from a module |
| [Datetime Module](https://www.w3schools.com/python/gloss_python_date.asp) | How to work with dates in Python |
| [Date Output](https://www.w3schools.com/python/gloss_python_date_output.asp) | How to output a date |
| [Create a Date Object](https://www.w3schools.com/python/gloss_python_date_create.asp) | How to create a date object |
| [The strftime Method](https://www.w3schools.com/python/gloss_python_date_strftime.asp) | How to format a date object into a readable string |
| [Date Format Codes](https://www.w3schools.com/python/gloss_python_date_format_codes.asp) | The datetime module has a set of legal format codes |
| [JSON](https://www.w3schools.com/python/gloss_python_json.asp) | How to work with JSON in Python |
| [Parse JSON](https://www.w3schools.com/python/gloss_python_json_parse.asp) | How to parse JSON code in Python |
| [Convert into JSON](https://www.w3schools.com/python/gloss_python_convert_into_JSON.asp) | How to convert a Python object in to JSON |
| [Format JSON](https://www.w3schools.com/python/gloss_python_format_json.asp) | How to format JSON output with indentations and line breaks |
| [Sort JSON](https://www.w3schools.com/python/gloss_python_json_sort.asp) | How to sort JSON |
| [RegEx Module](https://www.w3schools.com/python/gloss_python_regex.asp) | How to import the regex module |
| [RegEx Functions](https://www.w3schools.com/python/gloss_python_regex_functions.asp) | The re module has a set of functions |
| [Metacharacters in RegEx](https://www.w3schools.com/python/gloss_python_regex_metacharacters.asp) | Metacharacters are characters with a special meaning |
| [RegEx Special Sequences](https://www.w3schools.com/python/gloss_python_regex_sequences.asp) | A backslash followed by a a character has a special meaning |
| [RegEx Sets](https://www.w3schools.com/python/gloss_python_regex_sets.asp) | A set is a set of characters inside a pair of square brackets with a special meaning |
| [RegEx Match Object](https://www.w3schools.com/python/gloss_python_regex_match.asp) | The Match Object is an object containing information about the search and the result |
| [Install PIP](https://www.w3schools.com/python/gloss_python_pip_install.asp) | How to install PIP |
| [PIP Packages](https://www.w3schools.com/python/gloss_python_pip_packages.asp) | How to download and install a package with PIP |
| [PIP Remove Package](https://www.w3schools.com/python/gloss_python_pip_packages_remove.asp) | How to remove a package with PIP |
| [Error Handling](https://www.w3schools.com/python/gloss_python_error_handling.asp) | How to handle errors in Python |
| [Handle Many Exceptions](https://www.w3schools.com/python/gloss_python_try_except.asp) | How to handle more than one exception |
| [Try Else](https://www.w3schools.com/python/gloss_python_try_else.asp) | How to use the else keyword in a try statement |
| [Try Finally](https://www.w3schools.com/python/gloss_python_try_finally.asp) | How to use the finally keyword in a try statement |
| [raise](https://www.w3schools.com/python/gloss_python_raise.asp) | How to raise an exception in Python |

## W3 School Python module reference with descriptions

### Random module

| Method | Description |
| --: | :-- |
| [`seed()`](https://www.w3schools.com/python/ref_random_seed.asp) | Initialize the random number generator |
| [`getstate()`](https://www.w3schools.com/python/ref_random_getstate.asp) | Returns the current internal state of the random number generator |
| [`setstate()`](https://www.w3schools.com/python/ref_random_setstate.asp) | Restores the internal state of the random number generator |
| [`getrandbits()`](https://www.w3schools.com/python/ref_random_getrandbits.asp) | Returns a number representing the random bits |
| [`randrange()`](https://www.w3schools.com/python/ref_random_randrange.asp) | Returns a random number between the given range |
| [`randint()`](https://www.w3schools.com/python/ref_random_randint.asp) | Returns a random number between the given range |
| [`choice()`](https://www.w3schools.com/python/ref_random_choice.asp) | Returns a random element from the given sequence |
| [`choices()`](https://www.w3schools.com/python/ref_random_choices.asp) | Returns a list with a random selection from the given sequence |
| [`shuffle()`](https://www.w3schools.com/python/ref_random_shuffle.asp) | Takes a sequence and returns the sequence in a random order |
| [`sample()`](https://www.w3schools.com/python/ref_random_sample.asp) | Returns a given sample of a sequence |
| [`random()`](https://www.w3schools.com/python/ref_random_random.asp) | Returns a random float number between 0 and 1 |
| [`uniform()`](https://www.w3schools.com/python/ref_random_uniform.asp) | Returns a random float number between two given parameters |
| [`triangular()`](https://www.w3schools.com/python/ref_random_triangular.asp) | Returns a random float number between two given parameters, you can also set a mode parameter to specify the midpoint between the two other parameters |
| `betavariate()` | Returns a random float number between 0 and 1 based on the Beta distribution (used in statistics) |
| `expovariate()` | Returns a random float number based on the Exponential distribution (used in statistics) |
| `gammavariate()` | Returns a random float number based on the Gamma distribution (used in statistics) |
| `gauss()` | Returns a random float number based on the Gaussian distribution (used in probability theories) |
| `lognormvariate()` | Returns a random float number based on a log-normal distribution (used in probability theories) |
| `normalvariate()` | Returns a random float number based on the normal distribution (used in probability theories) |
| `vonmisesvariate()` | Returns a random float number based on the von Mises distribution (used in directional statistics) |
| `paretovariate()` | Returns a random float number based on the Pareto distribution (used in probability theories) |
| `weibullvariate()` | Returns a random float number based on the Weibull distribution (used in statistics) |

### Requests module

| Method | Description |
| --: | :-- |
| [`delete(url, args)`](https://www.w3schools.com/python/ref_requests_delete.asp) | Sends a DELETE request to the specified url |
| [`get(url, params, args)`](https://www.w3schools.com/python/ref_requests_get.asp) | Sends a GET request to the specified url |
| [`head(url, args)`](https://www.w3schools.com/python/ref_requests_head.asp) | Sends a HEAD request to the specified url |
| `patch(url, data, args)` | Sends a PATCH request to the specified url |
| [`post(url, data, json, args)`](https://www.w3schools.com/python/ref_requests_post.asp) | Sends a POST request to the specified url |
| `put(url, data, args)` | Sends a PUT request to the specified url |
| `request(method, url, args)` | Sends a request of the specified method to the specified url |

### Statistics module

| Method | Description |
| --: | :-- |
| [`statistics.harmonic_mean()`](https://www.w3schools.com/python/ref_stat_harmonic_mean.asp) | Calculates the harmonic mean (central location) of the given data |
| [`statistics.mean()`](https://www.w3schools.com/python/ref_stat_mean.asp) | Calculates the mean (average) of the given data |
| [`statistics.median()`](https://www.w3schools.com/python/ref_stat_median.asp) | Calculates the median (middle value) of the given data |
| [`statistics.median_grouped()`](https://www.w3schools.com/python/ref_stat_median_grouped.asp) | Calculates the median of grouped continuous data |
| [`statistics.median_high()`](https://www.w3schools.com/python/ref_stat_median_high.asp) | Calculates the high median of the given data |
| [`statistics.median_low()`](https://www.w3schools.com/python/ref_stat_median_low.asp) | Calculates the low median of the given data |
| [`statistics.mode()`](https://www.w3schools.com/python/ref_stat_mode.asp) | Calculates the mode (central tendency) of the given numeric or nominal data |
| [`statistics.pstdev()`](https://www.w3schools.com/python/ref_stat_pstdev.asp) | Calculates the standard deviation from an entire population |
| [`statistics.stdev()`](https://www.w3schools.com/python/ref_stat_stdev.asp) | Calculates the standard deviation from a sample of data |
| [`statistics.pvariance()`](https://www.w3schools.com/python/ref_stat_pvariance.asp) | Calculates the variance of an entire population |
| [`statistics.variance()`](https://www.w3schools.com/python/ref_stat_variance.asp) | Calculates the variance from a sample of data |

### Math module

| Method | Description |
| --: | :-- |
| [`math.acos()`](https://www.w3schools.com/python/ref_math_acos.asp) | Returns the arc cosine of a number |
| [`math.acosh()`](https://www.w3schools.com/python/ref_math_acosh.asp) | Returns the inverse hyperbolic cosine of a number |
| [`math.asin()`](https://www.w3schools.com/python/ref_math_asin.asp) | Returns the arc sine of a number |
| [`math.asinh()`](https://www.w3schools.com/python/ref_math_asinh.asp) | Returns the inverse hyperbolic sine of a number |
| [`math.atan()`](https://www.w3schools.com/python/ref_math_atan.asp) | Returns the arc tangent of a number in radians |
| [`math.atan2()`](https://www.w3schools.com/python/ref_math_atan2.asp) | Returns the arc tangent of y/x in radians |
| [`math.atanh()`](https://www.w3schools.com/python/ref_math_atanh.asp) | Returns the inverse hyperbolic tangent of a number |
| [`math.ceil()`](https://www.w3schools.com/python/ref_math_ceil.asp) | Rounds a number up to the nearest integer |
| [`math.comb()`](https://www.w3schools.com/python/ref_math_comb.asp) | Returns the number of ways to choose k items from n items without repetition and order |
| [`math.copysign()`](https://www.w3schools.com/python/ref_math_copysign.asp) | Returns a float consisting of the value of the first parameter and the sign of the second parameter |
| [`math.cos()`](https://www.w3schools.com/python/ref_math_cos.asp) | Returns the cosine of a number |
| [`math.cosh()`](https://www.w3schools.com/python/ref_math_cosh.asp) | Returns the hyperbolic cosine of a number |
| [`math.degrees()`](https://www.w3schools.com/python/ref_math_degrees.asp) | Converts an angle from radians to degrees |
| [`math.dist()`](https://www.w3schools.com/python/ref_math_dist.asp) | Returns the Euclidean distance between two points (p and q), where p and q are the coordinates of that point |
| [`math.erf()`](https://www.w3schools.com/python/ref_math_erf.asp) | Returns the error function of a number |
| [`math.erfc()`](https://www.w3schools.com/python/ref_math_erfc.asp) | Returns the complementary error function of a number |
| [`math.exp()`](https://www.w3schools.com/python/ref_math_exp.asp) | Returns E raised to the power of x |
| [`math.expm1()`](https://www.w3schools.com/python/ref_math_expm1.asp) | Returns Ex - 1 |
| [`math.fabs()`](https://www.w3schools.com/python/ref_math_fabs.asp) | Returns the absolute value of a number |
| [`math.factorial()`](https://www.w3schools.com/python/ref_math_factorial.asp) | Returns the factorial of a number |
| [`math.floor()`](https://www.w3schools.com/python/ref_math_floor.asp) | Rounds a number down to the nearest integer |
| [`math.fmod()`](https://www.w3schools.com/python/ref_math_fmod.asp) | Returns the remainder of x/y |
| [`math.frexp()`](https://www.w3schools.com/python/ref_math_frexp.asp) | Returns the mantissa and the exponent, of a specified number |
| [`math.fsum()`](https://www.w3schools.com/python/ref_math_fsum.asp) | Returns the sum of all items in any iterable (tuples, arrays, lists, etc.) |
| [`math.gamma()`](https://www.w3schools.com/python/ref_math_gamma.asp) | Returns the gamma function at x |
| [`math.gcd()`](https://www.w3schools.com/python/ref_math_gcd.asp) | Returns the greatest common divisor of two integers |
| [`math.hypot()`](https://www.w3schools.com/python/ref_math_hypot.asp) | Returns the Euclidean norm |
| [`math.isclose()`](https://www.w3schools.com/python/ref_math_isclose.asp) | Checks whether two values are close to each other, or not |
| [`math.isfinite()`](https://www.w3schools.com/python/ref_math_isfinite.asp) | Checks whether a number is finite or not |
| [`math.isinf()`](https://www.w3schools.com/python/ref_math_isinf.asp) | Checks whether a number is infinite or not |
| [`math.isnan()`](https://www.w3schools.com/python/ref_math_isnan.asp) | Checks whether a value is NaN (not a number) or not |
| [`math.isqrt()`](https://www.w3schools.com/python/ref_math_isqrt.asp) | Rounds a square root number downwards to the nearest integer |
| [`math.ldexp()`](https://www.w3schools.com/python/ref_math_ldexp.asp) | Returns the inverse of math.frexp() which is x * (2**i) of the given numbers x and i |
| [`math.lgamma()`](https://www.w3schools.com/python/ref_math_lgamma.asp) | Returns the log gamma value of x |
| [`math.log()`](https://www.w3schools.com/python/ref_math_log.asp) | Returns the natural logarithm of a number, or the logarithm of number to base |
| [`math.log10()`](https://www.w3schools.com/python/ref_math_log10.asp) | Returns the base-10 logarithm of x |
| [`math.log1p()`](https://www.w3schools.com/python/ref_math_log1p.asp) | Returns the natural logarithm of 1+x |
| [`math.log2()`](https://www.w3schools.com/python/ref_math_log2.asp) | Returns the base-2 logarithm of x |
| [`math.perm()`](https://www.w3schools.com/python/ref_math_perm.asp) | Returns the number of ways to choose k items from n items with order and without repetition |
| [`math.pow()`](https://www.w3schools.com/python/ref_math_pow.asp) | Returns the value of x to the power of y |
| [`math.prod()`](https://www.w3schools.com/python/ref_math_prod.asp) | Returns the product of all the elements in an iterable |
| [`math.radians()`](https://www.w3schools.com/python/ref_math_radians.asp) | Converts a degree value into radians |
| [`math.remainder()`](https://www.w3schools.com/python/ref_math_remainder.asp) | Returns the closest value that can make numerator completely divisible by the denominator |
| [`math.sin()`](https://www.w3schools.com/python/ref_math_sin.asp) | Returns the sine of a number |
| [`math.sinh()`](https://www.w3schools.com/python/ref_math_sinh.asp) | Returns the hyperbolic sine of a number |
| [`math.sqrt()`](https://www.w3schools.com/python/ref_math_sqrt.asp) | Returns the square root of a number |
| [`math.tan()`](https://www.w3schools.com/python/ref_math_tan.asp) | Returns the tangent of a number |
| [`math.tanh()`](https://www.w3schools.com/python/ref_math_tanh.asp) | Returns the hyperbolic tangent of a number |
| [`math.trunc()`](https://www.w3schools.com/python/ref_math_trunc.asp) | Returns the truncated integer parts of a number |
| [`math.e`](https://www.w3schools.com/python/ref_math_e.asp) | Returns Euler's number (2.7182...) |
| [`math.inf`](https://www.w3schools.com/python/ref_math_inf.asp) | Returns a floating-point positive infinity |
| [`math.nan`](https://www.w3schools.com/python/ref_math_nan.asp) | Returns a floating-point NaN (Not a Number) value |
| [`math.pi`](https://www.w3schools.com/python/ref_math_pi.asp) | Returns PI (3.1415...) |
| [`math.tau`](https://www.w3schools.com/python/ref_math_tau.asp) | Returns tau (6.2831...) |

### cMath module

| Method | Description |
| --: | :-- |
| [`cmath.acos(x)`](https://www.w3schools.com/python/ref_cmath_acos.asp) | Returns the arc cosine value of x |
| [`cmath.acosh(x)`](https://www.w3schools.com/python/ref_cmath_acosh.asp) | Returns the hyperbolic arc cosine of x |
| [`cmath.asin(x)`](https://www.w3schools.com/python/ref_cmath_asin.asp) | Returns the arc sine of x |
| [`cmath.asinh(x)`](https://www.w3schools.com/python/ref_cmath_asinh.asp) | Returns the hyperbolic arc sine of x |
| [`cmath.atan(x)`](https://www.w3schools.com/python/ref_cmath_atan.asp) | Returns the arc tangent value of x |
| [`cmath.atanh(x)`](https://www.w3schools.com/python/ref_cmath_atanh.asp) | Returns the hyperbolic arctangent value of x |
| [`cmath.cos(x)`](https://www.w3schools.com/python/ref_cmath_cos.asp) | Returns the cosine of x |
| [`cmath.cosh(x)`](https://www.w3schools.com/python/ref_cmath_cosh.asp) | Returns the hyperbolic cosine of x |
| [`cmath.exp(x)`](https://www.w3schools.com/python/ref_cmath_exp.asp) | Returns the value of Ex, where E is Euler's number (approximately 2.718281...), and x is the number passed to it |
| [`cmath.isclose()`](https://www.w3schools.com/python/ref_cmath_isclose.asp) | Checks whether two values are close, or not |
| [`cmath.isfinite(x)`](https://www.w3schools.com/python/ref_cmath_isfinite.asp) | Checks whether x is a finite number |
| [`cmath.isinf(x)`](https://www.w3schools.com/python/ref_cmath_isinf.asp) | Check whether x is a positive or negative infinty |
| [`cmath.isnan(x)`](https://www.w3schools.com/python/ref_cmath_isnan.asp) | Checks whether x is NaN (not a number) |
| [`cmath.log(x[, base])`](https://www.w3schools.com/python/ref_cmath_log.asp) | Returns the logarithm of x to the base |
| [`cmath.log10(x)`](https://www.w3schools.com/python/ref_cmath_log10.asp) | Returns the base-10 logarithm of x |
| [`cmath.phase()`](https://www.w3schools.com/python/ref_cmath_phase.asp) | Return the phase of a complex number |
| [`cmath.polar()`](https://www.w3schools.com/python/ref_cmath_polar.asp) | Convert a complex number to polar coordinates |
| [`cmath.rect()`](https://www.w3schools.com/python/ref_cmath_rect.asp) | Convert polar coordinates to rectangular form |
| [`cmath.sin(x)`](https://www.w3schools.com/python/ref_cmath_sin.asp) | Returns the sine of x |
| [`cmath.sinh(x)`](https://www.w3schools.com/python/ref_cmath_sinh.asp) | Returns the hyperbolic sine of x |
| [`cmath.sqrt(x)`](https://www.w3schools.com/python/ref_cmath_sqrt.asp) | Returns the square root of x |
| [`cmath.tan(x)`](https://www.w3schools.com/python/ref_cmath_tan.asp) | Returns the tangent of x |
| [`cmath.tanh(x)`](https://www.w3schools.com/python/ref_cmath_tanh.asp) | Returns the hyperbolic tangent of x |
| [`cmath.e`](https://www.w3schools.com/python/ref_cmath_e.asp) | Returns Euler's number (2.7182...) |
| [`cmath.inf`](https://www.w3schools.com/python/ref_cmath_inf.asp) | Returns a floating-point positive infinity value |
| [`cmath.infj`](https://www.w3schools.com/python/ref_cmath_infj.asp) | Returns a complex infinity value |
| [`cmath.nan`](https://www.w3schools.com/python/ref_cmath_nan.asp) | Returns floating-point NaN (Not a Number) value |
| [`cmath.nanj`](https://www.w3schools.com/python/ref_cmath_nanj.asp) | Returns coplext NaN (Not a Number) value |
| [`cmath.pi`](https://www.w3schools.com/python/ref_cmath_pi.asp) | Returns PI (3.1415...) |
| [`cmath.tau`](https://www.w3schools.com/python/ref_cmath_tau.asp) | Returns tau (6.2831...) |

## Common sequence operations (sequence types: list, tuple, range)

The operations in the following table are supported by most sequence types, both mutable and immutable. The [collections.abc.Sequence](https://docs.python.org/3/library/collections.abc.html#collections.abc.Sequence) ABC is provided to make it easier to correctly implement these operations on custom sequence types.

This table lists the sequence operations sorted in ascending priority. In the table, `s` and `t` are sequences of the same type, `n`, `i`, `j` and `k` are integers and `x` is an arbitrary object that meets any type and value restrictions imposed by `s`.

The `in` and `not in` operations have the same priorities as the comparison operations. The `+` (concatenation) and `*` (repetition) operations have the same priority as the corresponding numeric operations.

| Operation | Result | Notes |
| --: | :-- | :-- |
| `x in s` | `True` if an item of `s` is equal to `x`, else `False` | (1) |
| `x not in s` | `False` if an item of `s` is equal to `x`, else `True` | (1) |
| `s + t` | the concatenation of `s` and `t` | (6)(7) |
| `s * n` or `n * s` | equivalent to adding `s` to itself `n` times | (2)(7) |
| `s[i]` | *i*th item of `s`, origin `0` | (3) |
| `s[i:j]` | slice of `s` from `i` to `j` | (3)(4) |
| `s[i:j:k]` | slice of `s` from `i` to `j` with step `k` | (3)(5)) |
| `len(s)` | length of `s` |  |
| `min(s)` | smallest item of `s` |  |
| `max(s)` | largest item of `s` |  |
| `s.index(x[, i[, j]])` | index of the first occurrence of `x` in `s` (at or after index `i` and before index `j`) | (8) |
| `s.count(x)` | total number of occurrences of `x` in `s` |  |

Sequences of the same type also support comparisons. In particular, tuples and lists are compared lexicographically by comparing corresponding elements. This means that to compare equal, every element must compare equal and the two sequences must be of the same type and have the same length. (For full details see [Comparisons](https://docs.python.org/3/reference/expressions.html#comparisons) in the language reference.)

**Notes:** 

1\. While the `in` and `not in` operations are used only for simple containment testing in the general case, some specialised sequences (such as [`str`](https://docs.python.org/3/library/stdtypes.html#str), [`bytes`](https://docs.python.org/3/library/stdtypes.html#bytes) and [`bytearray`](https://docs.python.org/3/library/stdtypes.html#bytearray)) also use them for subsequence testing:

```
>>> "gg" in "eggs"
True
```

2\. Values of `n` less than `0` are treated as `0` (which yields an empty sequence of the same type as `s`). Note that items in the sequence `s` are not copied; they are referenced multiple times. This often haunts new Python programmers; consider:

```
>>> lists = [[]] * 3
>>> lists
[[], [], []]
>>> lists[0].append(3)
>>> lists
[[3], [3], [3]]
```

What has happened is that `[[]]` is a one-element list containing an empty list, so all three elements of `[[]] * 3` are references to this single empty list. Modifying any of the elements of lists modifies this single list. You can create a list of different lists this way:

```
>>> lists = [[] for i in range(3)]
>>> lists[0].append(3)
>>> lists[1].append(5)
>>> lists[2].append(7)
>>> lists
[[3], [5], [7]]
```

Further explanation is available in the FAQ entry [How do I create a multidimensional list?](https://docs.python.org/3/faq/programming.html#faq-multidimensional-list).

3\. If `i` or `j` is negative, the index is relative to the end of sequence `s`: `len(s) + i` or `len(s) + j` is substituted. But note that `-0` is still `0`.

4\. The slice of `s` from `i` to `j` is defined as the sequence of items with index `k` such that `i <= k < j`. If `i` or `j` is greater than `len(s)`, use `len(s)`. If `i` is omitted or `None`, use `0`. If `j` is omitted or `None`, use `len(s)`. If `i` is greater than or equal to `j`, the slice is empty.

5\. The slice of `s` from `i` to `j` with step `k` is defined as the sequence of items with index `x = i + n*k` such that `0 <= n < (j-i)/k`. In other words, the indices are `i`, `i+k`, `i+2*k`, `i+3*k` and so on, stopping when `j` is reached (but never including `j`). When `k` is positive, `i` and `j` are reduced to `len(s)` if they are greater. When `k` is negative, `i` and `j` are reduced to `len(s) - 1` if they are greater. If `i` or `j` are omitted or `None`, they become "end" values (which end depends on the sign of `k`). Note, `k` cannot be zero. If `k` is `None`, it is treated like `1`.

6\. Concatenating immutable sequences always results in a new object. This means that building up a sequence by repeated concatenation will have a quadratic runtime cost in the total sequence length. To get a linear runtime cost, you must switch to one of the alternatives below:
  + if concatenating [`str`](https://docs.python.org/3/library/stdtypes.html#str) objects, you can build a list and use [`str.join()`](https://docs.python.org/3/library/stdtypes.html#str.join) at the end or else write to an [io.StringIO](https://docs.python.org/3/library/io.html#io.StringIO) instance and retrieve its value when complete
  + if concatenating [`bytes`](https://docs.python.org/3/library/stdtypes.html#bytes) objects, you can similarly use [`bytes.join()`](https://docs.python.org/3/library/stdtypes.html#bytes.join) or [io.BytesIO](https://docs.python.org/3/library/io.html#io.BytesIO), or you can do in-place concatenation with a [`bytearray`](https://docs.python.org/3/library/stdtypes.html#bytearray) object. [`bytearray`](https://docs.python.org/3/library/stdtypes.html#bytearray) objects are mutable and have an efficient overallocation mechanism
  + if concatenating [`tuple`](https://docs.python.org/3/library/stdtypes.html#tuple) objects, extend a [`list`](https://docs.python.org/3/library/stdtypes.html#list) instead
  + for other types, investigate the relevant class documentation

7\. Some sequence types (such as [`range`](https://docs.python.org/3/library/stdtypes.html#range)) only support item sequences that follow specific patterns, and hence don't support sequence concatenation or repetition.

8\. `index` raises [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) when `x` is not found in `s`. Not all implementations support passing the additional arguments `i` and `j`. These arguments allow efficient searching of subsections of the sequence. Passing the extra arguments is roughly equivalent to using `s[i:j].index(x)`, only without copying any data and with the returned index being relative to the start of the sequence rather than the start of the slice.

## Mutable sequence types (operations such as slicing, insert, etc.)

The operations in the following table are defined on mutable sequence types. The [collections.abc.MutableSequence](https://docs.python.org/3/library/collections.abc.html#collections.abc.MutableSequence) ABC is provided to make it easier to correctly implement these operations on custom sequence types.

In the table `s` is an instance of a mutable sequence type, `t` is any iterable object and `x` is an arbitrary object that meets any type and value restrictions imposed by `s` (for example, [`bytearray`](https://docs.python.org/3/library/stdtypes.html#bytearray) only accepts integers that meet the value restriction `0 <= x <= 255`).

| Operation | Result | Notes |
| --: | :-- | :-- |
| `s[i] = x` | item `i` of `s` is replaced by `x` |  |
| `s[i:j] = t` | slice of `s` from `i` to `j` is replaced by the contents of the iterable `t` |  |
| `del s[i:j]` | same as `s[i:j] = []` |  |
| `s[i:j:k] = t` | the elements of `s[i:j:k]` are replaced by those of `t` | (1) |
| `del s[i:j:k]` | removes the elements of `s[i:j:k]` from the list |  |
| `s.append(x)` | appends `x` to the end of the sequence (same as `s[len(s):len(s)] = [x]`) |  |
| `s.clear()` | removes all items from `s` (same as `del s[:]`) | (5) |
| `s.copy()` | creates a shallow copy of `s` (same as `s[:]`) | (5) |
| `s.extend(t)` or `s += t` | extends `s` with the contents of `t` (for the most part the same as `s[len(s):len(s)] = t`) |  |
| `s *= n` | updates `s` with its contents repeated `n` times | (6) |
| `s.insert(i, x)` | inserts `x` into `s` at the index given by `i` (same as `s[i:i] = [x]`) |  |
| `s.pop([i])` | retrieves the item at `i` and also removes it from `s` | (2) |
| `s.remove(x)` | remove the first item from `s` where `s[i]` is equal to `x` | (3) |
| `s.reverse()` | reverses the items of `s` in place | (4) |

1\. `t` must have the same length as the slice it is replacing.

2\. The optional argument `i` defaults to `-1`, so that by default the last item is removed and returned.

3\. `remove()` raises [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) when `x` is not found in `s`.

4\. The `reverse()` method modifies the sequence in place for economy of space when reversing a large sequence. To remind users that it operates by side effect, it does not return the reversed sequence.

5\. `clear()` and `copy()` are included for consistency with the interfaces of mutable containers that don't support slicing operations (such as [`dict`](https://docs.python.org/3/library/stdtypes.html#dict) and [`set`](https://docs.python.org/3/library/stdtypes.html#set)). `copy()` is not part of the [collections.abc.MutableSequence](https://docs.python.org/3/library/collections.abc.html#collections.abc.MutableSequence) ABC, but most concrete mutable sequence classes provide it.

6\. The value `n` is an integer, or an object implementing [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__). Zero and negative values of `n` clear the sequence. Items in the sequence are not copied; they are referenced multiple times, as explained for `s * n` under [Common Sequence Operations](https://docs.python.org/3/library/stdtypes.html#typesseq-common).

## Docs and Examples

### Built-in Functions

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#abs" target="_blank"><code>abs(<em>x</em>)</code></a></strong></summary>

**Description:** The `abs()` function returns the absolute value of the given number. If the number is a complex number, then `abs()` returns its magnitude.

**Syntax:** The syntax of `abs()` method is: `abs(num)`.

**Paramaters:** `abs()` method takes a single argument, `num`: a number whose absolute value is to be returned. The number can be:

- integer
- floating number
- complex number

**Return value:** `abs()` method returns the absolute value of the given number.

- **For integers** - integer absolute value is returned
- **For floating numbers** - floating absolute value is returned
- **For complex numbers** - magnitude of the number is returned

**Examples:**

<details><summary> Ex 0: Documentation</summary>

Return the absolute value of a number. The argument may be an integer, a floating point number, or an object implementing `__abs__()`. If the argument is a complex number, its magnitude is returned.

---

</details>

<details><summary> Ex 1: Getting absolute value of an integer and a floating number</summary>

```python
# random integer
integer = -20
print('Absolute value of -20 is:', abs(integer))

#random floating number
floating = -30.33
print('Absolute value of -30.33 is:', abs(floating))
```

**Output:**

```
Absolute value of -20 is: 20
Absolute value of -30.33 is: 30.33
```

---

</details>

<details><summary> Ex 2: Getting magnitude of a complex number</summary>

```python
# random complex number
complex = (3 - 4j)
print('Magnitude of 3 - 4j is:', abs(complex))
```

**Output:**

```
Magnitude of 3 - 4j is: 5.0
```

---

</details>

<details><summary> Ex 3: Example using <code>abs</code> on an <code>int</code>, <code>float</code>, and <code>complex</code> number, respectively</summary>

``` Python
a = -2
b = -3.4
c = complex(-3,-4)

print(abs(a))   # 2
print(abs(b))   # 3.4
print(abs(c))   # 5.0 (comes from: sqrt((-3)^2 + (-4)^2))
```

As can be seen above, `abs` returns an `int` when it receives a whole number and a `float` otherwise.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#aiter" target="_blank"><code>aiter(<em>async_iterable</em>)</code></a></strong></summary>

Return an [asynchronous iterator](https://docs.python.org/3/glossary.html#term-asynchronous-iterator) for an [asynchronous iterable](https://docs.python.org/3/glossary.html#term-asynchronous-iterable). Equivalent to calling `x.__aiter__()`.

`aiter(x)` itself has an `__aiter__()` method that returns `x`, so `aiter(aiter(x))` is the same as `aiter(x)`.

Note: Unlike [`iter()`](https://docs.python.org/3/library/functions.html#iter), [`aiter()`](https://docs.python.org/3/library/functions.html#aiter) has no 2-argument variant.

*New in version 3.10.*

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#all" target="_blank"><code>all(<em>iterable</em>)</code></a></strong></summary>

**Description:** The `all()` function returns `True` if *all* elements in the given iterable are true (or if the iterable is empty). If not, it returns `False`.

**Syntax:** The syntax of the `all()` function is: `all(iterable)`.

**Parameters:** The `all()` function takes a single parameter, `iterable`: any iterable (list, tuple, dictionary, etc.) which contains elements.

**Return value:** The `all()` function returns:

- `True` - If all elements in an iterable are true (or if the iterable is empty)
- `False` - If any element in an iterable is false

**Falsy values in Python:** Recall that all values in Python are considered truthy except for [the following which are falsy](https://stackoverflow.com/questions/39983695/what-is-truthy-and-falsy-how-is-it-different-from-true-and-false) (more can be found in the docs on [truth value testing](https://docs.python.org/3/library/stdtypes.html#truth-value-testing)):

- `None`
- `False`
- `0`
- `0.0`
- `0j`
- `Decimal(0)`
- `Fraction(0, 1)`
- `[]` - an empty list
- `{}` - an empty dict
- `()` - an empty tuple
- `''` - an empty str
- `b''` - an empty bytes
- `set()` - an empty set
- an empty range, like `range(0)`
- objects for which
  + `obj.__bool__()` returns `False`
  + `obj.__len__()` returns `0`

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if all elements of the *iterable* are true (or if the iterable is empty). Equivalent to:

```python
def all(iterable):
    for element in iterable:
        if not element:
            return False
    return True
```

---

</details>

<details><summary> Ex 1: Lists (works in a similar way for tuples and sets)</summary>

``` Python
# all values true
l = [1, 3, 4, 5]
print(all(l))       # True

# all values false
l = [0, False]
print(all(l))       # False

# one false value
l = [1, 3, 4, 0]
print(all(l))       # False

# one true value
l = [0, False, 5]
print(all(l))       # False

# empty iterable
l = []
print(all(l))       # True
```

---

</details>

<details><summary> Ex 2: Strings</summary>

``` Python
s = "This is good"
print(all(s))       # True

# 0 is False
# '0' is True
s = '000'
print(all(s))       # True

s = ''
print(all(s))       # True
```

Some things to note about two of the code examples above:

- `"This is good"`: This is true because all values (i.e., characters) in the iterable `"This is good"` are truthy; in particular, the spaces `' '` have an ordinal value of `32` (i.e., `ord(' ')` returns `32`).
- `''`: This is true because the iterable `''` is *empty*. Hence, when the functional equivalent of `all()`

  ```python
  def all(iterable):
      for element in iterable:
          if not element:
              return False
      return True
  ```

  is executed, the `for` loop never runs and `True` is quickly returned.

---

</details>

<details><summary> Ex 3: Dictionaries (return <code>True</code> if all keys, not values, are true or the dictionary is empty; else return <code>False</code>)</summary>

``` Python
s = {0: 'False', 1: 'False'}
print(all(s))                   # False

s = {1: 'True', 2: 'True'}
print(all(s))                   # True

s = {1: 'True', False: 0}
print(all(s))                   # False

s = {}
print(all(s))                   # True

# 0 is False
# '0' is True
s = {'0': 'True'}
print(all(s))                   # True
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#anext" target="_blank"><code>anext(<em>async_iterator</em>[, default])</code></a></strong></summary>

When awaited, return the next item from the given [asynchronous iterator](https://docs.python.org/3/glossary.html#term-asynchronous-iterator), or `default` if given and the iterator is exhausted.

This is the async variant of the [`next()`](https://docs.python.org/3/library/functions.html#next) builtin, and behaves similarly.

This calls the [`__anext__()`](https://docs.python.org/3/reference/datamodel.html#object.__anext__) method of `async_iterator`, returning an [awaitable](https://docs.python.org/3/glossary.html#term-awaitable). Awaiting this returns the next value of the iterator. If `default` is given, it is returned if the iterator is exhausted, otherwise [`StopAsyncIteration`](https://docs.python.org/3/library/exceptions.html#StopAsyncIteration) is raised.

*New in version 3.10.*

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#any" target="_blank"><code>any(<em>iterable</em>)</code></a></strong></summary>

**Description:** The `any()` function returns `True` if *any* element of the given `iterable` is `True`. If not (or if the iterable is empty), it returns `False`.

**Syntax:** The syntax of the `any()` function is: `any(iterable)`.

**Parameters:** The `any()` function takes a single parameter, `iterable`: any iterable (list, tuple, dictionary, etc.) which contains elements.

**Return value:** The `any()` function returns:

- `True` - If at least one element of an iterable is true
- `False` - If all elements are false or if an iterable is empty

**Falsy values in Python:** Recall that all values in Python are considered truthy except for [the following which are falsy](https://stackoverflow.com/questions/39983695/what-is-truthy-and-falsy-how-is-it-different-from-true-and-false) (more can be found in the docs on [truth value testing](https://docs.python.org/3/library/stdtypes.html#truth-value-testing)):

- `None`
- `False`
- `0`
- `0.0`
- `0j`
- `Decimal(0)`
- `Fraction(0, 1)`
- `[]` - an empty list
- `{}` - an empty dict
- `()` - an empty tuple
- `''` - an empty str
- `b''` - an empty bytes
- `set()` - an empty set
- an empty range, like `range(0)`
- objects for which
  + `obj.__bool__()` returns `False`
  + `obj.__len__()` returns `0`

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if any element of the `iterable` is true. If the iterable is empty, return `False`. Equivalent to:

```python
def any(iterable):
    for element in iterable:
        if element:
            return True
    return False
```

---

</details>

<details><summary> Ex 1: Lists (works in a similar way for tuples and sets)</summary>

``` Python
# all true except 0
l = [1, 3, 4, 0]
print(any(l))         # True

# both false
l = [0, False]
print(any(l))         # False

# all false except 5
l = [0, False, 5]
print(any(l))         # True

# empty
l = []
print(any(l))         # False
```

---

</details>

<details><summary> Ex 2: Strings</summary>

``` Python
# all elements are true
s = "This is good"
print(any(s))             # True

# all elements are true
s = '000'
print(any(s))             # True

# false (empty iterable)
s = ''
print(any(s))             # False
```

---

</details>

<details><summary> Ex 3: Dictionaries (return False if all keys, not values, are false, or the dictionary is empty; else return True)</summary>

``` Python
# 0 is False
d = {0: 'False'}
print(any(d))                 # False

# 1 is True
d = {0: 'False', 1: 'True'}
print(any(d))                 # True

# 0 and False are false
d = {0: 'False', False: 0}
print(any(d))                 # False

# iterable is empty
d = {}
print(any(d))                 # False

# 0 is False
# '0' is True
d = {'0': 'False'}
print(any(d))                 # True
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#ascii" target="_blank"><code>ascii(<em>object</em>)</code></a></strong></summary>

**Description:** The `ascii()` method returns a string containing a printable representation of an object. It escapes the non-ASCII characters in the string using `\x`, `\u` or `\U` escapes.

**Syntax:** The syntax of `ascii()` is: `ascii(object)`

**Parameters:** The `ascii()` method takes an object (like: strings, list etc).

**Return value:** It returns a string containing a printable representation of an object. For example, `ö` is changed to `\xf6n`, `√` is changed to `\u221a`. The non-ASCII characters in the string are escaped using `\x`, `\u` or `\U`.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

As [`repr()`](https://docs.python.org/3/library/functions.html#repr), return a string containing a printable representation of an object, but escape the non-ASCII characters in the string returned by [`repr()`](https://docs.python.org/3/library/functions.html#repr) using `\x`, `\u` or `\U` escapes. This generates a string similar to that returned by [`repr()`](https://docs.python.org/3/library/functions.html#repr) in Python 2.

---

</details>

<details><summary> Ex 1: Basic usage (encoding and decoding simple strings)</summary>

``` Python
normalText = 'Python is interesting'
print(ascii(normalText))

otherText = 'Pythön is interesting'
print(ascii(otherText))

print('Pyth\xf6n is interesting')
```

**Output:**

```
'Python is interesting'
'Pyth\xf6n is interesting'
Pythön is interesting
```

---

</details>

<details><summary> Ex 2: Applying <code>ascii()</code> to each element of a list</summary>

```python
randomList = ['Python', 'Pythön', 5]
print(ascii(randomList))
```

**Output:**

```
['Python', 'Pyth\xf6n', 5]
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#bin" target="_blank"><code>bin(<em>x</em>)</code></a></strong></summary>

**Description:** The `bin()` method converts and returns the binary equivalent string of a given integer. If the parameter isn't an integer, it has to implement `__index__()` method to return an integer.

**Syntax:** The syntax of `bin()` method is: `bin(num)`

**Parameters:** The `bin()` method takes a single parameter `num`: an integer number whose binary equivalent is to be calculated. If not an integer, should implement `__index__()` method to return an integer.

**Return value:** `bin()` method returns the binary string equivalent to the given integer. If not specified an integer, it raises a `TypeError` exception highlighting the type cannot be interpreted as an integer.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Convert an integer number to a binary string prefixed with `0b`.

The result is a valid Python expression. If `x` is not a Python [`int`](https://docs.python.org/3/library/functions.html#int) object, it has to define an [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__) method that returns an integer.

``` Python
>>> bin(3)
'0b11'
>>> bin(-10)
'-0b1010'
```

If prefix `0b` is desired or not, you can use either of the following ways:

``` Python
>>> format(14, '#b'), format(14, 'b')
('0b1110', '1110')
>>> f'{14:#b}', f'{14:b}'
('0b1110', '1110')
```

See also [`format()`](https://docs.python.org/3/library/functions.html#format) for more information.

---

</details>

<details><summary> Ex 1: Converting an integer to binary using <code>bin()</code></summary>

```python
number = 5
print('The binary equivalent of 5 is:', bin(number))
```

**Output:**

```
The binary equivalent of 5 is: 0b101
```

The prefix `0b` represents that the result is a binary string.

---

</details>

<details><summary> Ex 2: Convert an object to binary implementing <code>__index__()</code> method</summary>

```python
class Quantity:
    apple = 1
    orange = 2
    grapes = 2
    
    def __index__(self):
        return self.apple + self.orange + self.grapes
        
print('The binary equivalent of quantity is:', bin(Quantity()))
```

**Output:**

```
The binary equivalent of quantity is: 0b101
```

Here, we've sent an object of class `Quantity` to the `bin()` method. The `bin()` method doesn't raise an error even if the object `Quantity` is not an integer. This is because we have implemented the `__index__()` method which returns an integer (sum of fruit quantities). This integer is then supplied to the `bin()` method.

---

</details>

<details><summary> Ex 3: Multiple one-line examples</summary>

``` Python
print(bin(4))             # 0b100
print(format(4,'#b'))     # 0b100
print(f'{4:#b}')          # 0b100
print(format(4,'b'))      # 100
print(f'{4:b}')           # 100
print(int('100', 2))      # 4
print(int('0b100', 2))    # 4
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#bool" target="_blank"><code>bool([<em>x</em>])</code></a></strong></summary>

**Description:** The `bool()` function converts a value to Boolean (`True` or `False`) using the standard [truth testing procedure](https://docs.python.org/3/library/stdtypes.html#truth).

**Syntax:** The syntax of `bool()` is: `bool([value])`

**Parameters:** It's not mandatory to pass a value to `bool()`. If you do not pass a value, `bool()` returns `False`. In general use, `bool()` takes a single parameter `value`.

**Return value:** `bool()` returns

- `False` if the value is omitted or false
- `True` if the value is true

**Falsy values in Python:** Recall that all values in Python are considered truthy except for [the following which are falsy](https://stackoverflow.com/questions/39983695/what-is-truthy-and-falsy-how-is-it-different-from-true-and-false) (more can be found in the docs on [truth value testing](https://docs.python.org/3/library/stdtypes.html#truth-value-testing)):

- `None`
- `False`
- `0`
- `0.0`
- `0j`
- `Decimal(0)`
- `Fraction(0, 1)`
- `[]` - an empty list
- `{}` - an empty dict
- `()` - an empty tuple
- `''` - an empty str
- `b''` - an empty bytes
- `set()` - an empty set
- an empty range, like `range(0)`
- objects for which
  + `obj.__bool__()` returns `False`
  + `obj.__len__()` returns `0`

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a Boolean value (i.e., one of `True` or `False`). If `x` is false or omitted, this (i.e., `bool()` or `bool(x)` where `x` is false) returns `False`; otherwise it returns `True`.

`x` is converted using the standard [truth testing procedure](https://docs.python.org/3/library/stdtypes.html#truth). The [`bool`](https://docs.python.org/3/library/functions.html#bool) class is a subclass of [`int`](https://docs.python.org/3/library/functions.html#int) (see [Numeric Types — int, float, complex](https://docs.python.org/3/library/stdtypes.html#typesnumeric)). It cannot be subclassed further. Its only instances are `False` and `True` (see [Boolean Values](https://docs.python.org/3/library/stdtypes.html#bltin-boolean-values)).

---

</details>

<details><summary> Ex 1: Basic usage on a variety of inputs</summary>

``` Python
test = []
print(test,'is',bool(test))

test = [0]
print(test,'is',bool(test))

test = 0.0
print(test,'is',bool(test))

test = None
print(test,'is',bool(test))

test = True
print(test,'is',bool(test))

test = 'Easy string'
print(test,'is',bool(test))
```

**Output:**

```
[] is False
[0] is True
0.0 is False
None is False
True is True
Easy string is True
```

---

</details>

*Changed in version 3.7:* `x` is now a positional-only parameter.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#breakpoint" target="_blank"><code>breakpoint(<em>*args, **kws</em>)</code></a></strong></summary>

**Description:** See documentation below. The primary purpose is to be able to drop into the debugger at the call site without the overhead of having to import the `pdb` module.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

This function drops you into the debugger at the call site. 

Specifically, it calls [sys.breakpointhook()](https://docs.python.org/3/library/sys.html#sys.breakpointhook), passing `args` and `kws` straight through. By default, [sys.breakpointhook()](https://docs.python.org/3/library/sys.html#sys.breakpointhook) calls [`pdb.set_trace()`](https://docs.python.org/3/library/pdb.html#pdb.set_trace) expecting no arguments. In this case, it is purely a convenience function so you don't have to explicitly import [`pdb`](https://docs.python.org/3/library/pdb.html#module-pdb) or type as much code to enter the debugger. However, [sys.breakpointhook()](https://docs.python.org/3/library/sys.html#sys.breakpointhook) can be set to some other function and [`breakpoint()`](https://docs.python.org/3/library/functions.html#breakpoint) will automatically call that, allowing you to drop into the debugger of choice.

Raises an [`auditing event`](https://docs.python.org/3/library/sys.html#auditing) `builtins.breakpoint` with argument `breakpointhook`.

*New in version 3.7.*

---

</details>

<details><summary> Ex 1: Basic usage of <code>breakpoint</code></summary>

Consider the following somewhat verbose silly example (note how `breakpoint` would allow us to avoid the usage of `pdb` below):

```python
import pdb

def add(num1, num2):
  # code tries to run until it hits the set_trace for pdb below
  pdb.set_trace()
  # within the debugger, we can test out what is going on thus far
  # for example, entering num1 will tell us what num1 is at this point (same for num2)
  # pdb really has a ton of helpful things; for example, 
  # simply typing 'help' shows documented commands you can use within the interactive debugger
  # if you see a command you're not sure about, then simply type 'help <command>'
  # we can type 'step' to step through our code
  # right now typing 'some_var' within pdb would give us a NameError since we have not reached that line yet
  # we can run 'continue' to continue through the code until we hit a return
  # the 'a' command is also helpful since it will give you the arguments of the function you're in at that point in execution
  # you can interactively change the value of different arguments to test things out
  # the 'w' command will give you context for debugging
  # finally 'exit' will let you exit the debugger
  some_var = 4 * 5
  print(some_var)
  return num1 + num2

add(4, 'string')
```

We can certainly use `pdb`, the Python debugging module in the standard library, as illustrated above, but it can be rather cumbersome to import a module just to do some debugging. For the sake of convenience, you can get everything above by simply removing the `import pdb` statement as well as changing the line `pdb.set_trace()` to `breakpoint()`. We then end up with the exact some functionality but avoid importing a module:

```python
def add(num1, num2):
  breakpoint()
  some_var = 4 * 5
  print(some_var)
  return num1 + num2

add(4, 'string')
```

---

</details>

---

</details>

<details><summary> <strong>NOTE: Some notes about <code>str</code>, <code>byte</code>, <code>bytearray</code>, and Unicode strings</strong></summary>

The following notes largely come from [[3]](#3) in a variety of places.

**Overview:** The normal `str` string object is an *immutable* (unchangeable) *sequence* of characters accessed by *offset* (position). Its *characters* are code point ordinals in the underlying character set, and individual characters are string objects of length 1.

The full string object model varies across lines.

Python 3.X has three string types with similar interfaces:

- `str`: An immutable sequence of characters, used for all text—-both ASCII and richer Unicode.
- `bytes`: An immutable sequence of short integers, used for the byte values of binary data.
- `bytearray`: A mutable variant of bytes.

The following literal forms and calls make specialized strings:

- `b'...'`: `bytes` string literal in Python 3.X: sequence of 8-bit byte values representing raw binary data.
- `bytearray(...)`: `bytearray` string construction: a mutable variant of `bytes`.
- `str()`, `bytes()`, `bytearray()`: Create strings from objects, with possible Unicode encoding/decoding in Python 3.X.

**`byte` and `bytearray` methods:** Python 3.X `bytes` and `bytearray` string types have method sets similar to that of the normal `str` type, but do not overlap exactly due to differing roles. (`str` is Unicode text, `bytes` is raw binary data, and `bytearray` is mutable.) In the following, run in Python 3.9, `set(dir(X)) – set(dir(Y))` computes attributes unique to `X`:

```
>>> set(dir(str)) - set(dir(bytes))
{
  'isidentifier', 'encode', 'isnumeric', 
  'format', 'format_map', 'isdecimal', 
  'isprintable', 'casefold'
}

>>> set(dir(bytes)) - set(dir(str))
{
  'fromhex', 'decode', 'hex'
}

>>> set(dir(bytearray)) - set(dir(bytes))
{
  'clear', '__setitem__', '__iadd__', 
  'reverse', 'pop', 'insert', 
  '__delitem__', 'append', '__imul__', 
  '__alloc__', 'remove', 'extend', 
  'copy'
}
```

Of note:

- `str` does not support Unicode *decoding* (it is already decoded text), but may be *encoded* to bytes.
- `bytes` and `bytearray` do not support Unicode *encoding* (they are raw bytes, including both media and already encoded text), but may be *decoded* to `str`.
- `bytes` and `bytearray` do not support string formatting (implemented by `str.format`).
- `bytearray` has extra mutable in-place methods and operators similar to `list` (e.g., `append`, `+=`).

**Unicode strings:** All text is Unicode text, including text encoded with one character
per byte (8 bits) in the ASCII scheme. Python supports richer character sets and encoding schemes with *Unicode*--strings which may use multiple bytes to represent characters in memory, and which translate text to and from various encodings on files. This support differs in Python lines. Python 3.X treats all text as Unicode and represents binary data separately, while Python 2.X distinguishes 8-bit text (and data) from possibly wider Unicode text. 

In Python 3.X, the normal `str` type and `'ccc'` literal represents all text, both 8-bit and richer Unicode. `str` is an immutable sequence of *characters*-—decoded Unicode code points (ordinal identifiers) in memory.

A separate `bytes` type and `b'ccc'` literal represents binary data byte values, including media and encoded Unicode text. `bytes` is an immutable sequence of small integers (8-bit byte values), but supports most `str` operations, and prints content as ASCII characters when possible. An additional `bytearray` type is a mutable variant of `bytes`, with extra list-like methods for in-place changes.

Also in 3.X, normal *files* created by `open()` imply `str` and `bytes` objects for content in text and binary mode, respectively. In text mode, files automatically encode on output and decode on input.

**Unicode support in Python 3.X:** Python 3.X allows non-ASCII characters to be coded in strings with hex (`\x`) and both 16- and 32-bit Unicode (`\u`, `\U`) escapes. In addition, `chr()` supports Unicode character codes:

```
>>> 'A\xE4B'
'AäB'

>>> 'A\u00E4B'
'AäB'

>>> 'A\U000000E4B'
'AäB'

>>> chr(0xe4)
'ä'
```

**`byte` and `bytearray` strings:** Python 3.X `bytes` and `bytearray` string objects represent 8-bit binary data (including encoded Unicode text); are printed as ASCII text when possible; and support most normal `str` string operations including methods and sequence operations (but not string formatting). For example, the code block

```python
B = b'spam'
print(B)

B = bytes('spam', 'utf-8')
print(B)

print(B[0])
print(ord('s'))

print(B + b'abc')
print(B.split(b'a'))

print(list(B))
print([ chr(c) for c in B ])

print([ ord(c) for c in 'spam' ])
print([ c for c in 'spam' ])
```

yields the following output (newlines for clarity):

```
b'spam'
b'spam'

115
115

b'spamabc'
[b'sp', b'm']

[115, 112, 97, 109]
['s', 'p', 'a', 'm']

[115, 112, 97, 109]
['s', 'p', 'a', 'm']
```

`bytearray` additionally supports list-like mutable operations:

```python
BA = bytearray(b'spam')
print(BA)
print(BA[0])
print(BA + b'abc')

BA[0] = 116     # Mutability
BA.append(115)  # List methods
print(BA)
```

yields:

```
bytearray(b'spam')
115
bytearray(b'spamabc')

bytearray(b'tpams')
```

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-bytearray" target="_blank"><code>bytearray([<em>source</em>[, <em>encoding</em>[, <em>errors</em>]]])</code></a></strong></summary>

**Description:** The `bytearray()` method returns a bytearray object which is an array of the given bytes.

```python
prime_numbers = [2, 3, 5, 7]

# convert list to bytearray
byte_array = bytearray(prime_numbers)
print(byte_array)

# Output: bytearray(b'\x02\x03\x05\x07')
```

**Syntax:** The syntax of `bytearray()` method is: `bytearray([source[, encoding[, errors]]])`. The `bytearray()` method returns a bytearray object (i.e., array of bytes) which is a mutable sequence of integers in the range `0 <= x < 256`. If you want an immutable version, then use the `bytes()` method.

**Parameters:** `bytearray()` takes three optional parameters:

- **source (Optional)** - source to initialize the array of bytes.
- **encoding (Optional)** - if the source is a string, the encoding of the string.
- **errors (Optional)** - if the source is a string, the action to take when the encoding conversion fails

The `source` parameter can be used to initialize the byte array in the following ways:

| Type | Description |
| :-- | :-- |
| String | Converts the string to bytes using `str.encode()`. Must also provide `encoding` and optionally `errors` |
| Integer | Creates an array of provided size, all initialized to `null` |
| Object | A read-only buffer of the object will be used to initialize the byte array |
| Iterable | Creates an array of size equal to the iterable count and initialized to the iterable elements. Must be iterable of integers between `0 <= x < 256` |
| No source (arguments) | Creates an array of size `0`. |

**Return value:** The `bytearray()` method returns an array of bytes of the given size and initialization values.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new array of bytes. 

The [`bytearray`](https://docs.python.org/3/library/stdtypes.html#bytearray) class is a mutable sequence of integers in the range `0 <= x < 256`. It has most of the usual methods of mutable sequences, described in [Mutable Sequence Types](https://docs.python.org/3/library/stdtypes.html#typesseq-mutable), as well as most methods that the [`bytes`](https://docs.python.org/3/library/stdtypes.html#bytes) type has, see [Bytes and Bytearray Operations](https://docs.python.org/3/library/stdtypes.html#bytes-methods).

The optional `source` parameter can be used to initialize the array in a few different ways:

- If it is a *string*, you must also give the `encoding` (and optionally, `errors`) parameters; [`bytearray()`](https://docs.python.org/3/library/stdtypes.html#bytearray) then converts the string to bytes using [`str.encode()`](https://docs.python.org/3/library/stdtypes.html#str.encode).
- If it is an *integer*, the array will have that size and will be initialized with null bytes.
- If it is an object conforming to the [buffer interface](https://docs.python.org/3/c-api/buffer.html#bufferobjects), a read-only buffer of the object will be used to initialize the bytes array.
- If it is an *iterable*, it must be an iterable of integers in the range `0 <= x < 256`, which are used as the initial contents of the array.

Without an argument, an array of size 0 is created.

See also [Binary Sequence Types — bytes, bytearray, memoryview](https://docs.python.org/3/library/stdtypes.html#binaryseq) and [Bytearray Objects](https://docs.python.org/3/library/stdtypes.html#typebytearray).

---

</details>

<details><summary> Ex 1: Array of bytes from a string</summary>

```python
string = "Python is interesting."

# string with encoding 'utf-8'
arr = bytearray(string, 'utf-8')
print(arr)
```

**Output:**

```
bytearray(b'Python is interesting.')
```

---

</details>

<details><summary> Ex 2: Array of bytes of given integer size</summary>

```python
size = 5

arr = bytearray(size)
print(arr)
```

**Output:**

```
bytearray(b'\x00\x00\x00\x00\x00')
```

---

</details>

<details><summary> Ex 3: Array of bytes from an iterable list</summary>

```python
rList = [1, 2, 3, 4, 5]

arr = bytearray(rList)
print(arr)
```

**Output:**

```
bytearray(b'\x01\x02\x03\x04\x05')
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-bytes" target="_blank"><code>bytes([<em>source</em>[, <em>encoding</em>[, <em>errors</em>]]])</code></a></strong></summary>

**Description:** The `bytes()` method returns an immutable bytes object initialized with the given size and data.

```python
message = 'Python is fun'

# convert string to bytes
byte_message = bytes(message, 'utf-8')
print(byte_message)

# Output: b'Python is fun'
```

**Syntax:** The syntax of `bytes()` method is

```
bytes([source[, encoding[, errors]]])
```

`bytes()` method returns a bytes object which is an immutable (cannot be modified) sequence of integers in the range `0 <=x < 256`. If you want to use the mutable version, use the `bytearray()` method.

**Parameters:** `bytes()` takes three optional parameters:

- **source (Optional)** - source to initialize the array of bytes.
- **encoding (Optional)** - if the source is a string, the encoding of the string.
- **errors (Optional)** - if the source is a string, the action to take when the encoding conversion fails

The `source` parameter can be used to initialize the byte array in the following ways:

| Type | Description |
| :-- | :-- |
| String | Converts the string to bytes using `str.encode()`. Must also provide `encoding` and optionally `errors` |
| Integer | Creates an array of provided size, all initialized to `null` |
| Object | A read-only buffer of the object will be used to initialize the byte array |
| Iterable | Creates an array of size equal to the iterable count and initialized to the iterable elements. Must be iterable of integers between `0 <= x < 256` |
| No source (arguments) | Creates an array of size `0`. |

**Return value:** The `bytes()` method returns a bytes object of the given size and initialization values.

**Return value:** 


**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new "bytes" object, which is an immutable sequence of integers in the range `0 <= x < 256`. [`bytes`](https://docs.python.org/3/library/stdtypes.html#bytes) is an immutable version of [`bytearray`](https://docs.python.org/3/library/stdtypes.html#bytearray) – it has the same non-mutating methods and the same indexing and slicing behavior.

Accordingly, constructor arguments are interpreted as for [`bytearray()`](https://docs.python.org/3/library/stdtypes.html#bytearray).

Bytes objects can also be created with literals, see [String and Bytes literals](https://docs.python.org/3/reference/lexical_analysis.html#strings).

See also [Binary Sequence Types — bytes, bytearray, memoryview](https://docs.python.org/3/library/stdtypes.html#binaryseq), [Bytes Objects](https://docs.python.org/3/library/stdtypes.html#typebytes), and [Bytes and Bytearray Operations](https://docs.python.org/3/library/stdtypes.html#bytes-methods).

---

</details>

<details><summary> Ex 1: Convert string to bytes</summary>

```python
string = "Python is interesting."

# string with encoding 'utf-8'
arr = bytes(string, 'utf-8')
print(arr)
```

**Output:** 

```
b'Python is interesting.'
```

---

</details>

<details><summary> Ex 2: Create a byte of given integer size</summary>

```python
size = 5

arr = bytes(size)
print(arr)
```

**Output:** 

```
b'\x00\x00\x00\x00\x00'
```

---

</details>

<details><summary> Ex 3: Convert iterable list to bytes</summary>

```python
rList = [1, 2, 3, 4, 5]

arr = bytes(rList)
print(arr)
```

**Output:** 

```
b'\x01\x02\x03\x04\x05'
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#callable" target="_blank"><code>callable(<em>object</em>)</code></a></strong></summary>

**Description:** The `callable()` method returns `True` if the object passed appears callable. If not, it returns `False`.

**Syntax:** The syntax of `callable()` is: `callable(object)`

**Parameters:** `callable()` method takes a single argument: `object`

**Return value:** The `callable()` method returns:

- `True` - if the object appears callable
- `False` - if the object is not callable.

It important to remember that, even if `callable()` is `True`, call to the object may still fail.

However, if `callable()` returns `False`, call to the object will certainly fail.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if the `object` argument appears callable, `False` if not. 

If this returns `True`, it is still possible that a call fails, but if it is `False`, calling `object` will never succeed. Note that classes are callable (calling a class returns a new instance); instances are callable if their class has a [`__call__()`](https://docs.python.org/3/reference/datamodel.html#object.__call__) method.

*New in version 3.2:* This function was first removed in Python 3.0 and then brought back in Python 3.2.

---

</details>

<details><summary> Ex 1: How <code>callable()</code> works</summary>

```python
x = 5
print(callable(x))

def testFunction():
  print("Test")

y = testFunction
print(callable(y))
```

**Output:**

```
False
True
```

Here, the object `x` is not callable. And, the object `y` appears to be callable (but may not be callable).

---

</details>

<details><summary> Ex 2: Callable object</summary>

```python
class Foo:
  def __call__(self):
    print('Print Something')

print(callable(Foo))
```

**Output:**

```
True
```

The instance of `Foo` class appears to be callable (and is callable in this case).

```python
class Foo:
  def __call__(self):
    print('Print Something')

InstanceOfFoo = Foo()

# Prints 'Print Something'
InstanceOfFoo()
```

---

</details>

<details><summary> Ex 3: Object appears to be callable but is not callable</summary>

```python
class Foo:
  def printLine(self):
    print('Print Something')

print(callable(Foo))
```

**Output:**

```
True
```

The instance of `Foo` class appears to be callable but it's not callable. The following code will raise an error.

```python
class Foo:
  def printLine(self):
    print('Print Something')

print(callable(Foo))

InstanceOfFoo = Foo()
# Raises an Error
# 'Foo' object is not callable
InstanceOfFoo()
```

**Output:**

```
True
Traceback (most recent call last):
File "", line 10, in 
TypeError: 'Foo' object is not callable
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#chr" target="_blank"><code>chr(<em>i</em>)</code></a></strong></summary>

**Description:** The `chr()` method returns a character (a string) from an integer (represents unicode code point of the character).

**Syntax:** The syntax of `chr()` is: `chr(i)`

**Parameters:** The `chr()` method takes a single parameter, an integer `i`. The valid range of the integer is from `0` through `1,114,111`.

**Return value:** `chr()` returns a character (a string) whose Unicode code point is the integer `i`. If the integer `i` is outside the range, `ValueError` will be raised.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Returns a one-character string whose Unicode code point is the integer `i`. 

For example, `chr(97)` returns the string `'a'`, while `chr(8364)` returns the string `'€'`. This is the inverse of [`ord()`](https://docs.python.org/3/library/functions.html#ord).

The valid range for the argument is from `0` through `1,114,111` (`0x10FFFF` in base 16). [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) will be raised if `i` is outside that range.

---

</details>

<details><summary> Ex 1: How <code>chr()</code> works</summary>

```python
print(chr(97))
print(chr(65))
print(chr(1200)
```

**Output:**

```
a
A
Ұ
```

---

</details>

<details><summary> Ex 2: Integer passed to <code>chr()</code> is out of the range</summary>

```python
print(chr(-1))
```

**Output:**

```
Traceback (most recent call last):
File "", line 1, in 
ValueError: chr() arg not in range(0x110000)
```

When you run the program, `ValueError` is raised. It's because the argument passed to `chr()` method is out of the range.

---

</details>

<details><summary> ASCII Table</summary>

| Dec | Hex | Oct | Binary | HTML | Char | Description |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| 0 | 00 | 000 | 00000000 | `&#0;` | `NUL` | Null |
| 1 | 01 | 001 | 00000001 | `&#1;` | `SOH` | Start of Header |
| 2 | 02 | 002 | 00000010 | `&#2;` | `STX` | Start of Text |
| 3 | 03 | 003 | 00000011 | `&#3;` | `ETX` | End of Text |
| 4 | 04 | 004 | 00000100 | `&#4;` | `EOT` | End of Transmission |
| 5 | 05 | 005 | 00000101 | `&#5;` | `ENQ` | Enquiry |
| 6 | 06 | 006 | 00000110 | `&#6;` | `ACK` | Acknowledge |
| 7 | 07 | 007 | 00000111 | `&#7;` | `BEL` | Bell |
| 8 | 08 | 010 | 00001000 | `&#8;` | `BS` | Backspace |
| 9 | 09 | 011 | 00001001 | `&#9;` | `HT` | Horizontal Tab |
| 10 | 0A | 012 | 00001010 | `&#10;` | `LF` | Line Feed |
| 11 | 0B | 013 | 00001011 | `&#11;` | `VT` | Vertical Tab |
| 12 | 0C | 014 | 00001100 | `&#12;` | `FF` | Form Feed |
| 13 | 0D | 015 | 00001101 | `&#13;` | `CR` | Carriage Return |
| 14 | 0E | 016 | 00001110 | `&#14;` | `SO` | Shift Out |
| 15 | 0F | 017 | 00001111 | `&#15;` | `SI` | Shift In |
| 16 | 10 | 020 | 00010000 | `&#16;` | `DLE` | Data Link Escape |
| 17 | 11 | 021 | 00010001 | `&#17;` | `DC1` | Device Control 1 |
| 18 | 12 | 022 | 00010010 | `&#18;` | `DC2` | Device Control 2 |
| 19 | 13 | 023 | 00010011 | `&#19;` | `DC3` | Device Control 3 |
| 20 | 14 | 024 | 00010100 | `&#20;` | `DC4` | Device Control 4 |
| 21 | 15 | 025 | 00010101 | `&#21;` | `NAK` | Negative Acknowledge |
| 22 | 16 | 026 | 00010110 | `&#22;` | `SYN` | Synchronize |
| 23 | 17 | 027 | 00010111 | `&#23;` | `ETB` | End of Transmission Block |
| 24 | 18 | 030 | 00011000 | `&#24;` | `CAN` | Cancel |
| 25 | 19 | 031 | 00011001 | `&#25;` | `EM` | End of Medium |
| 26 | 1A | 032 | 00011010 | `&#26;` | `SUB` | Substitute |
| 27 | 1B | 033 | 00011011 | `&#27;` | `ESC` | Escape |
| 28 | 1C | 034 | 00011100 | `&#28;` | `FS` | File Separator |
| 29 | 1D | 035 | 00011101 | `&#29;` | `GS` | Group Separator |
| 30 | 1E | 036 | 00011110 | `&#30;` | `RS` | Record Separator |
| 31 | 1F | 037 | 00011111 | `&#31;` | `US` | Unit Separator |
| 32 | 20 | 040 | 00100000 | `&#32;` | `space` | Space |
| 33 | 21 | 041 | 00100001 | `&#33;` | `!` | exclamation mark |
| 34 | 22 | 042 | 00100010 | `&#34;` | `"` | double quote |
| 35 | 23 | 043 | 00100011 | `&#35;` | `#` | number |
| 36 | 24 | 044 | 00100100 | `&#36;` | `$` | dollar |
| 37 | 25 | 045 | 00100101 | `&#37;` | `%` | percent |
| 38 | 26 | 046 | 00100110 | `&#38;` | `&` | ampersand |
| 39 | 27 | 047 | 00100111 | `&#39;` | `'` | single quote |
| 40 | 28 | 050 | 00101000 | `&#40;` | `(` | left parenthesis |
| 41 | 29 | 051 | 00101001 | `&#41;` | `)` | right parenthesis |
| 42 | 2A | 052 | 00101010 | `&#42;` | `*` | asterisk |
| 43 | 2B | 053 | 00101011 | `&#43;` | `+` | plus |
| 44 | 2C | 054 | 00101100 | `&#44;` | `,` | comma |
| 45 | 2D | 055 | 00101101 | `&#45;` | `-` | minus |
| 46 | 2E | 056 | 00101110 | `&#46;` | `.` | period |
| 47 | 2F | 057 | 00101111 | `&#47;` | `/` | slash |
| 48 | 30 | 060 | 00110000 | `&#48;` | `0` | zero |
| 49 | 31 | 061 | 00110001 | `&#49;` | `1` | one |
| 50 | 32 | 062 | 00110010 | `&#50;` | `2` | two |
| 51 | 33 | 063 | 00110011 | `&#51;` | `3` | three |
| 52 | 34 | 064 | 00110100 | `&#52;` | `4` | four |
| 53 | 35 | 065 | 00110101 | `&#53;` | `5` | five |
| 54 | 36 | 066 | 00110110 | `&#54;` | `6` | six |
| 55 | 37 | 067 | 00110111 | `&#55;` | `7` | seven |
| 56 | 38 | 070 | 00111000 | `&#56;` | `8` | eight |
| 57 | 39 | 071 | 00111001 | `&#57;` | `9` | nine |
| 58 | 3A | 072 | 00111010 | `&#58;` | `:` | colon |
| 59 | 3B | 073 | 00111011 | `&#59;` | `;` | | `semicolon` | |
| 60 | 3C | 074 | 00111100 | `&#60;` | `<` | less than |
| 61 | 3D | 075 | 00111101 | `&#61;` | `=` | equality sign |
| 62 | 3E | 076 | 00111110 | `&#62;` | `>` | greater than |
| 63 | 3F | 077 | 00111111 | `&#63;` | `?` | question mark |
| 64 | 40 | 100 | 01000000 | `&#64;` | `@` | at sign |
| 65 | 41 | 101 | 01000001 | `&#65;` | `A` |   |
| 66 | 42 | 102 | 01000010 | `&#66;` | `B` |   |
| 67 | 43 | 103 | 01000011 | `&#67;` | `C` |   |
| 68 | 44 | 104 | 01000100 | `&#68;` | `D` |   |
| 69 | 45 | 105 | 01000101 | `&#69;` | `E` |   |
| 70 | 46 | 106 | 01000110 | `&#70;` | `F` |   |
| 71 | 47 | 107 | 01000111 | `&#71;` | `G` |   |
| 72 | 48 | 110 | 01001000 | `&#72;` | `H` |   |
| 73 | 49 | 111 | 01001001 | `&#73;` | `I` |   |
| 74 | 4A | 112 | 01001010 | `&#74;` | `J` |   |
| 75 | 4B | 113 | 01001011 | `&#75;` | `K` |   |
| 76 | 4C | 114 | 01001100 | `&#76;` | `L` |   |
| 77 | 4D | 115 | 01001101 | `&#77;` | `M` |   |
| 78 | 4E | 116 | 01001110 | `&#78;` | `N` |   |
| 79 | 4F | 117 | 01001111 | `&#79;` | `O` |   |
| 80 | 50 | 120 | 01010000 | `&#80;` | `P` |   |
| 81 | 51 | 121 | 01010001 | `&#81;` | `Q` |   |
| 82 | 52 | 122 | 01010010 | `&#82;` | `R` |   |
| 83 | 53 | 123 | 01010011 | `&#83;` | `S` |   |
| 84 | 54 | 124 | 01010100 | `&#84;` | `T` |   |
| 85 | 55 | 125 | 01010101 | `&#85;` | `U` |   |
| 86 | 56 | 126 | 01010110 | `&#86;` | `V` |   |
| 87 | 57 | 127 | 01010111 | `&#87;` | `W` |   |
| 88 | 58 | 130 | 01011000 | `&#88;` | `X` |   |
| 89 | 59 | 131 | 01011001 | `&#89;` | `Y` |   |
| 90 | 5A | 132 | 01011010 | `&#90;` | `Z` |   |
| 91 | 5B | 133 | 01011011 | `&#91;` | `[` | left square bracket |
| 92 | 5C | 134 | 01011100 | `&#92;` | `\` | backslash |
| 93 | 5D | 135 | 01011101 | `&#93;` | `]` | right square bracket |
| 94 | 5E | 136 | 01011110 | `&#94;` | `^` | caret / circumflex |
| 95 | 5F | 137 | 01011111 | `&#95;` | `_` | underscore |
| 96 | 60 | 140 | 01100000 | `&#96;` | `` ` `` | grave / accent |
| 97 | 61 | 141 | 01100001 | `&#97;` | `a` |   |
| 98 | 62 | 142 | 01100010 | `&#98;` | `b` |   |
| 99 | 63 | 143 | 01100011 | `&#99;` | `c` |   |
| 100 | 64 | 144 | 01100100 | `&#100;` | `d` |   |
| 101 | 65 | 145 | 01100101 | `&#101;` | `e` |   |
| 102 | 66 | 146 | 01100110 | `&#102;` | `f` |   |
| 103 | 67 | 147 | 01100111 | `&#103;` | `g` |   |
| 104 | 68 | 150 | 01101000 | `&#104;` | `h` |   |
| 105 | 69 | 151 | 01101001 | `&#105;` | `i` |   |
| 106 | 6A | 152 | 01101010 | `&#106;` | `j` |   |
| 107 | 6B | 153 | 01101011 | `&#107;` | `k` |   |
| 108 | 6C | 154 | 01101100 | `&#108;` | `l` |   |
| 109 | 6D | 155 | 01101101 | `&#109;` | `m` |   |
| 110 | 6E | 156 | 01101110 | `&#110;` | `n` |   |
| 111 | 6F | 157 | 01101111 | `&#111;` | `o` |   |
| 112 | 70 | 160 | 01110000 | `&#112;` | `p` |   |
| 113 | 71 | 161 | 01110001 | `&#113;` | `q` |   |
| 114 | 72 | 162 | 01110010 | `&#114;` | `r` |   |
| 115 | 73 | 163 | 01110011 | `&#115;` | `s` |   |
| 116 | 74 | 164 | 01110100 | `&#116;` | `t` |   |
| 117 | 75 | 165 | 01110101 | `&#117;` | `u` |   |
| 118 | 76 | 166 | 01110110 | `&#118;` | `v` |   |
| 119 | 77 | 167 | 01110111 | `&#119;` | `w` |   |
| 120 | 78 | 170 | 01111000 | `&#120;` | `x` |   |
| 121 | 79 | 171 | 01111001 | `&#121;` | `y` |   |
| 122 | 7A | 172 | 01111010 | `&#122;` | `z` |   |
| 123 | 7B | 173 | 01111011 | `&#123;` | `{` | left curly bracket |
| 124 | 7C | 174 | 01111100 | `&#124;` | <code>&#124;</code> | vertical bar |
| 125 | 7D | 175 | 01111101 | `&#125;` | `}` | right curly bracket |
| 126 | 7E | 176 | 01111110 | `&#126;` | `~` | tilde |
| 127 | 7F | 177 | 01111111 | `&#127;` | `DEL` | delete |

---

</details>

<details><summary> Extended ASCII Table</summary>

| Dec | Hex | Binary | HTML | Char |
| :-- | :-- | :-- | :-- | :-- | 
| 128 | 80 | 10000000 | - |  |
| 129 | 81 | 10000001 | - |  |
| 130 | 82 | 10000010 | - |  |
| 131 | 83 | 10000011 | - |  |
| 132 | 84 | 10000100 | - |  |
| 133 | 85 | 10000101 | - |  |
| 134 | 86 | 10000110 | - |  |
| 135 | 87 | 10000111 | - |  |
| 136 | 88 | 10001000 | - |  |
| 137 | 89 | 10001001 | - |  |
| 138 | 8A | 10001010 | - |  |
| 139 | 8B | 10001011 | - |  |
| 140 | 8C | 10001100 | - |  |
| 141 | 8D | 10001101 | - |  |
| 142 | 8E | 10001110 | - |  |
| 143 | 8F | 10001111 | - |  |
| 144 | 90 | 10010000 | - |  |
| 145 | 91 | 10010001 | - |  |
| 146 | 92 | 10010010 | - |  |
| 147 | 93 | 10010011 | - |  |
| 148 | 94 | 10010100 | - |  |
| 149 | 95 | 10010101 | - |  |
| 150 | 96 | 10010110 | - |  |
| 151 | 97 | 10010111 | - |  |
| 152 | 98 | 10011000 | - |  |
| 153 | 99 | 10011001 | - |  |
| 154 | 9A | 10011010 | - |  |
| 155 | 9B | 10011011 | - |  |
| 156 | 9C | 10011100 | - |  |
| 157 | 9D | 10011101 | - |  |
| 158 | 9E | 10011110 | - |  |
| 159 | 9F | 10011111 | - |  |
| 160 | A0 | 10100000 | `&#160;` | | 
| 161 | A1 | 10100001 | `&#161;` | ¡ | 
| 162 | A2 | 10100010 | `&#162;` | ¢ | 
| 163 | A3 | 10100011 | `&#163;` | £ | 
| 164 | A4 | 10100100 | `&#164;` | ¤ | 
| 165 | A5 | 10100101 | `&#165;` | ¥ | 
| 166 | A6 | 10100110 | `&#166;` | ¦ | 
| 167 | A7 | 10100111 | `&#167;` | § | 
| 168 | A8 | 10101000 | `&#168;` | ¨ | 
| 169 | A9 | 10101001 | `&#169;` | © | 
| 170 | AA | 10101010 | `&#170;` | ª | 
| 171 | AB | 10101011 | `&#171;` | « | 
| 172 | AC | 10101100 | `&#172;` | ¬ | 
| 173 | AD | 10101101 | `&#173;` | ­ | 
| 174 | AE | 10101110 | `&#174;` | ® | 
| 175 | AF | 10101111 | `&#175;` | ¯ | 
| 176 | B0 | 10110000 | `&#176;` | ° | 
| 177 | B1 | 10110001 | `&#177;` | ± | 
| 178 | B2 | 10110010 | `&#178;` | ² | 
| 179 | B3 | 10110011 | `&#179;` | ³ | 
| 180 | B4 | 10110100 | `&#180;` | ´ | 
| 181 | B5 | 10110101 | `&#181;` | µ | 
| 182 | B6 | 10110110 | `&#182;` | ¶ | 
| 183 | B7 | 10110111 | `&#183;` | · | 
| 184 | B8 | 10111000 | `&#184;` | ¸ | 
| 185 | B9 | 10111001 | `&#185;` | ¹ | 
| 186 | BA | 10111010 | `&#186;` | º | 
| 187 | BB | 10111011 | `&#187;` | » | 
| 188 | BC | 10111100 | `&#188;` | ¼ | 
| 189 | BD | 10111101 | `&#189;` | ½ | 
| 190 | BE | 10111110 | `&#190;` | ¾ | 
| 191 | BF | 10111111 | `&#191;` | ¿ | 
| 192 | C0 | 11000000 | `&#192;` | À | 
| 193 | C1 | 11000001 | `&#193;` | Á | 
| 194 | C2 | 11000010 | `&#194;` | Â | 
| 195 | C3 | 11000011 | `&#195;` | Ã | 
| 196 | C4 | 11000100 | `&#196;` | Ä | 
| 197 | C5 | 11000101 | `&#197;` | Å | 
| 198 | C6 | 11000110 | `&#198;` | Æ | 
| 199 | C7 | 11000111 | `&#199;` | Ç | 
| 200 | C8 | 11001000 | `&#200;` | È | 
| 201 | C9 | 11001001 | `&#201;` | É | 
| 202 | CA | 11001010 | `&#202;` | Ê | 
| 203 | CB | 11001011 | `&#203;` | Ë | 
| 204 | CC | 11001100 | `&#204;` | Ì | 
| 205 | CD | 11001101 | `&#205;` | Í | 
| 206 | CE | 11001110 | `&#206;` | Î | 
| 207 | CF | 11001111 | `&#207;` | Ï | 
| 208 | D0 | 11010000 | `&#208;` | Ð | 
| 209 | D1 | 11010001 | `&#209;` | Ñ | 
| 210 | D2 | 11010010 | `&#210;` | Ò | 
| 211 | D3 | 11010011 | `&#211;` | Ó | 
| 212 | D4 | 11010100 | `&#212;` | Ô | 
| 213 | D5 | 11010101 | `&#213;` | Õ | 
| 214 | D6 | 11010110 | `&#214;` | Ö | 
| 215 | D7 | 11010111 | `&#215;` | × | 
| 216 | D8 | 11011000 | `&#216;` | Ø | 
| 217 | D9 | 11011001 | `&#217;` | Ù | 
| 218 | DA | 11011010 | `&#218;` | Ú | 
| 219 | DB | 11011011 | `&#219;` | Û | 
| 220 | DC | 11011100 | `&#220;` | Ü | 
| 221 | DD | 11011101 | `&#221;` | Ý | 
| 222 | DE | 11011110 | `&#222;` | Þ | 
| 223 | DF | 11011111 | `&#223;` | ß | 
| 224 | E0 | 11100000 | `&#224;` | à | 
| 225 | E1 | 11100001 | `&#225;` | á | 
| 226 | E2 | 11100010 | `&#226;` | â | 
| 227 | E3 | 11100011 | `&#227;` | ã | 
| 228 | E4 | 11100100 | `&#228;` | ä | 
| 229 | E5 | 11100101 | `&#229;` | å | 
| 230 | E6 | 11100110 | `&#230;` | æ | 
| 231 | E7 | 11100111 | `&#231;` | ç | 
| 232 | E8 | 11101000 | `&#232;` | è | 
| 233 | E9 | 11101001 | `&#233;` | é | 
| 234 | EA | 11101010 | `&#234;` | ê | 
| 235 | EB | 11101011 | `&#235;` | ë | 
| 236 | EC | 11101100 | `&#236;` | ì | 
| 237 | ED | 11101101 | `&#237;` | í | 
| 238 | EE | 11101110 | `&#238;` | î | 
| 239 | EF | 11101111 | `&#239;` | ï | 
| 240 | F0 | 11110000 | `&#240;` | ð | 
| 241 | F1 | 11110001 | `&#241;` | ñ | 
| 242 | F2 | 11110010 | `&#242;` | ò | 
| 243 | F3 | 11110011 | `&#243;` | ó | 
| 244 | F4 | 11110100 | `&#244;` | ô | 
| 245 | F5 | 11110101 | `&#245;` | õ | 
| 246 | F6 | 11110110 | `&#246;` | ö | 
| 247 | F7 | 11110111 | `&#247;` | ÷ | 
| 248 | F8 | 11111000 | `&#248;` | ø | 
| 249 | F9 | 11111001 | `&#249;` | ù | 
| 250 | FA | 11111010 | `&#250;` | ú | 
| 251 | FB | 11111011 | `&#251;` | û | 
| 252 | FC | 11111100 | `&#252;` | ü | 
| 253 | FD | 11111101 | `&#253;` | ý | 
| 254 | FE | 11111110 | `&#254;` | þ | 
| 255 | FF | 11111111 | `&#255;` | ÿ | 

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#classmethod" target="_blank"><code>@classmethod</code></a></strong></summary>

**Description:** Returns a class method for a function.

A class method receives the class as implicit first argument, just like an instance method receives the instance (i.e., `self`). To declare a class method, use this idiom:

```python
class C:
    @classmethod
    def f(cls, arg1, arg2, ...): ...
```

The `@classmethod` form is a function [decorator](https://docs.python.org/3/glossary.html#term-decorator) – see [Function definitions](https://docs.python.org/3/reference/compound_stmts.html#function) for details.

A class method can be called either on the class (such as `C.f()`) or on an instance (such as `C().f()`). The instance is ignored except for its class. If a class method is called for a derived class, the derived class object is passed as the implied first argument.

Class methods are different than C++ or Java static methods. If you want those, see [`staticmethod()`](https://docs.python.org/3/library/functions.html#staticmethod). For more information on class methods, see [The standard type hierarchy](https://docs.python.org/3/reference/datamodel.html#types).

*Changed in version 3.9:* Class methods can now wrap other [descriptors](https://docs.python.org/3/glossary.html#term-descriptor) such as [`property()`](https://docs.python.org/3/library/functions.html#property).

**Examples:** The `classmethod` syntax used to be `classmethod(function)` but was considered un-Pythonic; thus, in newer Python versions, you can use the `@classmethod` decorator for `classmethod` definitions.

<details><summary> Ex 1: Usage notes and difference from <code>staticmethod</code></summary>

A class method is a method that is bound to a class rather than its object. It doesn't require creation of a class instance, much like `staticmethod`.

The difference between a static method and a class method is:

- Static method knows nothing about the class and just deals with the parameters
- Class method works with the class since its parameter is always the class itself.

The class method can be called both by the class and its object: `Class.classmethod()` or `Class().classmethod()`. Regardless, the class method is always attached to a class with the first argument as the class itself, `cls`:

```python
class C:
    @classmethod
    def f(cls, arg1, arg2, ...): ...
```

---

</details>

<details><summary> Ex 2: Simple and equivalent usage of <code>classmethod(function)</code> and <code>@classmethod</code></summary>

The code block

```python
class Person:
    age = 25
    
    def printAge(cls):
        print('The age is:', cls.age)

# create printAge class method
Person.printAge = classmethod(Person.printAge)
Person.printAge()
```

and 

```python
class Person:
    age = 25
    
    # create printAge class method
    @classmethod
    def printAge(cls):
        print('The age is:', cls.age)

Person.printAge()
```

are effectively the same and have the following output:

```
The age is: 25
```

**Notes:** We have a `Person` class with a member variable `age` assigned to `25`. We also have a function `printAge` that takes a single parameter `cls` and not `self` which is what we would usually take; that is, `cls` accepts the `Person` class as a parameter rather than Person instance we typically refer to by `self`.

For the `classmethod(function)` syntaxm, we pass the method `Person.printAge` as an argument to the `classmethod` function. This converts the method to a class method so that it accepts the first parameter as a class (i.e., Person). We then call `printAge` without creating a `Person` object like we do for static methods. This prints the class variable `age`.

The `@classmethod` function decorator form allows our code to be cleaner and is the more modern way to write Python code.

---

</details>

<details><summary> Ex 3: Using <code>@classmethod</code> to create a factory method</summary>

Factory methods are those methods that return a class object (similar to the `__init__` constructor method which initializes the new instance of the class, `self`) for different use cases. 

It is similar to function overloading in C++. Since, Python doesn't have anything as such, class methods and static methods are used.

```python
from datetime import date

# random Person
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    @classmethod
    def fromBirthYear(cls, name, birthYear):
        return cls(name, date.today().year - birthYear)

    def display(self):
        print(self.name + "'s age is: " + str(self.age))

person = Person('Adam', 19)
person.display()

person1 = Person.fromBirthYear('John',  1985)
person1.display()
```

**Output:**

```
Adam's age is: 19
John's age is: 36
```

The code block that produces the output above has two class instance creators, a constructor (i.e., `__init__`) and a `fromBirthYear` method.

The constructor takes its normal parameters, `name` and `age` in this case, while `fromBirthYear` takes `cls` (i.e., the `Person` class), `name`, and `birthYear`, and calculates the current age by subtracting the `birthYear` from the current year and returns the newly created class instance (the fact that `fromBirthYear` returns a new class instance is what makes it a factory method).

The `fromBirthYear` method takes the `Person` class (not a `Person` instance or object) as the first parameter, `cls`, and returns the constructor by calling `cls(name, date.today().year - birthYear)`, which is equivalent to `Person(name, date.today().year - birthYear)`.

Before the definition of the `fromBirthYear` method, we see `@classmethod`. This is called a decorator for converting `fromBirthYear` to a class method as `classmethod()`.

---

</details>

<details><summary> Ex 4: How <code>@classmethod</code> works in the context of inheritance (and why <code>@staticmethod</code> would fail)</summary>

Whenever you derive a class from implementing a factory method as a class method, it ensures correct instance creation of the derived class. If, however, a factory method is implemented as a static method, then the instance created will always be hardcoded as the base class.

But when you use a class method, it creates the correct instance of the derived class. This is easier to understand by means of an example:

```python
from datetime import date

# random Person
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    @staticmethod
    def fromFathersAge(name, fatherAge, fatherPersonAgeDiff):
        # Cannot return cls(arg1, arg2, ...) or something like that since
        # static methods know nothing about the class and deal strictly with the parameters
        return Person(name, date.today().year - fatherAge + fatherPersonAgeDiff)

    @classmethod
    def fromBirthYear(cls, name, birthYear):
        return cls(name, date.today().year - birthYear)

    def display(self):
        print(self.name + "'s age is: " + str(self.age))

class Man(Person):
    sex = 'Male'

man_w_class_method = Man.fromBirthYear('John', 1985)
print(man_w_class_method)
print(isinstance(man_w_class_method, Man))
print(isinstance(man_w_class_method, Person))

man_w_static_method = Man.fromFathersAge('Bruce', 1965, 20)
print(man_w_static_method)
print(isinstance(man_w_static_method, Man))
print(isinstance(man_w_static_method, Person))
```

**Output:**

```
<__main__.Man object at 0x10dde4af0>
True
True

<__main__.Person object at 0x10dde49d0>
False
True
```

Using `@staticmethod` for the `fromFathersAge` factory method forces us to hardcode the instance tape (i.e., `Person`) during creation. This clearly causes a problem when `Man` inherits from `Person`. 

The `fromFathersAge` method doesn't return a `Man` object but its base class, a hardcoded `Person` object.  This violates the OOP paradigm. Using `@classmethod` for the `fromBirthYear` factory method can ensure the OOP-ness of the code since this method takes the first parameter as the class itself and calls its factory method.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#compile" target="_blank"><code>compile(<em>source, filename, mode, flags=0, dont_inherit=False, optimize=-1</em>)</code></a></strong></summary>

**Description:** [This StackOverflow answer](https://stackoverflow.com/a/22444050/5209533) gives a great somewhat dumbed down explanation (actual documentation reproduced below as an example): `compile` is a lower level version of `exec` and `eval`. It does not execute or evaluate your statements or expressions, but returns a code object that can do it. The modes are as follows:

1. `compile(string, '', 'eval')` returns the code object that would have been executed had you done `eval(string)`. Note that you *cannot* use statements in this mode; only a (single) expression is valid. Used for a single expression.
2. `compile(string, '', 'exec')` returns the code object that would have been executed had you done `exec(string)`. You can use any number of statements here. Used for an entire module.
3. `compile(string, '', 'single')` is like the `exec` mode, but it will ignore everything except for the first statement. Note that an `if/else` statement with its results is considered a single statement. Used for one single statement. [Does not seem to be particularly useful.]

**Examples:** 

<details><summary> Ex 0: Official documentation</summary>

**Syntax:** <code>compile(<em>source</em>, <em>filename</em>, <em>mode</em>, <em>flags=0</em>, <em>dont_inherit=False</em>, <em>optimize=-1</em>)</code>

Compile the <code>source</code> into a code or AST object. Code objects can be executed by [`exec()`](https://docs.python.org/3/library/functions.html#exec) or [`eval()`](https://docs.python.org/3/library/functions.html#eval). <code>source</code> can either be a normal string, a byte string, or an AST object. Refer to the [`ast`](https://docs.python.org/3/library/ast.html) module documentation for information on how to work with AST objects.

The <code>filename</code> argument should give the file from which the code was read; pass some recognizable value if it wasn't read from a file (`'<string>'` is commonly used).

The <code>mode</code> argument specifies what kind of code must be compiled; it can be `'exec'` if source consists of a sequence of statements, `'eval'` if it consists of a single expression, or `'single'` if it consists of a single interactive statement (in the latter case, expression statements that evaluate to something other than `None` will be printed).

The optional arguments `flags` and `dont_inherit` control which [compiler options](https://docs.python.org/3/library/ast.html#ast-compiler-flags) should be activated and which [future features](https://docs.python.org/3/reference/simple_stmts.html#future) should be allowed. If neither is present (or both are zero) the code is compiled with the same flags that affect the code that is calling [`compile()`](https://docs.python.org/3/library/functions.html#compile). If the <code>flags</code> argument is given and `dont_inherit` is not (or is zero) then the compiler options and the future statements specified by the `flags` argument are used in addition to those that would be used anyway. If `dont_inherit` is a non-zero integer then the `flags` argument is it – the flags (future features and compiler options) in the surrounding code are ignored.

Compiler options and future statements are specified by bits which can be bitwise ORed together to specify multiple options. The bitfield required to specify a given future feature can be found as the `compiler_flag` attribute on the `_Feature` instance in the [`__future__`](https://docs.python.org/3/library/__future__.html#module-__future__) module. [Compiler flags](https://docs.python.org/3/library/ast.html#ast-compiler-flags) can be found in [`ast`](https://docs.python.org/3/library/ast.html#module-ast) module, with `PyCF_` prefix.

The argument `optimize` specifies the optimization level of the compiler; the default value of `-1` selects the optimization level of the interpreter as given by [`-O`](https://docs.python.org/3/using/cmdline.html#cmdoption-o) options. Explicit levels are `0` (no optimization; `__debug__` is true), `1` (asserts are removed, `__debug__` is false) or `2` (docstrings are removed too).

This function raises [`SyntaxError`](https://docs.python.org/3/library/exceptions.html#SyntaxError) if the compiled source is invalid, and [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) if the source contains null bytes.

If you want to parse Python code into its AST representation, see [`ast.parse()`](https://docs.python.org/3/library/ast.html#ast.parse).

Raises an [auditing event](https://docs.python.org/3/library/sys.html#auditing) `compile` with arguments `source` and `filename`. This event may also be raised by implicit compilation.

**Note:** When compiling a string with multi-line code in `'single'` or `'eval'` mode, input must be terminated by at least one newline character. This is to facilitate detection of incomplete and complete statements in the [`code`](https://docs.python.org/3/library/code.html#module-code) module.

**Warning:** It is possible to crash the Python interpreter with a sufficiently large/complex string when compiling to an AST object due to stack depth limitations in Python's AST compiler.

*Changed in version 3.2:* Allowed use of Windows and Mac newlines. Also input in `'exec'` mode does not have to end in a newline anymore. Added the *optimize* parameter.

*Changed in version 3.5:* Previously, [`TypeError`](https://docs.python.org/3/library/exceptions.html#TypeError) was raised when null bytes were encountered in source.

*New in version 3.8:* `ast.PyCF_ALLOW_TOP_LEVEL_AWAIT` can now be passed in flags to enable support for top-level `await`, `async for`, and `async with`.

---

</details>

<details><summary> Ex 1: Examples and notes involving <code>single</code>, <code>eval</code>, and <code>exec</code> modes</summary>

As [this helpful post](https://joequery.me/code/python-builtin-functions/#compile) illustrates, `compile` is meant to compile a `source` string from `filename` into a code object, which can later be executed by `eval()` or `exec()`. `filename` is simply used for run-time error messages. It is recommended to use `'<string>'` as the `filename` if `source` was not read from a file. `mode` is a string which indicates the compilation mode with the following options available:

- `'single'`: indicates compilation is intended for a single statement
- `'eval'`: indicates compilation is intended for a single expression
- `'exec'`: indicates compliation is intended for an entire Python module

First, note that all expressions are statements (e.g., `5+5`) in Python but not all statements are expressions (e.g., `x = 5+5`). Second, note that use of `compile` is rather infrequent. If you do find yourself using `compile` then you will likely use the `exec` mode. In any case, let's explore a few trivial use cases to illustrate usage.

**Usage of `compile` with `mode` set to `'single'`:** Suppose you have two files, `example_usage.py` and `simple_module.py`, in the same directory with contents as follows

```python
# file: example_usage.py
with open('./simple_module.py') as f:
  contents = f.read()

code_obj_single = compile(contents, 'simple_module.py', 'single')
exec(code_obj_single)
```

```python
# file: simple_module.py
import json

def myfn(mydict):
    return json.dumps(mydict)

def myfn2():
    return myfn({"x": 30})

print(myfn2())
```

If we attempt to run `example_usage.py`, then we will get an error:

```
File "simple_module.py", line 1
  import json
              ^
SyntaxError: multiple statements found while compiling a single statement
```

The error is exactly what it sounds like: Multiple statements currently exist in the `simple_module.py` file, but `compile` with the `mode` option set to `'single'` is only meant to compile a *single* statement. Consider updating the `example_usage.py` and `simple_module.py` files as follows:

```python
# file: example_usage.py
with open('./simple_module.py') as f:
  contents = f.read()

code_obj_single = compile(contents, 'simple_module.py', 'single')
exec(code_obj_single)
print(json)
```

```python
# file: simple_module.py
import json
```

Note that now `simple_module.py` only has a single statement in it, namely `import json`. We compile that single statement in `example_usage.py` and we can see that the statement has been executed via the `print(json)` statement:

```
<module 'json' from '/Users/danielfarlow/.pyenv/versions/3.9.4/lib/python3.9/json/__init__.py'>
```

**Usage of `compile` with `mode` set to `'eval'`:** Suppose you have two files, `example_usage.py` and `simple_module.py`, in the same directory with contents as follows

```python
# file: example_usage.py
with open('./simple_module.py') as f:
  contents = f.read()

code_obj_eval = compile(contents, 'simple_module.py', 'eval')
eval(code_obj_eval)
```

```python
# file: simple_module.py
import json
```

If we attempt to run `example_usage.py`, then we will get an error:

```
File "simple_module.py", line 1
  import json
  ^
SyntaxError: invalid syntax
```

Why do we get this error? Because when `'eval'` is chosen as the `mode` option we can only use an *expression* (singular) as the source. Remember that all expressions are statements but not all statements are expressions (expressions must resolve to a value). Suppose you change `example_usage.py` and `simple_module.py` in the following manner:

```python
# file: example_usage.py
with open('./simple_module.py') as f:
  contents = f.read()

code_obj_eval = compile(contents, 'simple_module.py', 'eval')
```

```python
# file: simple_module.py
"2+3"
"5+10"
```

Will we get an error when running the `example_usage.py` file? Yes: 

```
File "simple_module.py", line 2
  "5+10"
  ^
SyntaxError: invalid syntax
```

Why do we get this error? Because we have more than one expression. Update the `simple_module.py` file to have `"2+3"` as its *only* line, and update the `example_usage.py` as well:

```python
# file: example_usage.py
with open('./simple_module.py') as f:
  contents = f.read()

code_obj_eval = compile(contents, 'simple_module.py', 'eval')
num = eval(code_obj_eval)
print(num)
```

```python
# file: simple_module.py
"2+3"
```

What do you think the output will be upon running the `example_usage.py` file? You might be surprised when you get `2+3` as the output. Why didn't `eval` actually evaluate `"2+3"` like we might have suspected? The easiest way to see this is probably by means of updating the `example_usage.py` file and running it again:

```python
# file: example_usage.py
with open('./simple_module.py') as f:
  contents = f.read()
  print("===== BEGIN READING FILE CONTENTS =====")
  print(dir(contents))
  print(type(contents))
  print("===== END READING FILE CONTENTS =====")

code_obj_eval = compile(contents, 'simple_module.py', 'eval')
print("===== BEGIN ATTRIBUTES OF COMPILED FILE CONTENTS OBJECT =====")
print(dir(code_obj_eval))
print("===== END ATTRIBUTES OF COMPILED FILE CONTENTS OBJECT =====")
print("Type of code object: ", type(code_obj_eval))
print("Type of evaluated code object: ", type(eval(code_obj_eval)))
```

```python
# file: simple_module.py
"2+3"
```

**Output:**

```
===== BEGIN READING FILE CONTENTS =====
['__add__', '__class__', '__contains__', '__delattr__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__getnewargs__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__iter__', '__le__', '__len__', '__lt__', '__mod__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__rmod__', '__rmul__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', 'capitalize', 'casefold', 'center', 'count', 'encode', 'endswith', 'expandtabs', 'find', 'format', 'format_map', 'index', 'isalnum', 'isalpha', 'isascii', 'isdecimal', 'isdigit', 'isidentifier', 'islower', 'isnumeric', 'isprintable', 'isspace', 'istitle', 'isupper', 'join', 'ljust', 'lower', 'lstrip', 'maketrans', 'partition', 'removeprefix', 'removesuffix', 'replace', 'rfind', 'rindex', 'rjust', 'rpartition', 'rsplit', 'rstrip', 'split', 'splitlines', 'startswith', 'strip', 'swapcase', 'title', 'translate', 'upper', 'zfill']
<class 'str'>
===== END READING FILE CONTENTS =====
===== BEGIN ATTRIBUTES OF COMPILED FILE CONTENTS OBJECT =====
['__class__', '__delattr__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__le__', '__lt__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', 'co_argcount', 'co_cellvars', 'co_code', 'co_consts', 'co_filename', 'co_firstlineno', 'co_flags', 'co_freevars', 'co_kwonlyargcount', 'co_lnotab', 'co_name', 'co_names', 'co_nlocals', 'co_posonlyargcount', 'co_stacksize', 'co_varnames', 'replace']
===== END ATTRIBUTES OF COMPILED FILE CONTENTS OBJECT =====
Type of code object:  <class 'code'>
Type of evaluated code object:  <class 'str'>
```

Some reflection seems to indicate that evaluating a `code` object essenitally "unwraps" the `code` object so we get the original code, namely a string in this case: `"2+3"`. If we then want to evaluate *that* string, we must use `eval` again (hence twice):

```python
# file: example_usage.py
with open('./simple_module.py') as f:
  contents = f.read()

code_obj_eval = compile(contents, 'simple_module.py', 'eval')
num = eval(eval(code_obj_eval))
print(num)
```

```python
# file: simple_module.py
"2+3"
```

The output is then more in line with what we might normally expect: `5`. This behavior suggests a way we could avoid all of this rigmarole entirely: instead of writing `"2+3"` in the `simple_module.py` file, why not simply have `2+3` which will be stringified upon reading and then effectively evaluated when `eval` is applied after `compile`? We can avoid the double use of `eval` in such a case. Hence, we could have the following which would also have an output of `5` (note how there is now only one use of `eval` in `example_usage.py` and the `"2+3"` is now simply `2+3` in the `simple_module.py` file):

```python
# file: example_usage.py
with open('./simple_module.py') as f:
  contents = f.read()

code_obj_eval = compile(contents, 'simple_module.py', 'eval')
num = eval(code_obj_eval)
print(num)
```

```python
# file: simple_module.py
2+3
```

**Usage of `compile` with `mode` set to `'exec'`:** If you find yourself using `compile`, then odds are this will be how you use it! Suppose you have two files, `example_usage.py` and `simple_module.py`, in the same directory with contents as follows:

```python
# file: example_usage.py
with open('./simple_module.py') as f:
  contents = f.read()

code_obj_exec = compile(contents, 'simple_module.py', 'exec')
exec(code_obj_exec)
```

```python
# file: simple_module.py
import json

def myfn(mydict):
    return json.dumps(mydict)

def myfn2():
    return myfn({"x": 30})

print(myfn2())
```

If we attempt to run `example_usage.py`, then we will get what we might expect:

```
{"x": 30}
```

Furthermore, if we tried to execute a statement like `print(myfn)` from within `example_usage.py`, then we would get something like `<function myfn at 0x10ba9fca0>` which indicates the `myfn` function has been read in effectively from the `simple_module.py` file.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#complex" target="_blank"><code>complex([<em>real</em>[, <em>imag</em>]])</code></a></strong></summary>

**Description:** The `complex()` method returns a complex number when real and imaginary parts are provided, or it converts a string to a complex number.

The syntax of `complex()` is: 

```python
complex([real[, imag]])
```

In general, `complex()` method takes two parameters:

- `real` - real part. If `real` is omitted, it defaults to `0`.
- `imag` - imaginary part. If `imag` is omitted, it defaults to `0`.

If the first parameter passed to this method is a string, it will be interpreted as a complex number. In this case, the second parameter shouldn't be passed.

As suggested by the name, `complex()` method returns a complex number. If the string passed to this method is not a valid complex number, `ValueError` exception is raised.

**Note:** The string passed to `complex()` should be in the form `real+imagj` or `real+imagJ`.

**Examples:**

<details><summary> Ex 0: Documentation</summary>

Return a complex number with the value `real + imag*1j` or convert a string or number to a complex number. If the first parameter is a string, it will be interpreted as a complex number and the function must be called without a second parameter. The second parameter can never be a string. Each argument may be any numeric type (including complex). If `imag` is omitted, it defaults to zero and the constructor serves as a numeric conversion like [`int`](https://docs.python.org/3/library/functions.html#int) and [`float`](https://docs.python.org/3/library/functions.html#float). If both arguments are omitted, returns `0j`.

For a general Python object `x`, `complex(x)` delegates to `x.__complex__()`. If `__complex__()` is not defined then it falls back to [`__float__()`](https://docs.python.org/3/reference/datamodel.html#object.__float__). If `__float__()` is not defined then it falls back to [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__).

**Note:** When converting from a string, the string must not contain whitespace around the central `+` or `-` operator. For example, `complex('1+2j')` is fine, but `complex('1 + 2j')` raises [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError).

The complex type is described in [Numeric Types — int, float, complex](https://docs.python.org/3/library/stdtypes.html#typesnumeric).

*Changed in version 3.6:* Grouping digits with underscores as in code literals is allowed.

*Changed in version 3.8:* Falls back to [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__) if [`__complex__()`](https://docs.python.org/3/reference/datamodel.html#object.__complex__) and [`__float__()`](https://docs.python.org/3/reference/datamodel.html#object.__float__) are not defined.

---

</details>

<details><summary> Ex 1: How to create a complex number in Python?</summary>

```python
z = complex(2, -3)
print(z)

z = complex(1)
print(z)

z = complex()
print(z)

z = complex('5-9j')
print(z)
```

**Output:**

```
(2-3j)
(1+0j)
0j
(5-9j)
```

---

</details>

<details><summary> Ex 2: Create complex Number Without Using <code>complex()</code></summary>

It's possible to create a complex number without using the `complex()` method explicitly. For that, you have to put `'j'` or `'J'` after a number.

```python
a = 2+3j
print('a =',a)
print('Type of a is',type(a))

b = -2j
print('b =',b)
print('Type of b is',type(a))

c = 0j
print('c =',c)
print('Type of c is',type(c))
```

**Output:**

```
a = (2+3j)
Type of a is <class 'complex'>
b = (-0-2j)
Type of b is <class 'complex'>
c = 0j
Type of c is <class 'complex'>
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#delattr" target="_blank"><code>delattr(<em>object, name</em>)</code></a></strong></summary>

**Description:** The `delattr()` built-in deletes an attribute from the provided object (if the object allows it).

The syntax of delattr() is:

```python
delattr(object, name)
```

`delattr()` takes two parameters:

- `object` - the object from which `name` attribute is to be removed
- `name` -  a string which must be the name of the attribute to be removed from the `object`

`delattr()` doesn't return any value (returns `None`). It only removes an attribute (if the object allows it).

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

This is a relative of [`setattr()`](https://docs.python.org/3/library/functions.html#setattr). The arguments are an object and a string. The string must be the name of one of the object's attributes. The function deletes the named attribute, provided the object allows it. For example, `delattr(x, 'foobar')` is equivalent to `del x.foobar`.

---

</details>

<details><summary> Ex 1: How <code>delattr()</code> works?</summary>

```python
class Coordinate:
  x = 10
  y = -5
  z = 0

point1 = Coordinate() 

print('x = ',point1.x)
print('y = ',point1.y)
print('z = ',point1.z)

delattr(Coordinate, 'z')

print('--After deleting z attribute--')
print('x = ',point1.x)
print('y = ',point1.y)

# Raises Error
print('z = ',point1.z)
```

**Output:**

```
x =  10
y =  -5
z =  0
--After deleting z attribute--
x =  10
y =  -5
Traceback (most recent call last):
  File "/Volumes/DEVFARLOW/development-and-engineering/python-learnings/mymodule.py", line 19, in <module>
    print('z = ',point1.z)
AttributeError: 'Coordinate' object has no attribute 'z'
```

---

</details>

<details><summary> Ex 2: Deleting attribute using <code>del</code> operator</summary>

You can also delete attribute of an object using `del` operator.

```python
class Coordinate:
  x = 10
  y = -5
  z = 0

point1 = Coordinate() 

print('x = ',point1.x)
print('y = ',point1.y)
print('z = ',point1.z)

# Deleting attribute z
del Coordinate.z

print('--After deleting z attribute--')
print('x = ',point1.x)
print('y = ',point1.y)

# Raises Attribute Error
print('z = ',point1.z)
```

The output of the program will be the same as in Example 1.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-dict" target="_blank"><code>dict(<em>**kwarg</em>); dict(<em>mapping, **kwarg</em>); dict(<em>iterable, **kwarg</em>)</code></a></strong></summary>

**Description:** The `dict()` constructor creates a dictionary in Python. Different forms of `dict()` constructors are:

```python
class dict(**kwarg)
class dict(mapping, **kwarg)
class dict(iterable, **kwarg)
```

**Note:** `**kwarg` lets you take an arbitrary number of keyword arguments.

A keyword argument is an argument preceded by an identifier (e.g., `name=`). Hence, the keyword argument of the form `kwarg=value` is passed to the `dict()` constructor to create dictionaries.

`dict()` doesn't return any value (returns `None`).

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

<pre>
class dict(**kwarg)
class dict(mapping, **kwarg)
class dict(iterable, **kwarg)
</pre>

Create a new dictionary. The [`dict`](https://docs.python.org/3/library/stdtypes.html#dict) object is the dictionary class. See dict and [Mapping Types — dict](https://docs.python.org/3/library/stdtypes.html#typesmapping) for documentation about this class.

For other containers see the built-in [`list`](https://docs.python.org/3/library/stdtypes.html#list), [`set`](https://docs.python.org/3/library/stdtypes.html#set), and [`tuple`](https://docs.python.org/3/library/stdtypes.html#tuple) classes, as well as the [collections](https://docs.python.org/3/library/collections.html#module-collections) module.

---

</details>

<details><summary> Ex 1: Create dictionary using keyword arguments only</summary>

```python
numbers = dict(x=5, y=0)
print('numbers =', numbers)
print(type(numbers))

empty = dict()
print('empty =', empty)
print(type(empty))
```

**Output:**

```
numbers = {'x': 5, 'y': 0}
<class 'dict'>
empty = {}
<class 'dict'>
```

---

</details>

<details><summary> Ex 2: Create dictionary using an iterable</summary>

```python
# keyword argument is not passed
numbers1 = dict([('x', 5), ('y', -5)])
print('numbers1 =',numbers1)

# keyword argument is also passed
numbers2 = dict([('x', 5), ('y', -5)], z=8)
print('numbers2 =',numbers2)

# zip() creates an iterable in Python 3
numbers3 = dict(dict(zip(['x', 'y', 'z'], [1, 2, 3])))
print('numbers3 =',numbers3)
```

**Output:**

```
numbers1 = {'x': 5, 'y': -5}
numbers2 = {'x': 5, 'y': -5, 'z': 8}
numbers3 = {'x': 1, 'y': 2, 'z': 3}
```

---

</details>

<details><summary> Ex 3: Create dictionary using mapping</summary>

```python
numbers1 = dict({'x': 4, 'y': 5})
print('numbers1 =',numbers1)

# you don't need to use dict() in above code
numbers2 = {'x': 4, 'y': 5}
print('numbers2 =',numbers2)

# keyword argument is also passed
numbers3 = dict({'x': 4, 'y': 5}, z=8)
print('numbers3 =',numbers3)
```

**Output:**

```
numbers1 = {'x': 4, 'y': 5}
numbers2 = {'x': 4, 'y': 5}
numbers3 = {'x': 4, 'y': 5, 'z': 8}
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#dir" target="_blank"><code>dir([<em>object</em>])</code></a></strong></summary>

**Description:** The `dir()` method tries to return a list of valid attributes of the object. 

The syntax of `dir()` is:

```python
dir([object])
```

`dir()` takes maximum of one object.

- `object` (optional) - `dir()` attempts to return all attributes of this object.

`dir()` tries to return a list of valid attributes of the object.

- If the object has `__dir__()` method, the method will be called and must return the list of attributes.
- If the object doesn't have `__dir__()` method, this method tries to find information from the `__dict__` attribute (if defined), and from type object. In this case, the list returned from `dir()` may not be complete.

If an object is not passed to `dir()` method, it returns the list of names in the current local scope.


**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Without arguments, return the list of names in the current local scope. With an argument, attempt to return a list of valid attributes for that object.

If the object has a method named [`__dir__()`](https://docs.python.org/3/reference/datamodel.html#object.__dir__), this method will be called and must return the list of attributes. This allows objects that implement a custom [`__getattr__()`](https://docs.python.org/3/reference/datamodel.html#object.__getattr__) or [`__getattribute__()`](https://docs.python.org/3/reference/datamodel.html#object.__getattribute__) function to customize the way [`dir()`](https://docs.python.org/3/library/functions.html#dir) reports their attributes.

If the object does not provide [`__dir__()`](https://docs.python.org/3/reference/datamodel.html#object.__dir__), the function tries its best to gather information from the object's [`__dict__`](https://docs.python.org/3/library/stdtypes.html#object.__dict__) attribute, if defined, and from its type object. The resulting list is not necessarily complete, and may be inaccurate when the object has a custom [`__getattr__()`](https://docs.python.org/3/reference/datamodel.html#object.__getattr__).

The default [`dir()`](https://docs.python.org/3/library/functions.html#dir) mechanism behaves differently with different types of objects, as it attempts to produce the most relevant, rather than complete, information:

- If the object is a module object, the list contains the names of the module's attributes.
- If the object is a type or class object, the list contains the names of its attributes, and recursively of the attributes of its bases.
- Otherwise, the list contains the object's attributes' names, the names of its class's attributes, and recursively of the attributes of its class's base classes.

The resulting list is sorted alphabetically. For example:

```
>>> import struct
>>> dir()
['__annotations__', '__builtins__', '__doc__', '__loader__', '__name__', '__package__', '__spec__', 'struct']
>>> class Shape:
...     def __dir__(self):
...             return ['area', 'perimeter', 'location']
... 
>>> s = Shape()
>>> dir(s)
['area', 'location', 'perimeter']
>>> 
```

**Note:** Because [`dir()`](https://docs.python.org/3/library/functions.html#dir) is supplied primarily as a convenience for use at an interactive prompt, it tries to supply an interesting set of names more than it tries to supply a rigorously or consistently defined set of names, and its detailed behavior may change across releases. For example, metaclass attributes are not in the result list when the argument is a class.

---

</details>

<details><summary> Ex 1: How <code>dir()</code> works?</summary>

```python
number = [1, 2, 3]
print(dir(number))

print('\nReturn Value from empty dir()')
print(dir())
```

**Output:**

```
['__add__', '__class__', '__class_getitem__', '__contains__', '__delattr__', '__delitem__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__gt__', '__hash__', '__iadd__', '__imul__', '__init__', '__init_subclass__', '__iter__', '__le__', '__len__', '__lt__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__reversed__', '__rmul__', '__setattr__', '__setitem__', '__sizeof__', '__str__', '__subclasshook__', 'append', 'clear', 'copy', 'count', 'extend', 'index', 'insert', 'pop', 'remove', 'reverse', 'sort']

Return Value from empty dir()
['__annotations__', '__builtins__', '__cached__', '__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'number']
```

Note how `'number'` is included in the list when we print `dir()` with no provided object.

---

</details>

<details><summary> Ex 2: <code>dir()</code> on user-defined object</summary>

```python
class Person:
  def __dir__(self):
    return ['age', 'name', 'salary']
    

teacher = Person()
print(dir(teacher))
```

**Output:**

```
['age', 'name', 'salary']
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#divmod" target="_blank"><code>divmod(<em>a,b</em>)</code></a></strong></summary>

**Description:** The `divmod()` method takes two numbers and returns a pair of numbers (a tuple) consisting of their quotient and remainder.

The syntax of `divmod()` is:

```python
divmod(x, y)
```

`divmod()` takes two parameters:

- `x` - a non-complex number (numerator)
- `y` - a non-complex number (denominator)

`divmod()` returns

- `(q, r)` - a pair of numbers (a tuple) consisting of quotient `q` and remainder `r`

If `x` and `y` are integers, the return value from `divmod()` is same as `(a // b, x % y)`.

If either `x` or `y` is a float, the result is `(q, x % y)`. Here, `q` is the whole part of the quotient.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Take two (non complex) numbers as arguments and return a pair of numbers consisting of their quotient and remainder when using integer division. With mixed operand types, the rules for binary arithmetic operators apply. For integers, the result is the same as `(a // b, a % b)`. For floating point numbers the result is `(q, a % b)`, where `q` is usually `math.floor(a / b)` but may be `1` less than that. In any case `q * b + a % b` is very close to `a`, if `a % b` is non-zero it has the same sign as `b`, and `0 <= abs(a % b) < abs(b)`.

---

</details>

<details><summary> Ex 1: How <code>divmod()</code> works in Python?</summary>

```python
print('divmod(8, 3) = ', divmod(8, 3))
print('divmod(3, 8) = ', divmod(3, 8))
print('divmod(5, 5) = ', divmod(5, 5))

# divmod() with Floats
print('divmod(8.0, 3) = ', divmod(8.0, 3))
print('divmod(3, 8.0) = ', divmod(3, 8.0))
print('divmod(7.5, 2.5) = ', divmod(7.5, 2.5))
print('divmod(2.6, 0.5) = ', divmod(2.6, 0.5))
```

divmod(8, 3) =  (2, 2)
divmod(3, 8) =  (0, 3)
divmod(5, 5) =  (1, 0)
divmod(8.0, 3) =  (2.0, 2.0)
divmod(3, 8.0) =  (0.0, 3.0)
divmod(7.5, 2.5) =  (3.0, 0.0)
divmod(2.6, 0.5) =  (5.0, 0.10000000000000009)

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#enumerate" target="_blank"><code>enumerate(<em>iterable, start=0</em>)</code></a></strong></summary>

**Description:** The `enumerate()` method adds a counter to an iterable and returns it (the enumerate object).

```python
languages = ['Python', 'Java', 'JavaScript']

enumerate_prime = enumerate(languages)

# convert enumerate object to list
print(list(enumerate_prime))

# Output: [(0, 'Python'), (1, 'Java'), (2, 'JavaScript')]
```

The syntax of `enumerate()` is:

```
enumerate(iterable, start=0)
```

`enumerate()` method takes two parameters:

- `iterable` - a sequence, an iterator, or objects that supports iteration
- `start` (optional) - `enumerate()` starts counting from this number. If start is omitted, `0` is taken as `start`.

`enumerate()` method adds counter to an iterable and returns it. The returned object is an enumerate object.

You can convert enumerate objects to a list or a tuple using the `list()` and `tuple()` methods, respectively.


**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return an enumerate object. iterable must be a sequence, an [iterator](https://docs.python.org/3/glossary.html#term-iterator), or some other object which supports iteration. The [`__next__()`](https://docs.python.org/3/library/stdtypes.html#iterator.__next__) method of the iterator returned by [`enumerate()`](https://docs.python.org/3/library/functions.html#enumerate) returns a tuple containing a count (from start which defaults to 0) and the values obtained from iterating over iterable.

```
>>> seasons = ['Spring', 'Summer', 'Fall', 'Winter']
>>> list(enumerate(seasons))
[(0, 'Spring'), (1, 'Summer'), (2, 'Fall'), (3, 'Winter')]
>>> list(enumerate(seasons, start=1))
[(1, 'Spring'), (2, 'Summer'), (3, 'Fall'), (4, 'Winter')]
```

Equivalent to:

```python
def enumerate(sequence, start=0):
    n = start
    for elem in sequence:
        yield n, elem
        n += 1
```

---

</details>

<details><summary> Ex 1: How <code>enumerate()</code> works in Python?</summary>

```python
grocery = ['bread', 'milk', 'butter']
enumerateGrocery = enumerate(grocery)

print(type(enumerateGrocery))

# converting to list
print(list(enumerateGrocery))

# changing the default counter
enumerateGrocery = enumerate(grocery, 10)
print(list(enumerateGrocery))
```

**Output:**

```
<class 'enumerate'>
[(0, 'bread'), (1, 'milk'), (2, 'butter')]
[(10, 'bread'), (11, 'milk'), (12, 'butter')]
```

---

</details>

<details><summary> Ex 2: Looping over an enumerator object</summary>

```python
grocery = ['bread', 'milk', 'butter']

for item in enumerate(grocery):
  print(item)

print('\n')

for count, item in enumerate(grocery):
  print(count, item)

print('\n')
# changing default start value
for count, item in enumerate(grocery, 100):
  print(count, item)
```

**Output:**

```
(0, 'bread')
(1, 'milk')
(2, 'butter')

0 bread
1 milk
2 butter

100 bread
101 milk
102 butter
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#eval" target="_blank"><code>eval(<em>expression</em>[, <em>globals</em>[, <em>locals</em>]])</code></a></strong></summary>

**Description:** The `eval()` method parses the expression passed to this method and runs python expression (code) within the program.

```python
number = 9

# eval performs the multiplication passed as argument
square_number = eval('number * number')
print(square_number)

# Output: 81
```

The syntax of `eval()` is:

```python
eval(expression, globals=None, locals=None)
```

The `eval()` function takes three parameters:

- `expression` - the string parsed and evaluated as a Python expression
- `globals` (optional) - a dictionary
- `locals` (optional)- a mapping object. Dictionary is the standard and commonly used mapping type in Python.

The use of `globals` and `locals` will be discussed more below in the examples.

The `eval()` method returns the result evaluated from the `expression`.

**Warnings when using `eval()`:** Consider a situation where you are using a Unix-like system (macOS, Linux, etc) and you have imported the `os` module. The `os` module provides a portable way to use operating system functionalities like reading or writing to a file.

If you allow users to input a value using `eval(input())`, the user may issue commands to change the file or even delete all the files using the command `os.system('rm -rf *')`.

If you are using `eval(input())` in your code, it is a good idea to check which variables and methods the user can use. You can see which variables and methods are available using the `dir()` method.

```python
from math import *
print(eval('dir()'))
```

**Output:**

```
['__annotations__', '__builtins__', '__cached__', '__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'acos', 'acosh', 'asin', 'asinh', 'atan', 'atan2', 'atanh', 'ceil', 'comb', 'copysign', 'cos', 'cosh', 'degrees', 'dist', 'e', 'erf', 'erfc', 'exp', 'expm1', 'fabs', 'factorial', 'floor', 'fmod', 'frexp', 'fsum', 'gamma', 'gcd', 'hypot', 'inf', 'isclose', 'isfinite', 'isinf', 'isnan', 'isqrt', 'lcm', 'ldexp', 'lgamma', 'log', 'log10', 'log1p', 'log2', 'modf', 'nan', 'nextafter', 'perm', 'pi', 'pow', 'prod', 'radians', 'remainder', 'sin', 'sinh', 'sqrt', 'tan', 'tanh', 'tau', 'trunc', 'ulp']
```

**Restricting the use of available methods and variables in `eval()` via `globals` and `locals` parameters:** More often than not, all the available methods and variables used in the `expression` (first parameter to `eval()`) may not be needed, or even may have a security hole. You may need to restrict the use of these methods and variables for `eval()`. You can do so by passing optional `globals` and `locals` parameters (dictionaries) to the eval() function.

1. **Both `globals` and `locals` parameters are omitted:** If both parameters are omitted (as in our earlier examples), the `expression` is executed in the current scope. You can check the available variables and methods using following code: `print(eval('dir()')`

2. **Passing `globals` parameter; `locals` parameter is omitted:** The `globals` and `locals` parameters (dictionaries) are used for global and local variables respectively. If the `locals` dictionary is omitted, it defaults to `globals` dictionary. Meaning, `globals` will be used for both global and local variables.

*Note:* You can check the current global and local dictionary in Python using `globals()` and `locals()` built-in methods respectively.

3. **Passing both `globals` and `locals` dictionaries:** You can make needed functions and variables available for use by passing the `locals` dictionary. For example:

```python
from math import *

a = 169
print(eval('sqrt(a)', {'__builtins__': None}, {'a': a, 'sqrt': sqrt}))
```

In this program, `expression` can have `sqrt()` method and variable `a` only. All other methods and variables are unavailable.

Restricting the use of `eval()` by passing `globals` and `locals` dictionaries will make your code secure particularly when you are using input provided by the user to the `eval()` method.

*Note:* Sometimes, `eval()` is not secure even with limited names. When an object and its methods are made accessible, almost anything can be done. The only secure way is by validating the user input.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

The arguments are a string and optional `globals` and `locals`. If provided, `globals` must be a dictionary. If provided, `locals` can be any mapping object.

The `expression` argument is parsed and evaluated as a Python expression (technically speaking, a condition list) using the `globals` and `locals` dictionaries as global and local namespace. If the `globals` dictionary is present and does not contain a value for the key `__builtins__`, a reference to the dictionary of the built-in module [`builtins`](https://docs.python.org/3/library/builtins.html#module-builtins) is inserted under that key before `expression` is parsed. This means that `expression` normally has full access to the standard [`builtins`](https://docs.python.org/3/library/builtins.html#module-builtins) module and restricted environments are propagated. If the `locals` dictionary is omitted it defaults to the `globals` dictionary. If both dictionaries are omitted, the expression is executed with the globals and locals in the environment where [`eval()`](https://docs.python.org/3/library/functions.html#eval) is called. Note, `eval()` does not have access to the [nested scopes](https://docs.python.org/3/glossary.html#term-nested-scope) (non-locals) in the enclosing environment.

The return value is the result of the evaluated expression. Syntax errors are reported as exceptions. Example:

```
>>> x = 1
>>> eval('x+1')
2
```

This function can also be used to execute arbitrary code objects (such as those created by [`compile()`](https://docs.python.org/3/library/functions.html#compile)). In this case pass a code object instead of a string. If the code object has been compiled with `'exec'` as the *mode* argument, [`eval()`](https://docs.python.org/3/library/functions.html#eval)'s return value will be `None`.

Hints: dynamic execution of statements is supported by the [`exec()`](https://docs.python.org/3/library/functions.html#exec) function. The [`globals()`](https://docs.python.org/3/library/functions.html#globals) and [`locals()`](https://docs.python.org/3/library/functions.html#locals) functions returns the current global and local dictionary, respectively, which may be useful to pass around for use by [`eval()`](https://docs.python.org/3/library/functions.html#eval) or [`exec()`](https://docs.python.org/3/library/functions.html#exec).

See [`ast.literal_eval()`](https://docs.python.org/3/library/ast.html#ast.literal_eval) for a function that can safely evaluate strings with expressions containing only literals.

Raises an [auditing event](https://docs.python.org/3/library/sys.html#auditing) `exec` with the code object as the argument. Code compilation events may also be raised.

---

</details>

<details><summary> Ex 1: How <code>eval()</code> works in Python</summary>

```python
x = 1
print(eval('x + 1'))
```

**Output:**

```
2
```

Here, the `eval()` function evaluates the expression `x + 1` and `print` is used to display this value.

---

</details>

<details><summary> Ex 2: Practical example to demonstrate use of <code>eval()</code></summary>

```python
# Perimeter of Square
def calculatePerimeter(l):
    return 4*l

# Area of Square
def calculateArea(l):
    return l*l

expression = input("Type a function: ")

for l in range(1, 5):
    if (expression == 'calculatePerimeter(l)'):
        print("If length is ", l, ", Perimeter = ", eval(expression))
    elif (expression == 'calculateArea(l)'):
        print("If length is ", l, ", Area = ", eval(expression))
    else:
        print('Wrong Function')
        break
```

**Output:**

```
Type a function: calculateArea(l)
If length is  1 , Area =  1
If length is  2 , Area =  4
If length is  3 , Area =  9
If length is  4 , Area =  16
```

---

</details>

<details><summary> Ex 3: Passing empty dictionary as <code>globals</code> parameter</summary>

```python
from math import *
print(eval('dir()', {}))

# The code will raise an exception
print(eval('sqrt(25)', {}))
```

**Output:**

```
['__builtins__']
Traceback (most recent call last):
  File "<string>", line 5, in <module>
    print(eval('sqrt(25)', {}))
  File "<string>", line 1, in <module>
NameError: name 'sqrt' is not defined
```

If you pass an empty dictionary as `globals`, only the `__builtins__` are available to `expression` (first parameter to the `eval()`).

Even though we have imported the `math` module in the above program, `expression` can't access any functions provided by the `math` module.

---

</details>

<details><summary> Ex 4: Making certain methods available</summary>

```python
from math import *
print(eval('dir()', {'sqrt': sqrt, 'pow': pow}))
print(eval('sqrt(4)', { 'sqrt': sqrt }))
```

**Output:**

```
['__builtins__', 'pow', 'sqrt']
2.0
```

Here, the first `expression` can only use the `sqrt()` and the `pow()` methods along with `__builtins__` while the second `expression` can only use the `sqrt()` method along with `__builtins__`.

It is also possible to change the name of the method available for the expression as you wish:

```python
from math import *
names = {'square_root': sqrt, 'power': pow}
print(eval('dir()', names))

# Using square_root in Expression
print(eval('square_root(9)', names))
```

**Output:**

```
['__builtins__', 'power', 'square_root']
3.0
```

In the above program, `square_root()` calculates the square root using `sqrt()`. However, trying to use `sqrt()` directly will raise an error.

---

</details>

<details><summary> Ex 5: Restricting the use of built-ins</summary>

You can restrict the use of `__builtins__` in the `expression` as follows:

```python
eval(expression, {'__builtins__': None})
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#exec" target="_blank"><code>exec(<em>object</em>[, <em>globals</em>[, <em>locals</em>]])</code></a></strong></summary>

**Description:** The `exec()` method executes the dynamically created program, which is either a string or a code object.

The syntax of `exec()`:

```python
exec(object, globals, locals)
```

`exec()` takes three parameters:

- `object` - Either a string or a code object
- `globals` (optional) - a dictionary
- `locals` (optional)- a mapping object. Dictionary is the standard and commonly used mapping type in Python.

The use of `globals` and `locals` will be discussed throughout the examples.

`exec()` doesn't return any value, it returns `None`.

**Be careful when using `exec()`:** Consider a situation, you are using a Unix-like system (macOS, Linux etc) and you have imported the `os` module. The `os` module provides a portable way to use operating system functionalities like read or write a file.

If you allow users to input a value using `exec(input())`, the user may issue commands to change the file or even delete all the files using the command `os.system('rm -rf *')`.

If you are using `exec(input())` in your code, it's a good idea to check which variables and methods the user can use. You can see which variables and methods are available using the `dir()` method.

```python
from math import *
exec('print(dir())')
```

**Output:**

```
['__annotations__', '__builtins__', '__cached__', '__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'acos', 'acosh', 'asin', 'asinh', 'atan', 'atan2', 'atanh', 'ceil', 'comb', 'copysign', 'cos', 'cosh', 'degrees', 'dist', 'e', 'erf', 'erfc', 'exp', 'expm1', 'fabs', 'factorial', 'floor', 'fmod', 'frexp', 'fsum', 'gamma', 'gcd', 'hypot', 'inf', 'isclose', 'isfinite', 'isinf', 'isnan', 'isqrt', 'lcm', 'ldexp', 'lgamma', 'log', 'log10', 'log1p', 'log2', 'modf', 'nan', 'nextafter', 'perm', 'pi', 'pow', 'prod', 'radians', 'remainder', 'sin', 'sinh', 'sqrt', 'tan', 'tanh', 'tau', 'trunc', 'ulp']
```

**Restricting the use of available methods and variables in `exec()` via `globals` and `locals` parameters:** More often than not, all the available methods and variables used in `exec()` may not be needed, or even may have a security hole. You can restrict the use of these variables and methods by passing optional `globals` and `locals` parameters (dictionaries) to the `exec()` method.

1. **Both `globals` and `locals` parameters are omitted:** If both parameters are omitted (as in our earlier examples), the code expected to be executed by `exec()` is executed in the current scope. You can check the available variables and methods using the following code: `exec('print(dir())')`

2. **Passing `globals` parameter; `locals` parameter is omitted:** The `globals` and `locals` parameters (dictionaries) are used for global and local variables respectively. If the `locals` dictionary is omitted, it defaults to `globals` dictionary. Meaning, `globals` will be used for both global and local variables.

*Note:* You can check the current global and local dictionary in Python using `globals()` and `locals()` built-in methods respectively.

3. **Passing empty dictionary as `globals` parameter:** 

```python
from math import *
exec('print(dir())', {})

# This code will raise an exception
# exec('print(sqrt(9))', {})
```

**Output:**

```
['__builtins__']
```

If you pass an empty dictionary as `globals`, only the `__builtins__` are available to the object (first parameter to `exec()`). Even though we have imported the `math` module in the above program, trying to access any of the functions provided by the `math` module will raise an exception.

**Making certain methods available:** 

```python
from math import *
exec('print(dir())', {'sqrt': sqrt, 'pow': pow})

# object can have sqrt() module
exec('print(sqrt(9))', {'sqrt': sqrt, 'pow': pow})
```

Here, the code that is executed by `exec()` can also have `sqrt()` and `pow()` methods along with `__builtins__`.

It's possible to change the name of the method as you wish:

```python
from math import *
exec('print(dir())', {'squareRoot': sqrt, 'pow': pow})

# object can have squareRoot() module
exec('print(squareRoot(9))', {'squareRoot': sqrt, 'pow': pow})
```

In the above program, `squareRoot()` calculates the square root (similar functionality like `sqrt()`). However, trying to use `sqrt()` will raise an exception.

**Restricting the use of built-ins:** You can restrict the use of `__builtins__` by giving value `None` to the `'__builtins__'` in the `globals` dictionary:

```python
exec(object, {'__builtins__': None}) 
```

4. **Passing both `globals` and `locals` dictionaries:** You can make needed functions and variables available for use by passing the `locals` dictionary. For example:

```python
from math import *

globalsParameter = {'__builtins__' : None}
localsParameter = {'print': print, 'dir': dir}
exec('print(dir())', globalsParameter, localsParameter)
```

**Output:**

```
['dir', 'print']
```

Here, only two built-in methods `print()` and `dir()` can be executed by `exec()` method.

It's important to note that, `exec()` executes the code and doesn't return any value (returns `None`). Hence, you cannot use `return` and `yield` statements outside of the function definitions.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

This function supports dynamic execution of Python code. `object` must be either a string or a code object. If it is a string, the string is parsed as a suite of Python statements which is then executed (unless a syntax error occurs). [Note that the parser only accepts the Unix-style end of line convention. If you are reading the code from a file, make sure to use newline conversion mode to convert Windows or Mac-style newlines.] If it is a code object, it is simply executed. In all cases, the code that's executed is expected to be valid as file input (see the section "File input" in the Reference Manual). Be aware that the [`nonlocal`](https://docs.python.org/3/reference/simple_stmts.html#nonlocal), [`yield`](https://docs.python.org/3/reference/simple_stmts.html#yield), and [`return`](https://docs.python.org/3/reference/simple_stmts.html#return) statements may not be used outside of function definitions even within the context of code passed to the [`exec()`](https://docs.python.org/3/library/functions.html#exec) function. The return value is `None`.

In all cases, if the optional parts are omitted, the code is executed in the current scope. If only `globals` is provided, it must be a dictionary (and not a subclass of dictionary), which will be used for both the global and the local variables. If `globals` and `locals` are given, they are used for the global and local variables, respectively. If provided, `locals` can be any mapping object. Remember that at module level, globals and locals are the same dictionary. If `exec` gets two separate objects as `globals` and `locals`, the code will be executed as if it were embedded in a class definition.

If the `globals` dictionary does not contain a value for the key `__builtins__`, a reference to the dictionary of the built-in module [`builtins`](https://docs.python.org/3/library/builtins.html#module-builtins) is inserted under that key. That way you can control what builtins are available to the executed code by inserting your own `__builtins__` dictionary into `globals` before passing it to [`exec()`](https://docs.python.org/3/library/functions.html#exec).

Raises an [auditing event](https://docs.python.org/3/library/sys.html#auditing) `exec` with the code object as the argument. Code compilation events may also be raised.

**Note:** The built-in functions [`globals()`](https://docs.python.org/3/library/functions.html#globals) and [`locals()`](https://docs.python.org/3/library/functions.html#locals) return the current `global` and `local` dictionary, respectively, which may be useful to pass around for use as the second and third argument to [`exec()`](https://docs.python.org/3/library/functions.html#exec).

**Note:** The default `locals` act as described for function [`locals()`](https://docs.python.org/3/library/functions.html#locals) below: modifications to the default `locals` dictionary should not be attempted. Pass an explicit `locals` dictionary if you need to see effects of the code on `locals` after function [`exec()`](https://docs.python.org/3/library/functions.html#exec) returns.

---

</details>

<details><summary> Ex 1: How <code>exec()</code> works?</summary>

```python
program = 'a = 5\nb=10\nprint("Sum =", a+b)'
exec(program)
```

**Output:**

```
Sum = 15
```

Here, the string object `program` is passed to `exec()` which executes the program. `globals` and `locals` are omitted in this case.

---

</details>

<details><summary> Ex 2: Allow user to provide input</summary>

```python
program = input('Enter a program:')
exec(program)
```

**Output:**

```
Enter a program: [print(item) for item in [1, 2, 3]]
1
2
3
```

If you want to take Python code from the user which allows multiline code (using `'\n'`), you can use the `compile()` method before using `exec()`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#filter" target="_blank"><code>filter(<em>function, iterable</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Construct an iterator from those elements of `iterable` for which `function` returns `true`. `iterable` may be either a sequence, a container which supports iteration, or an iterator. If function is `None`, the identity function is assumed, that is, all elements of `iterable` that are `false` are removed.

Note that `filter(function, iterable)` is equivalent to the generator expression `(item for item in iterable if function(item))` if function is not `None` and `(item for item in iterable if item)` if function is `None`.

See [`itertools.filterfalse()`](https://docs.python.org/3/library/itertools.html#itertools.filterfalse) for the complementary function that returns elements of `iterable` for which `function` returns `false`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#float" target="_blank"><code>float([<em>x</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a floating point number constructed from a number or string `x`.

If the argument is a string, it should contain a decimal number, optionally preceded by a sign, and optionally embedded in whitespace. The optional sign may be `'+'` or `'-'`; a `'+'` sign has no effect on the value produced. The argument may also be a string representing a NaN (not-a-number), or a positive or negative infinity. More precisely, the input must conform to the following grammar after leading and trailing whitespace characters are removed:

<pre>
<strong>sign</strong>           ::=  "+" | "-"
<strong>infinity</strong>       ::=  "Infinity" | "inf"
<strong>nan</strong>            ::=  "nan"
<strong>numeric_value</strong>  ::=  floatnumber | infinity | nan
<strong>numeric_string</strong> ::=  [sign] numeric_value
</pre>

Here `floatnumber` is the form of a Python floating-point literal, described in [Floating point literals](https://docs.python.org/3/reference/lexical_analysis.html#floating). Case is not significant, so, for example, "inf", "Inf", "INFINITY" and "iNfINity" are all acceptable spellings for positive infinity.

Otherwise, if the argument is an integer or a floating point number, a floating point number with the same value (within Python's floating point precision) is returned. If the argument is outside the range of a Python float, an [`OverflowError`](https://docs.python.org/3/library/exceptions.html#OverflowError) will be raised.

For a general Python object `x`, `float(x)` delegates to `x.__float__()`. If `__float__()` is not defined then it falls back to [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__).

If no argument is given, `0.0` is returned.

Examples:

```
>>> float('+1.23')
1.23
>>> float('   -12345\n')
-12345.0
>>> float('1e-003')
0.001
>>> float('+1E6')
1000000.0
>>> float('-Infinity')
-inf
```

The float type is described in [Numeric Types — int, float, complex](https://docs.python.org/3/library/stdtypes.html#typesnumeric).

*Changed in version 3.6:* Grouping digits with underscores as in code literals is allowed.

*Changed in version 3.7:* `x` is now a positional-only parameter.

*Changed in version 3.8:* Falls back to [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__) if [`__float__()`](https://docs.python.org/3/reference/datamodel.html#object.__float__) is not defined.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#format" target="_blank"><code>format(<em>value</em>[, <em>format_spec</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Convert a `value` to a "formatted" representation, as controlled by `format_spec`. The interpretation of `format_spec` will depend on the type of the `value` argument, however there is a standard formatting syntax that is used by most built-in types: [Format Specification Mini-Language](https://docs.python.org/3/library/string.html#formatspec).

The default `format_spec` is an empty string which usually gives the same effect as calling [`str(value)`](https://docs.python.org/3/library/stdtypes.html#str).

A call to `format(value, format_spec)` is translated to `type(value).__format__(value, format_spec)` which bypasses the instance dictionary when searching for the value's [`__format__()`](https://docs.python.org/3/reference/datamodel.html#object.__format__) method. A [`TypeError`](https://docs.python.org/3/library/exceptions.html#TypeError) exception is raised if the method search reaches [`object`](https://docs.python.org/3/library/functions.html#object) and the `format_spec` is non-empty, or if either the `format_spec` or the return value are not strings.

*Changed in version 3.4:* `object().__format__(format_spec)` raises [`TypeError`](https://docs.python.org/3/library/exceptions.html#TypeError) if `format_spec` is not an empty string.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-frozenset" target="_blank"><code>frozenset([<em>iterable</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new [`frozenset`](https://docs.python.org/3/library/stdtypes.html#frozenset) object, optionally with elements taken from iterable. frozenset is a built-in class. See [`frozenset`](https://docs.python.org/3/library/stdtypes.html#frozenset) and [Set Types — set, frozenset](https://docs.python.org/3/library/stdtypes.html#types-set) for documentation about this class.

For other containers see the built-in [`set`](https://docs.python.org/3/library/stdtypes.html#set), [`list`](https://docs.python.org/3/library/stdtypes.html#list), [`tuple`](https://docs.python.org/3/library/stdtypes.html#tuple), and [`dict`](https://docs.python.org/3/library/stdtypes.html#dict) classes, as well as the [`collections`](https://docs.python.org/3/library/collections.html#module-collections) module.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#getattr" target="_blank"><code>getattr(<em>object</em>, <em>name</em>[, <em>default</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the value of the named attribute of `object`. `name` must be a string. If the string is the name of one of the object's attributes, the result is the value of that attribute. For example, `getattr(x, 'foobar')` is equivalent to `x.foobar`. If the named attribute does not exist, `default` is returned if provided, otherwise [`AttributeError`](https://docs.python.org/3/library/exceptions.html#AttributeError) is raised.

**Note:** Since [private name mangling](https://docs.python.org/3/reference/expressions.html#private-name-mangling) happens at compilation time, one must manually mangle a private attribute's (attributes with two leading underscores) name in order to retrieve it with [`getattr()`](https://docs.python.org/3/library/functions.html#getattr).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#globals" target="_blank"><code>globals()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a dictionary representing the current global symbol table. This is always the dictionary of the current module (inside a function or method, this is the module where it is defined, not the module from which it is called).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#hasattr" target="_blank"><code>hasattr(<em>object, name</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

The arguments are an object and a string. The result is `True` if the string is the name of one of the object's attributes, `False` if not. (This is implemented by calling `getattr(object, name)` and seeing whether it raises an [`AttributeError`](https://docs.python.org/3/library/exceptions.html#AttributeError) or not.)

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#hash" target="_blank"><code>hash(<em>object</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the hash value of the object (if it has one). Hash values are integers. They are used to quickly compare dictionary keys during a dictionary lookup. Numeric values that compare equal have the same hash value (even if they are of different types, as is the case for 1 and 1.0).

**Note:** For objects with custom [`__hash__()`](https://docs.python.org/3/reference/datamodel.html#object.__hash__) methods, note that [`hash()`](https://docs.python.org/3/library/functions.html#hash) truncates the return value based on the bit width of the host machine. See [`__hash__()`](https://docs.python.org/3/reference/datamodel.html#object.__hash__) for details.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#help" target="_blank"><code>help([<em>object</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Invoke the built-in help system. (This function is intended for interactive use.) If no argument is given, the interactive help system starts on the interpreter console. If the argument is a string, then the string is looked up as the name of a module, function, class, method, keyword, or documentation topic, and a help page is printed on the console. If the argument is any other kind of object, a help page on the object is generated.

Note that if a slash(/) appears in the parameter list of a function, when invoking [`help()`](https://docs.python.org/3/library/functions.html#help), it means that the parameters prior to the slash are positional-only. For more info, see the [FAQ entry on positional-only parameters](https://docs.python.org/3/faq/programming.html#faq-positional-only-arguments).

This function is added to the built-in namespace by the [`site`](https://docs.python.org/3/library/site.html#module-site) module.

*Changed in version 3.4:* Changes to [`pydoc`](https://docs.python.org/3/library/pydoc.html#module-pydoc) and [`inspect`](https://docs.python.org/3/library/inspect.html#module-inspect) mean that the reported signatures for callables are now more comprehensive and consistent.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#hex" target="_blank"><code>hex(<em>x</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Convert an integer number to a lowercase hexadecimal string prefixed with "0x". If `x` is not a Python [`int`](https://docs.python.org/3/library/functions.html#int) object, it has to define an [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__) method that returns an integer. Some examples:

```
>>> hex(255)
'0xff'
>>> hex(-42)
'-0x2a'
```

If you want to convert an integer number to an uppercase or lower hexadecimal string with prefix or not, you can use either of the following ways:

```
>>> '%#x' % 255, '%x' % 255, '%X' % 255
('0xff', 'ff', 'FF')
>>> format(255, '#x'), format(255, 'x'), format(255, 'X')
('0xff', 'ff', 'FF')
>>> f'{255:#x}', f'{255:x}', f'{255:X}'
('0xff', 'ff', 'FF')
```

See also [`format()`](https://docs.python.org/3/library/functions.html#format) for more information.

See also [`int()`](https://docs.python.org/3/library/functions.html#int) for converting a hexadecimal string to an integer using a base of 16.

**Note:** To obtain a hexadecimal string representation for a float, use the [`float.hex()`](https://docs.python.org/3/library/stdtypes.html#float.hex) method.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#id" target="_blank"><code>id(<em>object</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the "identity" of an object. This is an integer which is guaranteed to be unique and constant for this object during its lifetime. Two objects with non-overlapping lifetimes may have the same [`id()`](https://docs.python.org/3/library/functions.html#id) value.

**CPython implementation detail:** This is the address of the object in memory.

Raises an [auditing event](https://docs.python.org/3/library/sys.html#auditing) `builtins.id` with argument `id`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#input" target="_blank"><code>input([<em>prompt</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

If the `prompt` argument is present, it is written to standard output without a trailing newline. The function then reads a line from input, converts it to a string (stripping a trailing newline), and returns that. When EOF is read, [`EOFError`](https://docs.python.org/3/library/exceptions.html#EOFError) is raised. Example:

```
>>> s = input('--> ')  
--> Monty Python's Flying Circus
>>> s  
"Monty Python's Flying Circus"
```

If the [`readline`](https://docs.python.org/3/library/readline.html#module-readline) module was loaded, then [`input()`](https://docs.python.org/3/library/functions.html#input) will use it to provide elaborate line editing and history features.

Raises an [auditing event](https://docs.python.org/3/library/sys.html#auditing) `builtins.input` with argument `prompt` before reading input

Raises an auditing event `builtins.input/result` with the result after successfully reading input.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#int" target="_blank"><code>int([<em>x</em>]); int(<em>x, base=10</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return an integer object constructed from a number or string `x`, or return `0` if no arguments are given. If `x` defines [`__int__()`](https://docs.python.org/3/reference/datamodel.html#object.__int__), `int(x)` returns `x.__int__()`. If `x` defines [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__), it returns `x.__index__()`. If `x` defines [`__trunc__()`](https://docs.python.org/3/reference/datamodel.html#object.__trunc__), it returns `x.__trunc__()`. For floating point numbers, this truncates towards zero.

If `x` is not a number or if `base` is given, then `x` must be a string, [`bytes`](https://docs.python.org/3/library/stdtypes.html#bytes), or [`bytearray`](https://docs.python.org/3/library/stdtypes.html#bytearray) instance representing an [integer literal](https://docs.python.org/3/reference/lexical_analysis.html#integers) in radix base. Optionally, the literal can be preceded by `+` or `-` (with no space in between) and surrounded by whitespace. A base-n literal consists of the digits `0` to `n-1`, with `a` to `z` (or `A` to `Z`) having values `10` to `35`. The default base is `10`. The allowed values are `0` and `2–36`. Base-2, -8, and -16 literals can be optionally prefixed with `0b/0B`, `0o/0O`, or `0x/0X`, as with integer literals in code. Base `0` means to interpret exactly as a code literal, so that the actual base is 2, 8, 10, or 16, and so that `int('010', 0)` is not legal, while `int('010')` is, as well as `int('010', 8)`.

The integer type is described in [Numeric Types — int, float, complex](https://docs.python.org/3/library/stdtypes.html#typesnumeric).

*Changed in version 3.4:* If `base` is not an instance of [`int`](https://docs.python.org/3/library/functions.html#int) and the `base` object has a [`base.__index__`](https://docs.python.org/3/reference/datamodel.html#object.__index__) method, that method is called to obtain an integer for the base. Previous versions used [`base.__int__`](https://docs.python.org/3/reference/datamodel.html#object.__int__) instead of [`base.__index__`](https://docs.python.org/3/reference/datamodel.html#object.__index__).

*Changed in version 3.6:* Grouping digits with underscores as in code literals is allowed.

*Changed in version 3.7:* `x` is now a positional-only parameter.

*Changed in version 3.8:* Falls back to [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__) if [`__int__()`](https://docs.python.org/3/reference/datamodel.html#object.__int__) is not defined.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#isinstance" target="_blank"><code>isinstance(<em>object, classinfo</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if the `object` argument is an instance of the `classinfo` argument, or of a (direct, indirect or [virtual](https://docs.python.org/3/glossary.html#term-abstract-base-class)) subclass thereof. If `object` is not an object of the given type, the function always returns `False`. If `classinfo` is a tuple of type objects (or recursively, other such tuples), return `True` if `object` is an instance of any of the types. If `classinfo` is not a type or tuple of types and such tuples, a [`TypeError`](https://docs.python.org/3/library/exceptions.html#TypeError) exception is raised.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#issubclass" target="_blank"><code>issubclass(<em>class, classinfo</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if `class` is a subclass (direct, indirect or [`virtual`](https://docs.python.org/3/glossary.html#term-abstract-base-class)) of `classinfo`. A class is considered a subclass of itself. `classinfo` may be a tuple of class objects, in which case every entry in `classinfo` will be checked. In any other case, a [`TypeError`](https://docs.python.org/3/library/exceptions.html#TypeError) exception is raised.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#iter" target="_blank"><code>iter(<em>object</em>[, <em>sentinel</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

Return an [iterator](https://docs.python.org/3/glossary.html#term-iterator) object. The first argument is interpreted very differently depending on the presence of the second argument. Without a second argument, `object` must be a collection object which supports the iteration protocol (the [`__iter__()`](https://docs.python.org/3/reference/datamodel.html#object.__iter__) method), or it must support the sequence protocol (the [`__getitem__()`](https://docs.python.org/3/reference/datamodel.html#object.__getitem__) method with integer arguments starting at `0`). If it does not support either of those protocols, [`TypeError`](https://docs.python.org/3/library/exceptions.html#TypeError) is raised. If the second argument, `sentinel`, is given, then `object` must be a callable object. The iterator created in this case will call `object` with no arguments for each call to its [`__next__()`](https://docs.python.org/3/library/stdtypes.html#iterator.__next__) method; if the value returned is equal to `sentinel`, [`StopIteration`](https://docs.python.org/3/library/exceptions.html#StopIteration) will be raised, otherwise the value will be returned.

See also [Iterator Types](https://docs.python.org/3/library/stdtypes.html#typeiter).

One useful application of the second form of [`iter()`](https://docs.python.org/3/library/functions.html#iter) is to build a block-reader. For example, reading fixed-width blocks from a binary database file until the end of file is reached:

```python
from functools import partial
with open('mydata.db', 'rb') as f:
    for block in iter(partial(f.read, 64), b''):
        process_block(block)
```

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#len" target="_blank"><code>len(<em>s</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the length (the number of items) of an object. The argument may be a sequence (such as a string, bytes, tuple, list, or range) or a collection (such as a dictionary, set, or frozen set).

**CPython implementation detail:** `len` raises [`OverflowError`](https://docs.python.org/3/library/exceptions.html#OverflowError) on lengths larger than [`sys.maxsize`](https://docs.python.org/3/library/sys.html#sys.maxsize), such as [`range(2 ** 100)`](https://docs.python.org/3/library/stdtypes.html#range).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-list" target="_blank"><code>list([<em>iterable</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Rather than being a function, [`list`](https://docs.python.org/3/library/stdtypes.html#list) is actually a mutable sequence type, as documented in [Lists and Sequence Types — list, tuple, range](https://docs.python.org/3/library/stdtypes.html#typesseq-list).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#locals" target="_blank"><code>locals()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Update and return a dictionary representing the current local symbol table. Free variables are returned by [`locals()`](https://docs.python.org/3/library/functions.html#locals) when it is called in function blocks, but not in class blocks. Note that at the module level, [`locals()`](https://docs.python.org/3/library/functions.html#locals) and [`globals()`](https://docs.python.org/3/library/functions.html#globals) are the same dictionary.

**Note:** The contents of this dictionary should not be modified; changes may not affect the values of local and free variables used by the interpreter.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#map" target="_blank"><code>map(<em>function, iterable, ...</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return an iterator that applies `function` to every item of `iterable` (e.g., a string, list, tuple, dict, etc.), yielding the results. If additional `iterable` arguments are passed, `function` must take that many arguments and is applied to the items from all iterables in parallel. With multiple iterables, the iterator stops when the shortest iterable is exhausted. For cases where the function inputs are already arranged into argument tuples, see [`itertools.starmap()`](https://docs.python.org/3/library/itertools.html#itertools.starmap).

---

</details>

<details><summary> Ex 1: Basic illustration of usage</summary>

The code block 

``` Python
nums = [1,2,3]

def non_lambda(num):
  return num ** 2

my_nonlambda_iterator = map(non_lambda, nums)
my_lambda_iterator = map(lambda x: x**2, nums)

print(my_lambda_iterator)
print(next(my_lambda_iterator))
print(next(my_lambda_iterator))
print(next(my_lambda_iterator))

print(my_nonlambda_iterator)
print(list(my_nonlambda_iterator))
```

has the following output:

```
<map object at 0x10753bdf0>
1
4
9
<map object at 0x10753be80>
[1, 4, 9]
```

This illustrates that the `map` function returns an *iterator* which can be unpacked all at once by means of something like `list` or can be iterated through by means of the built-in `next` function.

As noted in the description for `map`, this function can take multiple iterables--the iterator stops when the shortest iterable is exhausted. 

For example, the code block above can be adjusted to

``` Python
nums1 = [1,2,3]
nums2 = [4,5,6,7]
nums3 = [8,9,10,11,12]

def non_lambda(num1, num2, num3):
  return num1 + num2 + num3

my_nonlambda_iterator = map(non_lambda, nums1, nums2, nums3)
my_lambda_iterator = map(lambda x,y,z: x+y+z, nums1, nums2, nums3)

print(my_lambda_iterator)
print(next(my_lambda_iterator))
print(next(my_lambda_iterator))
print(next(my_lambda_iterator))

print(my_nonlambda_iterator)
print(list(my_nonlambda_iterator))
```

which will yield the output

```
<map object at 0x10fbcddf0>
13
16
19
<map object at 0x10fbcdf10>
[13, 16, 19]
```

In this case, `nums1 = [1,2,3]` is the shortest iterable.

---

</details>

<details><summary> Ex 2: Converting map object to set</summary>

``` Python
def calculateSquare(n):
    return n*n


numbers = (1, 2, 3, 4)
result = map(calculateSquare, numbers)
print(result)

# converting map object to set
numbersSquare = set(result)
print(numbersSquare)
```

yields

```
<map object at 0x7f722da129e8>
{16, 1, 4, 9}
```

Each item of the tuple is squared.

---

</details>

<details><summary> Ex 3: Using a <code>lambda</code> function with <code>map</code></summary>

Since `map` expects a function to be passed in, lambda functions are commonly used while working with `map`. A lambda function is a short function without a name (similar to anonymous functions `() => {}` in JavaScript; the main difference is that lambda functions need to be one-liners in Python).

The code block 

``` Python
numbers = (1, 2, 3, 4)
result = map(lambda x: x*x, numbers)
print(result)

# converting map object to set
numbersSquare = set(result)
print(numbersSquare)
```

yields as its output:

```
<map 0x7fafc21ccb00>
{16, 1, 4, 9}
```

There is no real difference from this example to the one previous.

---

</details>

<details><summary> Ex 4: Passing multiple iterables to <code>map</code> and using <code>lambda</code></summary>

We can add corresponding items of two lists:

``` Python
num1 = [4, 5, 6]
num2 = [5, 6, 7]

result = map(lambda n1, n2: n1+n2, num1, num2)
print(list(result))
```

This yields:

```
[9, 11, 13]
```

---

</details>

<details><summary> Ex 5: Number to sum of its numerals (Edabit challenge)</summary>

From [this challenge](https://edabit.com/challenge/eADRy5SA5QbasA3Qt) we see that a number is said to be **Harshad** if it is *exactly divisible* by the **sum** of its digits. Create a function that determines whether a number is Harshad or not.

```
is_harshad(75) ➞ False
# 7 + 5 = 12
# 75 is not exactly divisible by 12
 
is_harshad(171) ➞ True
# 1 + 7 + 1 = 9
# 9 exactly divides 171
 
is_harshad(481) ➞ True

is_harshad(89) ➞ False

is_harshad(516) ➞ True

is_harshad(200) ➞ True
```

The `map` function can be used to our advantage here:

``` Python
def is_harshad(n):
	S = sum(map(int, str(n)))
	return n % S == 0
```

By itself, `n` is not iterable. But strings are iterable. Hence, `str(n)` gives us an iterable string whose characters are the numerals that make up `n`. We can use the `map` function to apply the `int` function to each character in `str(n)` to yield an iterator upon which `sum` can act.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#max" target="_blank"><code>max(<em>iterable</em>, *[, <em>key, default</em>]); max(<em>arg1</em>, <em>arg2</em>, <em>*args</em>[, <em>key</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the largest item in an iterable or the largest of two or more arguments.

If one positional argument is provided, it should be an [`iterable`](https://docs.python.org/3/glossary.html#term-iterable). The largest item in the iterable is returned. If two or more positional arguments are provided, the largest of the positional arguments is returned.

There are two optional keyword-only arguments. The `key` argument specifies a one-argument ordering function like that used for [`list.sort()`](https://docs.python.org/3/library/stdtypes.html#list.sort). The `default` argument specifies an object to return if the provided iterable is empty. If the iterable is empty and `default` is not provided, a [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) is raised.

If multiple items are maximal, the function returns the first one encountered. This is consistent with other sort-stability preserving tools such as `sorted(iterable, key=keyfunc, reverse=True)[0]` and `heapq.nlargest(1, iterable, key=keyfunc)`.

*New in version 3.4:* The `default` keyword-only argument.

*Changed in version 3.8:* The `key` can be `None`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-memoryview" target="_blank"><code>memoryview(<em>object</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a "memory view" object created from the given argument. See [Memory Views](https://docs.python.org/3/library/stdtypes.html#typememoryview) for more information.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#min" target="_blank"><code>min(<em>iterable</em>, *[, <em>key, default</em>]); min(<em>arg1</em>, <em>arg2</em>, <em>*args</em>[, <em>key</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the smallest item in an iterable or the smallest of two or more arguments.

If one positional argument is provided, it should be an [iterable](https://docs.python.org/3/glossary.html#term-iterable). The smallest item in the iterable is returned. If two or more positional arguments are provided, the smallest of the positional arguments is returned.

There are two optional keyword-only arguments. The `key` argument specifies a one-argument ordering function like that used for [`list.sort()`](https://docs.python.org/3/library/stdtypes.html#list.sort). The `default` argument specifies an object to return if the provided iterable is empty. If the iterable is empty and `default` is not provided, a [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) is raised.

If multiple items are minimal, the function returns the first one encountered. This is consistent with other sort-stability preserving tools such as `sorted(iterable, key=keyfunc)[0]` and `heapq.nsmallest(1, iterable, key=keyfunc)`.

*New in version 3.4:* The `default` keyword-only argument.

*Changed in version 3.8:* The `key` can be `None`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#next" target="_blank"><code>next(<em>iterator</em>[, <em>default</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Retrieve the next item from the iterator by calling its [`__next__()`](https://docs.python.org/3/library/stdtypes.html#iterator.__next__) method. If default is given, it is returned if the iterator is exhausted, otherwise [`StopIteration`](https://docs.python.org/3/library/exceptions.html#StopIteration) is raised.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#object" target="_blank"><code>object()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

Return a new featureless object. [`object`](https://docs.python.org/3/library/functions.html#object) is a base for all classes. It has the methods that are common to all instances of Python classes. This function does not accept any arguments.

**Note:** [`object`](https://docs.python.org/3/library/functions.html#object) does not have a [`__dict__`](https://docs.python.org/3/library/stdtypes.html#object.__dict__), so you can't assign arbitrary attributes to an instance of the [`object`](https://docs.python.org/3/library/functions.html#object) class.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#oct" target="_blank"><code>oct(<em>x</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Convert an integer number to an octal string prefixed with "0o". The result is a valid Python expression. If `x` is not a Python [`int`](https://docs.python.org/3/library/functions.html#int) object, it has to define an [`__index__()`](https://docs.python.org/3/reference/datamodel.html#object.__index__) method that returns an integer. For example:

```
>>> oct(8)
'0o10'
>>> oct(-56)
'-0o70'
```

If you want to convert an integer number to octal string either with prefix "0o" or not, you can use either of the following ways.

```
>>> '%#o' % 10, '%o' % 10
('0o12', '12')
>>> format(10, '#o'), format(10, 'o')
('0o12', '12')
>>> f'{10:#o}', f'{10:o}'
('0o12', '12')
```

See also [`format()`](https://docs.python.org/3/library/functions.html#format) for more information.

---

</details>

**Ascii Table:**

<details><summary> ASCII Table</summary>

| Dec | Hex | Oct | Binary | HTML | Char | Description |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| 0 | 00 | 000 | 00000000 | `&#0;` | `NUL` | Null |
| 1 | 01 | 001 | 00000001 | `&#1;` | `SOH` | Start of Header |
| 2 | 02 | 002 | 00000010 | `&#2;` | `STX` | Start of Text |
| 3 | 03 | 003 | 00000011 | `&#3;` | `ETX` | End of Text |
| 4 | 04 | 004 | 00000100 | `&#4;` | `EOT` | End of Transmission |
| 5 | 05 | 005 | 00000101 | `&#5;` | `ENQ` | Enquiry |
| 6 | 06 | 006 | 00000110 | `&#6;` | `ACK` | Acknowledge |
| 7 | 07 | 007 | 00000111 | `&#7;` | `BEL` | Bell |
| 8 | 08 | 010 | 00001000 | `&#8;` | `BS` | Backspace |
| 9 | 09 | 011 | 00001001 | `&#9;` | `HT` | Horizontal Tab |
| 10 | 0A | 012 | 00001010 | `&#10;` | `LF` | Line Feed |
| 11 | 0B | 013 | 00001011 | `&#11;` | `VT` | Vertical Tab |
| 12 | 0C | 014 | 00001100 | `&#12;` | `FF` | Form Feed |
| 13 | 0D | 015 | 00001101 | `&#13;` | `CR` | Carriage Return |
| 14 | 0E | 016 | 00001110 | `&#14;` | `SO` | Shift Out |
| 15 | 0F | 017 | 00001111 | `&#15;` | `SI` | Shift In |
| 16 | 10 | 020 | 00010000 | `&#16;` | `DLE` | Data Link Escape |
| 17 | 11 | 021 | 00010001 | `&#17;` | `DC1` | Device Control 1 |
| 18 | 12 | 022 | 00010010 | `&#18;` | `DC2` | Device Control 2 |
| 19 | 13 | 023 | 00010011 | `&#19;` | `DC3` | Device Control 3 |
| 20 | 14 | 024 | 00010100 | `&#20;` | `DC4` | Device Control 4 |
| 21 | 15 | 025 | 00010101 | `&#21;` | `NAK` | Negative Acknowledge |
| 22 | 16 | 026 | 00010110 | `&#22;` | `SYN` | Synchronize |
| 23 | 17 | 027 | 00010111 | `&#23;` | `ETB` | End of Transmission Block |
| 24 | 18 | 030 | 00011000 | `&#24;` | `CAN` | Cancel |
| 25 | 19 | 031 | 00011001 | `&#25;` | `EM` | End of Medium |
| 26 | 1A | 032 | 00011010 | `&#26;` | `SUB` | Substitute |
| 27 | 1B | 033 | 00011011 | `&#27;` | `ESC` | Escape |
| 28 | 1C | 034 | 00011100 | `&#28;` | `FS` | File Separator |
| 29 | 1D | 035 | 00011101 | `&#29;` | `GS` | Group Separator |
| 30 | 1E | 036 | 00011110 | `&#30;` | `RS` | Record Separator |
| 31 | 1F | 037 | 00011111 | `&#31;` | `US` | Unit Separator |
| 32 | 20 | 040 | 00100000 | `&#32;` | `space` | Space |
| 33 | 21 | 041 | 00100001 | `&#33;` | `!` | exclamation mark |
| 34 | 22 | 042 | 00100010 | `&#34;` | `"` | double quote |
| 35 | 23 | 043 | 00100011 | `&#35;` | `#` | number |
| 36 | 24 | 044 | 00100100 | `&#36;` | `$` | dollar |
| 37 | 25 | 045 | 00100101 | `&#37;` | `%` | percent |
| 38 | 26 | 046 | 00100110 | `&#38;` | `&` | ampersand |
| 39 | 27 | 047 | 00100111 | `&#39;` | `'` | single quote |
| 40 | 28 | 050 | 00101000 | `&#40;` | `(` | left parenthesis |
| 41 | 29 | 051 | 00101001 | `&#41;` | `)` | right parenthesis |
| 42 | 2A | 052 | 00101010 | `&#42;` | `*` | asterisk |
| 43 | 2B | 053 | 00101011 | `&#43;` | `+` | plus |
| 44 | 2C | 054 | 00101100 | `&#44;` | `,` | comma |
| 45 | 2D | 055 | 00101101 | `&#45;` | `-` | minus |
| 46 | 2E | 056 | 00101110 | `&#46;` | `.` | period |
| 47 | 2F | 057 | 00101111 | `&#47;` | `/` | slash |
| 48 | 30 | 060 | 00110000 | `&#48;` | `0` | zero |
| 49 | 31 | 061 | 00110001 | `&#49;` | `1` | one |
| 50 | 32 | 062 | 00110010 | `&#50;` | `2` | two |
| 51 | 33 | 063 | 00110011 | `&#51;` | `3` | three |
| 52 | 34 | 064 | 00110100 | `&#52;` | `4` | four |
| 53 | 35 | 065 | 00110101 | `&#53;` | `5` | five |
| 54 | 36 | 066 | 00110110 | `&#54;` | `6` | six |
| 55 | 37 | 067 | 00110111 | `&#55;` | `7` | seven |
| 56 | 38 | 070 | 00111000 | `&#56;` | `8` | eight |
| 57 | 39 | 071 | 00111001 | `&#57;` | `9` | nine |
| 58 | 3A | 072 | 00111010 | `&#58;` | `:` | colon |
| 59 | 3B | 073 | 00111011 | `&#59;` | `;` | | `semicolon` | |
| 60 | 3C | 074 | 00111100 | `&#60;` | `<` | less than |
| 61 | 3D | 075 | 00111101 | `&#61;` | `=` | equality sign |
| 62 | 3E | 076 | 00111110 | `&#62;` | `>` | greater than |
| 63 | 3F | 077 | 00111111 | `&#63;` | `?` | question mark |
| 64 | 40 | 100 | 01000000 | `&#64;` | `@` | at sign |
| 65 | 41 | 101 | 01000001 | `&#65;` | `A` |   |
| 66 | 42 | 102 | 01000010 | `&#66;` | `B` |   |
| 67 | 43 | 103 | 01000011 | `&#67;` | `C` |   |
| 68 | 44 | 104 | 01000100 | `&#68;` | `D` |   |
| 69 | 45 | 105 | 01000101 | `&#69;` | `E` |   |
| 70 | 46 | 106 | 01000110 | `&#70;` | `F` |   |
| 71 | 47 | 107 | 01000111 | `&#71;` | `G` |   |
| 72 | 48 | 110 | 01001000 | `&#72;` | `H` |   |
| 73 | 49 | 111 | 01001001 | `&#73;` | `I` |   |
| 74 | 4A | 112 | 01001010 | `&#74;` | `J` |   |
| 75 | 4B | 113 | 01001011 | `&#75;` | `K` |   |
| 76 | 4C | 114 | 01001100 | `&#76;` | `L` |   |
| 77 | 4D | 115 | 01001101 | `&#77;` | `M` |   |
| 78 | 4E | 116 | 01001110 | `&#78;` | `N` |   |
| 79 | 4F | 117 | 01001111 | `&#79;` | `O` |   |
| 80 | 50 | 120 | 01010000 | `&#80;` | `P` |   |
| 81 | 51 | 121 | 01010001 | `&#81;` | `Q` |   |
| 82 | 52 | 122 | 01010010 | `&#82;` | `R` |   |
| 83 | 53 | 123 | 01010011 | `&#83;` | `S` |   |
| 84 | 54 | 124 | 01010100 | `&#84;` | `T` |   |
| 85 | 55 | 125 | 01010101 | `&#85;` | `U` |   |
| 86 | 56 | 126 | 01010110 | `&#86;` | `V` |   |
| 87 | 57 | 127 | 01010111 | `&#87;` | `W` |   |
| 88 | 58 | 130 | 01011000 | `&#88;` | `X` |   |
| 89 | 59 | 131 | 01011001 | `&#89;` | `Y` |   |
| 90 | 5A | 132 | 01011010 | `&#90;` | `Z` |   |
| 91 | 5B | 133 | 01011011 | `&#91;` | `[` | left square bracket |
| 92 | 5C | 134 | 01011100 | `&#92;` | `\` | backslash |
| 93 | 5D | 135 | 01011101 | `&#93;` | `]` | right square bracket |
| 94 | 5E | 136 | 01011110 | `&#94;` | `^` | caret / circumflex |
| 95 | 5F | 137 | 01011111 | `&#95;` | `_` | underscore |
| 96 | 60 | 140 | 01100000 | `&#96;` | `` ` `` | grave / accent |
| 97 | 61 | 141 | 01100001 | `&#97;` | `a` |   |
| 98 | 62 | 142 | 01100010 | `&#98;` | `b` |   |
| 99 | 63 | 143 | 01100011 | `&#99;` | `c` |   |
| 100 | 64 | 144 | 01100100 | `&#100;` | `d` |   |
| 101 | 65 | 145 | 01100101 | `&#101;` | `e` |   |
| 102 | 66 | 146 | 01100110 | `&#102;` | `f` |   |
| 103 | 67 | 147 | 01100111 | `&#103;` | `g` |   |
| 104 | 68 | 150 | 01101000 | `&#104;` | `h` |   |
| 105 | 69 | 151 | 01101001 | `&#105;` | `i` |   |
| 106 | 6A | 152 | 01101010 | `&#106;` | `j` |   |
| 107 | 6B | 153 | 01101011 | `&#107;` | `k` |   |
| 108 | 6C | 154 | 01101100 | `&#108;` | `l` |   |
| 109 | 6D | 155 | 01101101 | `&#109;` | `m` |   |
| 110 | 6E | 156 | 01101110 | `&#110;` | `n` |   |
| 111 | 6F | 157 | 01101111 | `&#111;` | `o` |   |
| 112 | 70 | 160 | 01110000 | `&#112;` | `p` |   |
| 113 | 71 | 161 | 01110001 | `&#113;` | `q` |   |
| 114 | 72 | 162 | 01110010 | `&#114;` | `r` |   |
| 115 | 73 | 163 | 01110011 | `&#115;` | `s` |   |
| 116 | 74 | 164 | 01110100 | `&#116;` | `t` |   |
| 117 | 75 | 165 | 01110101 | `&#117;` | `u` |   |
| 118 | 76 | 166 | 01110110 | `&#118;` | `v` |   |
| 119 | 77 | 167 | 01110111 | `&#119;` | `w` |   |
| 120 | 78 | 170 | 01111000 | `&#120;` | `x` |   |
| 121 | 79 | 171 | 01111001 | `&#121;` | `y` |   |
| 122 | 7A | 172 | 01111010 | `&#122;` | `z` |   |
| 123 | 7B | 173 | 01111011 | `&#123;` | `{` | left curly bracket |
| 124 | 7C | 174 | 01111100 | `&#124;` | <code>&#124;</code> | vertical bar |
| 125 | 7D | 175 | 01111101 | `&#125;` | `}` | right curly bracket |
| 126 | 7E | 176 | 01111110 | `&#126;` | `~` | tilde |
| 127 | 7F | 177 | 01111111 | `&#127;` | `DEL` | delete |

---

</details>

<details><summary> Extended ASCII Table</summary>

| Dec | Hex | Binary | HTML | Char |
| :-- | :-- | :-- | :-- | :-- | 
| 128 | 80 | 10000000 | - |  |
| 129 | 81 | 10000001 | - |  |
| 130 | 82 | 10000010 | - |  |
| 131 | 83 | 10000011 | - |  |
| 132 | 84 | 10000100 | - |  |
| 133 | 85 | 10000101 | - |  |
| 134 | 86 | 10000110 | - |  |
| 135 | 87 | 10000111 | - |  |
| 136 | 88 | 10001000 | - |  |
| 137 | 89 | 10001001 | - |  |
| 138 | 8A | 10001010 | - |  |
| 139 | 8B | 10001011 | - |  |
| 140 | 8C | 10001100 | - |  |
| 141 | 8D | 10001101 | - |  |
| 142 | 8E | 10001110 | - |  |
| 143 | 8F | 10001111 | - |  |
| 144 | 90 | 10010000 | - |  |
| 145 | 91 | 10010001 | - |  |
| 146 | 92 | 10010010 | - |  |
| 147 | 93 | 10010011 | - |  |
| 148 | 94 | 10010100 | - |  |
| 149 | 95 | 10010101 | - |  |
| 150 | 96 | 10010110 | - |  |
| 151 | 97 | 10010111 | - |  |
| 152 | 98 | 10011000 | - |  |
| 153 | 99 | 10011001 | - |  |
| 154 | 9A | 10011010 | - |  |
| 155 | 9B | 10011011 | - |  |
| 156 | 9C | 10011100 | - |  |
| 157 | 9D | 10011101 | - |  |
| 158 | 9E | 10011110 | - |  |
| 159 | 9F | 10011111 | - |  |
| 160 | A0 | 10100000 | `&#160;` | | 
| 161 | A1 | 10100001 | `&#161;` | ¡ | 
| 162 | A2 | 10100010 | `&#162;` | ¢ | 
| 163 | A3 | 10100011 | `&#163;` | £ | 
| 164 | A4 | 10100100 | `&#164;` | ¤ | 
| 165 | A5 | 10100101 | `&#165;` | ¥ | 
| 166 | A6 | 10100110 | `&#166;` | ¦ | 
| 167 | A7 | 10100111 | `&#167;` | § | 
| 168 | A8 | 10101000 | `&#168;` | ¨ | 
| 169 | A9 | 10101001 | `&#169;` | © | 
| 170 | AA | 10101010 | `&#170;` | ª | 
| 171 | AB | 10101011 | `&#171;` | « | 
| 172 | AC | 10101100 | `&#172;` | ¬ | 
| 173 | AD | 10101101 | `&#173;` | ­ | 
| 174 | AE | 10101110 | `&#174;` | ® | 
| 175 | AF | 10101111 | `&#175;` | ¯ | 
| 176 | B0 | 10110000 | `&#176;` | ° | 
| 177 | B1 | 10110001 | `&#177;` | ± | 
| 178 | B2 | 10110010 | `&#178;` | ² | 
| 179 | B3 | 10110011 | `&#179;` | ³ | 
| 180 | B4 | 10110100 | `&#180;` | ´ | 
| 181 | B5 | 10110101 | `&#181;` | µ | 
| 182 | B6 | 10110110 | `&#182;` | ¶ | 
| 183 | B7 | 10110111 | `&#183;` | · | 
| 184 | B8 | 10111000 | `&#184;` | ¸ | 
| 185 | B9 | 10111001 | `&#185;` | ¹ | 
| 186 | BA | 10111010 | `&#186;` | º | 
| 187 | BB | 10111011 | `&#187;` | » | 
| 188 | BC | 10111100 | `&#188;` | ¼ | 
| 189 | BD | 10111101 | `&#189;` | ½ | 
| 190 | BE | 10111110 | `&#190;` | ¾ | 
| 191 | BF | 10111111 | `&#191;` | ¿ | 
| 192 | C0 | 11000000 | `&#192;` | À | 
| 193 | C1 | 11000001 | `&#193;` | Á | 
| 194 | C2 | 11000010 | `&#194;` | Â | 
| 195 | C3 | 11000011 | `&#195;` | Ã | 
| 196 | C4 | 11000100 | `&#196;` | Ä | 
| 197 | C5 | 11000101 | `&#197;` | Å | 
| 198 | C6 | 11000110 | `&#198;` | Æ | 
| 199 | C7 | 11000111 | `&#199;` | Ç | 
| 200 | C8 | 11001000 | `&#200;` | È | 
| 201 | C9 | 11001001 | `&#201;` | É | 
| 202 | CA | 11001010 | `&#202;` | Ê | 
| 203 | CB | 11001011 | `&#203;` | Ë | 
| 204 | CC | 11001100 | `&#204;` | Ì | 
| 205 | CD | 11001101 | `&#205;` | Í | 
| 206 | CE | 11001110 | `&#206;` | Î | 
| 207 | CF | 11001111 | `&#207;` | Ï | 
| 208 | D0 | 11010000 | `&#208;` | Ð | 
| 209 | D1 | 11010001 | `&#209;` | Ñ | 
| 210 | D2 | 11010010 | `&#210;` | Ò | 
| 211 | D3 | 11010011 | `&#211;` | Ó | 
| 212 | D4 | 11010100 | `&#212;` | Ô | 
| 213 | D5 | 11010101 | `&#213;` | Õ | 
| 214 | D6 | 11010110 | `&#214;` | Ö | 
| 215 | D7 | 11010111 | `&#215;` | × | 
| 216 | D8 | 11011000 | `&#216;` | Ø | 
| 217 | D9 | 11011001 | `&#217;` | Ù | 
| 218 | DA | 11011010 | `&#218;` | Ú | 
| 219 | DB | 11011011 | `&#219;` | Û | 
| 220 | DC | 11011100 | `&#220;` | Ü | 
| 221 | DD | 11011101 | `&#221;` | Ý | 
| 222 | DE | 11011110 | `&#222;` | Þ | 
| 223 | DF | 11011111 | `&#223;` | ß | 
| 224 | E0 | 11100000 | `&#224;` | à | 
| 225 | E1 | 11100001 | `&#225;` | á | 
| 226 | E2 | 11100010 | `&#226;` | â | 
| 227 | E3 | 11100011 | `&#227;` | ã | 
| 228 | E4 | 11100100 | `&#228;` | ä | 
| 229 | E5 | 11100101 | `&#229;` | å | 
| 230 | E6 | 11100110 | `&#230;` | æ | 
| 231 | E7 | 11100111 | `&#231;` | ç | 
| 232 | E8 | 11101000 | `&#232;` | è | 
| 233 | E9 | 11101001 | `&#233;` | é | 
| 234 | EA | 11101010 | `&#234;` | ê | 
| 235 | EB | 11101011 | `&#235;` | ë | 
| 236 | EC | 11101100 | `&#236;` | ì | 
| 237 | ED | 11101101 | `&#237;` | í | 
| 238 | EE | 11101110 | `&#238;` | î | 
| 239 | EF | 11101111 | `&#239;` | ï | 
| 240 | F0 | 11110000 | `&#240;` | ð | 
| 241 | F1 | 11110001 | `&#241;` | ñ | 
| 242 | F2 | 11110010 | `&#242;` | ò | 
| 243 | F3 | 11110011 | `&#243;` | ó | 
| 244 | F4 | 11110100 | `&#244;` | ô | 
| 245 | F5 | 11110101 | `&#245;` | õ | 
| 246 | F6 | 11110110 | `&#246;` | ö | 
| 247 | F7 | 11110111 | `&#247;` | ÷ | 
| 248 | F8 | 11111000 | `&#248;` | ø | 
| 249 | F9 | 11111001 | `&#249;` | ù | 
| 250 | FA | 11111010 | `&#250;` | ú | 
| 251 | FB | 11111011 | `&#251;` | û | 
| 252 | FC | 11111100 | `&#252;` | ü | 
| 253 | FD | 11111101 | `&#253;` | ý | 
| 254 | FE | 11111110 | `&#254;` | þ | 
| 255 | FF | 11111111 | `&#255;` | ÿ | 

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#open" target="_blank"><code>open(<em>file, mode='r', buffering=-1, encoding=None, errors=None, newline=None, closefd=True, opener=None</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Open file and return a corresponding [file object](https://docs.python.org/3/glossary.html#term-file-object). If the file cannot be opened, an [`OSError`](https://docs.python.org/3/library/exceptions.html#OSError) is raised. See [Reading and Writing Files](https://docs.python.org/3/tutorial/inputoutput.html#tut-files) for more examples of how to use this function.

`file` is a [path-like object](https://docs.python.org/3/glossary.html#term-path-like-object) giving the pathname (absolute or relative to the current working directory) of the file to be opened or an integer file descriptor of the file to be wrapped. (If a file descriptor is given, it is closed when the returned I/O object is closed, unless `closefd` is set to `False`.)

`mode` is an optional string that specifies the mode in which the file is opened. It defaults to `'r'` which means open for reading in text mode. Other common values are `'w'` for writing (truncating the file if it already exists), `'x'` for exclusive creation and `'a'` for appending (which on *some* Unix systems, means that *all* writes append to the end of the file regardless of the current seek position). In text mode, if `encoding` is not specified the `encoding` used is platform dependent: `locale.getpreferredencoding(False)` is called to get the current locale encoding. (For reading and writing raw bytes use binary mode and leave `encoding` unspecified.) The available modes are:

| Character | Meaning |
| :-- | :-- |
| `'r'` | open for reading (default) |
| `'w'` | open for writing, truncating the file first |
| `'x'` | open for exclusive creation, failing if the file already exists |
| `'a'` | open for writing, appending to the end of the file if it exists |
| `'b'` | binary mode |
| `'t'` | text mode (default) |
| `'+'` | open for updating (reading and writing) |

The default mode is `'r'` (open for reading text, synonym of `'rt'`). Modes `'w+'` and `'w+b'` open and truncate the file. Modes `'r+'` and `'r+b'` open the file with no truncation.

As mentioned in the [Overview](https://docs.python.org/3/library/io.html#io-overview), Python distinguishes between binary and text I/O. Files opened in binary mode (including `'b'` in the `mode` argument) return contents as [`bytes`](https://docs.python.org/3/library/stdtypes.html#bytes) objects without any decoding. In text mode (the default, or when `'t'` is included in the `mode` argument), the contents of the file are returned as [`str`](https://docs.python.org/3/library/stdtypes.html#str), the bytes having been first decoded using a platform-dependent encoding or using the specified `encoding` if given.

There is an additional mode character permitted, `'U'`, which no longer has any effect, and is considered deprecated. It previously enabled [universal newlines](https://docs.python.org/3/glossary.html#term-universal-newlines) in text mode, which became the default behaviour in Python 3.0. Refer to the documentation of the [newline](https://docs.python.org/3/library/functions.html#open-newline-parameter) parameter for further details.

**Note:** Python doesn't depend on the underlying operating system's notion of text files; all the processing is done by Python itself, and is therefore platform-independent.

`buffering` is an optional integer used to set the buffering policy. Pass `0` to switch buffering off (only allowed in binary mode), `1` to select line buffering (only usable in text mode), and an integer `> 1` to indicate the size in bytes of a fixed-size chunk buffer. When no `buffering` argument is given, the default buffering policy works as follows:

- Binary files are buffered in fixed-size chunks; the size of the buffer is chosen using a heuristic trying to determine the underlying device's "block size" and falling back on [`io.DEFAULT_BUFFER_SIZE`](https://docs.python.org/3/library/io.html#io.DEFAULT_BUFFER_SIZE). On many systems, the buffer will typically be 4096 or 8192 bytes long.
- "Interactive" text files (files for which [`isatty()`](https://docs.python.org/3/library/io.html#io.IOBase.isatty) returns `True`) use line buffering. Other text files use the policy described above for binary files.

`encoding` is the name of the encoding used to decode or encode the file. This should only be used in text mode. The default encoding is platform dependent (whatever [`locale.getpreferredencoding()`](https://docs.python.org/3/library/locale.html#locale.getpreferredencoding) returns), but any [text encoding](https://docs.python.org/3/glossary.html#term-text-encoding) supported by Python can be used. See the [codecs](https://docs.python.org/3/library/codecs.html#module-codecs) module for the list of supported encodings.

`errors` is an optional string that specifies how encoding and decoding errors are to be handled—this cannot be used in binary mode. A variety of standard error handlers are available (listed under [Error Handlers](https://docs.python.org/3/library/codecs.html#error-handlers)), though any error handling name that has been registered with [`codecs.register_error()`](https://docs.python.org/3/library/codecs.html#codecs.register_error) is also valid. The standard names include:

- `'strict'` to raise a [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) exception if there is an encoding error. The default value of `None` has the same effect.
- `'ignore'` ignores errors. Note that ignoring encoding errors can lead to data loss.
- `'replace'` causes a replacement marker (such as `'?'`) to be inserted where there is malformed data.
- `'surrogateescape'` will represent any incorrect bytes as low surrogate code units ranging from U+DC80 to U+DCFF. These surrogate code units will then be turned back into the same bytes when the `surrogateescape` error handler is used when writing data. This is useful for processing files in an unknown encoding.
- `'xmlcharrefreplace'` is only supported when writing to a file. Characters not supported by the encoding are replaced with the appropriate XML character reference `&#nnn;`.
- `'backslashreplace'` replaces malformed data by Python's backslashed escape sequences.
- `'namereplace'` (also only supported when writing) replaces unsupported characters with `\N{...}` escape sequences.

`newline` controls how [universal newlines](https://docs.python.org/3/glossary.html#term-universal-newlines) mode works (it only applies to text mode). It can be `None`, `''`, `'\n'`, `'\r'`, and `'\r\n'`. It works as follows:

- When reading input from the stream, if `newline` is `None`, universal newlines mode is enabled. Lines in the input can end in `'\n'`, `'\r'`, or `'\r\n'`, and these are translated into `'\n'` before being returned to the caller. If it is '', universal newlines mode is enabled, but line endings are returned to the caller untranslated. If it has any of the other legal values, input lines are only terminated by the given string, and the line ending is returned to the caller untranslated.
- When writing output to the stream, if `newline` is `None`, any `'\n'` characters written are translated to the system default line separator, [`os.linesep`](https://docs.python.org/3/library/os.html#os.linesep). If `newline` is `''` or `'\n'`, no translation takes place. If `newline` is any of the other legal values, any `'\n'` characters written are translated to the given string.

If `closefd` is `False` and a file descriptor rather than a filename was given, the underlying file descriptor will be kept open when the file is closed. If a filename is given `closefd` must be `True` (the default) otherwise an error will be raised.

A custom opener can be used by passing a callable as `opener`. The underlying file descriptor for the file object is then obtained by calling `opener` with (`file`, `flags`). `opener` must return an open file descriptor (passing [`os.open()`](https://docs.python.org/3/library/os.html#os.open) as `opener` results in functionality similar to passing `None`).

The newly created file is [non-inheritable](https://docs.python.org/3/library/os.html#fd-inheritance).

The following example uses the [`dir_fd`](https://docs.python.org/3/library/os.html#dir-fd) parameter of the [`os.open()`](https://docs.python.org/3/library/os.html#os.open) function to open a file relative to a given directory:

```
>>> import os
>>> dir_fd = os.open('somedir', os.O_RDONLY)
>>> def opener(path, flags):
...     return os.open(path, flags, dir_fd=dir_fd)
...
>>> with open('spamspam.txt', 'w', opener=opener) as f:
...     print('This will be written to somedir/spamspam.txt', file=f)
...
>>> os.close(dir_fd)  # don't leak a file descriptor
```

The type of [file object](https://docs.python.org/3/glossary.html#term-file-object) returned by the [`open()`](https://docs.python.org/3/library/functions.html#open) function depends on the mode. When [`open()`](https://docs.python.org/3/library/functions.html#open) is used to open a file in a text mode (`'w'`, `'r'`, `'wt'`, `'rt'`, etc.), it returns a subclass of [`io.TextIOBase`](https://docs.python.org/3/library/io.html#io.TextIOBase) (specifically [`io.TextIOWrapper`](https://docs.python.org/3/library/io.html#io.TextIOWrapper)). When used to open a file in a binary mode with buffering, the returned class is a subclass of [`io.BufferedIOBase`](https://docs.python.org/3/library/io.html#io.BufferedIOBase). The exact class varies: in read binary mode, it returns an [`io.BufferedReader`](https://docs.python.org/3/library/io.html#io.BufferedReader); in write binary and append binary modes, it returns an [`io.BufferedWriter`](https://docs.python.org/3/library/io.html#io.BufferedWriter), and in read/write mode, it returns an [`io.BufferedRandom`](https://docs.python.org/3/library/io.html#io.BufferedRandom). When buffering is disabled, the raw stream, a subclass of [`io.RawIOBase`](https://docs.python.org/3/library/io.html#io.RawIOBase), [`io.FileIO`](https://docs.python.org/3/library/io.html#io.FileIO), is returned.

See also the file handling modules, such as, [`fileinput`](https://docs.python.org/3/library/fileinput.html#module-fileinput), [`io`](https://docs.python.org/3/library/io.html#module-io) (where [`open()`](https://docs.python.org/3/library/functions.html#open) is declared), [`os`](https://docs.python.org/3/library/os.html#module-os), [`os.path`](https://docs.python.org/3/library/os.path.html#module-os.path), [`tempfile`](https://docs.python.org/3/library/tempfile.html#module-tempfile), and [`shutil`](https://docs.python.org/3/library/shutil.html#module-shutil).

Raises an [auditing event](https://docs.python.org/3/library/sys.html#auditing) `open` with arguments `file`, `mode`, `flags`.

The `mode` and `flags` arguments may have been modified or inferred from the original call.

*Changed in version 3.3:*

- The `opener` parameter was added.
- The `'x'` mode was added.
- [`IOError`](https://docs.python.org/3/library/exceptions.html#IOError) used to be raised, it is now an alias of [`OSError`](https://docs.python.org/3/library/exceptions.html#OSError).
- [`FileExistsError`](https://docs.python.org/3/library/exceptions.html#FileExistsError) is now raised if the file opened in exclusive creation mode (`'x'`) already exists.

*Changed in version 3.4:*

- The file is now non-inheritable.

*Deprecated since version 3.4, will be removed in version 3.10: The `'U'` mode.*

*Changed in version 3.5:*

- If the system call is interrupted and the signal handler does not raise an exception, the function now retries the system call instead of raising an [`InterruptedError`](https://docs.python.org/3/library/exceptions.html#InterruptedError) exception (see [PEP 475](https://www.python.org/dev/peps/pep-0475/) for the rationale).
- The `'namereplace'` error handler was added.

*Changed in version 3.6:*

- Support added to accept objects implementing [`os.PathLike`](https://docs.python.org/3/library/os.html#os.PathLike).
- On Windows, opening a console buffer may return a subclass of [`io.RawIOBase`](https://docs.python.org/3/library/io.html#io.RawIOBase) other than [`io.FileIO`](https://docs.python.org/3/library/io.html#io.FileIO).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#ord" target="_blank"><code>ord(<em>c</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Given a string representing one Unicode character, return an integer representing the Unicode code point of that character. For example, `ord('a')` returns the integer `97` and `ord('€')` (Euro sign) returns `8364`. This is the inverse of [`chr()`](https://docs.python.org/3/library/functions.html#chr).

---

</details>

**Ascii Table:**

<details><summary> ASCII Table</summary>

| Dec | Hex | Oct | Binary | HTML | Char | Description |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| 0 | 00 | 000 | 00000000 | `&#0;` | `NUL` | Null |
| 1 | 01 | 001 | 00000001 | `&#1;` | `SOH` | Start of Header |
| 2 | 02 | 002 | 00000010 | `&#2;` | `STX` | Start of Text |
| 3 | 03 | 003 | 00000011 | `&#3;` | `ETX` | End of Text |
| 4 | 04 | 004 | 00000100 | `&#4;` | `EOT` | End of Transmission |
| 5 | 05 | 005 | 00000101 | `&#5;` | `ENQ` | Enquiry |
| 6 | 06 | 006 | 00000110 | `&#6;` | `ACK` | Acknowledge |
| 7 | 07 | 007 | 00000111 | `&#7;` | `BEL` | Bell |
| 8 | 08 | 010 | 00001000 | `&#8;` | `BS` | Backspace |
| 9 | 09 | 011 | 00001001 | `&#9;` | `HT` | Horizontal Tab |
| 10 | 0A | 012 | 00001010 | `&#10;` | `LF` | Line Feed |
| 11 | 0B | 013 | 00001011 | `&#11;` | `VT` | Vertical Tab |
| 12 | 0C | 014 | 00001100 | `&#12;` | `FF` | Form Feed |
| 13 | 0D | 015 | 00001101 | `&#13;` | `CR` | Carriage Return |
| 14 | 0E | 016 | 00001110 | `&#14;` | `SO` | Shift Out |
| 15 | 0F | 017 | 00001111 | `&#15;` | `SI` | Shift In |
| 16 | 10 | 020 | 00010000 | `&#16;` | `DLE` | Data Link Escape |
| 17 | 11 | 021 | 00010001 | `&#17;` | `DC1` | Device Control 1 |
| 18 | 12 | 022 | 00010010 | `&#18;` | `DC2` | Device Control 2 |
| 19 | 13 | 023 | 00010011 | `&#19;` | `DC3` | Device Control 3 |
| 20 | 14 | 024 | 00010100 | `&#20;` | `DC4` | Device Control 4 |
| 21 | 15 | 025 | 00010101 | `&#21;` | `NAK` | Negative Acknowledge |
| 22 | 16 | 026 | 00010110 | `&#22;` | `SYN` | Synchronize |
| 23 | 17 | 027 | 00010111 | `&#23;` | `ETB` | End of Transmission Block |
| 24 | 18 | 030 | 00011000 | `&#24;` | `CAN` | Cancel |
| 25 | 19 | 031 | 00011001 | `&#25;` | `EM` | End of Medium |
| 26 | 1A | 032 | 00011010 | `&#26;` | `SUB` | Substitute |
| 27 | 1B | 033 | 00011011 | `&#27;` | `ESC` | Escape |
| 28 | 1C | 034 | 00011100 | `&#28;` | `FS` | File Separator |
| 29 | 1D | 035 | 00011101 | `&#29;` | `GS` | Group Separator |
| 30 | 1E | 036 | 00011110 | `&#30;` | `RS` | Record Separator |
| 31 | 1F | 037 | 00011111 | `&#31;` | `US` | Unit Separator |
| 32 | 20 | 040 | 00100000 | `&#32;` | `space` | Space |
| 33 | 21 | 041 | 00100001 | `&#33;` | `!` | exclamation mark |
| 34 | 22 | 042 | 00100010 | `&#34;` | `"` | double quote |
| 35 | 23 | 043 | 00100011 | `&#35;` | `#` | number |
| 36 | 24 | 044 | 00100100 | `&#36;` | `$` | dollar |
| 37 | 25 | 045 | 00100101 | `&#37;` | `%` | percent |
| 38 | 26 | 046 | 00100110 | `&#38;` | `&` | ampersand |
| 39 | 27 | 047 | 00100111 | `&#39;` | `'` | single quote |
| 40 | 28 | 050 | 00101000 | `&#40;` | `(` | left parenthesis |
| 41 | 29 | 051 | 00101001 | `&#41;` | `)` | right parenthesis |
| 42 | 2A | 052 | 00101010 | `&#42;` | `*` | asterisk |
| 43 | 2B | 053 | 00101011 | `&#43;` | `+` | plus |
| 44 | 2C | 054 | 00101100 | `&#44;` | `,` | comma |
| 45 | 2D | 055 | 00101101 | `&#45;` | `-` | minus |
| 46 | 2E | 056 | 00101110 | `&#46;` | `.` | period |
| 47 | 2F | 057 | 00101111 | `&#47;` | `/` | slash |
| 48 | 30 | 060 | 00110000 | `&#48;` | `0` | zero |
| 49 | 31 | 061 | 00110001 | `&#49;` | `1` | one |
| 50 | 32 | 062 | 00110010 | `&#50;` | `2` | two |
| 51 | 33 | 063 | 00110011 | `&#51;` | `3` | three |
| 52 | 34 | 064 | 00110100 | `&#52;` | `4` | four |
| 53 | 35 | 065 | 00110101 | `&#53;` | `5` | five |
| 54 | 36 | 066 | 00110110 | `&#54;` | `6` | six |
| 55 | 37 | 067 | 00110111 | `&#55;` | `7` | seven |
| 56 | 38 | 070 | 00111000 | `&#56;` | `8` | eight |
| 57 | 39 | 071 | 00111001 | `&#57;` | `9` | nine |
| 58 | 3A | 072 | 00111010 | `&#58;` | `:` | colon |
| 59 | 3B | 073 | 00111011 | `&#59;` | `;` | | `semicolon` | |
| 60 | 3C | 074 | 00111100 | `&#60;` | `<` | less than |
| 61 | 3D | 075 | 00111101 | `&#61;` | `=` | equality sign |
| 62 | 3E | 076 | 00111110 | `&#62;` | `>` | greater than |
| 63 | 3F | 077 | 00111111 | `&#63;` | `?` | question mark |
| 64 | 40 | 100 | 01000000 | `&#64;` | `@` | at sign |
| 65 | 41 | 101 | 01000001 | `&#65;` | `A` |   |
| 66 | 42 | 102 | 01000010 | `&#66;` | `B` |   |
| 67 | 43 | 103 | 01000011 | `&#67;` | `C` |   |
| 68 | 44 | 104 | 01000100 | `&#68;` | `D` |   |
| 69 | 45 | 105 | 01000101 | `&#69;` | `E` |   |
| 70 | 46 | 106 | 01000110 | `&#70;` | `F` |   |
| 71 | 47 | 107 | 01000111 | `&#71;` | `G` |   |
| 72 | 48 | 110 | 01001000 | `&#72;` | `H` |   |
| 73 | 49 | 111 | 01001001 | `&#73;` | `I` |   |
| 74 | 4A | 112 | 01001010 | `&#74;` | `J` |   |
| 75 | 4B | 113 | 01001011 | `&#75;` | `K` |   |
| 76 | 4C | 114 | 01001100 | `&#76;` | `L` |   |
| 77 | 4D | 115 | 01001101 | `&#77;` | `M` |   |
| 78 | 4E | 116 | 01001110 | `&#78;` | `N` |   |
| 79 | 4F | 117 | 01001111 | `&#79;` | `O` |   |
| 80 | 50 | 120 | 01010000 | `&#80;` | `P` |   |
| 81 | 51 | 121 | 01010001 | `&#81;` | `Q` |   |
| 82 | 52 | 122 | 01010010 | `&#82;` | `R` |   |
| 83 | 53 | 123 | 01010011 | `&#83;` | `S` |   |
| 84 | 54 | 124 | 01010100 | `&#84;` | `T` |   |
| 85 | 55 | 125 | 01010101 | `&#85;` | `U` |   |
| 86 | 56 | 126 | 01010110 | `&#86;` | `V` |   |
| 87 | 57 | 127 | 01010111 | `&#87;` | `W` |   |
| 88 | 58 | 130 | 01011000 | `&#88;` | `X` |   |
| 89 | 59 | 131 | 01011001 | `&#89;` | `Y` |   |
| 90 | 5A | 132 | 01011010 | `&#90;` | `Z` |   |
| 91 | 5B | 133 | 01011011 | `&#91;` | `[` | left square bracket |
| 92 | 5C | 134 | 01011100 | `&#92;` | `\` | backslash |
| 93 | 5D | 135 | 01011101 | `&#93;` | `]` | right square bracket |
| 94 | 5E | 136 | 01011110 | `&#94;` | `^` | caret / circumflex |
| 95 | 5F | 137 | 01011111 | `&#95;` | `_` | underscore |
| 96 | 60 | 140 | 01100000 | `&#96;` | `` ` `` | grave / accent |
| 97 | 61 | 141 | 01100001 | `&#97;` | `a` |   |
| 98 | 62 | 142 | 01100010 | `&#98;` | `b` |   |
| 99 | 63 | 143 | 01100011 | `&#99;` | `c` |   |
| 100 | 64 | 144 | 01100100 | `&#100;` | `d` |   |
| 101 | 65 | 145 | 01100101 | `&#101;` | `e` |   |
| 102 | 66 | 146 | 01100110 | `&#102;` | `f` |   |
| 103 | 67 | 147 | 01100111 | `&#103;` | `g` |   |
| 104 | 68 | 150 | 01101000 | `&#104;` | `h` |   |
| 105 | 69 | 151 | 01101001 | `&#105;` | `i` |   |
| 106 | 6A | 152 | 01101010 | `&#106;` | `j` |   |
| 107 | 6B | 153 | 01101011 | `&#107;` | `k` |   |
| 108 | 6C | 154 | 01101100 | `&#108;` | `l` |   |
| 109 | 6D | 155 | 01101101 | `&#109;` | `m` |   |
| 110 | 6E | 156 | 01101110 | `&#110;` | `n` |   |
| 111 | 6F | 157 | 01101111 | `&#111;` | `o` |   |
| 112 | 70 | 160 | 01110000 | `&#112;` | `p` |   |
| 113 | 71 | 161 | 01110001 | `&#113;` | `q` |   |
| 114 | 72 | 162 | 01110010 | `&#114;` | `r` |   |
| 115 | 73 | 163 | 01110011 | `&#115;` | `s` |   |
| 116 | 74 | 164 | 01110100 | `&#116;` | `t` |   |
| 117 | 75 | 165 | 01110101 | `&#117;` | `u` |   |
| 118 | 76 | 166 | 01110110 | `&#118;` | `v` |   |
| 119 | 77 | 167 | 01110111 | `&#119;` | `w` |   |
| 120 | 78 | 170 | 01111000 | `&#120;` | `x` |   |
| 121 | 79 | 171 | 01111001 | `&#121;` | `y` |   |
| 122 | 7A | 172 | 01111010 | `&#122;` | `z` |   |
| 123 | 7B | 173 | 01111011 | `&#123;` | `{` | left curly bracket |
| 124 | 7C | 174 | 01111100 | `&#124;` | <code>&#124;</code> | vertical bar |
| 125 | 7D | 175 | 01111101 | `&#125;` | `}` | right curly bracket |
| 126 | 7E | 176 | 01111110 | `&#126;` | `~` | tilde |
| 127 | 7F | 177 | 01111111 | `&#127;` | `DEL` | delete |

---

</details>

<details><summary> Extended ASCII Table</summary>

| Dec | Hex | Binary | HTML | Char |
| :-- | :-- | :-- | :-- | :-- | 
| 128 | 80 | 10000000 | - |  |
| 129 | 81 | 10000001 | - |  |
| 130 | 82 | 10000010 | - |  |
| 131 | 83 | 10000011 | - |  |
| 132 | 84 | 10000100 | - |  |
| 133 | 85 | 10000101 | - |  |
| 134 | 86 | 10000110 | - |  |
| 135 | 87 | 10000111 | - |  |
| 136 | 88 | 10001000 | - |  |
| 137 | 89 | 10001001 | - |  |
| 138 | 8A | 10001010 | - |  |
| 139 | 8B | 10001011 | - |  |
| 140 | 8C | 10001100 | - |  |
| 141 | 8D | 10001101 | - |  |
| 142 | 8E | 10001110 | - |  |
| 143 | 8F | 10001111 | - |  |
| 144 | 90 | 10010000 | - |  |
| 145 | 91 | 10010001 | - |  |
| 146 | 92 | 10010010 | - |  |
| 147 | 93 | 10010011 | - |  |
| 148 | 94 | 10010100 | - |  |
| 149 | 95 | 10010101 | - |  |
| 150 | 96 | 10010110 | - |  |
| 151 | 97 | 10010111 | - |  |
| 152 | 98 | 10011000 | - |  |
| 153 | 99 | 10011001 | - |  |
| 154 | 9A | 10011010 | - |  |
| 155 | 9B | 10011011 | - |  |
| 156 | 9C | 10011100 | - |  |
| 157 | 9D | 10011101 | - |  |
| 158 | 9E | 10011110 | - |  |
| 159 | 9F | 10011111 | - |  |
| 160 | A0 | 10100000 | `&#160;` | | 
| 161 | A1 | 10100001 | `&#161;` | ¡ | 
| 162 | A2 | 10100010 | `&#162;` | ¢ | 
| 163 | A3 | 10100011 | `&#163;` | £ | 
| 164 | A4 | 10100100 | `&#164;` | ¤ | 
| 165 | A5 | 10100101 | `&#165;` | ¥ | 
| 166 | A6 | 10100110 | `&#166;` | ¦ | 
| 167 | A7 | 10100111 | `&#167;` | § | 
| 168 | A8 | 10101000 | `&#168;` | ¨ | 
| 169 | A9 | 10101001 | `&#169;` | © | 
| 170 | AA | 10101010 | `&#170;` | ª | 
| 171 | AB | 10101011 | `&#171;` | « | 
| 172 | AC | 10101100 | `&#172;` | ¬ | 
| 173 | AD | 10101101 | `&#173;` | ­ | 
| 174 | AE | 10101110 | `&#174;` | ® | 
| 175 | AF | 10101111 | `&#175;` | ¯ | 
| 176 | B0 | 10110000 | `&#176;` | ° | 
| 177 | B1 | 10110001 | `&#177;` | ± | 
| 178 | B2 | 10110010 | `&#178;` | ² | 
| 179 | B3 | 10110011 | `&#179;` | ³ | 
| 180 | B4 | 10110100 | `&#180;` | ´ | 
| 181 | B5 | 10110101 | `&#181;` | µ | 
| 182 | B6 | 10110110 | `&#182;` | ¶ | 
| 183 | B7 | 10110111 | `&#183;` | · | 
| 184 | B8 | 10111000 | `&#184;` | ¸ | 
| 185 | B9 | 10111001 | `&#185;` | ¹ | 
| 186 | BA | 10111010 | `&#186;` | º | 
| 187 | BB | 10111011 | `&#187;` | » | 
| 188 | BC | 10111100 | `&#188;` | ¼ | 
| 189 | BD | 10111101 | `&#189;` | ½ | 
| 190 | BE | 10111110 | `&#190;` | ¾ | 
| 191 | BF | 10111111 | `&#191;` | ¿ | 
| 192 | C0 | 11000000 | `&#192;` | À | 
| 193 | C1 | 11000001 | `&#193;` | Á | 
| 194 | C2 | 11000010 | `&#194;` | Â | 
| 195 | C3 | 11000011 | `&#195;` | Ã | 
| 196 | C4 | 11000100 | `&#196;` | Ä | 
| 197 | C5 | 11000101 | `&#197;` | Å | 
| 198 | C6 | 11000110 | `&#198;` | Æ | 
| 199 | C7 | 11000111 | `&#199;` | Ç | 
| 200 | C8 | 11001000 | `&#200;` | È | 
| 201 | C9 | 11001001 | `&#201;` | É | 
| 202 | CA | 11001010 | `&#202;` | Ê | 
| 203 | CB | 11001011 | `&#203;` | Ë | 
| 204 | CC | 11001100 | `&#204;` | Ì | 
| 205 | CD | 11001101 | `&#205;` | Í | 
| 206 | CE | 11001110 | `&#206;` | Î | 
| 207 | CF | 11001111 | `&#207;` | Ï | 
| 208 | D0 | 11010000 | `&#208;` | Ð | 
| 209 | D1 | 11010001 | `&#209;` | Ñ | 
| 210 | D2 | 11010010 | `&#210;` | Ò | 
| 211 | D3 | 11010011 | `&#211;` | Ó | 
| 212 | D4 | 11010100 | `&#212;` | Ô | 
| 213 | D5 | 11010101 | `&#213;` | Õ | 
| 214 | D6 | 11010110 | `&#214;` | Ö | 
| 215 | D7 | 11010111 | `&#215;` | × | 
| 216 | D8 | 11011000 | `&#216;` | Ø | 
| 217 | D9 | 11011001 | `&#217;` | Ù | 
| 218 | DA | 11011010 | `&#218;` | Ú | 
| 219 | DB | 11011011 | `&#219;` | Û | 
| 220 | DC | 11011100 | `&#220;` | Ü | 
| 221 | DD | 11011101 | `&#221;` | Ý | 
| 222 | DE | 11011110 | `&#222;` | Þ | 
| 223 | DF | 11011111 | `&#223;` | ß | 
| 224 | E0 | 11100000 | `&#224;` | à | 
| 225 | E1 | 11100001 | `&#225;` | á | 
| 226 | E2 | 11100010 | `&#226;` | â | 
| 227 | E3 | 11100011 | `&#227;` | ã | 
| 228 | E4 | 11100100 | `&#228;` | ä | 
| 229 | E5 | 11100101 | `&#229;` | å | 
| 230 | E6 | 11100110 | `&#230;` | æ | 
| 231 | E7 | 11100111 | `&#231;` | ç | 
| 232 | E8 | 11101000 | `&#232;` | è | 
| 233 | E9 | 11101001 | `&#233;` | é | 
| 234 | EA | 11101010 | `&#234;` | ê | 
| 235 | EB | 11101011 | `&#235;` | ë | 
| 236 | EC | 11101100 | `&#236;` | ì | 
| 237 | ED | 11101101 | `&#237;` | í | 
| 238 | EE | 11101110 | `&#238;` | î | 
| 239 | EF | 11101111 | `&#239;` | ï | 
| 240 | F0 | 11110000 | `&#240;` | ð | 
| 241 | F1 | 11110001 | `&#241;` | ñ | 
| 242 | F2 | 11110010 | `&#242;` | ò | 
| 243 | F3 | 11110011 | `&#243;` | ó | 
| 244 | F4 | 11110100 | `&#244;` | ô | 
| 245 | F5 | 11110101 | `&#245;` | õ | 
| 246 | F6 | 11110110 | `&#246;` | ö | 
| 247 | F7 | 11110111 | `&#247;` | ÷ | 
| 248 | F8 | 11111000 | `&#248;` | ø | 
| 249 | F9 | 11111001 | `&#249;` | ù | 
| 250 | FA | 11111010 | `&#250;` | ú | 
| 251 | FB | 11111011 | `&#251;` | û | 
| 252 | FC | 11111100 | `&#252;` | ü | 
| 253 | FD | 11111101 | `&#253;` | ý | 
| 254 | FE | 11111110 | `&#254;` | þ | 
| 255 | FF | 11111111 | `&#255;` | ÿ | 

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#pow" target="_blank"><code>pow(<em>base</em>, <em>exp</em>[, <em>mod</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `base` to the power `exp`; if `mod` is present, return `base` to the power `exp`, modulo `mod` (computed more efficiently than `pow(base, exp) % mod`). The two-argument form `pow(base, exp)` is equivalent to using the power operator: `base**exp`.

The arguments must have numeric types. With mixed operand types, the coercion rules for binary arithmetic operators apply. For [`int`](https://docs.python.org/3/library/functions.html#int) operands, the result has the same type as the operands (after coercion) unless the second argument is negative; in that case, all arguments are converted to float and a float result is delivered. For example, `10**2` returns `100`, but `10**-2` returns `0.01`.

For [`int`](https://docs.python.org/3/library/functions.html#int) operands `base` and `exp`, if `mod` is present, `mod` must also be of integer type and `mod` must be nonzero. If `mod` is present and `exp` is negative, `base` must be relatively prime to `mod`. In that case, `pow(inv_base, -exp, mod)` is returned, where `inv_base` is an inverse to `base` modulo `mod`.

Here's an example of computing an inverse for `38` modulo `97`:

```
>>> pow(38, -1, mod=97)
23
>>> 23 * 38 % 97 == 1
True
```

*Changed in version 3.8:* For [`int`](https://docs.python.org/3/library/functions.html#int) operands, the three-argument form of `pow` now allows the second argument to be negative, permitting computation of modular inverses.

*Changed in version 3.8:* Allow keyword arguments. Formerly, only positional arguments were supported.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#print" target="_blank"><code>print(<em>*objects, sep=' ', end='\n', file=sys.stdout, flush=False</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Print `objects` to the text stream `file`, separated by `sep` and followed by `end`. `sep`, `end`, `file` and `flush`, if present, must be given as keyword arguments.

All non-keyword arguments are converted to strings like [`str()`](https://docs.python.org/3/library/stdtypes.html#str) does and written to the stream, separated by `sep` and followed by `end`. Both `sep` and `end` must be strings; they can also be `None`, which means to use the default values. If no objects are given, [`print()`](https://docs.python.org/3/library/functions.html#print) will just write `end`.

The `file` argument must be an object with a `write(string) method`; if it is not present or `None`, [`sys.stdout`](https://docs.python.org/3/library/sys.html#sys.stdout) will be used. Since printed arguments are converted to text strings, [`print()`](https://docs.python.org/3/library/functions.html#print) cannot be used with binary mode file objects. For these, use `file.write(...)` instead.

Whether output is buffered is usually determined by `file`, but if the `flush` keyword argument is true, the stream is forcibly flushed.

*Changed in version 3.3:* Added the `flush` keyword argument.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#property" target="_blank"><code>property(<em>fget=None, fset=None, fdel=None, doc=None</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a property attribute.

`fget` is a function for getting an attribute value. `fset` is a function for setting an attribute value. `fdel` is a function for deleting an attribute value. And `doc` creates a docstring for the attribute.

A typical use is to define a managed attribute `x`:

```python
class C:
    def __init__(self):
        self._x = None

    def getx(self):
        return self._x

    def setx(self, value):
        self._x = value

    def delx(self):
        del self._x

    x = property(getx, setx, delx, "I'm the 'x' property.")
```

If `c` is an instance of `C`, `c.x` will invoke the getter, `c.x = value` will invoke the setter and `del c.x` the deleter.

If given, `doc` will be the docstring of the property attribute. Otherwise, the property will copy `fget`'s docstring (if it exists). This makes it possible to create read-only properties easily using [`property()`](https://docs.python.org/3/library/functions.html#property) as a [decorator](https://docs.python.org/3/glossary.html#term-decorator):

```python
class Parrot:
    def __init__(self):
        self._voltage = 100000

    @property
    def voltage(self):
        """Get the current voltage."""
        return self._voltage
```

The `@property` decorator turns the `voltage()` method into a "getter" for a read-only attribute with the same name, and it sets the docstring for `voltage` to "Get the current voltage."

A property object has `getter`, `setter`, and `deleter` methods usable as decorators that create a copy of the property with the corresponding accessor function set to the decorated function. This is best explained with an example:

```python
class C:
    def __init__(self):
        self._x = None

    @property
    def x(self):
        """I'm the 'x' property."""
        return self._x

    @x.setter
    def x(self, value):
        self._x = value

    @x.deleter
    def x(self):
        del self._x
```

This code is exactly equivalent to the first example. Be sure to give the additional functions the same name as the original property (`x` in this case.)

The returned property object also has the attributes `fget`, `fset`, and `fdel` corresponding to the constructor arguments.

*Changed in version 3.5:* The docstrings of property objects are now writeable.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-range" target="_blank"><code>range(<em>stop</em>); range(<em>start</em>, <em>stop</em>[, <em>step</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Rather than being a function, [`range`](https://docs.python.org/3/library/stdtypes.html#range) is actually an immutable sequence type, as documented in [Ranges](https://docs.python.org/3/library/stdtypes.html#typesseq-range) and [Sequence Types — list, tuple, range](https://docs.python.org/3/library/stdtypes.html#typesseq).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#repr" target="_blank"><code>repr(<em>object</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a string containing a printable representation of an object. For many types, this function makes an attempt to return a string that would yield an object with the same value when passed to [`eval()`](https://docs.python.org/3/library/functions.html#eval), otherwise the representation is a string enclosed in angle brackets that contains the name of the type of the object together with additional information often including the name and address of the object. A class can control what this function returns for its instances by defining a [`__repr__()`](https://docs.python.org/3/reference/datamodel.html#object.__repr__) method.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#reversed" target="_blank"><code>reversed(<em>seq</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a reverse [iterator](https://docs.python.org/3/glossary.html#term-iterator). `seq` must be an object which has a [`__reversed__()`](https://docs.python.org/3/reference/datamodel.html#object.__reversed__) method or supports the sequence protocol (the [`__len__()`](https://docs.python.org/3/reference/datamodel.html#object.__len__) method and the [`__getitem__()`](https://docs.python.org/3/reference/datamodel.html#object.__getitem__) method with integer arguments starting at `0`).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#round" target="_blank"><code>round(<em>number</em>[, <em>ndigits</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

Return `number` rounded to `ndigits` precision after the decimal point. If `ndigits` is omitted or is `None`, it returns the nearest integer to its input.

For the built-in types supporting [`round()`](https://docs.python.org/3/library/functions.html#round), values are rounded to the closest multiple of 10 to the power minus `ndigits`; if two multiples are equally close, rounding is done toward the even choice (so, for example, both `round(0.5)` and `round(-0.5)` are 0, and `round(1.5)` is `2`). Any integer value is valid for `ndigits` (positive, zero, or negative). The return value is an integer if `ndigits` is omitted or `None`. Otherwise the return value has the same type as `number`.

For a general Python object `number`, `round` delegates to `number.__round__`.

**Note:** The behavior of [`round()`](https://docs.python.org/3/library/functions.html#round) for floats can be surprising: for example, `round(2.675, 2)` gives `2.67` instead of the expected `2.68`. This is not a bug: it's a result of the fact that most decimal fractions can't be represented exactly as a float. See [Floating Point Arithmetic: Issues and Limitations](https://docs.python.org/3/tutorial/floatingpoint.html#tut-fp-issues) for more information.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-set" target="_blank"><code>set([<em>iterable</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new [`set`](https://docs.python.org/3/library/stdtypes.html#set) object, optionally with elements taken from `iterable`. `set` is a built-in class. See [`set`](https://docs.python.org/3/library/stdtypes.html#set) and [Set Types — set, frozenset](https://docs.python.org/3/library/stdtypes.html#types-set) for documentation about this class.

For other containers see the built-in [`frozenset`](https://docs.python.org/3/library/stdtypes.html#frozenset), [`list`](https://docs.python.org/3/library/stdtypes.html#list), [`tuple`](https://docs.python.org/3/library/stdtypes.html#tuple), and [`dict`](https://docs.python.org/3/library/stdtypes.html#dict) classes, as well as the [`collections`](https://docs.python.org/3/library/collections.html#module-collections) module.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#setattr" target="_blank"><code>setattr(<em>object, name, value</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

This is the counterpart of [`getattr()`](https://docs.python.org/3/library/functions.html#getattr). The arguments are an object, a string and an arbitrary value. The string may name an existing attribute or a new attribute. The function assigns the value to the attribute, provided the object allows it. For example, `setattr(x, 'foobar', 123)` is equivalent to `x.foobar = 123`.

**Note:** Since [private name mangling](https://docs.python.org/3/reference/expressions.html#private-name-mangling) happens at compilation time, one must manually mangle a private attribute's (attributes with two leading underscores) name in order to set it with [`setattr()`](https://docs.python.org/3/library/functions.html#setattr).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#slice" target="_blank"><code>slice(<em>stop</em>); slice(<em>start</em>, <em>stop</em>[, <em>step</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a [slice](https://docs.python.org/3/glossary.html#term-slice) object representing the set of indices specified by `range(start, stop, step)`. The `start` and `step` arguments default to `None`. Slice objects have read-only data attributes `start`, `stop` and `step` which merely return the argument values (or their default). They have no other explicit functionality; however they are used by Numerical Python and other third party extensions. Slice objects are also generated when extended indexing syntax is used. For example: `a[start:stop:step]` or `a[start:stop, i]`. See [`itertools.islice()`](https://docs.python.org/3/library/itertools.html#itertools.islice) for an alternate version that returns an iterator.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#sorted" target="_blank"><code>sorted(<em>iterable, *, key=None, reverse=False</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new sorted list from the items in `iterable`.

Has two optional arguments which must be specified as keyword arguments.

`key` specifies a function of one argument that is used to extract a comparison key from each element in `iterable` (for example, `key=str.lower`). The default value is `None` (compare the elements directly).

`reverse` is a boolean value. If set to `True`, then the list elements are sorted as if each comparison were reversed.

Use [`functools.cmp_to_key()`](https://docs.python.org/3/library/functools.html#functools.cmp_to_key) to convert an old-style `cmp` function to a `key` function.

The built-in [`sorted()`](https://docs.python.org/3/library/functions.html#sorted) function is guaranteed to be stable. A sort is stable if it guarantees not to change the relative order of elements that compare equal — this is helpful for sorting in multiple passes (for example, sort by department, then by salary grade).

For sorting examples and a brief sorting tutorial, see [Sorting HOW TO](https://docs.python.org/3/howto/sorting.html#sortinghowto).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#staticmethod" target="_blank"><code>@staticmethod</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Transform a method into a static method.

A static method does not receive an implicit first argument. To declare a static method, use this idiom:

```python
class C:
    @staticmethod
    def f(arg1, arg2, ...): ...
```

The `@staticmethod` form is a function [decorator](https://docs.python.org/3/glossary.html#term-decorator) – see [Function definitions](https://docs.python.org/3/reference/compound_stmts.html#function) for details.

A static method can be called either on the class (such as `C.f()`) or on an instance (such as `C().f()`).

Static methods in Python are similar to those found in Java or C++. Also see [`classmethod()`](https://docs.python.org/3/library/functions.html#classmethod) for a variant that is useful for creating alternate class constructors.

Like all decorators, it is also possible to call `staticmethod` as a regular function and do something with its result. This is needed in some cases where you need a reference to a function from a class body and you want to avoid the automatic transformation to instance method. For these cases, use this idiom:

```python
class C:
    builtin_open = staticmethod(open)
```

For more information on static methods, see [The standard type hierarchy](https://docs.python.org/3/reference/datamodel.html#types).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-str" target="_blank"><code>str(<em>object=''</em>); str(<em>object=b'', encoding='utf-8', errors='strict'</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a [`str`](https://docs.python.org/3/library/stdtypes.html#str) version of object. See [`str()`](https://docs.python.org/3/library/stdtypes.html#str) for details.

`str` is the built-in string [class](https://docs.python.org/3/glossary.html#term-class). For general information about strings, see [Text Sequence Type — str](https://docs.python.org/3/library/stdtypes.html#textseq).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#sum" target="_blank"><code>sum(<em>iterable, /, start=0</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Sums `start` and the items of an `iterable` from left to right and returns the total. The `iterable`'s items are normally numbers, and the start value is not allowed to be a string.

For some use cases, there are good alternatives to [`sum()`](https://docs.python.org/3/library/functions.html#sum). The preferred, fast way to concatenate a sequence of strings is by calling ''.join(sequence). To add floating point values with extended precision, see [`math.fsum()`](https://docs.python.org/3/library/math.html#math.fsum). To concatenate a series of iterables, consider using [`itertools.chain()`](https://docs.python.org/3/library/itertools.html#itertools.chain).

*Changed in version 3.8:* The `start` parameter can be specified as a keyword argument.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#super" target="_blank"><code>super([<em>type</em>[, <em>object-or-type</em>]])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a proxy object that delegates method calls to a parent or sibling class of `type`. This is useful for accessing inherited methods that have been overridden in a class.

The `object-or-type` determines the [method resolution order](https://docs.python.org/3/glossary.html#term-method-resolution-order) to be searched. The search starts from the class right after the `type`.

For example, if [`__mro__`](https://docs.python.org/3/library/stdtypes.html#class.__mro__) of `object-or-type` is `D -> B -> C -> A -> object` and the value of type is `B`, then [`super()`](https://docs.python.org/3/library/functions.html#super) searches `C -> A -> object`.

The [`__mro__`](https://docs.python.org/3/library/stdtypes.html#class.__mro__) attribute of the `object-or-type` lists the method resolution search order used by both [`getattr()`](https://docs.python.org/3/library/functions.html#getattr) and [`super()`](https://docs.python.org/3/library/functions.html#super). The attribute is dynamic and can change whenever the inheritance hierarchy is updated.

If the second argument is omitted, the super object returned is unbound. If the second argument is an object, `isinstance(obj, type)` must be true. If the second argument is a type, `issubclass(type2, type)` must be true (this is useful for classmethods).

There are two typical use cases for `super`. In a class hierarchy with single inheritance, `super` can be used to refer to parent classes without naming them explicitly, thus making the code more maintainable. This use closely parallels the use of `super` in other programming languages.

The second use case is to support cooperative multiple inheritance in a dynamic execution environment. This use case is unique to Python and is not found in statically compiled languages or languages that only support single inheritance. This makes it possible to implement "diamond diagrams" where multiple base classes implement the same method. Good design dictates that such implementations have the same calling signature in every case (because the order of calls is determined at runtime, because that order adapts to changes in the class hierarchy, and because that order can include sibling classes that are unknown prior to runtime).

For both use cases, a typical superclass call looks like this:

```python
class C(B):
    def method(self, arg):
        super().method(arg)    # This does the same thing as:
                               # super(C, self).method(arg)
```

In addition to method lookups, [`super()`](https://docs.python.org/3/library/functions.html#super) also works for attribute lookups. One possible use case for this is calling [descriptors](https://docs.python.org/3/glossary.html#term-descriptor) in a parent or sibling class.

Note that [`super()`](https://docs.python.org/3/library/functions.html#super) is implemented as part of the binding process for explicit dotted attribute lookups such as `super().__getitem__(name)`. It does so by implementing its own [`__getattribute__()`](https://docs.python.org/3/reference/datamodel.html#object.__getattribute__) method for searching classes in a predictable order that supports cooperative multiple inheritance. Accordingly, [`super()`](https://docs.python.org/3/library/functions.html#super) is undefined for implicit lookups using statements or operators such as `super()[name]`.

Also note that, aside from the zero argument form, [`super()`](https://docs.python.org/3/library/functions.html#super) is not limited to use inside methods. The two argument form specifies the arguments exactly and makes the appropriate references. The zero argument form only works inside a class definition, as the compiler fills in the necessary details to correctly retrieve the class being defined, as well as accessing the current instance for ordinary methods.

For practical suggestions on how to design cooperative classes using [`super()`](https://docs.python.org/3/library/functions.html#super), see [guide to using `super()`](https://rhettinger.wordpress.com/2011/05/26/super-considered-super/).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#func-tuple" target="_blank"><code>tuple([<em>iterable</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Rather than being a function, [`tuple`](https://docs.python.org/3/library/stdtypes.html#tuple) is actually an immutable sequence type, as documented in [Tuples](https://docs.python.org/3/library/stdtypes.html#typesseq-tuple) and [Sequence Types — list, tuple, range](https://docs.python.org/3/library/stdtypes.html#typesseq).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#type" target="_blank"><code>type(<em>object</em>); type(<em>name, bases, dict, **kwds</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

With one argument, return the type of an `object`. The return value is a type object and generally the same object as returned by [`object.__class__`](https://docs.python.org/3/library/stdtypes.html#instance.__class__).

The [`isinstance()`](https://docs.python.org/3/library/functions.html#isinstance) built-in function is recommended for testing the type of an object, because it takes subclasses into account.

With three arguments, return a new type object. This is essentially a dynamic form of the [`class`](https://docs.python.org/3/reference/compound_stmts.html#class) statement. The `name` string is the class name and becomes the [`__name__`](https://docs.python.org/3/library/stdtypes.html#definition.__name__) attribute. The `bases` tuple contains the base classes and becomes the [`__bases__`](https://docs.python.org/3/library/stdtypes.html#class.__bases__) attribute; if empty, [`object`](https://docs.python.org/3/library/functions.html#object), the ultimate base of all classes, is added. The `dict` dictionary contains attribute and method definitions for the class body; it may be copied or wrapped before becoming the [`__dict__`](https://docs.python.org/3/library/stdtypes.html#object.__dict__) attribute. The following two statements create identical [`type`](https://docs.python.org/3/library/functions.html#type) objects:

```
>>> class X:
...     a = 1
... 
>>> X = type('X', (), dict(a=1))
```

See also [Type Objects](https://docs.python.org/3/library/stdtypes.html#bltin-type-objects).

Keyword arguments provided to the three argument form are passed to the appropriate metaclass machinery (usually [`__init_subclass__()`](https://docs.python.org/3/reference/datamodel.html#object.__init_subclass__)) in the same way that keywords in a class definition (besides metaclass) would.

See also [Customizing class creation](https://docs.python.org/3/reference/datamodel.html#class-customization).

Changed in version 3.6: Subclasses of [`type`](https://docs.python.org/3/library/functions.html#type) which don't override `type.__new__` may no longer use the one-argument form to get the type of an object.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#vars" target="_blank"><code>vars([<em>object</em>])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the [`__dict__`](https://docs.python.org/3/library/stdtypes.html#object.__dict__) attribute for a module, class, instance, or any other object with a [`__dict__`](https://docs.python.org/3/library/stdtypes.html#object.__dict__) attribute.

Objects such as modules and instances have an updateable [`__dict__`](https://docs.python.org/3/library/stdtypes.html#object.__dict__) attribute; however, other objects may have write restrictions on their [`__dict__`](https://docs.python.org/3/library/stdtypes.html#object.__dict__) attributes (for example, classes use a [`types.MappingProxyType`](https://docs.python.org/3/library/types.html#types.MappingProxyType) to prevent direct dictionary updates).

Without an argument, [`vars()`](https://docs.python.org/3/library/functions.html#vars) acts like [`locals()`](https://docs.python.org/3/library/functions.html#locals). Note, the locals dictionary is only useful for reads since updates to the locals dictionary are ignored.

A [`TypeError`](https://docs.python.org/3/library/exceptions.html#TypeError) exception is raised if an object is specified but it doesn't have a [`__dict__`](https://docs.python.org/3/library/stdtypes.html#object.__dict__) attribute (for example, if its class defines the [`__slots__`](https://docs.python.org/3/reference/datamodel.html#object.__slots__) attribute).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#zip" target="_blank"><code>zip(<em>*iterables</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Make an iterator that aggregates elements from each of the iterables.

Returns an iterator of tuples, where the i-th tuple contains the i-th element from each of the argument sequences or iterables. The iterator stops when the shortest input iterable is exhausted. With a single iterable argument, it returns an iterator of 1-tuples. With no arguments, it returns an empty iterator. Equivalent to:

```python
def zip(*iterables):
    # zip('ABCD', 'xy') --> Ax By
    sentinel = object()
    iterators = [iter(it) for it in iterables]
    while iterators:
        result = []
        for it in iterators:
            elem = next(it, sentinel)
            if elem is sentinel:
                return
            result.append(elem)
        yield tuple(result)
```

The left-to-right evaluation order of the iterables is guaranteed. This makes possible an idiom for clustering a data series into n-length groups using `zip(*[iter(s)]*n)`. This repeats the *same* iterator `n` times so that each output tuple has the result of `n` calls to the iterator. This has the effect of dividing the input into `n`-length chunks.

[`zip()`](https://docs.python.org/3/library/functions.html#zip) should only be used with unequal length inputs when you don't care about trailing, unmatched values from the longer iterables. If those values are important, use [`itertools.zip_longest()`](https://docs.python.org/3/library/itertools.html#itertools.zip_longest) instead.

[`zip()`](https://docs.python.org/3/library/functions.html#zip) in conjunction with the * operator can be used to unzip a list:

```
>>> x = [1, 2, 3]
>>> y = [4, 5, 6]
>>> zipped = zip(x, y)
>>> list(zipped)
[(1, 4), (2, 5), (3, 6)]
>>> x2, y2 = zip(*zip(x, y))
>>> x == list(x2) and y == list(y2)
True
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#__import__" target="_blank"><code>__import__(<em>name, globals=None, locals=None, fromlist=(), level=0</em>)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

**Note:** This is an advanced function that is not needed in everyday Python programming, unlike [`importlib.import_module()`](https://docs.python.org/3/library/importlib.html#importlib.import_module).

This function is invoked by the [`import`](https://docs.python.org/3/reference/simple_stmts.html#import) statement. It can be replaced (by importing the [`builtins`](https://docs.python.org/3/library/builtins.html#module-builtins) module and assigning to `builtins.__import__`) in order to change semantics of the `import` statement, but doing so is **strongly** discouraged as it is usually simpler to use import hooks (see [PEP 302](https://www.python.org/dev/peps/pep-0302/)) to attain the same goals and does not cause issues with code which assumes the default import implementation is in use. Direct use of [`__import__()`](https://docs.python.org/3/library/functions.html#__import__) is also discouraged in favor of [`importlib.import_module()`](https://docs.python.org/3/library/importlib.html#importlib.import_module).

The function imports the module `name`, potentially using the given `globals` and `locals` to determine how to interpret the name in a package context. The `fromlist` gives the names of objects or submodules that should be imported from the module given by `name`. The standard implementation does not use its `locals` argument at all, and uses its `globals` only to determine the package context of the [`import`](https://docs.python.org/3/reference/simple_stmts.html#import) statement.

`level` specifies whether to use absolute or relative imports. `0` (the default) means only perform absolute imports. Positive values for `level` indicate the number of parent directories to search relative to the directory of the module calling [`__import__()`](https://docs.python.org/3/library/functions.html#__import__) (see [PEP 328](https://www.python.org/dev/peps/pep-0328/) for the details).

When the `name` variable is of the form `package.module`, normally, the top-level package (the name up till the first dot) is returned, *not* the module named by `name`. However, when a non-empty `fromlist` argument is given, the module named by `name` is returned.

For example, the statement `import spam` results in bytecode resembling the following code:

```python
spam = __import__('spam', globals(), locals(), [], 0)
```

The statement `import spam.ham` results in this call:

```python
spam = __import__('spam.ham', globals(), locals(), [], 0)
```

Note how [`__import__()`](https://docs.python.org/3/library/functions.html#__import__) returns the toplevel module here because this is the object that is bound to a name by the [`import`](https://docs.python.org/3/reference/simple_stmts.html#import) statement.

On the other hand, the statement `from spam.ham import eggs, sausage as saus` results in

```python
_temp = __import__('spam.ham', globals(), locals(), ['eggs', 'sausage'], 0)
eggs = _temp.eggs
saus = _temp.sausage
```

Here, the `spam.ham` module is returned from [`__import__()`](https://docs.python.org/3/library/functions.html#__import__). From this object, the names to import are retrieved and assigned to their respective names.

If you simply want to import a module (potentially within a package) by name, use [`importlib.import_module()`](https://docs.python.org/3/library/importlib.html#importlib.import_module).

*Changed in version 3.3:* Negative values for `level` are no longer supported (which also changes the default value to `0`).

*Changed in version 3.9:* When the command line options [`-E`](https://docs.python.org/3/using/cmdline.html#cmdoption-e) or [`-I`](https://docs.python.org/3/using/cmdline.html#id2) are being used, the environment variable [`PYTHONCASEOK`](https://docs.python.org/3/using/cmdline.html#envvar-PYTHONCASEOK) is now ignored.

---

</details>

---

</details>

### String Methods

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.capitalize" target="_blank"><code>capitalize()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string with its first character capitalized and the rest lowercased.

*Changed in version 3.8:* The first character is now put into titlecase rather than uppercase. This means that characters like digraphs will only have their first letter capitalized, instead of the full character.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.casefold" target="_blank"><code>casefold()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a casefolded copy of the string. Casefolded strings may be used for caseless matching.

Casefolding is similar to lowercasing but more aggressive because it is intended to remove all case distinctions in a string. For example, the German lowercase letter `'ß'` is equivalent to `"ss"`. Since it is already lowercase, [`lower()`](https://docs.python.org/3/library/stdtypes.html#str.lower) would do nothing to `'ß'`; [`casefold()`](https://docs.python.org/3/library/stdtypes.html#str.casefold) converts it to `"ss"`.

The casefolding algorithm is described in section 3.13 of the Unicode Standard.

*New in version 3.3.*

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.center" target="_blank"><code>center(width[, fillchar])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return centered in a string of length `width`. Padding is done using the specified `fillchar` (default is an ASCII space). The original string is returned if `width` is less than or equal to `len(s)`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.count" target="_blank"><code>count(sub[, start[, end]])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the number of non-overlapping occurrences of substring `sub` in the range [`start`, `end`]. Optional arguments `start` and `end` are interpreted as in slice notation.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.encode" target="_blank"><code>encode(encoding="utf-8", errors="strict")</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return an encoded version of the string as a bytes object. Default encoding is `'utf-8'`. `errors` may be given to set a different error handling scheme. The default for `errors` is `'strict'`, meaning that encoding errors raise a [`UnicodeError`](https://docs.python.org/3/library/exceptions.html#UnicodeError). Other possible values are `'ignore'`, `'replace'`, `'xmlcharrefreplace'`, `'backslashreplace'` and any other name registered via [`codecs.register_error()`](https://docs.python.org/3/library/codecs.html#codecs.register_error), see section [Error Handlers](https://docs.python.org/3/library/codecs.html#error-handlers). For a list of possible encodings, see section [Standard Encodings](https://docs.python.org/3/library/codecs.html#standard-encodings).

By default, the `errors` argument is not checked for best performances, but only used at the first encoding error. Enable the [Python Development Mode](https://docs.python.org/3/library/devmode.html#devmode), or use a debug build to check `errors`.

*Changed in version 3.1:* Support for keyword arguments added.

*Changed in version 3.9:* The `errors` is now checked in development mode and in debug mode.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.endswith" target="_blank"><code>endswith(suffix[, start[, end]])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if the string ends with the specified `suffix`, otherwise return `False`. `suffix` can also be a tuple of suffixes to look for. With optional `start`, test beginning at that position. With optional `end`, stop comparing at that position.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.expandtabs" target="_blank"><code>expandtabs(tabsize=8)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string where all tab characters are replaced by one or more spaces, depending on the current column and the given tab size. Tab positions occur every `tabsize` characters (default is `8`, giving tab positions at columns `0`, `8`, `16` and so on). To expand the string, the current column is set to zero and the string is examined character by character. If the character is a tab (`\t`), one or more space characters are inserted in the result until the current column is equal to the next tab position. (The tab character itself is not copied.) If the character is a newline (`\n`) or return (`\r`), it is copied and the current column is reset to zero. Any other character is copied unchanged and the current column is incremented by one regardless of how the character is represented when printed.

```
>>> '01\t012\t0123\t01234'.expandtabs()
'01      012     0123    01234'
>>> '01\t012\t0123\t01234'.expandtabs(4)
'01  012 0123    01234'
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.find" target="_blank"><code>find(sub[, start[, end]])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the lowest index in the string where substring `sub` is found within the slice `s[start:end]`. Optional arguments `start` and `end` are interpreted as in slice notation. Return `-1` if `sub` is not found.

**Note:** The `find()` method should be used only if you need to know the position of `sub`. To check if `sub` is a substring or not, use the [`in`](https://docs.python.org/3/reference/expressions.html#in) operator:

```python
>>> 'Py' in 'Python'
True
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.format" target="_blank"><code>format(*args, **kwargs)</code></a></strong></summary>

<details open><summary> Syntax details for formatting expressions (using <code>%</code>) as well as the explicit <code>format</code> method</summary>

- **Formatting expression syntax:**

  ```
  %[(keyname)][flags][width][.prec]typecode
  ```

- **String formatting method syntax:** Substitution targets in strings used for format method calls take the following general form, all four parts of which are optional, and must appear without intervening spaces (used here for clarity):

  ```
  {fieldname component !conversionflag :formatspec}
  ```

  The nested formatspec component after the colon character has a syntax of its own, formally described as follows (brackets in this denote optional components and are not coded literally):

  ```
  [[fill]align][sign][#][0][width][,][.prec][typecode]
  ```

- **f-strings:** See the Python docs for more about [formatted string literals](https://docs.python.org/3/tutorial/inputoutput.html#formatted-string-literals) or so-called "f-strings" for short. [Here](https://docs.python.org/3/reference/lexical_analysis.html#f-strings) is a more detailed reference.

---

</details>

**Description:** Formats the given string. The syntax for the `format()` string method is

``` Python
template.format(p0, p1, ..., k0=v0, k1=v1, ...)
```

where `p0, p1, ...` are *positional* arguments, `k0, k1, ...` are *keyword* arguments (with values `v0, v1, ...`, respectively), and `template` is a string comprised of a mixture of format codes with placeholders for the arguments.

**Parameters:** The `format()` method will take any number of parameters, but the *type* of parameters provided matters:

- *Positional parameters*: List of parameters that can be accessed with index of parameter inside curly braces `{index}`. (Or the `index` can be omitted entirely and empty braces `{}` in the template will be substituted for by the *order* of the positional arguments supplied to `format()`.)
- *Keyword parameters*: List of parameters of type `key=value`, that can be accessed with key of parameter inside curly braces `{key}`.

**Formatting method syntax:** The following details are adapted from [[2]](#2). Substitution targets in strings used for format method calls take the following general form, all four parts of which are optional, and must appear without intervening spaces (used here for clarity):

```
{fieldname component !conversionflag :formatspec}
```

In this substitution target syntax:

- `fieldname`

  An optional number or keyword identifying an argument, which may be omitted to use relative argument numbering in 2.7, 3.1, and later.

- `component`

  A string of zero or more `.name` or `[index]` references used to fetch attributes and indexed values of the argument, which may be omitted to use the whole argument value.

- `conversionflag`

  Introduced by a `!` if present, which is followed by `r`, `s`, or `a` to call `repr()`, `str()`, or `ascii()` built-in functions on the value, respectively.

- `formatspec`

  Introduced by a `:` if present, and consists of text that specifies how the value should be presented, including details such as field width, alignment, padding, decimal precision, and so on, and ending with an optional datatype code.

The nested `formatspec` component after the colon character has a syntax of its own, formally described as follows (brackets in this denote optional components and are not coded literally):

```
[[fill]align][sign][#][0][width][,][.prec][typecode]
```

In this `formatspec` nested syntax:

- `fill`
  
  Can be any fill character other than `{` or `}`.

- `align`

  May be `<`, `>`, `=`, or `^`, for left alignment, right alignment, padding after a sign character, or centered alignment, respectively. 

- `sign`

  May be `+`, `−`, or space.

- `,` (comma)

  Requests a comma for a thousands separator as of Python 3.1 and 2.7.

`width` and `prec`

  Much as in the `%` expression (i.e., `width` for total minimum field width where `*` can be used to fetch from values and `prec` for the number of digits or precision to include after the decimal point `.` where `*` can be used to fetch from values), and the `formatspec` may also contain nested `{}` format strings having a `fieldname` only, to take values from the arguments list dynamically (much like the `*` in formatting expressions). A `0` preceding `width` enables sign-aware zero padding (similar to `fill`), and a `#` enables an alternative conversion (if available).

`typecode`

  Largely the same as in `%` expressions (type codes provided in table below), but the format method has an extra `b` type code used to give integers in binary format (much like using the `bin` built-in); has an extra `%` type code to format percentages as of Python 3.1 and 2.7; and uses only `d` for base-10 integers (`i` or `u` are not used).

Note that unlike the expression's generic `%s`, the method's `s` type code requires a *string* object argument; omit the type code to accept any type generically in the method.

**Format type codes for formatting numbers:** You can format numbers using the format specifier given below:

| Type | Meaning |
| --: | :-- |
| `d` | Displays `int` as a decimal integer |
| `f` | Displays `float` as a fixed point number (Default: `6`) |
| `F` | Same as `'f'`. Except displays `'inf'` as `'INF'` and `'nan'` as `'NAN'` |
| `g` | General format. Rounds number to `p` significant digits. (Default precision: `6`) |
| `G` | Same as `'g'`. Except switches to `'E'` if the number is large. |
| `%` | Percentage. Multiples by `100` and puts `%` at the end. |
| `s` | String format. This is the default type for strings and may be omitted. |
| `c` | Corresponding Unicode character |
| `b` | Binary format |
| `o` | Octal format |
| `x` | Hexadecimal format (lower case) |
| `X` | Hexadecimal format (upper case) |
| `n` | Same as `'d'`. Except it uses current locale setting for number separator |
| `e` | Exponential notation. (lowercase `e`) |
| `E` | Exponential notation (uppercase `E`) |

**Format type codes for formatting numbers with alignment:** The operators `<`, `^`, `>` and `=` are used for alignment when assigned a certain width to the numbers.

| Type | Meaning |
| --: | :-- |
| `<` | Left aligned to the remaining space |
| `^` | Center aligned to the remaining space |
| `>` | Right aligned to the remaining space |
| `=` | Forces the signed (`+`) (`-`) to the leftmost position |

**Examples:** The `format()` string method reads the types of arguments passed to `format` and formats the template string according to the format codes used within the template string. The return value is the formatted string.

<details><summary> Ex 0a: Documentation</summary>

Perform a string formatting operation. The string on which this method is called can contain literal text or replacement fields delimited by braces `{}`. Each replacement field contains either the numeric index of a positional argument, or the name of a keyword argument. Returns a copy of the string where each replacement field is replaced with the string value of the corresponding argument.

```
>>> "The sum of 1 + 2 is {0}".format(1+2)
'The sum of 1 + 2 is 3'
```

See [Format String Syntax](https://docs.python.org/3/library/string.html#formatstrings) for a description of the various formatting options that can be specified in format strings.

**Note:** When formatting a number ([`int`](https://docs.python.org/3/library/functions.html#int), [`float`](https://docs.python.org/3/library/functions.html#float), [`complex`](https://docs.python.org/3/library/functions.html#complex), [`decimal.Decimal`](https://docs.python.org/3/library/decimal.html#decimal.Decimal) and subclasses) with the `n` type (ex: `'{:n}'.format(1234)`), the function temporarily sets the `LC_CTYPE` locale to the `LC_NUMERIC` locale to decode `decimal_point` and `thousands_sep` fields of `localeconv()` if they are non-ASCII or longer than 1 byte, and the `LC_NUMERIC` locale is different than the `LC_CTYPE` locale. This temporary change affects other threads.

*Changed in version 3.7:* When formatting a number with the `n` type, the function sets temporarily the `LC_CTYPE` locale to the `LC_NUMERIC` locale in some cases.

---

</details>

<details><summary> Ex 0b: Examples from the official docs</summary>

Accessing arguments by position:

``` Python
>>> '{0}, {1}, {2}'.format('a', 'b', 'c')
'a, b, c'
>>> '{}, {}, {}'.format('a', 'b', 'c')  # 3.1+ only
'a, b, c'
>>> '{2}, {1}, {0}'.format('a', 'b', 'c')
'c, b, a'
>>> '{2}, {1}, {0}'.format(*'abc')      # unpacking argument sequence
'c, b, a'
>>> '{0}{1}{0}'.format('abra', 'cad')   # arguments' indices can be repeated
'abracadabra'
```

Accessing arguments by name:

``` Python
>>> 'Coordinates: {latitude}, {longitude}'.format(latitude='37.24N', longitude='-115.81W')
'Coordinates: 37.24N, -115.81W'
>>> coord = {'latitude': '37.24N', 'longitude': '-115.81W'}
>>> 'Coordinates: {latitude}, {longitude}'.format(**coord)
'Coordinates: 37.24N, -115.81W'
```

Accessing arguments' attributes:

``` Python
>>> c = 3-5j
>>> ('The complex number {0} is formed from the real part {0.real} '
...  'and the imaginary part {0.imag}.').format(c)
'The complex number (3-5j) is formed from the real part 3.0 and the imaginary part -5.0.'
>>> class Point:
...     def __init__(self, x, y):
...         self.x, self.y = x, y
...     def __str__(self):
...         return 'Point({self.x}, {self.y})'.format(self=self)
...
>>> str(Point(4, 2))
'Point(4, 2)'
```

Accessing arguments' items:

``` Python
>>> coord = (3, 5)
>>> 'X: {0[0]};  Y: {0[1]}'.format(coord)
'X: 3;  Y: 5'
```

Replacing `%s` and `%r`:

``` Python
>>> "repr() shows quotes: {!r}; str() doesn't: {!s}".format('test1', 'test2')
"repr() shows quotes: 'test1'; str() doesn't: test2"
```

Aligning the text and specifying a width:

``` Python
>>> '{:<30}'.format('left aligned')
'left aligned                  '
>>> '{:>30}'.format('right aligned')
'                 right aligned'
>>> '{:^30}'.format('centered')
'           centered           '
>>> '{:*^30}'.format('centered')  # use '*' as a fill char
'***********centered***********'
```

Replacing `%+f`, `%-f`, and `% f` and specifying a sign:

``` Python
>>> '{:+f}; {:+f}'.format(3.14, -3.14)  # show it always
'+3.140000; -3.140000'
>>> '{: f}; {: f}'.format(3.14, -3.14)  # show a space for positive numbers
' 3.140000; -3.140000'
>>> '{:-f}; {:-f}'.format(3.14, -3.14)  # show only the minus -- same as '{:f}; {:f}'
'3.140000; -3.140000'
```

Replacing `%x` and `%o` and converting the value to different bases:

``` Python
>>> # format also supports binary numbers
>>> "int: {0:d};  hex: {0:x};  oct: {0:o};  bin: {0:b}".format(42)
'int: 42;  hex: 2a;  oct: 52;  bin: 101010'
>>> # with 0x, 0o, or 0b as prefix:
>>> "int: {0:d};  hex: {0:#x};  oct: {0:#o};  bin: {0:#b}".format(42)
'int: 42;  hex: 0x2a;  oct: 0o52;  bin: 0b101010'
```

Using the comma as a thousands separator:

``` Python
>>> '{:,}'.format(1234567890)
'1,234,567,890'
```

Expressing a percentage:

``` Python
>>> points = 19
>>> total = 22
>>> 'Correct answers: {:.2%}'.format(points/total)
'Correct answers: 86.36%'
```

Using type-specific formatting:

``` Python
>>> import datetime
>>> d = datetime.datetime(2010, 7, 4, 12, 15, 58)
>>> '{:%Y-%m-%d %H:%M:%S}'.format(d)
'2010-07-04 12:15:58'
```

Nesting arguments and more complex examples:

``` Python
>>> for align, text in zip('<^>', ['left', 'center', 'right']):
...     '{0:{fill}{align}16}'.format(text, fill=align, align=align)
...
'left<<<<<<<<<<<<'
'^^^^^center^^^^^'
'>>>>>>>>>>>right'
>>>
>>> octets = [192, 168, 0, 1]
>>> '{:02X}{:02X}{:02X}{:02X}'.format(*octets)
'C0A80001'
>>> int(_, 16)
3232235521
>>>
>>> width = 5
>>> for num in range(5,12): 
...     for base in 'dXob':
...         print('{0:{width}{base}}'.format(num, base=base, width=width), end=' ')
...     print()
...
    5     5     5   101
    6     6     6   110
    7     7     7   111
    8     8    10  1000
    9     9    11  1001
   10     A    12  1010
   11     B    13  1011
```

---

</details>

<details><summary> Ex 1: Basic use of <code>format</code> with positional arguments</summary>

Illustrated usage of `format` with basic positional arguments:

<p align='center'>
  <img width='600px' src='https://user-images.githubusercontent.com/73953353/189053309-d30e061c-5548-46bc-9faa-632ab857a9ea.png' />
</p>

Here, `Argument 0` is the string `"Adam"` and `Argument 1` is the floating number `230.2346`. (Note that the argument list for `format` starts at `0`.) 

The string `"Hello {0}, your balance is {1:9.3f}"` is the template string. This contains the format codes for formatting. The curly braces are just placeholders for the arguments to be placed. In the above example, `{0}` is placeholder for `"Adam"` and `{1:9.3f}` is placeholder for `230.2346`. Since the template string references `format()` arguments as `{0}` and `{1}`, the arguments are positional arguments. They both can also be referenced without the numbers as `{}` and Python internally converts them to numbers. 

Internally, we have the following:

- Since `"Adam"` is the 0th argument, it is substituted in place of `{0}`. Since, `{0}` doesn't contain any other format codes, it doesn't perform any other operations.
- However, this is not the case for the 1st argument of `230.2346`. Here, `{1:9.3f}` places `230.2346` in its place and performs the operation `9.3f`.
- As noted in the format specifier table above, `f` specifies the format is dealing with a float number. If not correctly specified, an error will be raised.
- The numeral before `"."` (i.e., `9` in this case) specifies the minimum width/padding the number (`230.2346`) can take. In this case, `230.2346` is allotted a minimum of `9` places including the `"."`. If no alignment option is specified, the number is aligned to the right of the remaining spaces. (For strings, the string is aligned to the left.)
- The numeral after `"."` (i.e., `3` in this case) truncates the decimal part (i.e., `2346` in this case) up to the given number. Here, `2346` is truncated after 3 places. The remaining numeric portion, if it exists, is rounded (hence, the remaining portion of `46` here is rounded to `50` resulting in `2346` being truncated to `235`).

---

</details>

<details><summary> Ex 2: Basic use of <code>format</code> with keyword arguments </summary>

<p align='center'>
  <img width='575px' src='https://user-images.githubusercontent.com/73953353/189053306-26b6c235-30df-4cc5-9466-4b62fcdb2976.png' />
</p>

We've used the same example from before to show the difference between keyword and positional arguments. Here, instead of just the parameters, we've used key-value pairings for the parameters. Namely, `name="Adam"` and `blc=230.2346`. Since these parameters are referenced by their keys as `{name}` and `{blc:9.3f}`, they are known as keyword or named arguments.

Internally,

- The placeholder `{name}` is replaced by the value of name - `"Adam"`. Since it doesn't contain any other format codes, `"Adam"` is placed.
- For the argument `blc=230.2346`, the placeholder `{blc:9.3f}` is replaced by the value `230.2346`. But before replacing it, like previous example, it performs `9.3f` operation on it. This outputs `  230.235`. The decimal part is truncated after `3` places and remaining digits are rounded off. Likewise, the total width is assigned 9 leaving two spaces to the left.

---

</details>

<details><summary> Ex 3: Basic formatting for default, positional and keyword arguments</summary>

``` Python
# default arguments
print("Hello {}, your balance is {}.".format("Adam", 230.2346))

# positional arguments
print("Hello {0}, your balance is {1}.".format("Adam", 230.2346))

# keyword arguments
print("Hello {name}, your balance is {blc}.".format(name="Adam", blc=230.2346))

# mixed arguments
print("Hello {0}, your balance is {blc}.".format("Adam", blc=230.2346))
```

**Output:**

```
Hello Adam, your balance is 230.2346.
Hello Adam, your balance is 230.2346.
Hello Adam, your balance is 230.2346.
Hello Adam, your balance is 230.2346.
```

Note that when arguments are *mixed* (i.e., positional as well as keyword arguments are provided) the keyword arguments must always follow the positional arguments.

---

</details>

<details><summary> Ex 4: Simple number formatter (integer, float, octal, binary, and hexadecimal)</summary>

``` Python
# integer arguments
print("The number is: {:d}".format(123))

# float arguments
print("The float number is: {:f}".format(123.4567898))

# octal, binary and hexadecimal format
print("bin: {0:b}, oct: {0:o}, hex: {0:x}".format(12))
```

**Output:**

```
The number is: 123
The float number is: 123.456790
bin: 1100, oct: 14, hex: c
```

---

</details>

<details><summary> Ex 5: Number formatting with padding for ints and floats</summary>

``` Python
# integer numbers with minimum width
print("{:5d}".format(12))

# width doesn't work for numbers longer than padding
print("{:2d}".format(1234))

# padding for float numbers
print("{:8.3f}".format(12.2346))

# integer numbers with minimum width filled with zeros
print("{:05d}".format(12))

# padding for float numbers filled with zeros
print("{:08.3f}".format(12.2346))
```

**Output:**

```
   12
1234
  12.235
00012
0012.235
```

**Notes:**

- In the first statement, `{:5d}` takes an integer argument and assigns a minimum width of `5`. Since, no alignment is specified, the number is aligned to the right (recall that numbers are aligned to the right by default while strings are aligned to the left by default).
- In the second statement, we can see the minimum width (i.e., `2`) is less than the width of the provided number (i.e., `1234`), so space is not impacted and the number is not truncated.
- Unlike integers, floats have both integer and decimal parts. The mininum width, if provided, applies to both integer and decimal parts as a whole including `.`. Hence, once `12.2346` is rounded to three decimal places for precision, we get `12.235`, which has a width of `6`. Since the minimum specified is `8`, we end up with the following (note the two empty spaces at the beginning and the default right alignment): `  12.235`
- If specifying a minimum width leaves unoccupied space, then you can optionally fill that space with zeroes by placing a zero before the format specifier. This will work for both integers and floats: `{:05d}` and `{:08.3f}`.

---

</details>

<details><summary> Ex 6: Number formatting for signed numbers</summary>

``` Python
# show the + sign
print("{:+f} {:+f}".format(12.23, -12.23))

# show the - sign only
print("{:-f} {:-f}".format(12.23, -12.23))

# show space for + sign
print("{: f} {: f}".format(12.23, -12.23))
```

**Output:**

```
+12.230000 -12.230000
12.230000 -12.230000
 12.230000 -12.230000
```

---

</details>

<details><summary> Ex 7: Number formatting with left, right, and center alignment</summary>

``` Python
# integer numbers with right alignment (default)
print("{:5d}".format(12))

# float numbers with center alignment
print("{:^10.3f}".format(12.2346))

# integer left alignment filled with zeros
print("{:<05d}".format(12))

# float numbers with center alignment
print("{:=8.3f}".format(-12.2346))
```

**Output:**

```
   12
  12.235  
12000
- 12.235
```

**Note:** Left alignment filled with zeros for integer numbers can cause problems as the 3rd example which returns `12000`, rather than `12`.

---

</details>

<details><summary> Ex 8: String formatting with padding and alignment</summary>

``` Python
# string padding with left alignment
print("{:5}".format("cat"))

# string padding with right alignment
print("{:>5}".format("cat"))

# string padding with center alignment
print("{:^5}".format("cat"))

# string padding with center alignment
# and '*' padding character
print("{:*^5}".format("cat"))
```

**Output:**

```
cat  
  cat
 cat 
*cat*
```

---

</details>

<details><summary> Ex 9: Truncating strings</summary>

``` Python
# truncating strings to 3 letters
print("{:.3}".format("caterpillar"))

# truncating strings to 3 letters
# and padding
print("{:5.3}".format("caterpillar"))

# truncating strings to 3 letters,
# padding and center alignment
print("{:^5.3}".format("caterpillar"))
```

**Output:**

```
cat
cat  
 cat 
```

---

</details>

<details><summary> Ex 10: Formatting class members</summary>

``` Python
# define Person class
class Person:
    age = 23
    name = "Adam"

# format age
print("{p.name}'s age is: {p.age}".format(p=Person()))
```

**Output:**

```
Adam's age is: 23
```

Here, the `Person` object is passed as a keyword argument `p`. Inside the template string, `Person`'s `name` and `age` attributes are accessed using `.name` and `.age` respectively.

---

</details>

<details><summary> Ex 11: Formatting dictionary members</summary>

``` Python
# define Person dictionary
person = {'age': 23, 'name': 'Adam'}

# format age
print("{p[name]}'s age is: {p[age]}".format(p=person))
```

**Output:**

```
Adam's age is: 23
```

The `person` dictionary is passed as a keyword argument `p`, and the behavior exhibited here is similar to that exhibited by classes. Inside the template string, `person`'s `name` and `age` values are accessed using `[name]` and `[age]` respectively.

---

</details>

<details><summary> Ex 12: Arguments as format codes</summary>

You can pass format codes like `precision`, `alignment`, `fill` character as positional or keyword arguments dynamically:

``` Python
# dynamic string format template
string = "{:{fill}{align}{width}}"

# passing format codes as arguments
print(string.format('cat', fill='*', align='^', width=5))

# dynamic float format template
num = "{:{align}{width}.{precision}f}"

# passing format codes as arguments
print(num.format(123.236, align='<', width=8, precision=2))
```

**Output:**

```
*cat*
123.24  
```

**Notes:**

- In the first example, `'cat'` is the positional argument is to be formatted. Likewise, `fill='*'`, `align='^'`, and `width=5` are keyword arguments.
- In the template string, these keyword arguments are not retrieved as normal strings to be printed but as the actual format codes `fill`, `align`, and `width`. The arguments replace the corresponding named placeholders and the string `'cat'` is formatted accordingly.
- Likewise, in the second example, `123.236` is the positional argument and, align, width and precision are passed to the template string as format codes.

---

</details>

<details><summary> Ex 13: Type-specific formatting (datetime and complex numbers)</summary>

`format()` also supports type-specific formatting options like `datetime` (see [here](https://docs.python.org/3/library/datetime.html#strftime-and-strptime-format-codes) for more about formatting codes for datetime) and `complex` number formatting. `format()` internally calls `__format__()` for datetime, while `format()` accesses the attributes of the complex number. You can easily override the `__format__()` method of any object for custom formatting.

``` Python
import datetime
# datetime formatting
date = datetime.datetime.now()
print("It's now: {:%Y/%m/%d %H:%M:%S}".format(date))

# complex number formatting
complexNumber = 1+2j
print("Real part: {0.real} and Imaginary part: {0.imag}".format(complexNumber))

# custom __format__() method
class Person:
    def __format__(self, format):
        if(format == 'age'):
            return '23'
        return 'None'

print("Adam's age is: {:age}".format(Person()))
```

**Output:**

```
It's now: 2021/05/31 18:13:06
Real part: 1.0 and Imaginary part: 2.0
Adam's age is: 23
```

**Notes:** 

- For datetime: Current datetime is passed as a positional argument to the `format()` method. And, internally using `__format__()` method, `format()` accesses the year, month, day, hour, minutes and seconds. (See [this post](https://stackoverflow.com/a/2073189/5209533) for how to remove undesired leading zeroes; TLDR: use a dash after `%` like `%Y/%-m/%-d` to remove leading zeroes for the month and day.)
- For complex numbers: `1+2j` is internally converted to a `ComplexNumber` object. Then accessing its attributes `real` and `imag`, the number is formatted.
- Overriding `__format__()`: Like datetime, you can override your own `__format__()` method for custom formatting which returns age when accessed as `{:age}`

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.format_map" target="_blank"><code>format_map(mapping)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Similar to `str.format(**mapping)`, except that `mapping` is used directly and not copied to a [`dict`](https://docs.python.org/3/library/stdtypes.html#dict). This is useful if for example `mapping` is a dict subclass:


```
>>> class Default(dict):
...    def __missing__(self, key):
...        return key
...
>>> '{name} was born in {country}'.format_map(Default(name='Guido'))
'Guido was born in country'
```

*New in version 3.2.*

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.index" target="_blank"><code>index(sub[, start[, end]])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Like [`find()`](https://docs.python.org/3/library/stdtypes.html#str.find), but raise [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) when the substring is not found.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isalnum" target="_blank"><code>isalnum()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if all characters in the string are alphanumeric and there is at least one character, `False` otherwise. A character `c` is alphanumeric if one of the following returns `True`: `c.isalpha()`, `c.isdecimal()`, `c.isdigit()`, or `c.isnumeric()`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isalpha" target="_blank"><code>isalpha()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if all characters in the string are alphabetic and there is at least one character, `False` otherwise. Alphabetic characters are those characters defined in the Unicode character database as "Letter", i.e., those with general category property being one of "Lm", "Lt", "Lu", "Ll", or "Lo". Note that this is different from the "Alphabetic" property defined in the Unicode Standard.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isascii" target="_blank"><code>isascii()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if the string is empty or all characters in the string are ASCII, `False` otherwise. ASCII characters have code points in the range U+0000-U+007F.

*New in version 3.7.*

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isdecimal" target="_blank"><code>isdecimal()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if all characters in the string are decimal characters and there is at least one character, `False` otherwise. Decimal characters are those that can be used to form numbers in base 10, e.g. U+0660, ARABIC-INDIC DIGIT ZERO. Formally a decimal character is a character in the Unicode General Category “Nd”.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isdigit" target="_blank"><code>isdigit()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if all characters in the string are digits and there is at least one character, `False` otherwise. Digits include decimal characters and digits that need special handling, such as the compatibility superscript digits. This covers digits which cannot be used to form numbers in base 10, like the Kharosthi numbers. Formally, a digit is a character that has the property value `Numeric_Type=Digit` or `Numeric_Type=Decimal`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isidentifier" target="_blank"><code>isidentifier()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if the string is a valid identifier according to the language definition, section [Identifiers and keywords](https://docs.python.org/3/reference/lexical_analysis.html#identifiers).

Call [`keyword.iskeyword()`](https://docs.python.org/3/library/keyword.html#keyword.iskeyword) to test whether string `s` is a reserved identifier, such as [`def`](https://docs.python.org/3/reference/compound_stmts.html#def) and [`class`](https://docs.python.org/3/reference/compound_stmts.html#class).

Example:

```
>>> from keyword import iskeyword

>>> 'hello'.isidentifier(), iskeyword('hello')
True, False
>>> 'def'.isidentifier(), iskeyword('def')
True, True
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.islower" target="_blank"><code>islower()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if all cased characters in the string are lowercase and there is at least one cased character, `False` otherwise.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isnumeric" target="_blank"><code>isnumeric()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if all characters in the string are numeric characters, and there is at least one character, `False` otherwise. Numeric characters include digit characters, and all characters that have the Unicode numeric value property, e.g. U+2155, VULGAR FRACTION ONE FIFTH. Formally, numeric characters are those with the property value `Numeric_Type=Digit`, `Numeric_Type=Decimal` or `Numeric_Type=Numeric`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isprintable" target="_blank"><code>isprintable()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if all characters in the string are printable or the string is empty, `False` otherwise. Nonprintable characters are those characters defined in the Unicode character database as “Other” or “Separator”, excepting the ASCII space (0x20) which is considered printable. (Note that printable characters in this context are those which should not be escaped when [`repr()`](https://docs.python.org/3/library/functions.html#repr) is invoked on a string. It has no bearing on the handling of strings written to [`sys.stdout`](https://docs.python.org/3/library/sys.html#sys.stdout) or [`sys.stderr`](https://docs.python.org/3/library/sys.html#sys.stderr).)

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isspace" target="_blank"><code>isspace()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if there are only whitespace characters in the string and there is at least one character, `False` otherwise.

A character is *whitespace* if in the Unicode character database (see [`unicodedata`](https://docs.python.org/3/library/unicodedata.html#module-unicodedata)), either its general category is `Zs` (“Separator, space”), or its bidirectional class is one of `WS`, `B`, or `S`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.istitle" target="_blank"><code>istitle()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if the string is a titlecased string and there is at least one character, for example uppercase characters may only follow uncased characters and lowercase characters only cased ones. Return `False` otherwise.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.isupper" target="_blank"><code>isupper()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if all cased characters in the string are uppercase and there is at least one cased character, `False` otherwise.

```
>>> 'BANANA'.isupper()
True
>>> 'banana'.isupper()
False
>>> 'baNana'.isupper()
False
>>> ' '.isupper()
False
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.join" target="_blank"><code>join(iterable)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a string which is the concatenation of the strings in `iterable`. A [`TypeError`](https://docs.python.org/3/library/exceptions.html#TypeError) will be raised if there are any non-string values in `iterable`, including [`bytes`](https://docs.python.org/3/library/stdtypes.html#bytes) objects. The separator between elements is the string providing this method.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.ljust" target="_blank"><code>ljust(width[, fillchar])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the string left justified in a string of length `width`. Padding is done using the specified `fillchar` (default is an ASCII space). The original string is returned if `width` is less than or equal to `len(s)`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.lower" target="_blank"><code>lower()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string with all the cased characters converted to lowercase.

The lowercasing algorithm used is described in section 3.13 of the Unicode Standard.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.lstrip" target="_blank"><code>lstrip([chars])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string with leading characters removed. The `chars` argument is a string specifying the set of characters to be removed. If omitted or `None`, the `chars` argument defaults to removing whitespace. The `chars` argument is not a prefix; rather, all combinations of its values are stripped:

```
>>> '   spacious   '.lstrip()
'spacious   '
>>> 'www.example.com'.lstrip('cmowz.')
'example.com'
```

See [`str.removeprefix()`](https://docs.python.org/3/library/stdtypes.html#str.removeprefix) for a method that will remove a single prefix string rather than all of a set of characters. For example:

```
>>> 'Arthur: three!'.lstrip('Arthur: ')
'ee!'
>>> 'Arthur: three!'.removeprefix('Arthur: ')
'three!'
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.maketrans" target="_blank"><code>maketrans(x[, y[, z]])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

This static method returns a translation table usable for [`str.translate()`](https://docs.python.org/3/library/stdtypes.html#str.translate).

If there is only one argument, it must be a dictionary mapping Unicode ordinals (integers) or characters (strings of length 1) to Unicode ordinals, strings (of arbitrary lengths) or `None`. Character keys will then be converted to ordinals.

If there are two arguments, they must be strings of equal length, and in the resulting dictionary, each character in `x` will be mapped to the character at the same position in `y`. If there is a third argument, it must be a string, whose characters will be mapped to `None` in the result.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.partition" target="_blank"><code>partition(sep)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Split the string at the first occurrence of `sep`, and return a 3-tuple containing the part before the separator, the separator itself, and the part after the separator. If the separator is not found, return a 3-tuple containing the string itself, followed by two empty strings.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.removeprefix" target="_blank"><code>removeprefix(prefix, /)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

If the string starts with the prefix string, return string[len(prefix):]. Otherwise, return a copy of the original string:

```
>>> 'TestHook'.removeprefix('Test')
'Hook'
>>> 'BaseTestCase'.removeprefix('Test')
'BaseTestCase'
```

*New in version 3.9.*

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.removesuffix" target="_blank"><code>removesuffix(suffix, /)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

If the string ends with the `suffix` string and that `suffix` is not empty, return `string[:-len(suffix)]`. Otherwise, return a copy of the original string:

```
>>> 'MiscTests'.removesuffix('Tests')
'Misc'
>>> 'TmpDirMixin'.removesuffix('Tests')
'TmpDirMixin'
```

*New in version 3.9.*

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.replace" target="_blank"><code>replace(old, new[, count])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string with all occurrences of substring `old` replaced by `new`. If the optional argument `count` is given, only the first `count` occurrences are replaced.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.rfind" target="_blank"><code>rfind(sub[, start[, end]])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the highest index in the string where substring `sub` is found, such that `sub` is contained within `s[start:end]`. Optional arguments `start` and `end` are interpreted as in slice notation. Return `-1` on failure.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.rindex" target="_blank"><code>rindex(sub[, start[, end]])</code></a></strong></summary>

**Description:** Recall how [`rfind(sub[, start[, end]])`](https://docs.python.org/3/library/stdtypes.html#str.rfind) works:

> Return the highest index in the string where substring `sub` is found, such that `sub` is contained within `s[start:end]`. Optional arguments `start` and `end` are interpreted as in slice notation. Return `-1` on failure.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Like [`rfind()`](https://docs.python.org/3/library/stdtypes.html#str.rfind) but raises [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) when the substring `sub` is not found.

---

</details>

<details><summary> Ex 1: Finding the length of a string without using <code>len</code></summary>

A good example of use for `rindex` is finding the length of a string without using `len` (see [this Stack Overflow answer](https://stackoverflow.com/a/3993450/5209533) for reference):

``` Python
def strlen(s):
    if s == "": return 0
    return s.rindex(s[-1]) + 1
```

In other words, it doesn't work by counting the characters, so it should be just as fast for a 1GB string as it is for a 1 byte string.

It works by looking at the last character and searching from the very end to find that character. Since it's the last character it will always find it at the first place it looks, essentially always returning the index of the last character. The length is just one more than the index of the last character.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.rjust" target="_blank"><code>rjust(width[, fillchar])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the string right justified in a string of length `width`. Padding is done using the specified `fillchar` (default is an ASCII space). The original string is returned if `width` is less than or equal to `len(s)`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.rpartition" target="_blank"><code>rpartition(sep)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Split the string at the last occurrence of `sep`, and return a 3-tuple containing the part before the separator, the separator itself, and the part after the separator. If the separator is not found, return a 3-tuple containing two empty strings, followed by the string itself.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.rsplit" target="_blank"><code>rsplit(sep=None, maxsplit=-1)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a list of the words in the string, using `sep` as the delimiter string. If `maxsplit` is given, at most `maxsplit` splits are done, the *rightmost* ones. If `sep` is not specified or `None`, any whitespace string is a separator. Except for splitting from the right, [`rsplit()`](https://docs.python.org/3/library/stdtypes.html#str.rsplit) behaves like [`split()`](https://docs.python.org/3/library/stdtypes.html#str.split) which is described in detail below.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.rstrip" target="_blank"><code>rstrip([chars])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string with trailing characters removed. The `chars` argument is a string specifying the set of characters to be removed. If omitted or `None`, the `chars` argument defaults to removing whitespace. The `chars` argument is not a suffix; rather, all combinations of its values are stripped:

```
>>> '   spacious   '.rstrip()
'   spacious'
>>> 'mississippi'.rstrip('ipz')
'mississ'
```

See [`str.removesuffix()`](https://docs.python.org/3/library/stdtypes.html#str.removesuffix) for a method that will remove a single suffix string rather than all of a set of characters. For example:

```
>>> 'Monty Python'.rstrip(' Python')
'M'
>>> 'Monty Python'.removesuffix(' Python')
'Monty'
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.split" target="_blank"><code>split(sep=None, maxsplit=-1)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a list of the words in the string, using `sep` as the delimiter string. If `maxsplit` is given, at most `maxsplit` splits are done (thus, the list will have at most `maxsplit+1` elements). If `maxsplit` is not specified or `-1`, then there is no limit on the number of splits (all possible splits are made).

If `sep` is given, consecutive delimiters are not grouped together and are deemed to delimit empty strings (for example, `'1,,2'.split(',')` returns `['1', '', '2']`). The `sep` argument may consist of multiple characters (for example, `'1<>2<>3'.split('<>')` returns `['1', '2', '3']`). Splitting an empty string with a specified separator returns `['']`.

For example:

```
>>> '1,2,3'.split(',')
['1', '2', '3']
>>> '1,2,3'.split(',', maxsplit=1)
['1', '2,3']
>>> '1,2,,3,'.split(',')
['1', '2', '', '3', '']
```

If `sep` is not specified or is `None`, a different splitting algorithm is applied: runs of consecutive whitespace are regarded as a single separator, and the result will contain no empty strings at the start or end if the string has leading or trailing whitespace. Consequently, splitting an empty string or a string consisting of just whitespace with a `None` separator returns `[]`.

For example:

```
>>> '1 2 3'.split()
['1', '2', '3']
>>> '1 2 3'.split(maxsplit=1)
['1', '2 3']
>>> '   1   2   3   '.split()
['1', '2', '3']
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.splitlines" target="_blank"><code>splitlines([keepends])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a list of the lines in the string, breaking at line boundaries. Line breaks are not included in the resulting list unless `keepends` is given and true.

This method splits on the following line boundaries. In particular, the boundaries are a superset of [universal newlines](https://docs.python.org/3/glossary.html#term-universal-newlines).

| Representation | Description |
| :-- | :-- |
| `\n` | Line Feed |
| `\r` | Carriage Return |
| `\r\n` | Carriage Return + Line Feed |
| `\v or \x0b` | Line Tabulation |
| `\f or \x0c` | Form Feed |
| `\x1c` | File Separator |
| `\x1d` | Group Separator |
| `\x1e` | Record Separator |
| `\x85` | Next Line (C1 Control Code) |
| `\u2028` | Line Separator |
| `\u2029` | Paragraph Separator |

*Changed in version 3.2:* `\v` and `\f` added to list of line boundaries.

For example:

```
>>> 'ab c\n\nde fg\rkl\r\n'.splitlines()
['ab c', '', 'de fg', 'kl']
>>> 'ab c\n\nde fg\rkl\r\n'.splitlines(keepends=True)
['ab c\n', '\n', 'de fg\r', 'kl\r\n']
```

Unlike [`split()`](https://docs.python.org/3/library/stdtypes.html#str.split) when a delimiter string `sep` is given, this method returns an empty list for the empty string, and a terminal line break does not result in an extra line:

```
>>> "".splitlines()
[]
>>> "One line\n".splitlines()
['One line']
```

For comparison, `split('\n')` gives:

```
>>> ''.split('\n')
['']
>>> 'Two lines\n'.split('\n')
['Two lines', '']
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.startswith" target="_blank"><code>startswith(prefix[, start[, end]])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if string starts with the `prefix`, otherwise return `False`. `prefix` can also be a tuple of prefixes to look for. With optional `start`, test string beginning at that position. With optional `end`, stop comparing string at that position.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.strip" target="_blank"><code>strip([chars])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string with the leading and trailing characters removed. The `chars` argument is a string specifying the set of characters to be removed. If omitted or `None`, the `chars` argument defaults to removing whitespace. The `chars` argument is not a prefix or suffix; rather, all combinations of its values are stripped:

```
>>> '   spacious   '.strip()
'spacious'
>>> 'www.example.com'.strip('cmowz.')
'example'
```

The outermost leading and trailing `chars` argument values are stripped from the string. Characters are removed from the leading end until reaching a string character that is not contained in the set of characters in `chars`. A similar action takes place on the trailing end. For example:

```
>>> comment_string = '#....... Section 3.2.1 Issue #32 .......'
>>> comment_string.strip('.#! ')
'Section 3.2.1 Issue #32'
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.swapcase" target="_blank"><code>swapcase()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string with uppercase characters converted to lowercase and vice versa. Note that it is not necessarily true that `s.swapcase().swapcase() == s`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.title" target="_blank"><code>title()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a titlecased version of the string where words start with an uppercase character and the remaining characters are lowercase.

For example:

```
>>> 'Hello world'.title()
'Hello World'
```

The algorithm uses a simple language-independent definition of a word as groups of consecutive letters. The definition works in many contexts but it means that apostrophes in contractions and possessives form word boundaries, which may not be the desired result:

```
>>> "they're bill's friends from the UK".title()
"They'Re Bill'S Friends From The Uk"
```

A workaround for apostrophes can be constructed using regular expressions:

```
>>> import re
>>> def titlecase(s):
...     return re.sub(r"[A-Za-z]+('[A-Za-z]+)?",
...                   lambda mo: mo.group(0).capitalize(),
...                   s)
...
>>> titlecase("they're bill's friends.")
"They're Bill's Friends."
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.translate" target="_blank"><code>translate(table)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string in which each character has been mapped through the given translation table. The table must be an object that implements indexing via [`__getitem__()`](https://docs.python.org/3/reference/datamodel.html#object.__getitem__), typically a [mapping](https://docs.python.org/3/glossary.html#term-mapping) or [sequence](https://docs.python.org/3/glossary.html#term-sequence). When indexed by a Unicode ordinal (an integer), the table object can do any of the following: return a Unicode ordinal or a string, to map the character to one or more other characters; return None, to delete the character from the return string; or raise a [`LookupError`](https://docs.python.org/3/library/exceptions.html#LookupError) exception, to map the character to itself.

You can use [`str.maketrans()`](https://docs.python.org/3/library/stdtypes.html#str.maketrans) to create a translation map from character-to-character mappings in different formats.

See also the [`codecs`](https://docs.python.org/3/library/codecs.html#module-codecs) module for a more flexible approach to custom character mappings.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.upper" target="_blank"><code>upper()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string with all the cased characters converted to uppercase. Note that `s.upper().isupper()` might be `False` if `s` contains uncased characters or if the Unicode category of the resulting character(s) is not “Lu” (Letter, uppercase), but e.g. “Lt” (Letter, titlecase).

The uppercasing algorithm used is described in section 3.13 of the Unicode Standard.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#str.zfill" target="_blank"><code>zfill(width)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a copy of the string left filled with ASCII `'0'` digits to make a string of length `width`. A leading sign prefix (`'+'`/`'-'`) is handled by inserting the padding `after` the sign character rather than before. The original string is returned if `width` is less than or equal to `len(s)`.

For example:

```
>>> "42".zfill(5)
'00042'
>>> "-42".zfill(5)
'-0042'
```

---

</details>

---

</details>

### List Methods

<details><summary> Examples from the docs</summary>

```
>>> fruits = ['orange', 'apple', 'pear', 'banana', 'kiwi', 'apple', 'banana']

>>> fruits.count('apple')
2

>>> fruits.count('tangerine')
0

>>> fruits.index('banana')
3

>>> fruits.index('banana', 4)  # Find next banana starting a position 4
6

>>> fruits.reverse()

>>> fruits
['banana', 'apple', 'kiwi', 'banana', 'pear', 'apple', 'orange']

>>> fruits.append('grape')

>>> fruits
['banana', 'apple', 'kiwi', 'banana', 'pear', 'apple', 'orange', 'grape']

>>> fruits.sort()

>>> fruits
['apple', 'apple', 'banana', 'banana', 'grape', 'kiwi', 'orange', 'pear']

>>> fruits.pop()
'pear'
```

You might have noticed that methods like `insert`, `remove` or `sort` that only modify the list have no return value printed – they return the default `None`. This is a design principle for all mutable data structures in Python.

Another thing you might notice is that not all data can be sorted or compared. For instance, `[None, 'hello', 10]` doesn't sort because integers can't be compared to strings and `None` can't be compared to other types. Also, there are some types that don't have a defined ordering relation. For example, `3+4j < 5+7j` isn't a valid comparison.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>append(x)</code></a></strong></summary>

**Description:** The `append()` method adds an item to the end of the list:

```python
currencies = ['Dollar', 'Euro', 'Pound']

# append 'Yen' to the list
currencies.append('Yen')

print(currencies)

# Output: ['Dollar', 'Euro', 'Pound', 'Yen']
```

The syntax of the `append()` method is: `list.append(item)`

The method takes a single argument:

- `item` - an item (number, string, list etc.) to be added at the end of the list

The method doesn't return any value (i.e., returns `None`).

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Add an item to the end of the list. Equivalent to `a[len(a):] = [x]`.

---

</details>

<details><summary> Ex 1: Adding element to a list</summary>

```python
# animals list
animals = ['cat', 'dog', 'rabbit']

# Add 'guinea pig' to the list
animals.append('guinea pig')

print('Updated animals list: ', animals)
```

**Output:**

```
Updated animals list:  ['cat', 'dog', 'rabbit', 'guinea pig']
```

---

</details>

<details><summary> Ex 2: Adding list to a list</summary>

```python
# animals list
animals = ['cat', 'dog', 'rabbit']

# list of wild animals
wild_animals = ['tiger', 'fox']

# appending wild_animals list to animals
animals.append(wild_animals)

print('Updated animals list: ', animals)
```

**Output:**

```
Updated animals list:  ['cat', 'dog', 'rabbit', ['tiger', 'fox']]
```

In the program, a single item (`wild_animals` list) is added to the `animals` list.

**Note:** If you need to add items of a list (rather than the list itself) to another list, use the [`extend()`](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists) method.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>clear()</code></a></strong></summary>

**Description:** The `clear()` method removes all items from the list.

```python
prime_numbers = [2, 3, 5, 7, 9, 11]

# remove all elements
prime_numbers.clear()

# Updated prime_numbers List
print('List after clear():', prime_numbers)


# Output: List after clear(): []
```

- The syntax of `clear()` method is: `list.clear()`
- The `clear()` method doesn't take any parameters.
- The `clear()` method only empties the given list. It doesn't return any value.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove all items from the list. Equivalent to `del a[:]`.

---

</details>

<details><summary> Ex 1: Working of <code>clear()</code> method</summary>

```python
# Defining a list
list = [{1, 2}, ('a'), ['1.1', '2.2']]

# clearing the list
list.clear()


print('List:', list)
```

**Output:**

```
List: []
```

**Note:** If you are using Python 2 or Python 3.2 and below, you cannot use the `clear()` method. You can use the `del` operator instead.

---

</details>

<details><summary> Ex 2: Emptying the list using <code>del</code></summary>

```python
# Defining a list
list = [{1, 2}, ('a'), ['1.1', '2.2']]

# clearing the list
del list[:]


print('List:', list)
```

**Output:**

```
List: []
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>copy()</code></a></strong></summary>

**Description:** The `copy()` method returns a shallow copy of the list.

```python
# mixed list
prime_numbers = [2, 3, 5]

# copying a list
numbers = prime_numbers.copy()


print('Copied List:', numbers)

# Output: Copied List: [2, 3, 5]
```

- The syntax of the `copy()` method is: `new_list = list.copy()`
- The `copy()` method doesn't take any parameters.
- The `copy()` method returns a new list. It doesn't modify the original list.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a shallow copy of the list. Equivalent to `a[:]`.

---

</details>

<details><summary> Ex 1: Copying a list</summary>

```python
# mixed list
my_list = ['cat', 0, 6.7]

# copying a list
new_list = my_list.copy()


print('Copied List:', new_list)
```

**Output:**

```
Copied List: ['cat', 0, 6.7]
```

If you modify the `new_list` in the above example, `my_list` will not be modified.

---

</details>

<details><summary> Ex 2: List copy using <code>=</code></summary>

We can also use the `=` operator to copy a list. For example,

```python
old_list = [1, 2, 3]
new_list = old_list
```

However, there is one problem with copying lists in this way. If you modify `new_list`, `old_list` is also modified. It is because the new list is referencing or pointing to the same `old_list` object.

```python
old_list = [1, 2, 3]

# copy list using =
new_list = old_list


# add an element to list
new_list.append('a')

print('New List:', new_list)
print('Old List:', old_list)
```

**Output:**

```
Old List: [1, 2, 3, 'a']
New List: [1, 2, 3, 'a']
```

However, if you need the original list unchanged when the new list is modified, you can use the `copy()` method.

---

</details>

<details><summary> Ex 3: Copy list using slicing syntax</summary>

```python
# shallow copy using the slicing syntax

# mixed list
list = ['cat', 0, 6.7]

# copying a list using slicing
new_list = list[:]


# Adding an element to the new list
new_list.append('dog')

# Printing new and old list
print('Old List:', list)
print('New List:', new_list)
```

**Output:**

```
Old List: ['cat', 0, 6.7]
New List: ['cat', 0, 6.7, 'dog']
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>count(x)</code></a></strong></summary>

**Description:** The `count()` method returns the number of times the specified element appears in the list.

```python
# create a list
numbers = [2, 3, 5, 2, 11, 2, 7]

# check the count of 2
count = numbers.count(2)


print('Count of 2:', count)

# Output: Count of 2: 3
```

- The syntax of the `count()` method is: `list.count(element)`
- The `count()` method takes a single argument:
  + `element` - the element to be counted
- The `count()` method returns the number of times `element` appears in the list.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the number of times `x` appears in the list.

---

</details>

<details><summary> Ex 1: Use of <code>count()</code></summary>

```python
# vowels list
vowels = ['a', 'e', 'i', 'o', 'i', 'u']

# count element 'i'
count = vowels.count('i')


# print count
print('The count of i is:', count)

# count element 'p'
count = vowels.count('p')


# print count
print('The count of p is:', count)
```

**Output:**

```
The count of i is: 2
The count of p is: 0
```

---

</details>

<details><summary> Ex 2: Count tuple and list elements inside list</summary>

```python
# random list
random = ['a', ('a', 'b'), ('a', 'b'), [3, 4]]

# count element ('a', 'b')
count = random.count(('a', 'b'))

# print count
print("The count of ('a', 'b') is:", count)

# count element [3, 4]
count = random.count([3, 4])

# print count
print("The count of [3, 4] is:", count)
```

**Output:**

```
The count of ('a', 'b') is: 2
The count of [3, 4] is: 1
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>extend(iterable)</code></a></strong></summary>

**Description:** The `extend()` method adds all the elements of an iterable (list, tuple, string etc.) to the end of the list in-place.

```python
# create a list
prime_numbers = [2, 3, 5]

# create another list
numbers = [1, 4]

# add all elements of prime_numbers to numbers
numbers.extend(prime_numbers)


print('List after extend():', numbers)

# Output: List after extend(): [1, 4, 2, 3, 5]
```

- The syntax of the `extend()` method is: `list.extend(iterable)`. Here, all the elements of `iterable` are added to the end of `list`.
- The `extend()` method takes an iterable such as list, tuple, string, etc.
- The `extend()` method modifies the original list in-place. It doesn't return any value.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Extend the list by appending all the items from the iterable. Equivalent to `a[len(a):] = iterable`.

---

</details>

<details><summary> Ex 1: Using <code>extend()</code> method</summary>

```python
# languages list
languages = ['French', 'English']

# another list of language
languages1 = ['Spanish', 'Portuguese']

# appending language1 elements to language
languages.extend(languages1)


print('Languages List:', languages)
```

**Output:**

```
Languages List: ['French', 'English', 'Spanish', 'Portuguese']
```

---

</details>

<details><summary> Ex 2: Add elements of tuple and set to list</summary>

```python
# languages list
languages = ['French']

# languages tuple
languages_tuple = ('Spanish', 'Portuguese')

# languages set
languages_set = {'Chinese', 'Japanese'}

# appending language_tuple elements to language
languages.extend(languages_tuple)


print('New Language List:', languages)

# appending language_set elements to language
languages.extend(languages_set)


print('Newer Languages List:', languages)
```

**Output:**

```
New Languages List: ['French', 'Spanish', 'Portuguese']
Newer Languages List: ['French', 'Spanish', 'Portuguese', 'Japanese', 'Chinese']
```

---

</details>

<details><summary> Ex 3: Using the <code>+</code> operator</summary>

```python
a = [1, 2]
b = [3, 4]

a += b    # a = a + b


# Output: [1, 2, 3, 4]
print('a =', a)
```

**Output:**

```
a = [1, 2, 3, 4]
```

---

</details>

<details><summary> Ex 4: Extend by using list slicing</summary>

```python
a = [1, 2]
b = [3, 4]

a[len(a):] = b


# Output: [1, 2, 3, 4]
print('a =', a)
```

**Output:**

```
a = [1, 2, 3, 4]
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>index(x[, start[, end]])</code></a></strong></summary>

**Description:** The `index()` method returns the index of the specified element in the list (and raises a `ValueError` if not found).

```python
animals = ['cat', 'dog', 'rabbit', 'horse']

# get the index of 'dog'
index = animals.index('dog')


print(index)

# Output: 1
```

- The syntax of the list `index()` method is: `list.index(element, start, end)`
- The list `index()` method can take a maximum of three arguments:
  + `element` - the element to be searched
  + `start` (optional) - start searching from this index
  + `end` (optional) - search the element up to this index
- The `index()` method returns the index of the given element in the list.
- If the element is not found, a `ValueError` exception is raised.
- **Note:** The `index()` method only returns the first occurrence of the matching element.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return zero-based index in the list of the first item whose value is equal to `x`. Raises a [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) if there is no such item.

The optional arguments `start` and `end` are interpreted as in the slice notation and are used to limit the search to a particular subsequence of the list. The returned index is computed relative to the beginning of the full sequence rather than the `start` argument.

---

</details>

<details><summary> Ex 1: Find the index of the element</summary>

```python
# vowels list
vowels = ['a', 'e', 'i', 'o', 'i', 'u']

# index of 'e' in vowels
index = vowels.index('e')

print('The index of e:', index)

# element 'i' is searched
# index of the first 'i' is returned
index = vowels.index('i')


print('The index of i:', index)
```

**Output:**

```
The index of e: 1
The index of i: 2
```

---

</details>

<details><summary> Ex 2: Index of the element not present in the list</summary>

```python
# vowels list
vowels = ['a', 'e', 'i', 'o', 'u']

# index of 'p' in vowels
index = vowels.index('p')

print('The index of p:', index)
```

**Output:**

```
ValueError: 'p' is not in list
```

---

</details>

<details><summary> Ex 3: Working of <code>index()</code> with <code>start</code> and <code>end</code> parameters</summary>

```python
# alphabets list
alphabets = ['a', 'e', 'i', 'o', 'g', 'l', 'i', 'u']

# index of 'i' in alphabets
index = alphabets.index('e')   # 1

print('The index of e:', index)

# 'i' after the 4th index is searched
index = alphabets.index('i', 4)   # 6

print('The index of i:', index)

# 'i' between 3rd and 5th index is searched
index = alphabets.index('i', 3, 5)   # Error!

print('The index of i:', index)
```

**Output:**

```
The index of e: 1
The index of i: 6
Traceback (most recent call last):
  File "*lt;string>", line 13, in 
ValueError: 'i' is not in list
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>insert(i, x)</code></a></strong></summary>

**Description:** The `insert()` method inserts an element to the list at the specified index.

```python
# create a list of vowels
vowel = ['a', 'e', 'i', 'u']

# 'o' is inserted at index 3 (4th position)
vowel.insert(3, 'o')


print('List:', vowel)

# Output: List: ['a', 'e', 'i', 'o', 'u']
```

- The syntax of the `insert()` method is: `list.insert(i, elem)`. Here, `elem` is inserted to the list at the `i`th index. All the elements after `elem` are shifted to the right.
- The `insert()` method takes two parameters:
  + `index` - the index where the element needs to be inserted
  + `element` - this is the element to be inserted in the list
- The `insert()` method doesn't return anything; returns `None`. It only updates the current list.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Insert an item at a given position. The first argument is the index of the element before which to insert, so `a.insert(0, x)` inserts at the front of the list, and `a.insert(len(a), x)` is equivalent to `a.append(x)`.

---

</details>

<details><summary> Ex 1: Inserting an element into the list</summary>

```python
# create a list of prime numbers
prime_numbers = [2, 3, 5, 7]

# insert 11 at index 4
prime_numbers.insert(4, 11)


print('List:', prime_numbers)
```

**Output:**

```
List: [2, 3, 5, 7, 11]
```

---

</details>

<details><summary> Ex 2: Inserting a tuple (as an element) into the list</summary>

```python
mixed_list = [{1, 2}, [5, 6, 7]]

# number tuple
number_tuple = (3, 4)

# inserting a tuple to the list
mixed_list.insert(1, number_tuple)


print('Updated List:', mixed_list)
```

**Output:**

```
Updated List: [{1, 2}, (3, 4), [5, 6, 7]]
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>pop([i])</code></a></strong></summary>

**Description:** The `pop()` method removes the item at the given index from the list and returns the removed item.

```python
# create a list of prime numbers
prime_numbers = [2, 3, 5, 7]

# remove the element at index 2
removed_element = prime_numbers.pop(2)

print('Removed Element:', removed_element)

# Output: Removed Element: 5
```

- The syntax of the `pop()` method is: `list.pop(index)`
- The `pop()` method takes a single argument (i.e., `index`).
- The argument passed to the method is optional. If not passed, the default index `-1` is passed as an argument (index of the last item).
- If the index passed to the method is not in range, it throws `IndexError: pop index out of range` exception.
- The `pop()` method returns the item present at the given index. This item is also removed from the list.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove the item at the given position in the list, and return it. If no index is specified, `a.pop()` removes and returns the last item in the list. (The square brackets around the `i` in the method signature denote that the parameter is optional, not that you should type square brackets at that position. You will see this notation frequently in the Python Library Reference.)

---

</details>

<details><summary> Ex 1: Pop item at the given index from the list</summary>

```python
# programming languages list
languages = ['Python', 'Java', 'C++', 'French', 'C']

# remove and return the 4th item
return_value = languages.pop(3)

print('Return Value:', return_value)

# Updated List
print('Updated List:', languages)
```

**Output:**

```
Return Value: French
Updated List: ['Python', 'Java', 'C++', 'C']
```

---

</details>

<details><summary> Ex 2: <code>pop()</code> without an index, and for negative indices</summary>

```python
# programming languages list
languages = ['Python', 'Java', 'C++', 'Ruby', 'C']

# remove and return the last item
print('When index is not passed:') 
print('Return Value:', languages.pop())

print('Updated List:', languages)

# remove and return the last item
print('\nWhen -1 is passed:') 
print('Return Value:', languages.pop(-1))

print('Updated List:', languages)

# remove and return the third last item
print('\nWhen -3 is passed:') 
print('Return Value:', languages.pop(-3))

print('Updated List:', languages)
```

**Output:**

```
When index is not passed:
Return Value: C
Updated List: ['Python', 'Java', 'C++', 'Ruby']

When -1 is passed:
Return Value: Ruby
Updated List: ['Python', 'Java', 'C++']

When -3 is passed:
Return Value: Python
Updated List: ['Java', 'C++']
```

If you need to remove the given item from the list, you can use the `remove()` method.

You can use the `del` statement to remove an item or slices from the list.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>remove(x)</code></a></strong></summary>

**Description:** The `remove()` method removes the first matching element (which is passed as an argument) from the list (raises a `ValueError` if there is no such item).

```python
# create a list
prime_numbers = [2, 3, 5, 7, 9, 11]

# remove 9 from the list
prime_numbers.remove(9)


# Updated prime_numbers List
print('Updated List: ', prime_numbers)

# Output: Updated List:  [2, 3, 5, 7, 11]
```

- The syntax of the `remove()` method is: `list.remove(element)`
- The `remove()` method takes a single element as an argument and removes it from the list.
- If the `element` doesn't exist, it throws `ValueError: list.remove(x): x not in list` exception.
- The `remove()` doesn't return any value (returns `None`).

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove the first item from the list whose value is equal to `x`. It raises a [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError) if there is no such item.

---

</details>

<details><summary> Ex 1: Remove element from the list</summary>

```python
# animals list
animals = ['cat', 'dog', 'rabbit', 'guinea pig']

# 'rabbit' is removed
animals.remove('rabbit')


# Updated animals List
print('Updated animals list: ', animals)
```

**Output:**

```
Updated animals list:  ['cat', 'dog', 'guinea pig']
```

---

</details>

<details><summary> Ex 2: <code>remove()</code> method on a list having duplicate elements</summary>

If a list contains duplicate elements, the `remove()` method only removes the first matching element.

```python
# animals list
animals = ['cat', 'dog', 'dog', 'guinea pig', 'dog']

# 'dog' is removed
animals.remove('dog')


# Updated animals list
print('Updated animals list: ', animals)
```

**Output:**

```
Updated animals list:  ['cat', 'dog', 'guinea pig', 'dog']
```

Here, only the first occurrence of element `'dog'` is removed from the list.

---

</details>

<details><summary> Ex 3: Deleting element that doesn't exist</summary>

```python
# animals list
animals = ['cat', 'dog', 'rabbit', 'guinea pig']

# Deleting 'fish' element
animals.remove('fish')


# Updated animals List
print('Updated animals list: ', animals)
```

**Output:**

```
Traceback (most recent call last):
  File ".. .. ..", line 5, in <module>
    animal.remove('fish')
ValueError: list.remove(x): x not in list
```

Here, we are getting an error because the `animals` list doesn't contain `'fish'`.

If you need to delete elements based on the index (like the fourth element), you can use the `pop()` method.

Also, you can use the Python `del` statement to remove items from the list.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>reverse()</code></a></strong></summary>

**Description:** The `reverse()` method reverses the elements of the list in-place.

```python
# create a list of prime numbers
prime_numbers = [2, 3, 5, 7]

# reverse the order of list elements
prime_numbers.reverse()


print('Reversed List:', prime_numbers)

# Output: Reversed List: [7, 5, 3, 2]
```

- The syntax of the `reverse()` method is: `list.reverse()`
- The `reverse()` method doesn't take any arguments.
- The `reverse()` method doesn't return any value. It updates the existing list.

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Reverse the elements of the list in place.

---

</details>

<details><summary> Ex 1: Reverse a list</summary>

```python
# Operating System List
systems = ['Windows', 'macOS', 'Linux']
print('Original List:', systems)

# List Reverse
systems.reverse()


# updated list
print('Updated List:', systems)
```

**Output:**

```
Original List: ['Windows', 'macOS', 'Linux']
Updated List: ['Linux', 'macOS', 'Windows']
```

There are other several ways to reverse a list.

---

</details>

<details><summary> Ex 2: Reverse a list using slice operator</summary>

```python
# Operating System List
systems = ['Windows', 'macOS', 'Linux']
print('Original List:', systems)

# Reversing a list	
# Syntax: reversed_list = systems[start:stop:step] 
reversed_list = systems[::-1]


# updated list
print('Updated List:', reversed_list)
```

**Output:**

```
Original List: ['Windows', 'macOS', 'Linux']
Updated List: ['Linux', 'macOS', 'Windows']
```

---

</details>

<details><summary> Ex 3: Accessing elements in reversed order</summary>

```python
# Operating System List
systems = ['Windows', 'macOS', 'Linux']

# Printing Elements in Reversed Order
for o in reversed(systems):
    print(o)

```

**Output:**

```
Linux
macOS
Windows
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank"><code>sort(*, key=None, reverse=False)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Sort the items of the list in place (the arguments can be used for sort customization, see [`sorted()`](https://docs.python.org/3/library/functions.html#sorted) for their explanation).

---

</details>

---

</details>

### Dictionary Methods

For several of the entries below, `d` refers to the *dictionary* `d`.

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>list(d)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a list of all the keys used in the dictionary `d`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>len(d)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the number of items in the dictionary `d`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>d[key]</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the item of `d` with key `key`. Raises a [`KeyError`](https://docs.python.org/3/library/exceptions.html#KeyError) if `key` is not in the map.

If a subclass of dict defines a method [`__missing__()`](https://docs.python.org/3/reference/datamodel.html#object.__missing__) and `key` is not present, the `d[key]` operation calls that method with the key `key` as argument. The `d[key]` operation then returns or raises whatever is returned or raised by the `__missing__(key)` call. No other operations or methods invoke [`__missing__()`](https://docs.python.org/3/reference/datamodel.html#object.__missing__). If [`__missing__()`](https://docs.python.org/3/reference/datamodel.html#object.__missing__) is not defined, KeyError is raised. [`__missing__()`](https://docs.python.org/3/reference/datamodel.html#object.__missing__) must be a method; it cannot be an instance variable:

```
>>> class Counter(dict):
...     def __missing__(self, key):
...         return 0
>>> c = Counter()
>>> c['red']
0
>>> c['red'] += 1
>>> c['red']
1
```

The example above shows part of the implementation of [`collections.Counter`](https://docs.python.org/3/library/collections.html#collections.Counter). A different `__missing__` method is used by [`collections.defaultdict`](https://docs.python.org/3/library/collections.html#collections.defaultdict).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>d[key] = value</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Set `d[key]` to `value`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>del d[key]</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove `d[key]` from `d`. Raises a [`KeyError`](https://docs.python.org/3/library/exceptions.html#KeyError) if `key` is not in the map.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>key in d</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if `d` has a key `key`, else `False`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>key not in d</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Equivalent to `not key in d`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>iter(d)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return an iterator over the keys of the dictionary. This is a shortcut for `iter(d.keys())`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.clear" target="_blank"><code>clear()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove all items from the dictionary.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.copy" target="_blank"><code>copy()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a shallow copy of the dictionary.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.fromkeys" target="_blank"><code>fromkeys(iterable[, value])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Create a new dictionary with keys from `iterable` and values set to `value`.

[`fromkeys()`](https://docs.python.org/3/library/stdtypes.html#dict.fromkeys) is a class method that returns a new dictionary. `value` defaults to `None`. All of the values refer to just a single instance, so it generally doesn’t make sense for `value` to be a mutable object such as an empty list. To get distinct values, use a [dict comprehension](https://docs.python.org/3/reference/expressions.html#dict) instead.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.get" target="_blank"><code>get(key[, default])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the value for `key` if `key` is in the dictionary, else `default`. If `default` is not given, it defaults to `None`, so that this method never raises a [`KeyError`](https://docs.python.org/3/library/exceptions.html#KeyError).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.items" target="_blank"><code>items()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new view of the dictionary’s items (`(key, value)` pairs). See the [documentation of view objects](https://docs.python.org/3/library/stdtypes.html#dict-views).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.keys" target="_blank"><code>keys()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new view of the dictionary’s keys. See the [documentation of view objects](https://docs.python.org/3/library/stdtypes.html#dict-views).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.pop" target="_blank"><code>pop(key[, default])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

If `key` is in the dictionary, remove it and return its value, else return `default`. If `default` is not given and `key` is not in the dictionary, a [`KeyError`](https://docs.python.org/3/library/exceptions.html#KeyError) is raised.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.popitem" target="_blank"><code>popitem()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove and return a `(key, value)` pair from the dictionary. Pairs are returned in LIFO order.

[`popitem()`](https://docs.python.org/3/library/stdtypes.html#dict.popitem) is useful to destructively iterate over a dictionary, as often used in set algorithms. If the dictionary is empty, calling [`popitem()`](https://docs.python.org/3/library/stdtypes.html#dict.popitem) raises a [`KeyError`](https://docs.python.org/3/library/exceptions.html#KeyError).

*Changed in version 3.7:* LIFO order is now guaranteed. In prior versions, [`popitem()`](https://docs.python.org/3/library/stdtypes.html#dict.popitem) would return an arbitrary key/value pair.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>reversed(d)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a reverse iterator over the keys of the dictionary. This is a shortcut for `reversed(d.keys())`.

*New in version 3.8.*

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.setdefault" target="_blank"><code>setdefault(key[, default])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

If `key` is in the dictionary, return its value. If not, insert `key` with a value of `default` and return `default`. `default` defaults to `None`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.update" target="_blank"><code>update([other])</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Update the dictionary with the key/value pairs from `other`, overwriting existing keys. Return `None`.

[`update()`](https://docs.python.org/3/library/stdtypes.html#dict.update) accepts either another dictionary object or an iterable of key/value pairs (as tuples or other iterables of length two). If keyword arguments are specified, the dictionary is then updated with those key/value pairs: `d.update(red=1, blue=2)`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict.values" target="_blank"><code>values()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new view of the dictionary’s values. See the [documentation of view objects](https://docs.python.org/3/library/stdtypes.html#dict-views).

An equality comparison between one `dict.values()` view and another will always return `False`. This also applies when comparing `dict.values()` to itself:

```
>>> d = {'a': 1}
>>> d.values() == d.values()
False
```

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>d | other</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Create a new dictionary with the merged keys and values of `d` and `other`, which must both be dictionaries. The values of `other` take priority when `d` and `other` share keys.

*New in version 3.9.*

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dict" target="_blank"><code>d |= other</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Update the dictionary `d` with keys and values from `other`, which may be either a [mapping](https://docs.python.org/3/glossary.html#term-mapping) or an [iterable](https://docs.python.org/3/glossary.html#term-iterable) of key/value pairs. The values of `other` take priority when `d` and `other` share keys.

*New in version 3.9.*

---

</details>

---

</details>

Dictionary view objects: The objects returned by `dict.keys()`, `dict.values()` and `dict.items()` are *view objects*. They provide a dynamic view on the dictionary's entries, which means that when the dictionary changes, the view reflects these changes. Dictionary views can be iterated over to yield their respective data, and support membership tests:

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dictionary-view-objects" target="_blank"><code>len(dictview)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return the number of entries in the dictionary.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dictionary-view-objects" target="_blank"><code>iter(dictview)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return an iterator over the keys, values or items (represented as tuples of `(key, value)`) in the dictionary.

Keys and values are iterated over in insertion order. This allows the creation of `(value, key)` pairs using [`zip()`](https://docs.python.org/3/library/functions.html#zip): `pairs = zip(d.values(), d.keys())`. Another way to create the same list is `pairs = [(v, k) for (k, v) in d.items()]`.

Iterating views while adding or deleting entries in the dictionary may raise a [`RuntimeError`](https://docs.python.org/3/library/exceptions.html#RuntimeError) or fail to iterate over all entries.

*Changed in version 3.7:* Dictionary order is guaranteed to be insertion order.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dictionary-view-objects" target="_blank"><code>x in dictview</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if `x` is in the underlying dictionary’s keys, values or items (in the latter case, `x` should be a `(key, value)` tuple).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#dictionary-view-objects" target="_blank"><code>reversed(dictview)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a reverse iterator over the keys, values or items of the dictionary. The view will be iterated in reverse order of the insertion.

*Changed in version 3.8:* Dictionary views are now reversible.

---

</details>

---

</details>

### Tuple Methods

See the "Common Sequence Operations" note at the top of this document.

### Set Methods

Instances of [`set`](https://docs.python.org/3/library/stdtypes.html#set) and [`frozenset`](https://docs.python.org/3/library/stdtypes.html#frozenset) provide the following operations:

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#set" target="_blank"><code>len(s)</code></a></strong></summary>

**Description:** tbd

<details><summary> Ex 0: Documentation</summary>

Return the number of elements in set `s` (cardinality of `s`).

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#set" target="_blank"><code>x in s</code></a></strong></summary>

**Description:** tbd

<details><summary> Ex 0: Documentation</summary>

Test `x` for membership in `s`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#set" target="_blank"><code>x not in s</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Test `x` for non-membership in `s`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.isdisjoint" target="_blank"><code>isdisjoint(other)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return `True` if the set has no elements in common with `other`. Sets are disjoint if and only if their intersection is the empty set.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.issubset" target="_blank"><code>issubset(other)</code></a> (alternative form: <code>set &lt;= other</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Test whether every element in the set is in `other`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#set" target="_blank"><code>set &lt; other</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Test whether the set is a proper subset of `other`, that is, `set <= other` and `set != other`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.issuperset" target="_blank"><code>issuperset(other)</code></a> (alternative form: <code>set >= other</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Test whether every element in `other` is in the set.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#set" target="_blank"><code>set > other</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Test whether the set is a proper superset of `other`, that is, `set >= other and set != other`.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.union" target="_blank"><code>union(*others)</code></a> (alternative form: <code>set | other | ...</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new set with elements from the set and all others.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.intersection" target="_blank"><code>intersection(*others)</code></a> (alternative form: <code>set & other & ...</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new set with elements common to the set and all others.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.difference" target="_blank"><code>difference(*others)</code></a> (alternative form: <code>set - other - ...</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new set with elements in the set that are not in the others.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.symmetric_difference" target="_blank"><code>symmetric_difference(other)</code></a> (alternative form: <code>set ^ other</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a new set with elements in either the set or other but not both.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.copy" target="_blank"><code>copy()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Return a shallow copy of the set.

---

</details>

---

</details>

The following table lists operations available for [`set`](https://docs.python.org/3/library/stdtypes.html#set) that do not apply to immutable instances of [`frozenset`](https://docs.python.org/3/library/stdtypes.html#frozenset):

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.update" target="_blank"><code>update(*others)</code></a> (alternative form: <code>set |= other | ...</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Update the set, adding elements from all others.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.intersection_update" target="_blank"><code>intersection_update(*others)</code></a> (alternative form: <code>set &= other & ...</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Update the set, keeping only elements found in it and all others.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.difference_update" target="_blank"><code>difference_update(*others)</code></a> (alternative form: <code>set -= other | ...</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Update the set, removing elements found in others.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.symmetric_difference_update" target="_blank"><code>symmetric_difference_update(other)</code></a> (alternative form: <code>set ^= other</code>)</strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Update the set, keeping only elements found in either set, but not in both.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.add" target="_blank"><code>add(elem)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Add element `elem` to the set.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.remove" target="_blank"><code>remove(elem)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove element `elem` from the set. Raises [`KeyError`](https://docs.python.org/3/library/exceptions.html#KeyError) if `elem` is not contained in the set.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.discard" target="_blank"><code>discard(elem)</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove element `elem` from the set if it is present.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.pop" target="_blank"><code>pop()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove and return an arbitrary element from the set. Raises [`KeyError`](https://docs.python.org/3/library/exceptions.html#KeyError) if the set is empty.

---

</details>

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/stdtypes.html#frozenset.clear" target="_blank"><code>clear()</code></a></strong></summary>

**Description:** tbd

**Examples:** 

<details><summary> Ex 0: Documentation</summary>

Remove all elements from the set.

---

</details>

---

</details>

### File Methods

<details><summary> <strong>Overview</strong></summary>

See [[1]](#1) for for a nice reference (mostly reproduced below). Also see the Python docs on the [io module](https://docs.python.org/3/library/io.html) (core tools for working with streams).

The built-in `open()` function creates a *file object*, the most common
interface to external files. File objects export the data transfer
methods in the following sections, where file content is
represented as Python strings. This is a partial list: see Python
manuals for lesser-used calls and attributes.

In Python 2.X only, the name `file()` can be used as a synonym
for `open()` when creating a file object, but `open()` is the generally
recommended spelling. In Python 3.X, `file()` is no longer available.
(The `io` module's classes are used for file customization.)

---

</details>

<details><summary> <strong>File Context Managers and File Usage Notes</strong></summary>

In standard Python (CPython), file objects normally close themselves
when garbage collected if still open. Because of this, temporary
files (e.g., `open('name').read()`) suffice and need not be
closed explicitly, as the file object is immediately reclaimed and
closed. Other Python implementations (e.g., Jython), however,
may collect and close files less deterministically.
To guarantee closes after a block of code exits, regardless of
whether the block raises an exception, use the `try/finally` statement
and manual closes:

``` Python
myfile = open(r'C:\misc\script', 'w')
try:
    ...use myfile...
finally:
    myfile.close()
```

Or use the `with/as` statement available in Python 3.X and 2.X (as
of 2.6 and 3.0):

``` Python
with open(r'C:\misc\script', 'w') as myfile:
    ...use myfile...
```

The first of these inserts a close call as a termination-time action.
The latter employs file object *context managers*, which guarantee
that a file is automatically closed when the enclosed code block
exits.

Some general file usage notes:

- Some file-open modes (e.g., `'r+'`) allow a file to be both
input and output, and others (e.g., `'rb'`) specify binary-mode
transfer to suppress line-end marker conversions
(and Unicode encodings in Python 3.X).
- File-transfer operations occur at the current file position,
but `seek()` method calls reposition the file for random
access.
- File transfers can be made *unbuffered*: see `open()` arguments and the -u command-line flag.

---

</details>

#### Input Files

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#open" target="_blank"><code><em>infile</em> = open(<em>filename</em>, 'r')</code></a></strong></summary>

**Description:** Creates input file object, connected to the named external file.

`filename` is normally a string (e.g., `'data.txt'`), and
maps to the current working directory unless it includes a
directory path prefix (e.g., `r'c:\dir\data.txt'`). Argument
two gives file *mode*: `'r'` reads text, `'rb'` reads binary with
no line-break translation. Mode is optional and defaults to
`'r'`. 

As noted in [the docs for `open()`](https://docs.python.org/3/library/functions.html#open), the following are the available modes:

| Character | Meaning |
| --: | :-- |
| `r` | open for reading (default) |
| `w` | open for writing, truncating the file first |
| `x` | open for exclusive creation, failing if the file already exists |
| `a` | open for writing, appending to the end of the file if it exists |
| `b` | binary mode |
| `t` | text mode (default) |
| `+` | open for updating (reading and writing) |

Python 3.X's `open()` also accepts an optional Unicode
encoding name in text mode; 2.X's `codecs.open()` has similar
tools.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.TextIOBase.read" target="_blank"><code><em>infile</em>.read()</code></a></strong></summary>

**Description:** Returns the file content.

Reads entire file, returning its contents as a single string. In
text mode (`'r'`), line-ends are translated to `'\n'` by default.
In binary mode (`'rb'`), the result string can contain nonprintable
characters (e.g., `'\0'`). In Python 3.X, text mode
*decodes* Unicode text into a `str` string, and binary mode returns
unaltered content in a `bytes` string.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.RawIOBase.read" target="_blank"><code><em>infile</em>.read(<em>N</em>)</code></a></strong></summary>

**Description:** Reads at most *`N`* more bytes (1 or more); empty at end-offile.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.TextIOBase.readline" target="_blank"><code><em>infile</em>.readline()</code></a></strong></summary>

**Description:** Reads next line (through end-of-line marker); empty at end-of-file.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.readlines" target="_blank"><code><em>infile</em>.readlines()</code></a></strong></summary>

**Description:** Reads entire file into a list of line strings. See also the file
object's line iterator alternative, discussed in the next list
item.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.readlines" target="_blank"><code>for <em>line</em> in <em>infile</em></code></a></strong></summary>

**Description:** Step through the lines in a file automatically.

This syntax uses the *line iterator* of file object *`infile`* to step through
lines in the file automatically. Available in all iteration contexts,
including `for` loops, `map()`, and comprehensions (e.g.,
`[line.rstrip() for line in open('filename')]`). The
iteration `for line in infile` has an effect similar to `for line
in infile.readlines()`, but the line iterator version fetches
lines on demand instead of loading the entire file into memory,
and so is more space-efficient.

---

</details>

#### Output Files

<details><summary> <strong><a href="https://docs.python.org/3/library/functions.html#open" target="_blank"><code><em>outfile</em> = open(<em>filename</em>, 'w')</code></a></strong></summary>

**Description:** Creates output file object, connected to external file.

Creates output file object, connected to external file named
by `filename` (defined in the preceding section). Mode `'w'`
writes text, `'wb'` writes binary data with no line-break translation.
Python 3.X's `open()` also accepts an optional Unicode
encoding name in text mode; 2.X's `codecs.open()` has similar
tools.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.TextIOBase.write" target="_blank"><code><em>outfile</em>.write(<em>S</em>)</code></a></strong></summary>

**Description:** Write the string `S` to the stream and return the number of characters written.

Writes all content in string `S` onto file, with no formatting
applied. In text mode, `'\n'` is translated to the platform-specific
line-end marker sequence by default. In binary
mode, the string can contain nonprintable bytes (e.g., use
`'a\0b\0c'` to write a string of five bytes, two of which are
binary zero). In Python 3.X, text mode requires `str` Unicode
strings and *encodes* them when written, and binary mode
expects and writes `bytes` strings unaltered.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.writelines" target="_blank"><code><em>outfile</em>.writelines(<em>I</em>)</code></a></strong></summary>

**Description:** Writes a list of strings to the file.

Writes all strings in iterable `I` onto file, not adding any lineend
characters automatically.

---

</details>

#### Any Files

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.close" target="_blank"><code><em>file</em>.close()</code></a></strong></summary>

**Description:** Closes the file.

Manual close to free resources (although CPython currently
auto-closes files if still open when they are garbage collected).

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.tell" target="_blank"><code><em>file</em>.tell()</code></a></strong></summary>

**Description:** Returns the file's current position.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.seek" target="_blank"><code><em>file</em>.seek(<em>offset</em> [, <em>whence</em>])</code></a></strong></summary>

**Description:** Change the file position.

Sets the current file position to `offset` for random access.
`whence` can be `0` (offset from front), `1` (offset +/– from current
position), or `2` (offset from end). `whence` defaults to `0`.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.isatty" target="_blank"><code><em>file</em>.isatty()</code></a></strong></summary>

**Description:** Returns whether the file stream is interactive or not.

Returns `True` if the file is connected to a tty-like (interactive)
device, else `False` (may return `1` or `0` in older Python
versions).

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.flush" target="_blank"><code><em>file</em>.flush()</code></a></strong></summary>

**Description:** Flushes the internal buffer.

Flushes the file's `stdio` buffer. Useful for buffered pipes, if
another process (or human) is reading. Also useful for files
created and read in the same process.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.truncate" target="_blank"><code><em>file</em>.truncate([size])</code></a></strong></summary>

**Description:** Resizes the file to a specified size.

Truncates file to, at most, `size` bytes (or current position if
no size is passed). Not available on all platforms.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.fileno" target="_blank"><code><em>file</em>.fileno()</code></a></strong></summary>

**Description:** Returns a number that represents the stream, from the operating system's perspective.

Gets file number (file descriptor integer) for file. This roughly
converts file objects to file descriptors that can be passed
to tools in the os module. Hint: use `os.fdopen()` or 3.X's
`open()` to convert a file descriptor to a file object.

---

</details>

#### Other File Methods/Attributes

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.readable" target="_blank"><code><em>file</em>.readable()</code></a></strong></summary>

**Description:** Returns whether the file stream can be read or not.

Return `True` if the stream can be read from. If `False`, `read()` will raise [`OSError`](https://docs.python.org/3/library/exceptions.html#OSError).

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.writable" target="_blank"><code><em>file</em>.writable()</code></a></strong></summary>

**Description:** Returns whether the file can be written to or not.

Return `True` if the stream supports writing. If `False`, `write()` and [`truncate()`](https://docs.python.org/3/library/io.html#io.IOBase.truncate) will raise [OSError](https://docs.python.org/3/library/exceptions.html#OSError).

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.seekable" target="_blank"><code><em>file</em>.seekable()</code></a></strong></summary>

**Description:** Returns whether the file allows us to change the file position.

Return `True` if the stream supports random access. If `False`, [`seek()`](https://docs.python.org/3/library/io.html#io.IOBase.seek), [`tell()`](https://docs.python.org/3/library/io.html#io.IOBase.tell) and [`truncate()`](https://docs.python.org/3/library/io.html#io.IOBase.truncate) will raise [OSError](https://docs.python.org/3/library/exceptions.html#OSError).

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.IOBase.closed" target="_blank"><code><em>file</em>.closed</code></a></strong></summary>

**Description:** `True` if file has been closed

`True` if the stream is closed.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.FileIO.mode" target="_blank"><code><em>file</em>.mode</code></a></strong></summary>

**Description:** Mode string (e.g., `'r'`) passed to `open()` function.

The mode as given in the constructor.

---

</details>

<details><summary> <strong><a href="https://docs.python.org/3/library/io.html#io.FileIO.name" target="_blank"><code><em>file</em>.name</code></a></strong></summary>

**Description:** String name of corresponding external file.

The file name. This is the file descriptor of the file when no name is given in the constructor.

---

</details>