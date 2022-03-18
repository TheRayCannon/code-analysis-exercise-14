# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

| Input | Output |
| ------------ | ------------------------------------------------------------------- |
|    SinisterShawn     |  Welcome back, SinisterShawn!                               | 
|    AwesomeAllison    |  Welcom back, AwesomeAllison!                               | 
|    CuteClyde         |  Hey CuteClyde! Would you like to renew your subscription?  | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program will take the input of someones user name (such as SinisterShawn, AwesomeAllison, or CuteClyde) and run the isActive aray, is the username is found in the array it would return a string "Hello (user), Welcome back!" as the expression user.isActive would be true. If they do not appear in the referenced array "isActive" the expresion would be false and the program would go to the next statement whioch ius an else, and is therefore the only alternattive option for the program, and return the string "Hey (user)! Would yoyu like to renew your subscription?>"</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
