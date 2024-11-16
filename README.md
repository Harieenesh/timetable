# Ex03 Time Table
## Date: 16/11/24

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
<html>
    <head>
        <title>my timetable</title>
    </head>
    <body>
        <center>
            <img src="C:\Users\admin\slot\hari\slotapp\static\logo.png" width="600">
        <b>SLOT TIME TABLE-sha Harieenesh (24002342)</b>
        <TABLE BORDER="1" CELLPADDING="5" BGCOLOR="aqua">
        <tr BGCOLOR="yellow">
            <TH>TIME</TH><th>MON</th><TH>THU</TH><TH>WEN</TH><TH>THR</TH><TH>FRI</TH><TH>SAT</TH>
        </tr>
        <TR>
            <TD BGCOLOR="yellow">08-10</TD>
            <TD colspan="2">-----------------------------------</TD>
            <TD>PYTHON</TD><TD colspan="3">--------------------------------------------</TD>
        </TR>
        <TR>
            <TD BGCOLOR="yellow">10-12</TD>
            <TD>WEB,APP</TD>
            <TD>DATA.S</TD>
            <TD>WEB,AP</TD>
            <TD>PYTHON</TD>
            <TD>PHYSICS</TD><TD>PYTHON</TD>
        </TR>
        <TR>
            <TD COLSPAN="7" ALIGN="CENTER" BGCOLOR="yellow">&LT;12:00-1:00&GT;LUNCH</TD>
        </TR>
        <TR>
            <TD BGCOLOR="yellow">01-03</TD><TD>CAREER</TD><TD>PYTHON</TD><TD>MENTOR MEETING</TD><TD>PHYSICS</TD><TD>DATA.S</TD><TD>WEB,APP</TD>
        </TR>

        </TABLE>
        </center>
    </body>
</html>
'''

## OUTPUT
![Alt text](<Screenshot 2024-11-16 143115-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
