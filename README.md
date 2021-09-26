# JavaScript Interview Questions

## 1. What will the code below output to the console and why?
```
const person = {
  age: 20,
  name: 'Ben'
};

const peopleArray = [person, person, person];
peopleArray[1].name = 'Joe';
console.log(peopleArray[0].name);
```

## 2. What will the code below output to the console and why?
```
const carOne = {
  color: 'blue',
  status: {
    running: true,
    passengers: 4,
    wiperFluid: 'empty'
  },
  age: 5,
  miles: 50000,
  value: '8000'
}

const carTwo = {
  color: 'green',
  status: {
    running: 'yes',
    passengers: 2,
    fuelTank: 'empty'
  },
  value: 9000
}

const combinedCar = {
...carOne,
...carTwo
}

console.log(combinedCar);
```

## 3. To what evaluates typeof a and typeof b in the following snippet:
```
function foo() {
  let a = b = 0;
  a++;
  return a;
}
foo();
typeof a; // => ???
typeof b; // => ???
```

## 4. What is the content of numbers array:
```
const length = 4;
const numbers = [];
for (var i = 0; i < length; i++);{
  numbers.push(i + 1);
}
numbers; // => ???
```