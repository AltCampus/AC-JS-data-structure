#### Copy by value and reference

1. Go through the code and answer

```js
let x = 10;
let y = 'Hello';
let a = x;
let b = y;
```

Answer the following after looking at above code along with the reason:

- Value of x // output
- Value of y
- Value of a
- Value of b

---

2. Go through the code and answer

```js
var x = 10;
var y = 'Hello';
var a = x;
var b = y;
a = 5;
b = 'test';
```

Answer the following after looking at above code along with the reason:

- Value of x // output
- Value of y
- Value of a
- Value of b

---

3. Go through the code and answer

```js
var users = ['sam', 'aman'];
var usersCopy = users;
users.push('nathan');
```

Answer the following after looking at above code along with the reason:

- Value of `users` // output
- Value of `usersCopy`
- Length of the `users` variable
- Length of the `usersCopy` variable

---

4. Go through the code and answer

```js
let a = { language: 'Javascript' };
let b = learn;

console.log(a); // 1
console.log(b); // 2

a.language = 'Python';

console.log(a); // 3
console.log(b); // 4
```

Answer the following after looking at above code along with the reason:

- Output of 1 // output
- Output of 2
- Output of 3
- Output of 4

5. Go through the code and answer

```js
let username = 'Arya';
let usernameCopy = username;
let userInfo = {
  name: 'John',
};
let userCopy = userInfo;
```

Answer the following after looking at above code along with the reason:

```js
username == usernameCopy; // output
username === usernameCopy;
userInfo === userCopy;
userInfo == userCopy;
userInfo.name == userCopy.name;
userInfo.name === userCopy.name;
username == userInfo.name;
```

---

6. What does the following code print to the console?

```jsx
var game = { game: 'Vollyball' };
console.log(game === game);

// Output -
```

---

7. What does the following code print to the console and Why?

```jsx
var game = { title: 'Vollyball' };
var sameGame = { title: 'Vollyball' };
console.log(game === sameGame);

// Output -
```
