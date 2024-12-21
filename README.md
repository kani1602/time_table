# Ex03 Time Table
# Date: 2/11/24
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time Table - V. Kanishka (24003362)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: rgb(245, 225, 200);
        }
        h3 {
            margin-top: 20px;
        }
        table {
            border-collapse: collapse;
            margin: 20px auto;
            background-color: rgb(143, 250, 250);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        th, td {
            border: 2px solid black;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: rgb(240, 240, 167);
        }
        .subject-table {
            border: 4px solid black;
            width: 300px;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <center>
        <h3>SLOT TIME TABLE - V. KANISHKA (24003362)</h3>
        <table border="1" width="80%" height="25%">
            <tr>
                <th>Day/Time</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-2</th>
                <th>3-5</th>
            </tr>
            <tr>
                <th>Monday</th>
                <td rowspan="3">Free Slot</td>
                <td>Digital Electronics</td>
                <td rowspan="6">Lunch</td>
                <td>Web Applications</td>
                <td rowspan="2">Free Slot</td>
            </tr>
            <tr>
                <th>Tuesday</th>
                <td>Free Slot</td>
                <td>Python</td>
            </tr>
            <tr>
                <th>Wednesday</th>
                <td>Career Development</td>
                <td>Free Slot</td>
                <td>Chemistry</td>
            </tr>
            <tr>
                <th>Thursday</th>
                <td>Human Values</td>
                <td>Python</td>
                <td>Digital Electronics</td>
                <td>Chemistry</td>
            </tr>
            <tr>
                <th>Friday</th>
                <td rowspan="2">Free Slot</td>
                <td rowspan="2">Web Applications</td>
                <td rowspan="2">Python</td>
                <td rowspan="2">Free Slot</td>
            </tr>
            <tr>
                <th>Saturday</th>
            </tr>
        </table>
        <table class="subject-table">
            <tr>
                <th>S.NO</th>
                <th>Subject Name</th>
                <th>Subject Code</th>
            </tr>
            <tr>
                <td>1</td>
                <td>Fundamentals of Web Applications</td>
                <td>19AI401</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Maths for AI/Python/Linear Algebra</td>
                <td>19MA301</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Principles of Chemistry</td>
                <td>19CY205</td>
            </tr>
            <tr>
                <td>4</td>
                <td>Digital Electronics</td>
                <td>19EE404</td>
            </tr>
            <tr>
                <td>5</td>
                <td>Career Development Skills</td>
                <td>19EY708</td>
            </tr>
            <tr>
                <td>6</td>
                <td>Human Values and Professional Ethics</td>
                <td>SH7801</td>
            </tr>
        </table>
    </center>
</body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2024-12-21 101738.png>)
![alt text](<Screenshot 2024-12-21 101751.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
