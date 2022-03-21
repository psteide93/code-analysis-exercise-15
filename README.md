# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){        
  for (dog in person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

| Input | Output |
| ----- | ------ |
| ({name: "Joe", age: 17, dog: [{name: "Sparky", breed: "German Shepard" }, {name: "Racer", breed: "Husky" }}, "Sparky") |    {name: "Sparky", breed: "German Shepard" } | 
| ({name: "Karen", age: 87, dog: {name: "Cleo", breed: "Chihuaha" }}, "Bean")      |   undefined     | 


<table>
  <tr>
    <th>What does this program do?</th>
    <td> What this function does is it takes an object called person, and looks for a nested object within it called dogs, if the pet name, which is the second parameter of the function, matches the name of the pet in the nested object, it will return the dog object. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
