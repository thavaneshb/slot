# Ex03 Time Table
## Date:18/11/2024

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
    <body>
        <img src="logo.png" width="800" height="200">
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>SLOT TIME TABLE-thavanesh(24900957)</caption>
            <tr bgcolor="purple">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td>free slot</td>
                <td>caree devolopment</td>
                <td>maths</td>
                <td>english</td>
                <td>web</td>
            </tr>
            <TR>
                <td>10-12</td>
                <td>english</td>
                <td>DE</td>
                <td>c programing</td>
                <td>maths</td>
                <td>free slot</td>
            </TR>
            <TR>
                <td>12-1</td>
                <td colspan="5" align="center">LUNCH</td>
            </TR>
            <TR>
                <td>1-3</td>
                <td>WEB</td>
                <td>WEB</td>
                <td>Mentor meet</td>
                <td>Cprogram</td>
                <td>de</td>
            </TR>
        </table>
    </body>
</html>
<br>
<html>
    <body>
        <table border="2" cellspacing="15" cellpadding="2">
            <caption>COURSE</caption>
            <tr bgcolor="orange">
                <th>S.No</th>
                <th>COURSE CODE</th>
                <th>COURSE NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19EY708</td>
                <td>CAREER DEVOLPMENT</td>
            </tr>
            <TR>
                <td>2</td>
                <td>19EN101</td>
                <td>ENGLISH</td>
            </TR>
            <TR>
                <td>3</td>
                <td>19MA201</td>
                <td>MATHS</td>
            </TR>
            <TR>
                <td>4</td>
                <td>19CY205</td>
                <td>CHEMISTRY</td>
            </TR>
            <TR>
                <td>5</td>
                <td>19AI414</td>
                <td>WEB</td>
            </TR>
            <TR>
                <td>6</td>
                <td>19AI304</td>
                <td>Cprogram</td>
            </TR>
            <TR>
                <td>7</td>
                <td>19EE404</td>
                <td>DE</td>
            </TR>
        </table>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (35).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
