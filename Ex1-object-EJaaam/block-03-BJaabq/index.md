## BLOCK-writeTextAnswer

### special key

Can you define the key named `let, var, true, or const` or anyother JS keywords in an object. Explain why?

### Accessing values from object

```js
let keyValue = "username";
let charactor = {
  username: "arya",
};
// 1.
console.log(charactor["keyValue"]);
// 2.
console.log(charactor[keyValue]);
```

After going through the code above answer the following

- What will be the output of 1 and 2.
- Why are they different.
- Can I use `.` dot notation to access the value (using variable name). Write reason.
- What is the difference between `.` dot notation and `[]` bracket notation. Example
- What are situation where we use dot notation and bracket notation.

### Access in array

What will be the output if you access index greater than the length of the array. Like array length is 10 and `arr[11]`. Same with object if you access the key that doesnot exist.
