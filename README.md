# Math-as-Rust
A mathematical notation list in Rust code form.

##Contents 

- [variable name conventions](#variable-name-conventions)
- [equals `=` `≈` `≠` `:=`](#equals-symbols)
- [square root and complex numbers `√` *`i`*](#square-root-and-complex-numbers)
- [dot & cross `·` `×` `∘`](#dot--cross)
  - [scalar multiplication](#scalar-multiplication)
  - [vector multiplication](#vector-multiplication)
  - [dot product](#dot-product)
  - [cross product](#cross-product)
- [sigma `Σ`](#sigma) - *summation*
- [capital Pi `Π`](#capital-pi) - *products of sequences*
- [pipes `||`](#pipes)
  - [absolute value](#absolute-value)
  - [Euclidean norm](#euclidean-norm)
  - [determinant](#determinant)
- [hat **`â`**](#hat) - *unit vector*
- ["element of" `∈` `∉`](#element)
- [common number sets `ℝ` `ℤ` `ℚ` `ℕ`](#common-number-sets)
- [function `ƒ`](#function)
  - [piecewise function](#piecewise-function)
  - [common functions](#common-functions)
  - [function notation `↦` `→`](#function-notation)
- [prime `′`](#prime)
- [floor & ceiling `⌊` `⌉`](#floor--ceiling)
- [arrows](#arrows)
  - [material implication `⇒` `→`](#material-implication)
  - [equality `<` `≥` `≫`](#equality)
  - [conjunction & disjunction `∧` `∨`](#conjunction--disjunction)
- [logical negation `¬` `~` `!`](#logical-negation)
- [intervals](#intervals)
- [more...](#more)

## variable name conventions

There are a variety of naming conventions depending on the context and field of study, and they are not always consistent. However, in some of the literature you may find variable names to follow a pattern like so:

- *s* - italic lowercase letters for scalars (e.g. a number)
- **x** - bold lowercase letters for vectors (e.g. a 2D point)
- **A** - bold uppercase letters for matrices (e.g. a 3D transformation)
- *θ* - italic lowercase Greek letters for constants and special variables (e.g. [polar angle *θ*, *theta*](https://en.wikipedia.org/wiki/Spherical_coordinate_system))

This will also be the format of this guide.

## equals symbols

There are a number of symbols resembling the equals sign `=`. Here are a few common examples:

- `=` is for equality (values are the same)
- `≠` is for inequality (value are not the same)
- `≈` is for approximately equal to (`π ≈ 3.14159`)
- `:=` is for definition (A is defined as B)
