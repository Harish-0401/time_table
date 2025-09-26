<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3f1cde27-f4ff-4310-999a-66417d8ed3e2" /># Ex03 Time Table
# Date:26.09.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE HTML>
<html>
    <head>
        <title>Microsoft</title>
        
    </head>
    <body>
        <center>
            <img src="c:\Users\Jesna Karan\Downloads\saveetha logo.png">
            <h1 style="font-size: 20px;">Slot TimeTable Harish S (25010105)</h1> 

        <table border="2" cellpadding="10" cellspacing="3" row="3" style="border-color: black;"> 
            <tr>
                <th bgcolor="brown">DAY</th>
                <th bgcolor="brown">8-10</th>
                <th bgcolor="brown">10-12</th>
                <th bgcolor="brown">1-3</th>
                <th bgcolor="brown">3-5</th>
            </tr>
            <tr>
                <td bgcolor="brown" >MONDAY</td>
                <td bgcolor="cream">Free Period</td>
                <td bgcolor="cream">Fundamentals of web development</td>
                <td bgcolor="cream">Free Period</td>
                <td bgcolor="cream">PYTHON</td>
            </tr>
            <tr>
                <td bgcolor="brown">TUESDAY</td>
                <td bgcolor="cream">Fundamentals of web development</td>
                <td bgcolor="cream">Free Period</td>
                <td bgcolor="cream">Fundamentals of web development</td>
                <td rowspan="4" bgcolor="cream">Free Period</td>
                
            </tr>
            <tr>
                <td bgcolor="brown">WEDNESDAY</td>
                <td rowspan="2" bgcolor="cream">Free Period</td>
                <td rowspan="2" bgcolor="cream">PYTHON</td>
                <td bgcolor="cream">Mentor Meet</td>
              
            </tr>
            <tr>
                <td bgcolor="brown">THURSDAY</td>
                <td bgcolor="cream">Free Period</td>
            </tr> 
            <tr>
                <td bgcolor="brown">FRIDAY</td>
                <td bgcolor="cream">PYTHON</td>
                <td rowspan="2" bgcolor="cream">Free Period</td>
                <td bgcolor="cream">Fundamentals of web development</td>
          
            </tr> 
            <tr>
            <td bgcolor="brown">SATURDAY</td>
                <td bgcolor="cream">Fundamentals of web development</td>
                <td bgcolor="cream">Free Period </td>
                <td bgcolor="cream">PYTHON</td>
              </tr>  
        </center>    
        </table>
        
        <table border="3" cellpadding="10" cellspacing="3" row="3" style="border-color: black;">
            
          <table border="3" style="margin-top:20px;"> 
            <tr>
                <th bgcolor="brown">S No</th>
                <th bgcolor="brown">Subject Code</th>
                <th bgcolor="brown">Subject Name</th>
            </tr>
              <tr>
                <td bgcolor="brown">1</td>
                <td bgcolor="cream">19A1414</td>
                <td bgcolor="cream">Fundamentals of web development</td>
            </tr> 
            <tr>
                <td bgcolor="brown">2</td>
                <td bgcolor="cream">19A1303</td>
                <td bgcolor="cream">PYTHON</td>
            </tr> 

          </table>      
     </body>
</html>
```

# OUTPUT

<img width="1366" height="768" alt="time table" src="https://github.com/user-attachments/assets/40890f50-bf11-4907-ac24-a991609ddf7f" />


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
