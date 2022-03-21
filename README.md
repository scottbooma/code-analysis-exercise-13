# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input | Output |
| ----- | ------ |
|   ("Scott", "Booma", 27)    | {firstName: "Scott", lastName: "Booma", age: 27 }       | 
|   ("Stephanie", "Booma", 28)    | {firstName: "Stephanie", lastName: "Booma", age: 28 }       | 
|    (1, 2, 3)   | {firstName: 1, lastName: 2, age: 3 }       | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes three inputs, it then creates an object called 'person' and places the first input in a property called 'firstName', the second input in a property called 'lastName', and the third input into a property called 'age'. The output is then that object that was just created. Useful for creating a database of people.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
