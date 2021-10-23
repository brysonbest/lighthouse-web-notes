### Truthy and Falsey

Javascript - comparing two values you can use either the === operator, or the == operator.

#### ===

* Compares two values, and also the type of those values.

#### ==

* Compares two values, and uses "Type Coercion":
  * == Attempts to force the two values to be of the same type.

### Everything in JavaScript has a Boolean Value

* Most things in JavaScript are Truthy, however, there are some things which have falsey values:

``` javascript
False // False is False

0 // 0 is the only falsey Number

"" // an empty string is falsey

null // a null, or empty value, is falsey.

undefined // an undefined object is  falsey.

NaN // Not a Number. Falsey.
```