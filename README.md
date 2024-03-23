# Ex03 Time Table
## Date:14/03/2024

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
		<title>Sample Web Page</title>
	</head>
	<body>
	<table border="3" cellspacing="5" cellpadding="6" width="1200" height="50">
        <img src="logo.png" height="200" width="1200">
	</br>>
		<caption>SLOT TIMETABLE-SAMAKASH.R.S(212223230182)</caption>
		<tr bgcolor="yellow">
			<th>Day/time</th>
			<th>Monday</th>
			<th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
		</tr>
		<tr>
			<td bgcolor="red">8-10</td>
			<td bgcolor="mid blue">FREE SLOT</td>
			<td bgcolor="mid blue">ADVANCED C PROGRAMMING</td>
            <td bgcolor="mid blue">FREE SLOT</td>
            <td bgcolor="mid blue">FREE SLOT</td>
            <td align="center" bgcolor="mid blue">FWAD</td>
		</tr>
		<tr>
			<td bgcolor="red">10-12</td>
			<td bgcolor="mid blue">FREE SLOT</td>
			<td bgcolor="mid blue">PYHTON PROGRAMMING</td>
            <td bgcolor="mid blue">COMPUTER NETWORKS</td>
            <td bgcolor="mid blue">ADVANCED C PROGRAMMING</td>
            <td align="center" bgcolor="mid blue">EDM</td>
		</tr>
		<tr>
			<td bgcolor="red">12-1</td>
			<td colspan="5" align="center" bgcolor="mid blue">LUNCH</td>
		</tr>
        <tr>
			<td bgcolor="red">1-3</td>
			<td bgcolor="mid blue">FREE SLOT</td>
			<td align="center" bgcolor="mid blue">FWAD</td>
            <td bgcolor="mid blue">FREE SLOT</td>
            <td align="center" bgcolor="mid blue">FWED</td>
            <td bgcolor="mid blue">PYTHON PROGRAMMING</td>
		</tr>
        <tr bgcolor="mid blue">
			<td bgcolor="red">3-5</td>
			<td>FREE SLOT</td>
			<td align="center">FREE SLOT</td>
            <td>PYTHON PROGRAMMING</td>
            <td align="center">EDM</td>
            <td align="center">FREE SLOT</td>
		</tr>
        </table>
        </bR>
	<table border="2" cellspacing="5" cellpadding="10" width="1200" height="50">
		<tr>
			<th>S.NO</th>
			<th>SUBJECT CODE</th>
			<th>SUBJECT NAME</th>
		</tr>
		<tr>
			<td align="center">1</td>
			<td align="center">19AI414</td>
			<td align="center">FWAD</td>
		</tr>
		<tr>
			<td align="center">2</td>
			<td align="center">19AI305</td>
			<td align="center">ADVANCED C PROGRAMMING</td>
		</tr>
		<tr>
			<td align="center">3</td>
			<td align="center">19AI301C</td>
			<td align="center">PYTHON PROGRAMMING</td>
		</tr>
		<tr>
			<td align="center">4</td>
			<td align="center">19CS406</td>
			<td align="center">COMPUTER NETWORKS</td>
		</tr>
		<tr>
			<td align="center">5</td>
			<td align="center">19AI302</td>
			<td align="center">EDM</td>
		</tr>
	</body>
</html>
```
## OUTPUT
![Screenshot 2024-03-14 153128](https://github.com/Samakas/slot/assets/154731670/bb4130af-128e-40e4-bee9-c8adc10c150d)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
