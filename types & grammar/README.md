# You Don't Know JS: Types & Grammar

<img src="cover.jpg" width="300">

## Read These If You Haven't Already

* [Foreword](foreword.md) (by [Jenn Lukas](http://jennlukas.com))
* [Preface](../preface.md)

## Chapter 1 TL;DR

JavaScript has seven built-in *types*: `null`, `undefined`,  `boolean`, `number`, `string`, `object`, `symbol`. They can be identified by the `typeof` operator.

Variables don't have types, but the values in them do. These types define intrinsic behavior of the values.

Many developers will assume "undefined" and "undeclared" are roughly the same thing, but in JavaScript, they're quite different. `undefined` is a value that a declared variable can hold. "Undeclared" means a variable has never been declared.

JavaScript unfortunately kind of conflates these two terms, not only in its error messages ("ReferenceError: a is not defined") but also in the return values of `typeof`, which is `"undefined"` for both cases.

However, the safety guard (preventing an error) on `typeof` when used against an undeclared variable can be helpful in certain cases.

