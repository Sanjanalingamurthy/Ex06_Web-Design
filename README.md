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
~~~
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
    alert("O Grade");
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
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
~~~

## OUTPUT
![sc1](https://github.com/Sanjanalingamurthy/Ex06_Web-Design/assets/127816526/3394a1bd-155b-44e1-9eaf-b3e2770862b3)
![sc2](https://github.com/Sanjanalingamurthy/Ex06_Web-Design/assets/127816526/4e5a7a56-334c-438d-a8d7-d6d50cdeec17)
![sc3](https://github.com/Sanjanalingamurthy/Ex06_Web-Design/assets/127816526/c13a2125-132b-4bfd-b089-b19785b758cc)
![sc4](https://github.com/Sanjanalingamurthy/Ex06_Web-Design/assets/127816526/13cc5762-d995-4b92-9c51-d0d6256c0404)
![sc5](https://github.com/Sanjanalingamurthy/Ex06_Web-Design/assets/127816526/71551eb7-301d-47fe-9805-e69d68eac250)
![sc6](https://github.com/Sanjanalingamurthy/Ex06_Web-Design/assets/127816526/8503ae80-252b-407f-b7ef-6fe7206958c9)
![sc7](https://github.com/Sanjanalingamurthy/Ex06_Web-Design/assets/127816526/fdc90ec3-4a93-4096-8b2b-0a05f0342fec)


## RESULT
  Student result using JavaScript is created successfully.
