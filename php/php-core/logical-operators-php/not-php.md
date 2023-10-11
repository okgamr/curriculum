---
author: Stefan-Stojanovic
tags:
  - introduction
type: normal
category: must-know
practiceQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
---

# NOT (!) Operator

---

## Content

The `!` operator returns the inverse of the operand's boolean value. If the operand is true, it returns false, and vice versa.

```cpp
bool a = true;

if(!a) {
  printf("a is false.")
} else {
  printf("a is true.")
}
// Output: "a is true."
```

---

## Practice

Finish the code to output 'a is false'?

```cpp
$a = ???;

if(???) { 
  echo "a is false";
} else {
  echo "a is true";
}
// Output: a is false 
```

- false
- `!$a`
- `!$b`
- true

---

## Revision

What is the output of the following code?

```cpp
$a = true;

if(!$a) {
  echo "a is false";
} else {
  echo "a is true";
}
// Output: a is ???
```

- true
- false