# Ex04 Places Around Me
## Date: 26-11-24

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
<font color="red"><b>Thiruttani</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>MUBARAK R (24900694)</b></font>
</h3>
<center>
    <img src="Screenshot (71).png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="" title="" href="thiruttani.html" coords="903,526,1058,621" shape="rect">
        <area target="" alt="" title="" href="murugantemple.html" coords="861,549,659,549,710,656,879,656,861,549" shape="poly">
        <area target="" alt="" title="" href="palliyakuppam.html" coords="1327,583,1463,734,1514,579" shape="poly">
        <area target="" alt="" title="" href="suryanagaram.html" coords="288,225,500,346" shape="rect">
        <area target="" alt="" title="" href="perungalathur.html" coords="1702,307,1490,412,1663,519" shape="poly">
    </map>
</center>
</body>
</html>

thiruttani.html

<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="blue">
        <h1 allign="center">
            <font color="red"> <b>Tiruvallur</b></font>

        </h1>
        <h3 allign="center">
            <font color="green"> <b>THIRUTTANI</b></font>
        </h3>
        <hr size="3" color="blue">
        <p allign="justify">
            <font face="Georgia" size="40px"></font> 
            </p>
         This town is known for the Tiruttani Murugan Temple, which is a significant pilgrimage site for devotees of the Hindu god of war, Kartikeya. The temple is one of the six Arupadaiveedu, which are the most important abodes of Murugan. During the Sangam era, Tiruttani was called Kundruthoradal. 

    </body>
</html>

murugantemple.html

<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="brown">
        <h1 allign="center">
            <font color="pink"> <b> Tiruvallur</b></font>

        </h1>
        <h3 allign="center">
            <font color="violet"> <b>MURUGANTEMPLE</b></font>
        </h3>
        <hr size="3" color="orange">
        <p allign="justify">
            <font face="Georgia" size="35px"></font>
        Murugantemple in thiruttani is one of the places of temples for murugan god.  
            </p>
            

    </body>
</html>

palliyakuppam.html

<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="gray">
        <h1 allign="center">
            <font color="orange"> <b> Tiruvallur</b></font>

        </h1>
        <h3 allign="center">
            <font color="blue"> <b>PALLIYAKUPAM</b></font>
        </h3>
        <hr size="3" color="black">
        <p allign="justify">
            <font face="Georgia" size="30px"></font>
        This place is one of the nearest village in thiruttani.
            </p>
            

    </body>
</html>

suryanagaram.html

<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="violet">
        <h1 allign="center">
            <font color="yellow"> <b> Tiruvallur</b></font>

        </h1>
        <h3 allign="center">
            <font color="blue"> <b>SURYANAGARAM</b></font>
        </h3>
        <hr size="3" color="black">
        <p allign="justify">
            <font face="Georgia" size="20px"></font>
            Suryanagaram is surrounded by Nagari Block towards North , Pallipattu Block towards west , Arakkonam Block towards East , Vijayapuram Block towards East . Tiruttani , Nagari , Arakkonam , Sholingur are the near by Cities to Suryanagaram. This Place is in the border of the Thiruvallur District and Vellore District.
            </p>
            

    </body>
</html>

perungalathur.html

<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="yellow">
        <h1 allign="center">
            <font color="red"> <b> Tiruvallur</b></font>

        </h1>
        <h3 allign="center">
            <font color="violet"> <b>PERUNGALATHUR</b></font>
        </h3>
        <hr size="3" color="green">
        <p allign="justify">
            <font face="Georgia" size="5"></font>
         </p>
            Perungalathur is known for its strategic position which is located about 30 kilometers from Chennai's city center. It lies along the Chennai-Trichy Highway (NH 45), making it a critical junction for travelers heading towards the southern parts of Tamil Nadu.

    </body>
</html>

```

## OUTPUT
![Screenshot (90)](https://github.com/user-attachments/assets/b0e25558-55ff-4579-a649-9b7b550a96af)

![alt text](<Screenshot (73)-1.png>)
![alt text](<Screenshot (74)-1.png>)
![alt text](<Screenshot (75)-1.png>)
![alt text](<Screenshot (72)-1.png>)
![alt text](<Screenshot (77)-1.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
