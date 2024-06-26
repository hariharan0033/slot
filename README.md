# Ex03 Time Table
## Date:03/04/2024

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
<!DOCTYPE html>
<html>
<head>
    <title>Timetable</title>
</head>
<body style="display: flex; flex-direction: column; align-items: center; font-size: 1.5rem;">
    <img src="/static/logo.png" width="40%">
    <h1>HARIHARAN E(212221040052)</h1>
	<table border='3'  cellspacing="4" cellpadding='4'   style="width: 50%;">
		<tr bgcolor="paleblue">
			<th>Day/Time</th>
			<th>Monday</th>
			<th>Tuesday</th>
			<th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
		</tr>
		<tr>
			<td bgcolor="paleblue">8-10</td>
			<td>ET</td>
			<td>WEB</td>
            <td>MERN</td>
            <td>Free</td>
            <td>MERN</td>
		</tr>

		<tr>
            <td bgcolor="paleblue">10-12</td>
			<td>CSA</td>
			<td>MERN</td>
			<td>BEEE</td>
            <td>MPMC</td>
			<td>Free</td>
		</tr>

		<tr>
            <td bgcolor="paleblue">12-1</td>
			<td colspan="5" align="center" bgcolor="#808080">LUNCH</td>
			
		</tr>
		<tr>
            <td bgcolor="paleblue">1-3</td>
			
			<td>BEEE</td>
			<td>MPMC</td>
			<td>WEB</td>
			<td>MERN</td>
			<td>Free</td>
		</tr>
		<tr>
            <td bgcolor="paleblue">3-5</td>
			<td>MERN</td>
			<td>Free</td>
			<td>Free</td>
			<td>ET</td>
			<td>WEB</td>
		</tr>
	</table>
    <br>
    <table border='3' cellspacing="4" cellpadding='4' style="width: 50%;">
		<tr bgcolor="paleblue">
			<th>S.NO</th>
			<th>Subject code</th>
			<th>Subject Name</th>
			
		</tr>
		<tr>
			<td>1.</td>
			<td>19AI414</td>
            <td>Fundamentals of Web Apllication Development</td>
		</tr>

		<tr>
            <td>2.</td>
			<td>19AI512C</td>
            <td>MERN Full Stack</td>
		</tr>

		<tr>
            <td>3.</td>
			<td>19PH206</td>
            <td>Microprocessor and Microcontroller(MPMC)</td>
			
		</tr>
		<tr>
            <td>4.</td>
			<td>19EE305</td>
            <td>Basic Electrical, Electronics Engineering(BEEE)</td>
		</tr>
		<tr>
            <td>5.</td>
			<td>19CH503</td>
            <td>Energy Technology(ET)</td>
		</tr>
        <tr>
            <td>6.</td>
			<td>19EY706</td>
            <td>Company Specific Assessments(CSA)</td>
		</tr>
	</table>
	</body>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot (176).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
