#### Understanding copy by reference

```js
let brothers = ['John', 'Bran', 'Robb'];
let house = 'Stark';
let user = {
  name: 'Arya',
  house: house,
  brothers: brothers,
};

let user2 = {
  name: 'Arya',
  house: house,
  brothers: brothers,
};

let user3 = {
  name: 'Arya',
  house: 'Stark',
  brothers: ['John', 'Bran', 'Robb'],
};
```

1. After going through above code answer the following with reason:

```js
user.house === user2.house; // output:
user.house == user2.house; // output:
user.brothers === user2.brothers; // output:
user.brothers == user2.brothers; // output:
user.name == user2.name; // output:
user.name === user2.name; // output:
user.brothers == user3.brothers; // output:
user.brothers === user3.brothers; // output:
user.house === user2.house; // output
user.house === user3.house; // output
user.brothers[0] === user2.brothers[0]; // output
user.brothers[0] === user3.brothers[0]; // output
```

2. Copy the value of `character` variable into variable named `characterOne` and `characterTwo`.

```js
let charactor = {
  charactorName: 'Sansa',
  sisters: 1,
  brothers: 4,
};
// Your code
```

Check the output of below code after copying. The output of all of all of the below should be `true`

```js
charactor === characterOne;
characterOne == characterTwo;
characterTwo == character;
```

3. Clone (no reference) the value of `character` variable into variables named `characterThree` and `characterFour`.

```js
let charactor = {
  charactorName: 'Sansa',
  sisters: 1,
  brothers: 4,
};

// Your code
```

Check your result by comparing the values:
All the below result should be false.

```js
charactor === characterOne;
characterOne == characterTwo;
characterTwo == character;
```
