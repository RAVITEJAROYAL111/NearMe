# Ex03 Places Around Me
## Date: 29-11-2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
    <head align="center">
       <h1 align="center"> KRISHNAGIRI </h1>
       <h3 align="center">Siva (25007668)</h3> 
       <img src="Screenshot 2025-11-26 113451.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="childeren's park" title="childeren's park" href="park.html" coords="81,268,277,373" shape="rect">
    <area target="" alt="mount view inn" title="mount view inn" href="mount.html" coords="585,358,119" shape="circle">
    <area target="" alt="Goverment Museum" title="Goverment Museum" href="museum.html" coords="944,487,1059,420,1193,521,1193,633,959,624" shape="poly">
    <area target="" alt="KGN mobile " title="KGN mobile " href="mobile.html" coords="799,274,1011,362" shape="rect">
    <area target="" alt="Balakrishnan Fish Farm" title="Balakrishnan Fish Farm" href="fish.html" coords="1080,163,118" shape="circle">
</map>
       
    </head>
    <body>

    </body>
</html>
```

## OUTPUT
<img width="1909" height="1080" alt="Screenshot 2025-11-29 131548" src="https://github.com/user-attachments/assets/0e905600-3705-4595-aac0-a4babb3accba" />








## RESULT
The program for implementing image maps using HTML is executed successfully.
