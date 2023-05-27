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
![Screenshot (23)](https://github.com/DSREWINJAYASAMSHAJIN/Ex07_Web-Design/assets/127816515/f30144fe-c522-4f50-8d4b-8716b45ebfa8)
![Screenshot (18)](https://github.com/DSREWINJAYASAMSHAJIN/Ex07_Web-Design/assets/127816515/0ecd4b2d-5a85-4ec9-81a6-f0bf6d910351)
![Screenshot (19)](https://github.com/DSREWINJAYASAMSHAJIN/Ex07_Web-Design/assets/127816515/f3b5b766-f973-477f-bb20-7c637a9b6793)
![Screenshot (20)](https://github.com/DSREWINJAYASAMSHAJIN/Ex07_Web-Design/assets/127816515/781efb85-4e66-4876-b2e3-ac31a680299f)
![Screenshot (21)](https://github.com/DSREWINJAYASAMSHAJIN/Ex07_Web-Design/assets/127816515/ecaf6b80-4e27-4a9b-b54a-c7d0ce2f1933)
![Screenshot (22)](https://github.com/DSREWINJAYASAMSHAJIN/Ex07_Web-Design/assets/127816515/e4586217-8d45-4400-b30c-4e520fe5bddf)


## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
