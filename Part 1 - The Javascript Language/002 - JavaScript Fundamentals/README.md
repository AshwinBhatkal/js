## Hello, world!

As a rule, only the simplest scripts are put into HTML. More complex ones reside in separate files. The benefit of a separate file is that the browser will download it and store it in its cache.

File paths beginning with "/" are absolute paths from the "site root".

`A single <script> tag can’t have both the src attribute and code inside.`

--
## Code Structure

A line break is interpreted as an "implicit" semicolon. This is called an [automatic semicolon insertion](https://tc39.es/ecma262/#sec-automatic-semicolon-insertion). There are certain rules to it though. It is inserted mostly after ) or } and it does not assume a ; before [.

Better to use semicolons everywhere

## The modern mode, "use strict"

2005 ES5 appeared

We can add "use script" at the beginning of the file to explicitly disable old code in JS p. It should always be at the top - file or function.

"use strict" can be put at the beginning of a function. Doing that enables strict mode in that function only.

Inside native ECMAScript modules (with import and export statements) and ES6 classes, strict mode is always enabled and cannot be disabled

You cannot cancel it

Without "use strict", this would work => num = 5;

### Should we “use strict”?

Modern JavaScript supports “classes” and “modules” – advanced language structures (we’ll surely get to them), that enable "use strict" automatically. So we don’t need to add the "use strict" directive, if we use them.

--
## Variables

A variable is a "named storage" for data.

For the sake of better readability, use a single line per variable.

### Limitations on variable names in JavaScript:

1. The name must contain only letters, digits, or the symbols $ and _.
2. The first character must not be a digit.

Non-Latin letters are allowed, but not recommended

Generator functions\[()*\] can be replace with async functions

There are constants that are known prior to execution. These are capital-named. Capital-named constants are only used as aliases for “hard-coded” values.
There are constants that are calculated in run-time, during the execution, but do not change after their initial assignment. These are normally named.

A variable name should have a clean, obvious meaning, describing the data that it stores.

--
## Data types

