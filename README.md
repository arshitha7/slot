# Ex03 Time Table
## Date:15/03/2024

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
        <title>My Time Table</title>
    </head>
    <body>
        <img src="logo.png" height="200" width="710">
    </body>
</html>
<html>
	<head>
		<title>Sample Web Page</title>
	</head>
	<body>
	<table  border="2" cellspacing="5" cellpadding="5" width="700" height="50">
        <caption> </caption>
		<tr>
			<th bgcolor="pink">Day/Time</th>
			<th bgcolor="pink">Monday</th>
			<th bgcolor="pink">Tuesday</th>
                        <th bgcolor="pink">Wednesday</th>
			<th bgcolor="pink">Thursday</th>
			<th bgcolor="pink">Friday</th>

		</tr>
		<tr>
			<td bgcolor="pink">8-10</td>
			<td bgcolor="lightgreen">BEEE</td>
			<th bgcolor="lightgreen" colspan="3">FREE SLOT</th>
                        <td bgcolor="lightgreen">WEB</td>
                        


                        
		</tr>
		<tr>
			<td bgcolor="pink">10-12</td>
			<td bgcolor="lightgreen">FREE SLOT</td>
			<td bgcolor="lightgreen">ML</td>
                        <td bgcolor="lightgreen">PHY</td>
                        <td bgcolor="lightgreen">PROBABLITY</td>
                        <td bgcolor="lightgreen">C PROGRAM</td>

		</tr>
		<tr>
                        <td bgcolor="pink">12-1</td>
			<th  bgcolor="lightgreen" colspan="6">LUNCH</th>

		</tr>
		<tr>
			<td bgcolor="pink">1-3</td>
			<td bgcolor="lightgreen">STOCK</td>
			<td bgcolor="lightgreen">WEB</td>
                        <td bgcolor="lightgreen">ENGLISH</td>
                        <td bgcolor="lightgreen">WEB</td>
                        <td bgcolor="lightgreen">ML</td>

		</tr>
		<tr>
			<td bgcolor="pink">3-5</td>
			<td bgcolor="lightgreen">C PROGRAM</td>
			<td bgcolor="lightgreen">PHYSICS</td>
                        <td bgcolor="lightgreen">STOCK MARKET</td>
                        <td bgcolor="lightgreen">CREATIVE SKILL</td>
                        <td bgcolor="lightgreen">ENGLISH</td>

		</tr>



	</table>
<br>
	<html>
	<head>
		<title>EXP1</title>
	</head>
	<body>
	<table border="3" cellspacing="2" cellpadding="10" width="700" height="60">
        
		<tr>
			<th>S.NO.</th>
			<th>SUBJECT CODE</th>
			<th>SUBJECT NAME</th>
                </tr>
		<tr>
			<td>1</td>
			<td>19AI304</td>
			<td>Fundamentals of C Programming</td>
 
		</tr>
		<tr>
			<td>2</td>
			<td>19AI410</td>
			<td>Introduction to Machine Learning</td>

		</tr>
		<tr>
                        <td>3</td>
			<td>19AI414</td>
			<td>Fundamentals of Web Application Development</td>

		</tr>
                <tr>
                        <td>4</td>
			<td>19EE305</td>
			<td>Basic Electrical,Electronics and Measurement Engineering</td>

		</tr>
                <tr>
                        <td>5</td>
			<td>19EN101</td>
			<td>Communicative English</td>

		</tr>
                <tr>
                        <td>6</td>
			<td>19EY702</td>
			<td>Creative Skill for Communication</td>

		</tr>
                <tr>
                        <td>7</td>
			<td>19MA222</td>
			<td>Probablity and Queueing Models</td>

		</tr>
                <tr>
                        <td>8</td>
			<td>19MS115</td>
			<td>Stock Market and Company Operations</td>

		</tr>
                <tr>
                        <td>9</td>
			<td>19PH214</td>
			<td>Physics for Quantum Computing</td>

		</tr>
	</table>
	</body>
</html>
	</body>
</html>
```

## OUTPUT
![output](<Screenshot (3).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
