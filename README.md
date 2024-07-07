1. b)using <link> tag
2. b) using p tag
3. b) false
4. b) false
5. c) 10000000000
6. 6   a) const resultA = people.map(person => person.name);
console.log(resultA); // Output: ['John', 'Jane', 'Bob']
    b) const resultB = people.map(person => ({...person, salary: 50000 }));
console.log(resultB);
// Output: 
// [{ "id":1,"name":"John","age":30,"salary":50000},
// {"id": 2,"name": "Jane","age": 25,"salary": 50000},
// {"id": 3,"name": "Bob","age": 40,"salary": 50000}]
    c) const resultB = people.map(person => ({...person, salary: 50000 }));
console.log(resultB);
// Output: 
// [{ "id":1,"name":"John","age":30,"salary":50000},
// {"id": 2,"name": "Jane","age": 25,"salary": 50000},
// {"id": 3,"name": "Bob","age": 40,"salary": 50000}]



7. function main(cb1, cb2, x, y) {
  cb1(x, y);
  cb2(x, y);
}

function cb1(a, b) {
  const sum = a + b;
  console.log("Sum of", a, "and", b, "is:", sum);
}

function cb2(a, b) {
  const diff = a - b;
  console.log("Difference of", a, "and", b, "is:", diff);
}

// Define the numbers x and y
const x = 11;
const y = 4;

// Call the main function with cb1 and cb2 as parameters
main(cb1, cb2, x, y);
```
 x = 11 and y = 4, it will output:
- Sum of 11 and 4 is: 15
- Difference of 11 and 4 is: 7


8. c)map function
10. c) []
11. b) )display : none apply property to element opacity
: 0,while visibility : hidden just remove that
element from dom.

12. a) 4 10 18
13. a) [1,2,3,4]
