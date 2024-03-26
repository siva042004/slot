# Ex03 Time Table
## Date:17-3-24

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
<title> Sample Super  Web</title>
</head>
<img src="logo.png" height="200" width="1200">
<table border ="2" cellpadding="2" width="400" heigth="400" bgcolor="light brown">
<caption> <h2>Camu Schedule-Sivaragul(212221040155) </h2></caption>
<tr>


<th>Date</th>
<th>MONDAY</th>
<th>TUESDAY</th>
<th>WEDNESDAY</th>
<th>THURSDAY</th>
<th>FRIDAY</th>
<th>SATURDAY</th>


</tr>
<tr>
<td>8-10</td>
<td>MAD</td>
<td>3D</td>
<td>CD</td>
<td>MAD</td>
<td>FWAD</td>
<td rowspan="2">FREE</td>

</tr>
<tr>
<td>10-12</td>
<td>CD</td>
<td>SPM</td>
<td>GP</td>

<td>SPM</td>
<td>GP</td>

</tr>
<tr>

<td>12-1</td>

<td colspan="6" align="center"> LUNCH BREAK</td>


</tr>

<tr>

<td>1-3</td>
<td>EES</td>
<td>FWAT</td>
<td>AI</td>
<td>FWAD</td>
<td>FREE</td>
<td rowspan="2">FREE</td>

</tr>
<tr>
<td>3-5</td>
<td>AI</td>
<td>FREE</td>
<td>3D</td>
<td>FREE</td>
<td>FREE</td>
</tr>


</table>
<table border ="2" cellpadding="2" width="400" heigth="400" >
<tr>
<th>S.no</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td>1</td>
<td>19CS413</td>
<td>Artifical Intelligence</td>
</tr>
<tr>
<td>2</td>
<td>19CS515</td>
<td>mobile applications</td>
</tr>
<tr>
<td>3</td>
<td>19AI414</td>
<td>Fundamental Of web Development</td>
</tr>
<tr>
<td>4</td>
<td>19ME304</td>
<td>3d printing</td>
</tr>
<tr>
<td>5</td>
<td>19cs403</td>
<td>complier desisn</td></tr>
<tr>
<td>6</td>
<td>19ai405</td>
<td>game programming</td>
</tr>
</table>
</body>
</html>

</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-18 231343.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
