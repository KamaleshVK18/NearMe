# Ex04 Places Around Me
## Date: 30/11/2024

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
```
map.html
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Poonamallee</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>V Kamalesh Vijayakumar(24011704)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700, 250, 850,400" href="home.html" title="My Home Town">
<area shape="circle" coords="570,230,45" href="temple1.html" title="Kamakshi Amman temple">
<area shape="circle" coords="540, 200, 30" href="theatre.html" title="EVP cinemas">
<area shape="rect" coords="600, 200, 700,500" href="TMZ.html" title="Thirumazhisai">
<area shape="rect" coords="950, 120, 1100, 140" href="temple2.html" title="Sri Kasi Visvanadhar kovil">
</map>
</center>
</body>
</html>
home.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>POONAMALLEE</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>THE TOWN</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Poonamallee is a town and suburb of Chennai, India under the Chennai Metropolitan Area. It was historically called Pushpagirimangalam, later renamed in Tamil as Poovirundhavalli,It is the headquarters of the Poonamallee taluk of the Tiruvallur district in the Indian state of Tamil Nadu.Historically, Poonamallee played a significant role during the Carnatic Wars. The old fort, which no longer exists, was a key military stronghold during this period.In the late 19th century, Poonamallee served as a convalescent depot for British troops stationed across the Madras Presidency and Burma, primarily due to its healthy climate.
</p>
</body>
</html>
temple1.html
<html>
<head>
<title>TEMPLE</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="yellow"><b>KAMAKSHI AMMAN TEMPLE</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>TEMPLE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The Mangadu Kamakshi Amman Temple is a famous pilgrim destination Hindu temple dedicated to goddess Parvathi, in the suburbs of poonamallee.The temple sports the Chola style of Architecture and construction. The Raja Gopuram was a recent addition to the Temple. The Raja Gopuram or the Main entrance faces South and is 7 tiered with great sculptures on it, But the east entrance is still used by many devotees as there is a market along the road leading to the east gate.
</p>
</body>
</html>
temple2.html
<html>
<head>
<title>TEMPLE</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="BLACK"><b>SRI KASI VISVANADHAR TEMPLE</b></font>
</h1>
<h3 align="center">
<font color="red"><b>TEMPLE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
A beautiful twin temple one for Kasi Viswanathar and one for Venugopal Swamy. The temple is in a shambles with structures disintegrating.The temple has Sannidhies in the internal prakaram for Aadhi Shankarar, Varasiddhi Vinayagar, Valli Devasena Samedha Subramania Swamy. Also, there is a sannidhi for Anna poorani and Sri Thripurasundari Samedha Sri Thrikalagnaneshwarar sannidhi. 
</p>
</body>
</html>
theatre.html
<html>
<head>
<title>EVP CINEMAS</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>EVP CINEMAS</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ENTERTAINMENT</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
EVP Cinemas is a movie theater and theater company in Chennai, Tamil Nadu that offers 3D movies, live performances, arcade games, and food. It also has EVP film city adjoining it which is a popular shooting spot and many famous Tamil films have been shot here
</p>
</body>
</html>
TMZ.html
<html>
<head>
<title>THIRUMAZHISAI</title>
</head>
<body bgcolor="black">
<h1 align="center">
<font color="white"><b>THIRUMAZHISAI</b></font>
</h1>
<h3 align="center">
<font color="white"><b>Neighbouring town</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="5" color="white">
Thirumazhisai is a western suburb of Chennai, India. It is located in Thiruvallur district of Tamil Nadu. It is a nearby town to poonamallee.The main attraction of this place is the othandeeswarar temple which is a temple dedication LORD SHIVA.
</p>
</body>
</html>
```


## OUTPUT
![1](https://github.com/user-attachments/assets/8b333a0f-3367-4cfb-95d5-0dab4125b420)
![2](https://github.com/user-attachments/assets/89a01ad1-9604-4953-98e8-08c5e508a527)
![3](https://github.com/user-attachments/assets/cb850074-0697-4cdb-8618-ee5a47298890)
![4](https://github.com/user-attachments/assets/dbf9d980-5df2-4682-9e8f-1663e9b7f607)
![5](https://github.com/user-attachments/assets/04eb825c-babb-43bb-9f18-deef9cf9cd5c)
![6](https://github.com/user-attachments/assets/0e583e4c-f874-4c8b-a6ec-e9f5cfdb0a0a)

## RESULT
The program for implementing image maps using HTML is executed successfully.
