# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
<html>
<head>
<title>JavaScript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;

mark1=parseInt(prompt("Enter Subject-1 Mark"));
mark2=parseInt(prompt("Enter Subject-2 Mark"));
mark3=parseInt(prompt("Enter Subject-3 Mark"));
total=mark1+mark2+mark3;
percentage=total/3;
if((percentage>=91)&&(percentage<=100))
{
altert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
alert("B Grade");
}
else
{
alert("RA Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to find Grade Result of a student
</h1>
</body>
</html>

## OUTPUT
![assignment6](https://github.com/Krithikadini/Ex06_Web-Design/assets/127816336/3ca69328-2738-4c5f-b576-b51234f1b8dd)


## RESULT
  Student result using JavaScript is created successfully.
