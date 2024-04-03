# Ex03 Time Table
## Date:3-4-2024

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
        <title>SLOT TIMETABLE-LAHARI</title>
</head>
<body bgcolor="yellow">
    <center>
    <img src="/static/logo.png" height="100" width="540">
    </center>
<table border="3" cellspacing="4" cellpadding="6" align="center" bgcolor="lightgrey">
<caption>SLOT TIMETABLE-LAHARI(212223230111)</caption>
            <tr>
               <th bgcolor="pink">Day/Time</th>
               <th bgcolor="pink">Monday</th>
               <th bgcolor="pink">Tuesday</th>
               <th bgcolor="pink">Wednesday</th>
               <th bgcolor="pink">Thursday</th>
               <th bgcolor="pink">Friday</th>
               <th bgcolor="pink">Saturday</th>
          </tr>
           <tr>
               <td>8:00-10:00</td>
               <td>Digital Electronics</td>
               <td>Free Slot</td>
               <td>Maths</td>
               <td>fundamental of web applications</td>
               <td>fundamental of web applications</td>
               <td>Free slot</td>
          </tr>
          <tr>
               <td>10:00-12:00</td>
               <td>English</td>
               <td>C programming</td>
               <td>Creative Skills</td>
               <td>C programming</td>
               <td>Computer Networks</td>
               <td>Free Slot</td>
          </tr>
          <tr>
               <td>12:00-1:00</td>
               <td colspan="6" align="center" bgcolor="skyblue">Lunch</td>
          </tr>
          <tr>
               <td>1:00-3:00</td>
               <td>Computer Networks</td>
               <td>Physics</td>
               <td>Physics</td>
               <td>Free Slot</td>
               <td>English</td>
               <td>Free Slot</td>

          </tr>
          <tr>
               <td>3:00-5:00</td>
               <td>Maths</td>
               <td>fundamental of web applications</td>
               <td>Free Slot</td>
               <td>Digital Electronics</td>
               <td>Free Slot</td>
               <td>Free Slot</td>
         
          </tr>
<table border="3" cellspacing="4" cellpadding="6" align="center" bgcolor="lightgrey">
<caption>SUBJECT DETAILS</caption>
          <tr>
               <th bgcolor="pink">S.no</th>
               <th bgcolor="pink">Subject Code</th>
               <th bgcolor="pink">Subject Name</th>
               
          </tr>
          <tr>
               <td>01</td>
               <td>19EE404</td>
               <td>Digital Electronics</td>
           </tr>
            <tr>
               <td>02</td>
               <td>19AI304</td>
               <td>Fundamentals of C programming</td>
           </tr> <tr>
               <td>03</td>
               <td>19AI414</td>
               <td>Fundamentals of web</td>
           </tr>
            <tr>
               <td>04</td>
               <td>19PH214</td>
               <td>Physics for quantum computing</td>
           </tr>
             <tr>
               <td>05</td>
               <td>19CS406</td>
               <td>Computer Networks</td>
           </tr>
            <tr>
               <td>06</td>
               <td>19EN101</td>
               <td>English</td>
           </tr>
            <tr>
               <td>07</td>
               <td>19EY702</td>
               <td>Creative Skills</td>
           </tr>
            <tr>
               <td>08</td>
               <td>19MA222</td>
               <td>Maths</td>
           </tr>
          
</body>
</html>
```

## OUTPUT:

![WhatsApp Image 2024-04-03 at 20 56 58_ec9eeac3](https://github.com/AnnaLahari/slot/assets/149365425/98f75d1f-0428-4973-b817-85f16a4a43f9)



## RESULT:
The program for creating slot timetable using basic HTML tags is executed successfully.
