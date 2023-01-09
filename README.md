# PHP AllFactor

**PHP AllFactor** is a comprehensive PHP refactoring tool for Visual Studio Code. It aims to provide all popular and feasible refactoring operations for PHP, and then some. The main goal is that, coupled with a code intelligence solution like [Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client), they should provide practically everything you need in order to enjoy a full PHP development experience in Visual Studio Code that parallels the offerings of any competing IDE.

## Early development period

The extension is in its infancy now. It's planned to provide freemium support, with some functions remaining available for free, while others for a single, one-time purchase, perpetual use premium key. Developing and maintaining such an extension requires a considerable amount of time and effort and is only feasible with some support from its users. Right now, during this early period, it's freely available but when it matures, early adopters will be rewarded for their continuing support, although the details are not yet determined (probably in the form of a limited time period to claim a free license key, or something similar).

## Features

### Code actions

* Extract, inline and rename constants, variables, methods and functions across the workspace. (Please note that this is a new feature under development. _**It's very strongly recommended**_ to preview the rename operation with <kbd>Shift</kbd> + <kbd>Enter</kbd> first to make sure nothing untoward happens.)
* Splitting and merging **if** statements, swapping **then** and **else** branches, conversion of conditionals to ternary operations.
* Conversion between **for** and **foreach** loops.
* Conversion between **switch** statements, **match** expressions and **if-else** chains.
* Surround existing code with **if, foreach, for, while, do...while, try...catch** statements.
* Add and remove **numeric separators**.
* String manipulations, single and double **quotes, case changes.**
* Conversion between interpolated and concatenated **strings.**
* Conversion between arrow and anonymous **functions.**
* Conversion between short and long format **arrays** and **lists.**
* Moving **operators** into and out of **assignments.**
* Creating **getters** and **setters** of properties. Renaming properties with getters/setters. Splitting property declarations.
* Infer function **return and parameter types** from actual usage.
* Organize **use** imports with customizable grouping level. Add, rename and remove **use aliases.**
* Add, delete, reorder **function arguments,** change **signature.**

### Commands

Available in the _Command Palette:_

* _Add log message:_ Configurable automatic **log call,** picking up the expression under the cursor and placing it automatically into a log call, into its most logical position (eg. inside the loop or before a return statement). The message can include current file, line number, enclosing class and function name automatically. The actual error call can be customized to the framework you use. The command can be bound to a keyboard shortcut (defaults to <kbd>Alt/Cmd</kbd> + <kbd>L</kbd>).
* _Clear workspace cache:_ clear any analysis data collected for the current workspace by **PHP AllFactor**. Use it if you suspect any issue with stale analysis.

### Code completions

* `$_SERVER` fields with description.

## Acknowledgements

**PHP AllFactor** uses the following open source libraries. Visit the following links for source code and licences.

* [vscode-languageserver-node](https://github.com/Microsoft/vscode-languageserver-node)
* [php-parser](https://github.com/glayzzle/php-parser)
* [doc-parser](https://github.com/glayzzle/doc-parser)
* [minimatch](https://github.com/isaacs/minimatch)
* [Simple-DataTables](https://github.com/fiduswriter/Simple-DataTables)
* [codicon](https://github.com/microsoft/vscode-codicons)
