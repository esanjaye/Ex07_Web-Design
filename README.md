# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>


## OUTPUT
![Screenshot 2023-05-27 094454](https://github.com/esanjaye/Ex07_Web-Design/assets/127818044/7e6ec656-429a-42b7-8174-066cad64fa04)
![Screenshot 2023-05-27 094358](https://github.com/esanjaye/Ex07_Web-Design/assets/127818044/5af96d96-fd5b-41fa-9fa5-df2dc0d1169e)
![Screenshot 2023-05-27 094415](https://github.com/esanjaye/Ex07_Web-Design/assets/127818044/37a2c1ec-5cfa-42b3-a5e2-512e70097305)
![Screenshot 2023-05-27 094432](https://github.com/esanjaye/Ex07_Web-Design/assets/127818044/7faa1208-a422-4ac6-b601-58aa70f36711)
![Screenshot 2023-05-27 094445](https://github.com/esanjaye/Ex07_Web-Design/assets/127818044/0dc68f49-f334-47fe-9a1b-8233a86f7de2)


## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
