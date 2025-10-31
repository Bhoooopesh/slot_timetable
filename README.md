# Ex03 Time Table

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - BHOOPESH P (24001306)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF AI</td>
<td>PROTOTYPE OF IOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>OPERATING SYSTEM</td>
<td>OPERATING SYSTEM</td>
<td>FREE SLOT</td>
<td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
<td>PROTOTUPE OF IOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>FREE SLOT</td>
<td>HRM</td>
<td>MENTOR MEET</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>REASONING ABILITY</td>
<td>FREE SLOT</td>
<td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
<td>DBMS</td>
<td>DBMS</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19CS420</td>
<td>Prototype of iot</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI405</td>
<td>Fundamentals of ai (FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS405</td>
<td>operating system</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MS156</td>
<td>HRM</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS404</td>
<td>DBMS</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/a6cd9271-be13-4805-9f62-d3e10fbb907a" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
