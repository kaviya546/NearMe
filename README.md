# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
'''
      
      <html>

     <head>
   
    <title> My City</title>
    
     </head>

     <body>

    <h1 align="center"> 
    
    <font color="red"><b> Gingee</b></font>
    
    </h1>
    
    <h3 align="center">
    
    <font color="blue"><b>Daisy R (212223220016)</b></font>
    
    </h3>
    
    <center>
    
    <img src="Gingee.png" usemap="#MyCity" height="610" width="1450">
    
    <map name="MyCity">
    
    <area shape="circle" coords="700,250,850,400" href="church.html" title="My Home">
    
    <area shape="circle" coords="570,230,45" href="school.html" title="My School">
    
    <area shape="circle" coords="640,200,30" href="ground.html" title="Ground">
    
    <area shape="circle" coords="1120,360,25" href="church.html" title="Church">
    
    </center>
    
    </map>
    </body>
    </html>


## OUTPUT
![Screenshot 2024-04-10 174103](https://github.com/kaviya546/NearMe/assets/150368823/26c9c3d2-a113-4034-91b8-764298f40c01)

![alt text](<daisy/mapapp/static/Screenshot 2024-04-10 141518.png>)
![alt text](<daisy/mapapp/static/Screenshot 2024-04-10 141753.png>)
![alt text](<daisy/mapapp/static/Screenshot 2024-04-10 141819.png>)
![alt text](<daisy/mapapp/static/Screenshot 2024-04-10 141938.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
