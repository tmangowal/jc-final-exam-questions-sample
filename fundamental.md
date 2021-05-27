## Fundamental

#### Q1. Which operator returns true if the two compared values are not equal?

- [ ] <>
- [ ] ~
- [ ] ==!
- [ ] !==

#### Q2. How is a forEach statement different from a for statement?

- [ ] Only a for statement uses a callback function.
- [ ] A for statement is generic, but a forEach statement can be used only with an array.
- [ ] Only a forEach statement lets you specify your own iterator.
- [ ] A forEach statement is generic, but a for statement can be used only with an array.

#### Q3. Which statement creates a new Person object called "student"?

- [ ] var student = new Person();
- [ ] var student = construct Person;
- [ ] var student = Person();
- [ ] var student = construct Person();

#### Q4. How would you reference the text 'avenue' in the code shown?

```js
let roadTypes = ['street', 'road', 'avenue', 'circle'];
```

- [ ] roadTypes.2
- [ ] roadTypes\[3\]
- [ ] roadTypes.3
- [ ] roadTypes\[2\]

#### Q5. What is the result of running this statement?

`console.log(typeof(42));`

- [ ] 'float'
- [ ] 'value'
- [ ] 'number'
- [ ] 'integer'

#### Q6. You're adding error handling to the code shown. Which code would you include within the if statement to specify an error message?

```js
function addNumbers(x, y) {
  if (isNaN(x) || isNaN(y)) {
  }
}
```

- [ ] exception('One or both parameters are not numbers')
- [ ] catch('One or both parameters are not numbers')
- [ ] error('One or both parameters are not numbers')
- [ ] throw('One or both parameters are not numbers')

#### Q7. Which method converts JSON data to a JavaScript object?

- [ ] JSON.fromString();
- [ ] JSON.parse()
- [ ] JSON.toObject()
- [ ] JSON.stringify()

#### Q8. When would you use a conditional statement?

- [ ] When you want to reuse a set of statements multiple times.
- [ ] When you want your code to choose between multiple options.
- [ ] When you want to group data together.
- [ ] When you want to loop through a group of statement.

#### Q9. Which Object method returns an iterable that can be used to iterate over the properties of an object?

- [ ] Object.get()
- [ ] Object.loop()
- [ ] Object.each()
- [ ] Object.keys()

#### Q10. What will be logged to the console?
```js
var a = ['dog', 'cat', 'hen'];
a[100] = 'fox';
console.log(a.length);
```

- [ ] 101
- [ ] 3
- [ ] 4
- [ ] 100

#### Q11. 0 && hi

- [ ] ReferenceError
- [ ] True
- [ ] 0
- [ ] false

#### Q12. Which Variable-defining keyword allows its variable to be accessed (as undefined) before the line that defines it?

- [ ] all of them
- [ ] const
- [ ] var
- [ ] let

#### Q13. Which of the following values is not a Boolean false?

- [ ] Boolean(0)
- [ ] Boolean("")
- [ ] Boolean(NaN)
- [ ] Boolean("false")

#### Q14. Which of the following is not a keyword in JavaScript?

- [ ] this
- [ ] catch
- [ ] function
- [ ] array

#### Q15. Why is it usually better to work with Objects instead of Arrays to store a collection of records?

- [ ] Objects are more efficient in terms of storage.
- [ ] Adding a record to an object is significantly faster than pushing a record into an array.
- [ ] Most operations involve looking up a record, and objects can do that better than arrays.
- [ ] Working with objects makes the code more readable.

**Explanation:** Records in an object can be retrieved using their key which can be any given value (e.g. an employee ID, a city name, etc), whereas to retrieve a record from an array we need to know its index.

#### Q16. How do you import the lodash library making it top-level Api available as the "\_" variable?

- [ ] import \_ from 'lodash';
- [ ] import 'lodash' as \_;
- [ ] import '\_' from 'lodash;
- [ ] import lodash as \_ from 'lodash';

#### Q17. What does the following expression evaluate to?

```js
[] == [];
```

- [ ] True
- [ ] undefined
- [ ] []
- [ ] False

#### Q18. Your code is producing the error: TypeError: Cannot read property 'reduce' of undefined. What does that mean?

- [ ] You are calling a method named reduce on an object that's declared but has no value.
- [ ] You are calling a method named reduce on an object that does not exist.
- [ ] You are calling a method named reduce on an empty array.
- [ ] You are calling a method named reduce on an object that's has a null value.

#### Q19. The following program has a problem. What is it?

```js
var a;
var b = (a = 3) ? true : false;
```

- [ ] The condition in the ternary is using the assignment operator.
- [ ] You can't define a variable without initializing it.
- [ ] You can't use a ternary in the right-hand side of an assignment operator.
- [ ] The code is using the deprecated var keyword.

#### Q20. Why might you choose to make your code asynchronous?

- [ ] to start tasks that might take some time without blocking subsequent tasks from executing immediately
- [ ] to ensure that tasks further down in your code are not initiated until earlier tasks have completed
- [ ] to make your code faster
- [ ] to ensure that the call stack maintains a LIFO (Last in, First Out) structure

#### Q21. Which of these is a valid variable name?

- [ ] 5thItem
- [ ] firstName
- [ ] grand total
- [ ] function

#### Q22. Which choice is valid example for an arrow function?

- [ ] (a,b) => c
- [ ] a, b => {return c;}
- [ ] a, b => c
- [ ] { a, b } => c

#### Q23. Which concept is defined as a template that can be used to generate different objects that share some shape and/or behavior?

- [ ] class
- [ ] generator function
- [ ] map
- [ ] proxy

#### Q24. Which method is called automatically when an object is initialized?

- [ ] create()
- [ ] new()
- [ ] constructor()
- [ ] init()

#### Q25. How would you use the TaxCalculator to determine the amount of tax on \$50?

```javascript
class TaxCalculator {
  static calculate(total) {
    return total * 0.05;
  }
}
```

- [ ] calculate(50);
- [ ] new TaxCalculator().calculate(\$50);
- [ ] TaxCalculator.calculate(50);
- [ ] new TaxCalculator().calculate(50);
