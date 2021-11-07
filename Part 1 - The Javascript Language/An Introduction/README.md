## An Introduction to JavaScript

Javascript was created to make "web pages alive"

The JS Engine is responsible for the execution of the JS code. Chrome's engine is called V8.

### How does the engine work?
- Engine reads/parses the script
- JIT Compiles script to machine language 
- Machine code runs

Modern JS is a "safe" programming language as it does not provide low-level access.

JS's capabilities depend on the environment it is running in.

In a browser environmnent, it works in sync with the rendering/browser/layout engine that is responsible for the tranformation of HTML and other resources into an interactive visual representation on a user's device

JavaScript lacks static types and this can be solved by tools like Flow or TypeScript. Flow seems to be a better alternative than TypeScript:
1. Flow is a type checker, wheras
2. TypeScript is a language in itself that implements a type checker as well as a transpiler that emits plain JS
3. Flow does interprocedural analyses
4. TypeScript provides great tooling and language services for autocompletion, code navigation, and refactoring
5. You can deviate from writing standard Javascript when using Flow. However, you can get around it by using inline comments

---

## Manuals & Specifications

- [ECMA-262 spec](https://www.ecma-international.org/publications-and-standards/standards/ecma-262/)
- [Latest spec](https://tc39.es/ecma262/)
- [Proposals](https://github.com/tc39/proposals)
- [MDN Manual](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
- [CanIUse](http://caniuse.com/)
- [Kangax](https://kangax.github.io/compat-table/es6/)