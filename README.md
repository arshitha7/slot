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
	<style>
		#image{
			padding-left: 500px;
		}
		#slot{
			font-size: x-large;
		}
	</style>
    <body>

    
    <img src="logo.png" id="image" height="200" width="900">
    
	<br>
	<br>
	<table  align="center" border="2" cellspacing="5" cellpadding="5" width="900" height="90" bgcolor="lightgreen">
        <caption id="slot"><b>SLOT TIME TABLE-ARSHITHA MS(212223240015)</b> </caption>
		<tr align="center">
			<th bgcolor="pink">Day/Time</th>
			<th bgcolor="pink">Monday</th>
			<th bgcolor="pink">Tuesday</th>
            <th bgcolor="pink">Wednesday</th>
			<th bgcolor="pink">Thursday</th>
			<th bgcolor="pink">Friday</th>

		</tr>
		<tr align="center">
			<th bgcolor="pink">8-10</th>
			<td>BEEE</td>
			<td colspan="3" align="center">FREE SLOT</td>
            <td>WEB</td>
                        


                        
		</tr>
		<tr>
			<th bgcolor="pink">10-12</th>
			<td >FREE SLOT</td>
			<td>ML</td>
            <td>PHY</td>
            <td>PROBABLITY</td>
            <td>C PROGRAM</td>

		</tr>
		<tr>
            <th bgcolor="pink">12-1</th>
			<td  clospan="5" align="center" bgcolor="lightgreen" colspan="6">LUNCH</td>

		</tr>
		<tr>
			<td bgcolor="pink">1-3</td>
			<td>STOCK</td>
			<td>WEB</td>
            <td>ENGLISH</td>
            <td>WEB</td>
            <td>ML</td>

		</tr>
		<tr>
			<td bgcolor="pink">3-5</td>
			<td>C PROGRAM</td>
			<td>PHYSICS</td>
            <td>STOCK MARKET</td>
            <td>CREATIVE SKILL</td>
            <td>ENGLISH</td>

		</tr>



	</table>
<br>
	<table align="center" border="3" cellspacing="2" cellpadding="10" width="900" height="90">
        
		<tr align="center">
			<th>S.NO.</th>
			<th>SUBJECT CODE</th>
			<th>SUBJECT NAME</th>
        </tr>
		<tr>
			<td align="center">1</td>
			<td align="center">19AI304</td>
			<td>Fundamentals of C Programming</td>
 
		</tr>
		<tr>
			<td align="center">2</td>
			<td align="center">19AI410</td>
			<td>Introduction to Machine Learning</td>

		</tr>
		<tr>
            <td align="center">3</td>
			<td align="center">19AI414</td>
			<td>Fundamentals of Web Application Development</td>

		</tr>
        <tr>
            <td align="center">4</td>
			<td align="center">19EE305</td>
			<td>Basic Electrical,Electronics and Measurement Engineering</td>

		</tr>
        <tr>
            <td align="center">5</td>
			<td align="center">19EN101</td>
			<td>Communicative English</td>

		</tr>
        <tr>
            <td align="center">6</td>
			<td align="center">19EY702</td>
			<td>Creative Skill for Communication</td>

		</tr>
        <tr>
            <td align="center">7</td>
			<td align="center">19MA222</td>
			<td>Probablity and Queueing Models</td>

		</tr>
        <tr>
            <td align="center">8</td>
			<td align="center">19MS115</td>
			<td>Stock Market and Company Operations</td>

		</tr>
        <tr>
            <td align="center">9</td>
			<td align="center">19PH214</td>
			<td>Physics for Quantum Computing</td>

		</tr>                
    </table>
	</body>
</html>
```

## OUTPUT
![output](<slot output.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
