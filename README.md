# EX 04 Places Around Me
## Date: 23.11.25
## Developed by : Kamlesh Y
## Register No. : 212224100029
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

## CODE :
### map.html :
```
<html>
<head>
    <title>My City</title>
</head>
<body> 
    <h1 align="center"><font color="Black"><b>Perambur</b></font></h1>
    <h2 align="center"><font color="Black"><b>Akash G (212224100004)</b></font></h2>
    <center>
        <img src="map.png" usemap="#MyCity" height="610" width="1243">

        <map name="MyCity">
            <area target="_blank" 
                  alt="Spectrum Mall" 
                  title="Spectrum Mall" 
                  href="spectrum.html" 
                  coords="300,200,350,250" 
                  shape="rect">

            <area target="_blank" 
                  alt="Perambur Railway Station" 
                  title="Perambur Railway Station" 
                  href="railway.html" 
                  coords="500,300,550,350" 
                  shape="rect">

            <area target="_blank" 
                  alt="Perambur Bus Depot" 
                  title="Perambur Bus Depot" 
                  href="busdepot.html" 
                  coords="700,250,750,300" 
                  shape="rect">

            <area target="_blank" 
                  alt="Our Lady of Lourdes Shrine" 
                  title="Our Lady of Lourdes Shrine" 
                  href="lourdes.html" 
                  coords="900,350,950,400" 
                  shape="rect">

            <area target="_blank" 
                  alt="Sembium Police Station" 
                  title="Sembium Police Station" 
                  href="sembiumpolice.html" 
                  coords="1100,150,1150,200" 
                  shape="rect">

        </map>
    </center>
</body>
</html>
```

### home.html :

```
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="white" align="center">
        <h2 align="center">
            <font color="black"><b>MY HOME</b></font>
        </h2>
        <hr size="3" color="black">
        <img src="myhome.png" alt="My Home" width="1100" height="500">
        <p align="justify" style="line-height: 1.5;">
            <font face="Georgia" size="5" color="black">
                I live in Perambur, a prominent locality in Chennai, Tamil Nadu, India. It is known for its rich cultural heritage and bustling markets. The area is well-connected by road and rail, making it a convenient place to live. Perambur boasts several educational institutions, parks, and shopping centers, providing residents with ample amenities. The community here is diverse and vibrant, contributing to the unique charm of the neighborhood. Overall, Perambur is a wonderful place to call home.
            </font>
        </p>
    </body>
</html>
```

### mall.html :
```
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="white" align="center">
        <h2 align="center">
            <font color="black"><b>Spectrum Mall</b></font>
        </h2>
        <hr size="3" color="black">
        <img src="mall.png" usemap="#My Home Town" width="900" height="500" >
        <p align="justify" style="line-height: 1.5;">
            <font face="Georgia" size="5"> 
                Spectrum Mall, located in Perambur, Chennai, is one of the most popular shopping and entertainment destinations in the area. The mall features a wide range of retail stores, dining options, and family-friendly attractions, making it a favorite spot for both locals and visitors. It also houses S2 Cinemas, offering a modern movie-going experience. With its convenient location, spacious design, and vibrant atmosphere, Spectrum Mall provides a complete and enjoyable outing for people of all ages.
        </p>
    </body>

```
### rail.html :
```
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="white" align="center">
        <h2 align="center">
            <font color="black"><b>Perambur Railway Station</b></font>
        </h2>
        <hr size="3" color="black">
        <img src="rail.png" usemap="#My Home Town" width="900" height="500" >
        <p align="justify" style="line-height: 1.5;">
            <font face="Georgia" size="5"> 
            Perambur Railway Station is one of the oldest and most important railway stations in Chennai, Tamil Nadu. It serves as a major suburban hub on the Chennai Central to Arakkonam line, connecting thousands of daily commuters to various parts of the city and beyond. The station is known for its spacious platforms, good connectivity, and its proximity to the Integral Coach Factory, one of India's largest train-coach manufacturing units.    
        </p>
    </body>
</html> 
```
### bus.html :
```
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="white" align="center">
        <h2 align="center">
            <font color="black"><b>Perambur Bus Stand</b></font>
        </h2>
        <hr size="3" color="black">
        <img src="bus.png" usemap="#My Home Town" width="900" height="500" >
        <p align="justify" style="line-height: 1.5;">
            <font face="Georgia" size="5"> 
            Perambur Bus Stand is an important transport hub that connects the neighborhood with various parts of Chennai through frequent and reliable bus services. It serves as a convenient point for daily commuters, students, and shoppers, offering easy access to nearby areas such as Ayanavaram, Periyar Nagar, and Purasaiwalkam. The bus stand is usually busy throughout the day and provides essential facilities for passengers. With its central location and good connectivity, Perambur Bus Stand plays a key role in making daily travel smooth and accessible for the community.
        </p>
    </body>
</html> 
```

## OUTPUT :

<img width="1440" height="900" alt="1" src="https://github.com/user-attachments/assets/171a6189-ce57-4c09-b4b2-5e22fc8dff63" />

<img width="1440" height="900" alt="Screenshot 2025-11-23 at 8 55 28 PM" src="https://github.com/user-attachments/assets/93160865-a4d9-4a09-9367-d0d5cac3685f" />

<img width="1440" height="900" alt="Screenshot 2025-11-23 at 9 07 05 PM" src="https://github.com/user-attachments/assets/96a2854b-45ba-43ae-a8ca-f5a4d3b69251" />

<img width="1440" height="900" alt="Screenshot 2025-11-23 at 10 29 11 PM" src="https://github.com/user-attachments/assets/b35400aa-bc6a-4893-8b2d-ef07851ff19f" />

<img width="1440" height="900" alt="Screenshot 2025-11-23 at 10 33 43 PM" src="https://github.com/user-attachments/assets/41739050-f599-4db4-86ce-1d34137d0e1a" />

<img width="1853" height="993" alt="image" src="https://github.com/user-attachments/assets/f24a07a9-157b-4029-a213-ae70d68fa48b" />

## RESULT
The program for implementing image maps using HTML is executed successfully.
