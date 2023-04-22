# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
Developed by: Manoj S
Reg no : 212222100025
```
```
<!DOCTYPE html>
<html lang=en>
    <head>
        <title>TIME TABLE</title>
    </head>
    <body >
        <center>
        <img src="logo.png" height="100" width="540" ><br>
        <caption><b>SLOT TIME TABLE - MANOJ S (212222100025)</b></caption> </center>
        <table border="5px" align="center" bgcolor="cyan">
            <tr bgcolor="yellow" align="center" >
                <td>Day/time</td>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>Wednesday</td>
                <td>Thursday</td>
                <td>Friday</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">8-10</td>
                <td>FWAD</td>
                <td>C Prog</td>
                <td>FREE SLOT</td>
                <td>KDR</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">10-12</td>
                <td>FWAD</td>
                <td>PMC</td>
                <td>PQM</td>    
                <td>PQM</td>
                <td>KDR</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">12-1</td>
                <td colspan="5"align="center">LUNCH</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">1-3</td>
                <td>EHT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>PMC</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">3-5</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>C Prog</td>
                <td>FREE SLOT</td>
                <td>EHT</td>
            </tr>
        </table>
        <table border="2" align="center" cellspacing="2" cellpadding="4">
            <th>S.NO</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
            <tr align="center">
                <td>1</td>
                <td>19A1414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr align="center">
                <td>2</td>
                <td>19EE309</td>
                <td>Programming Microcontrollers(PMC)</td>
            </tr>
            <tr align="center">
                <td>3</td>
                <td>19MA333</td>
                <td>Probability and Queueing Models(PQM)</td>
            </tr>
            <tr align="center">
                <td>4</td>
                <td>19AI304</td>
                <td>Fundamentals of nC Programming(C Prog)</td>
            </tr>
            <tr align="center">
                <td>5</td>
                <td>19AI534</td>
                <td>Kinematics and Dynamics of Robotics(KDR)</td>
            </tr>
            <tr align="center">
                <td>6</td>
                <td>19CS417</td>
                <td>Ethical Hacking Techniques(EHT)</td>
            </tr>
        </table>  
    </body>
</html>
```
# OUPUT
![output-image](Timetable-output.png)

# HTML VALIDATOR
![validator](valid.png)

# RESULT
The program for creating slot time table is completed successfully.