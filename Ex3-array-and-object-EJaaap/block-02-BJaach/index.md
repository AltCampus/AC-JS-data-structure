#### What will be the output of the following code snippet given below:

1. What does the following code print to the console?

```jsx
let hat = {
  size: 'large',
  color: 'orange',
};
console.log(hat.size);

// Output -
```

2. What does the following code print to the console?

```jsx
let hat = {
  size: 'large',
  color: 'orange',
};
console.log(hat['color']);

// Output -
```

3. What does the following code print to the console?

```jsx
let hat = {
  size: 'large',
  color: 'orange',
};

hat.color = 'red';
console.log(hat.color);

// Output -
```

4. What does the following code print to the console?

```jsx
let pen = {};
pen.ink = 'blue';
console.log(pen.ink);

// Output -
```

5. What does the following code print to the console?

```jsx
let hat = {
  size: 'large',
  color: 'orange',
};

console.log(hat['cost']);

// Output -
```

6. What does the following code print to the console?

```jsx
let hat = {
  rating: function () {
    return 'Hat is top rated';
  },
  color: 'green',
};
console.log(hat.rating());

// Output -
```

7. What does the following code print to the console?

```jsx
let hat = {
  size: 'medium',
  color: 'green',
  introduction: function () {
    return `The size of hat is ${hat.size} and color is ${hat.color}`;
  },
};
hat.introduction();

// Output -
```

8. What does the following code print to the console?

```jsx
let hat = {
  rating: function () {
    return 'Hat is top rated';
  },
  color: 'green',
};
console.log(hat.rating());

// Output -
```

9. What does the following code print to the console?

```jsx
let bucket = {
  capacity: '5 Litre',
  customerMessage: function (desiredSize) {
    if (desiredSize > 5) {
      return 'This bucket is not large enough for you';
    }
  },
};
console.log(bucket.customerMessage(13));

// Output -
```

10. What does the following code print to the console?

```jsx
function globalFunction() {
  return 'I can be called anywhere';
}
let obj = {
  func: globalFunction,
};
console.log(obj.func());

// Output -
```

11. What does the following code print to the console?

```jsx
let student = {
  age: 21,
  address: {
    city: 'Dharamshala',
    state: 'Himachal Pradesh',
  },
};
console.log(student.address.city);

// Output -
```

12. What does the following code print to the console?

```jsx
let student = {
  age: 21,
  address: {
    city: 'Dharamshala',
    state: 'Himachal Pradesh',
  },
};
student.address.zip = '176057';
console.log(student.address.zip);

// Output -
```

13. What does the following code print to the console?

```jsx
let student = {
  age: 21,
  address: {
    city: 'Dharamshala',
    state: 'Himachal Pradesh',
  },
};
console.log(student);
delete student.age;
console.log(student);

// Output -
```

14. What does the following code print to the console?

```jsx
var altcampus = {
  batch16: {
    totalStudents: '11',
  },
  batch15: {
    totalStudents: '9',
  },
  batch14: {
    totalStudents: '8',
  },
};
console.log(altcampus.batch16.totalStudents);

// Output -
```

15. What does the following code print to the console?

```jsx
var obj = {
  name: 'Panther',
};
console.log('name' in obj);

// Output -
```
