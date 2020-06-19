## BLOCK-WriteCode

Copy by value and copy by reference

###

```js
const user = {
  name: "Arya",
};
user.name = "Sansa";
console.log(user.name);
```

After going through above code explain the following:

- Is the code above is valid or invalid.
- Can we change the variable defined with `const`. Explain with reason.
- What will be the output and why?

### Find out the value

- What will be the value of a, b, x and y.

```js
let x = 10;
let y = "abc";
let a = x;
let b = y;
```

Answer:

---

- What will be the value of a, b, x and y.

```js
var x = 10;
var y = "abc";
var a = x;
var b = y;
a = 5;
b = "def";
```

Answer:

---

- What will be the value of `arr` and `arrCopy`.

```js
var arr = [1];
var arrCopy = arr;
arr.push(2);
```

Answer:
