# PHP AllFactor

**AllFactor** is a comprehensive PHP refactoring tool for Visual Studio Code. It aims to provide all popular and feasible refactoring operations for PHP, and then some. The main goal is that, coupled with a code intelligence solution like [Intelephense](https://intelephense.com), they should provide practically everything you need in order to enjoy a full PHP development experience in Visual Studio Code that parallels the offerings of any competing IDE.

## Early development period

The extension is in its infancy now. It's planned to provide freemium support, with some functions remaining available for free, while others for a single, one-time purchase, perpetual use premium key. Developing and maintaining such an extension requires a considerable amount of time and effort and is only feasible with some support from its users. Right now, during this early period, it's freely available but when it matures, early adopters will be rewarded for their continuing support, although the details are not yet determined (probably in the form of a limited time period to claim a free license key, or something similar).

* Extract, inline and rename constants, variables, methods and functions.
* Splitting and merging **if** statements, swapping **then** and **else** branches, conversion of conditionals to ternary operations.
* Conversion between **for** and **foreach** loops.
* Conversion between **switch** statements, **match** expressions and **if-else** chains.
* Surround existing code with **if, foreach, for, while, do...while, try...catch** statements.
* Add and remove numeric separators.
* String manipulations, single and double quotes, case changes.
* Conversion between interpolated and concatenated strings.
* Conversion between arrow and anonymous functions.
* Conversion between short and long format arrays and lists.
* Moving operators into and out of assignments.
* Creating getters and setters of properties. Renaming properties with getters/setters. Splitting property declarations.
* Infer function return and parameter types from actual usage.
* Organize **use** imports with customizable grouping level.
* Add, delete, reorder function parameters.
