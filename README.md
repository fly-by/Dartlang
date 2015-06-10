# Dartlang _Fly-by_

> Dart is a new platform for scalable web app engineering.  
> \- [dartlang.org](https://www.dartlang.org/)

`Dartlang` is developed as a wannabe JavaScript successor by Google and is in the process of becoming an [ECMA standard](http://www.ecma-international.org/memento/TC52.htm). It can be compiled into JavaScript. A VM is in development by Google with the goal of integrating it into Chrome.

Due to its libraries it provides support for working with the file system along with features for creating and managing native processes. Thus it can be used like NodeJS.

Dartlang is part of the Dart toolkit. `Dart` comprises:

- **Dart VM (virtual machine)**  
Will be included in Chrome at some point.
- **Dartium**  
Special build of Chromium that provides the Dart VM.
- **Dart to JavaScript compiler**
- **Dart Editor**  
A lightweight version of Eclipse that e.g. provides Dart debugging and refactoring support.
- **Dart SDK (software development kit)**  
Libraries that provide a set of functionality for Dart as listed below.

### Language features

- Dart runs about [1.5 to 2 times faster than JavaScript](https://www.dartlang.org/performance/).
- Is object oriented with single inheritance.
- Allows for mixins.
- Is optionally typed.
- Allows for top level functions.
- The VM can be used on the server side like NodeJS.
- Supports library/package structuring.
- Includes a promise-like feature called `Futures`.
- Supports concurrency.
- When building for the web Dart performs `tree shaking` meaning that it strips away unsued functions.

### Included Libraries

Includes the following [libraries](https://api.dartlang.org/apidocs/channels/stable/dartdoc-viewer/home) (<small>short descriptions taken from [here](https://www.dartlang.org/docs/dart-up-and-running/contents/ch03.html) and [here](https://api.dartlang.org/apidocs/channels/stable/dartdoc-viewer/home)</small>):

- **dart:async**  
Asynchronous Programming
- **dart:collection**  
Classes and utilities that supplement the collection support in dart:core.
- **dart:convert**  
Decoding and Encoding JSON, UTF-8, and more.
- **dart:core**  
Numbers, Collections, Strings, and more. This library gets imported automatically.
- **dart:html**  
Browser-Based Apps
- **dart:indexed_db**  
A client-side key-value store with support for indexes.
- **dart:io**  
I/O for Command-Line Apps
- **dart:isolate**  
Concurrent programming using isolates: independent workers that are similar to threads but don't share memory, communicating only via messages.
- **dart:js**  
Support for interoperating with JavaScript.
- **dart:math**  
Math and Random
- **dart:mirrors**  
Reflection support. Meaning that code can get information about code like for example how many methods there are in a certain class.
- **dart:profiler**
- **dart:svg**  
Two-dimensional vector graphics with support for events and animation.
- **dart:typed_data**  
Specialized integers and floating point numbers, with SIMD support and efficient lists.
- **dart:web_audio**  
High-fidelity audio programming in the browser.
- **dart:web_gl**  
3D programming in the browser.
- **dart:web_sql**  
An API for storing data in the browser that can be queried with SQL.

Support is provided for unit testing and documenting. Third-party packages can be pulled from and be maintained by the NPM-like package manager [Pub](https://pub.dartlang.org/).

### Benefits

Compared to JavaScript Dart provides the following benefits:

- Faster execution speed when run within the Dart VM.
- The flexibility to start out writing simple prototypes using top level functions and untyped variables and then scaling up using classes, types and libraries.
- When run in Dart VM the state of the programm can be saved as a snapshot resulting in faster startup times.

## Local Installation

```bash
sudo add-apt-repository ppa:hachre/dart
sudo apt-get update
sudo apt-get install darteditor
```

Which depends on and installs:
- **dartvm**  
Just the Dart VM, allows you to run Dart command line scripts
- **dartsdk**  
Additionally installs the Dart source and some command line development tools (dart2js, pub, etc.)
- **dartium**  
Sspecial version of Chromium with integrated Dart VM
- **darteditor**  
The official Dart IDE

## Usage in Bash Scripts

```dart
#!/usr/bin/env dart
import 'dart:io';

// accessing arguments
stdin

// printing out
// including other dart files
```

More in the dartlang.org article ["Write Command-Line Apps"](https://www.dartlang.org/docs/tutorials/cmdline/).

## Dartlang Syntax

## Comments
## Variables
