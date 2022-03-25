# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
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

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
|'Joe' 'Ford' 39| {firstName: 'Joe', lastName: 'Ford', age: 79} |
|'Sally' 'Mustang' '38'| {firstName: 'Sally', lastName: 'Mustang', age: 38} |
|'Edgar' 'Explorer' '19'|{firstName: 'Edgar', lastName: 'Explorer', age: 19} |

<table>
  <tr>
    <th>What does this program do?</th>
    <td>Evaluates the entered firstName, lastName, and age in order to return the person object</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
