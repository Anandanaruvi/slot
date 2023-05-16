# Ex03 Time Table

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

## CODE
```
<html>
     <head>
              <title> ARUVI </title>
     </head>
     <body bgcolor="white" TEXT=" blue">
<center>
     <img src="C:\Users\SEC\Downloads\programiz-html-css\programiz-html-css\images\sec.png"  height="100" width="1000" align="center" /></center>
          
          <table border= "4" cellspacing="0px" cellpadding="10px" bgcolor=green" align="center" >
          <CAPTION align=“top”> SLOT TIME TABLE - ARUVI(22001229) </CAPTION>
          <br>
          <br>
               <tr> 
               <th bgcolor="GREEN">   DAY/TIME </th>
               <th bgcolor="yellow">   MONDAY </th>
               <th bgcolor="yellow">   TUESDAY </th>
               <th bgcolor="yellow">   WEDNESDAY </th>
               <th bgcolor="yellow">   THURSDAY </th>
               <th bgcolor="yellow">   FRIDAY </th>
               </tr>
               <tr>
               <th bgcolor="PINK"> 8-10 </th>
                <td> DE</td>
                <td> PHY </td>
                <td> -- </td>
                <td> FWAD </td>
                <td> FWAD </td>
               </tr>
               <tr>
                <th bgcolor="PINK"> 10-12 </th>
                <td> -- </td>
                <td> IDS </td>
                <td> -- </td>
                <td> DE </td>
                <td> IDS </td>
               </tr>
               <tr>
                <th bgcolor="PINK"> 12-1 </th>
                 <td colspan="5" align="center">LUNCH TIME</td>
   td>                               
               </tr>
               <tr>
                <th bgcolor="PINK"> 1-3 </th>
                <td> C P </td>
                <td> -- </td>
                <td> FWAD </td>
                <td> PHY </td>
                <td> CN </td>
               </tr>

               <tr>
               <th bgcolor="PINK"> 3-5 </th>
               <td> STAT </td>
               <td> -- </td>
               <td> CN </td> 
               <td> -- </td> 
               <td> STAT </td>
              </tr>
            </table>
            <table border= "4" cellspacing="0px" 
cellpadding="10px"  align="center" >
            <tr>
           <th> S.No </th>
           <th> SUBJECT CODE </th>
           <th> SUBJECT NAME </th>
           </tr>
           <tr> 
           <td> 1. </td>
           <td> 19AI414 </td>
           <td> Fundamental of web application and development </td>
            </tr>
            <tr>
           <td> 2. </td>
           <td> 19EE404 </td>
           <td> Digital Electronics </td>
           </tr>
           <tr>
           <td> 3. </td>
           <td> 19AI304 </td> 
           <td> Fundamental of C programming </td>
           </tr>
           <tr>
           <td> 4. </td>
           <td> 19PH214 </td>
           <td> Physics for quantum computing </td>
           </tr>
           <tr>
           <td> 5. </td>
           <td> 19CS406 </td>
           <td> Computer Networks </td>
           </tr>
           <tr>
           <td> 6. </td>
           <td> 19MA211 </td>
           <td> Statistics and Numerical methods </td>
           </tr>
           <tr>
           <td> 6.</td>
           <td> 19AI403 </td>
           <td> Introduction to data science</td>
           </tr>
           </table>
              
        </body>
</html>
```
### OUTPUT
                                  
![web timetable](https://github.com/Anandanaruvi/slot/assets/120443233/837622d0-2275-40bf-b32c-dc1c8c6f0eb4)

### HTML VALIDATOR

![ARUVI WEB OUTPUT 3](https://github.com/Anandanaruvi/slot/assets/120443233/9cdda793-7c5c-4b1e-9734-d933fefd1074)

## RESULT

The program for creating slot timetable using basic HTML tags is executed successfully.
