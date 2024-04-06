# Ex03 Time Table
## Date: 6-4-24

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
              <title> web </title>
              <style>    
               th{
                    border: solid rgb(0, 0, 0);
               }
               td{
                    border: solid cyan 2px;
               }
               .mycolor{
                    background-color: gold;

               }
               #a{
                    background-color: red;
               }
              </style>         
     </head>
     <body bgcolor="white" TEXT="black">
<center>
     <img src="/static/images/logo.png"  height="100" width="1000" align="center" /></center>
          
          <table border= "4" cellspacing="0px" cellpadding="10px" bgcolor=green" align="center" style="color: white; background-color: black;" >
          <CAPTION align=“top” style="color: black;font-weight: bold;"> SLOT TIME TABLE - Kurapati Vishnu Vardhan Reddy(212223040103) </CAPTION>
          <br>
          <br>
               <tr> 
               <th bgcolor="orange" >   DAY/TIME </th>
               <th bgcolor="orange">   MONDAY </th>
               <th bgcolor="orange">   TUESDAY </th>
               <th bgcolor="orange">   WEDNESDAY </th>
               <th bgcolor="orange">   THURSDAY </th>
               <th bgcolor="orange">   FRIDAY </th>
               </tr>
               <tr>
                <th bgcolor="orange"> 8-10 </th>
                <td style="border: solid cyan ;"> CREATIVE SKILLS </td>
                <td> DE</td>
                <td> FREE SLOT </td>
                <td colspan="2" align="center"> FWAD </td>
                
                
               </tr>
               <tr>
                <th bgcolor="orange"> 10-12 </th>
                <td> MAT</td>
                <td> PYTHON </td>
                <td> DE </td>
                <td> CA </td>
                <td> MAT </td>
               </tr>
               <tr>
                <th bgcolor="orange"> 12-1 </th>
                 <td colspan="5" align="center">LUNCH TIME</td>
               </tr>
               <tr>
                <th bgcolor="orange"> 1-3 </th>
                <td> FREE SLOT </td>
                <td> ADV C</td>
                <td> PYTHON </td>
                <td> ADV C </td>
                <td> CA </td>
               </tr>
               
              
              <tr>
               <th bgcolor="orange"> 3-5 </th>
               <td> FREE SLOT </td>
               <td> FWAD </td>
               <td colspan="3" align="center"> FREE SLOT </td> 
              </tr>
           </table>
            <table border= "4" cellspacing="0px" cellpadding="10px"  align="center" >
           <tr>
        <br>    
           <th bgcolor="pink"> S.No </th>
             <th bgcolor="pink"> SUBJECT CODE </th>
           <th bgcolor="pink"> SUBJECT NAME </th>
           </tr>
           <tr> 
           <td class="mycolor"> 1. </td>
           <td class="mycolor"> 19AI414 </td>
           <td id="a"> Fundamental of web application and development(FWAD) </td>
           </tr>
           <tr>
           <td class="mycolor"> 2. </td>
           <td class="mycolor"> 19AI305 </td>
           <td id="a"> Advanced C programming (ADV C) </td>
           </tr>
           <tr>
           <td class="mycolor"> 3. </td>
           <td class="mycolor"> 19MA201 </td> 
           <td id="a"> Calculus and Matrix Algebra(MAT) </td>
           </tr>
           <tr>
           <td class="mycolor"> 4. </td>
           <td class="mycolor"> 19EY702 </td>
           <td id="a"> Creative Skills For Communication </td>
           </tr>
           <tr>
           <td class="mycolor"> 5. </td>
           <td class="mycolor"> 19EE404 </td>
           <td id="a"> Digital Electronics (DE) </td>
           </tr>
           <tr>
           <td class="mycolor"> 6. </td>
           <td class="mycolor"> 19AI301 </td>
           <td id="a"> Python programming </td>
           </tr>
           </table>
              
        </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-04-06 134344.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
