# Ex03 Time Table
## Date:

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
'''
<!DOCTYPE html>
<html>
    <center>
        <head>
            <title>
                SLOT TIMETABLE SEC
            </title>
        </head>
    </center>
    <body>
        <table border="2" cellpadding="5" align="center" bgcolor="skyblue">
            <tr>
                <th>DAY/TIME</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr>
                <th>8:00-10:00</th>
                <td>          </td>
                <td>          </td>
                <td>19AI301C</td>
                <td>         </td>
                <td>          </td>
                <td>          </td>
            </tr>
            <tr>
                <th>10:00-12:00</th>
                <td>19AI414</td>
                <td>19AI403</td>
                <td>19AI414</td>
                <td>19AI301C</td>
                <td>SH3214</td>
                <td>19AI301C</td>
            </tr>
            
            <tr>
                <th>12:00-1:00</th>
                <td>L</td>
                <td>U</td>
                <td>N</td>
                <td>C</td>
                <td>H</td>
                <td></td>
            </tr>
            
            <tr>
                <th>1:00-3:00</th>
                <td>19EY708</td>
                <td>19AI301C</td>
                <td></td>
                <td>SH3214</td>
                <td>19AI403</td>
                <td>19AI414</td>
            </tr>
        </table>
    </body>
</html>
'''


## OUTPUT
![alt text](<Screenshot 2024-11-18 204553.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
