"// Get the input from the user
const num1 = prompt(""Enter the first number: "");
const num2 = prompt(""Enter the second number: "");

// Get the operator from the user
const op = prompt(""Enter the operator (+, -, *, /): "");

// Perform the operation
let result;
if (op == ""+"") {
  result = parseFloat(num1) + parseFloat(num2);
} else if (op == ""-"") {
  result = parseFloat(num1) - parseFloat(num2);
} else if (op == ""*"") {
  result = parseFloat(num1) * parseFloat(num2);
} else if (op == ""/"") {
  result = parseFloat(num1) / parseFloat(num2);
} else {
  console.log(""Invalid operator"");
}

// Print the result
console.log(result);
"
![image](https://user-images.githubusercontent.com/120620350/208027096-ca6ba52b-b521-4818-a8e5-64ddd3c34278.png)
