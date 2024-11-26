# Ex04 Places Around Me
## Date: 23.11.24

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
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>SIRKALI</b></font>
</h1>  
<h3 align="center">
<font color="black"><b>CHARITHRAKSHI K (24900651)</b></font>
</h3> 
<center>
<img src="Map.png" usemap="#MyCity">
<map name="MyCity">
    
        <area target="_blank" alt="vivekananda college" title="vivekananda college" href="college.html" coords="785,916,93" shape="circle">
        <area target="_blank" alt="sirkali new bustand" title="sirkali new bustand" href="bustand.html" coords="905,582,59" shape="circle">
        <area target="_blank" alt="Brahmapureeswarar temple" title="Brahmapureeswarar temple" href="temple.html" coords="1005,261,80" shape="circle">
        <area target="_blank" alt="Grand white palace" title="Grand white palace" href="hotel.html" coords="794,171,52" shape="circle">
        <area target="_blank" alt="sirkali church" title="sirkali church" href="church.html" coords="1490,798,58" shape="circle">
    </map>
</map>  
</map>
</center> 
</body>
</html>

college.html

<html>
    <head>
        <title>Sirkali Church</title>
    </head>
    <body bgcolor="green"></bgcolor>
        <h1 align="center">
            <font color="red">
                SIRKALI
            </font>
        </h1>
    <h3 align="center">
        <font color="blue">
        VIVEKNANDA ARTS AND SCIENCE COLLEGE
    </font></h3>
<h3>Vivekananda Arts and Science College for Women, Nagapattinam Tamil Nadu is a recognised college. Vivekananda Arts and Science College for Women is situated in Nagapattinam of Tamil Nadu state (Province) in India. Vivekananda Arts and Science College for Women, Nagapattinam is affiliated to Bharathidasan University, Tiruchirappalli and approved by University Grants Commission. Vivekananda Arts and Science College for Women, Nagapattinam was established in 2004</h3>
</body>
</html>

church.html

<html>
    <head>
        <title>Sirkali Church</title>
    </head>
    <body bgcolor="yellow"></bgcolor>
        <h1 align="center">
            <font color="red">
                SIRKALI
            </font>
        </h1>
    <h3 align="center">
        <font color="blue">
        Sirklali Church
    </font></h3>
    <h3>The church is a place of worship and spiritual community for believers in the Christian faith. It serves as a sanctuary where individuals gather to express their devotion to God through prayer and reflection and participate in religious rituals and ceremonies. Churches can take many forms. But they all share a common purpose: to provide a sacred space for people to encounter the divine and grow in their faith. At the heart of the church is the congregation, a community of believers who come together to worship and support one another in their spiritual journey</h3>
    </body>
</html>

bustand.html

<html>
    <head>
        <title>Sirkali Church</title>
    </head>
    <body bgcolor="pink"></bgcolor>
        <h1 align="center">
            <font color="red">
                SIRKALI
            </font>
        </h1>
    <h3 align="center">
        <font color="blue">
        Sirklali New Bustand
    </font></h3>
<h3>Renovation of Sirkazhi bus stand to be completed in nine months
    The work has been taken up under the Kalaignar Nagarpura Membattu Thittam and includes construction of new bus bays, restaurants, two-wheeler parking facilities and office buildings</h3>
</body>
</html>

hotel.html

<html>
    <head>
        <title>Sirkali Church</title>
    </head>
    <body bgcolor="white"></bgcolor>
        <h1 align="center">
            <font color="red">
                SIRKALI
            </font>
        </h1>
    <h3 align="center">
        <font color="blue">
        THE GRAND WHITE PALACE
    </font></h3>
<h3>The Grand White Palace Sirkazhi hotel includes 29 rooms and is 6 km from Vaitheeswaran Kovil Shrine to Mars. The hotel also provides car rentals to explore the area.

Sirkazhi centre can be reached within 5 minutes' walk. Swetharanyeswarar Temple is 15 minutes' drive from this 3-star hotel and Pondicherry airport is 95 km away. No matter the religion, travellers prefer to visit Vaidyanathaswamy Temple, a popular place of worship located 15 minutes by car from the accommodation. Also, Sirkazhi Stand bus station is a few minutes' drive from The Grand White Palace hotel.</h3>
</body>
</html>

temple.html

<html>
    <head>
        <title>Sirkali Church</title>
    </head>
    <body bgcolor="cyan"></bgcolor>
        <h1 align="center">
            <font color="red">
                SIRKALI
            </font>
        </h1>
    <h3 align="center">
        <font color="blue">
        BRAHMAPUREESWARAR TEMPLE
    </font></h3>
<h3>Sattainathar temple, Sirkazhi (also called Brahmapureeswarar temple and Thoniappar temple) is a Hindu temple dedicated to Shiva located in Sirkali, Tamil Nadu, India.[1] The temple is incarnated by the hymns of Thevaram and is classified as Paadal Petra Sthalam. It is an ancient temple complex with three different Shiva shrines in three stories.</h3>
</body>
</html>

```

## OUTPUT

![alt text](<Screenshot 2024-11-25 143732-2.png>)
![alt text](<Screenshot 2024-11-25 143722-1.png>)
![alt text](<Screenshot 2024-11-25 143925.png>)
![alt text](<Screenshot 2024-11-25 143938.png>)
![alt text](<Screenshot 2024-11-25 144004.png>)
![alt text](<Screenshot 2024-11-25 144017.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
