# Ex04 Places Around Me
## Date:
24-APRIL-2025

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
            <font color="blue"><b>Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="pink"><b>Mrudhula (212224040056)</b></font>
        </h3>
        <center>
            <img src="map.png.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="rect" coords="100,350,260,500" href="temple.html" title="Sri Kanchi Kamatchi Amman Temple"> 
                <area shape="rect" coords="1100,400,1260,550" href="temple2.html" title="Arulmigu sri varatharaja perumal kovil"> 
                <area shape="rect" coords="600,380,850,550" href="temple3.html" title="Kailasanathar temple"> 
                <area shape="rect" coords="640,70,760,160" href="lake.html" title="Nathapettai Lake"> 
                <area shape="rect" coords="1240,110,1500,230" href="saree.html" title="A S BABU SAH"> 

            </map>
        </center>
    </body>
</html>

temple.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body style="background-color: #9DC08B;">
        <h1 align="center">
            <font color="black"><b> Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Sri Kanchi Kamatchi Amman Temple</b></font>
        </h3>
        <center><img src="temple.jpg" usemapp="#temple" height="400" width="650"></center>
        <p align="justify">
            <font face="Monospace ,Monaco" size="4">Sri Kanchi Kamakshi Amman Temple, located in Kanchipuram, Tamil Nadu, is a renowned Hindu temple dedicated to Goddess Kamakshi, a form of Parvati.
                 The goddess is seen in a seated yogic posture called Padmasana, symbolizing peace and spiritual strength. It is one of the 51 Shakti Peethas and holds great religious significance.
                  The temple is known for its rich history, intricate architecture, and vibrant festivals, especially the annual Panguni Utsavam.</font>
        </p>
    </body>
</html>

temple2.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body style="background-color: rgb(41, 44, 208)">
        <h1 align="center">
            <font color="black"><b> Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="yellow"><b>Arulmigu sri varatharaja perumal kovil</b></font>
        </h3>
        <center><img src="temple2.jpg" usemapp="#temple" height="400" width="650"></center>
        <p align="justify">
            <font face="Monospace ,Monaco" size="4">Arulmigu Sri Varadharaja Perumal Temple, located in Kanchipuram, Tamil Nadu, is a revered Hindu temple dedicated to Lord Vishnu, known here as Varadharaja Perumal.
                 It stands as one of the 108 Divya Desams, the sacred abodes of Vishnu celebrated in the works of the Alvars. The temple showcases magnificent Dravidian architecture, featuring towering gopurams, intricately carved pillars, and a sacred tank named Anantha Theertham.
                  A unique aspect of the temple is the wooden idol of Varadharaja Perumal, made from the fig tree (Atthi), which is brought out for worship once every 40 years and kept immersed in water otherwise. The temple is also notable for its association with the philosopher Ramanuja, who is believed to have resided here.</font>
        </p>
    </body>
</html>

temple3.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body style="background-color: #cbed0b;">
        <h1 align="center">
            <font color="black"><b> Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Kailasanathar temple</b></font>
        </h3>
        <center><img src="temple3.jpg" usemapp="#temple" height="400" width="650"></center>
        <p align="justify">
            <font face="Monospace ,Monaco" size="4">
                Kailasanathar Temple, located in Kanchipuram, Tamil Nadu, is one of the oldest and most important temples dedicated to Lord Shiva.
                Built by the Pallava king Rajasimha (Narasimhavarman II) in the 8th century, it is famous for its stunning Dravidian architecture, intricate carvings, and sandstone construction.                
                The temple is a masterpiece of early South Indian temple design, featuring beautiful sculptures of deities, lions, and mythical creatures. It holds great historical and spiritual significance, attracting devotees and history lovers alike.</font>
        </p>
    </body>
</html>

lake.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body style="background-color: rgb(255, 255, 255)">
        <h1 align="center">
            <font color="black"><b> Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Nathapettai Lake</b></font>
        </h3>

        <center><img src="lake.jpg"  style="float: center;" usemapp="#lake" height="300" width="1000"></center>
        <p align="justify">
            <font face="Monospace ,Monaco" size="4">Nathapettai Lake is a serene freshwater lake located approximately 6 km from Kanchipuram, Tamil Nadu.
                 Spanning around 2 km in size, it is fed by the Palar River and serves as a vital resource for local fishing communities. The lake supports a diverse range of fish species, including Katla, Theli, Kendai, Keluthi, and the locally favored Kulla Kendai .
                Renowned as a seasonal bird-watching destination, Nathapettai Lake has recorded over 120 bird species, attracting enthusiasts and researchers alike . 
                However, environmental concerns have arisen due to reports of untreated sewage being discharged into the lake, impacting its ecological balance .
                Despite these challenges, the lake remains a peaceful retreat for nature lovers and bird watchers. Its proximity to Kanchipuram's historic temples makes it a worthwhile addition to any travel itinerary.</font>
        </p>
    </body>
</html>

saree.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body style="background-color: #04f93d;">
        <h1 align="center">
            <font color="black"><b> Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>A S BABU SAH</b></font>
        </h3>
        <center><img src="saree.jpg" usemapp="#Saree" height="400" width="650"></center>
        <p align="justify">
            <font face="Monospace ,Monaco" size="4">
                A.S. Babu Sah is a well-known silk saree store located in Kanchipuram, Tamil Nadu, established in 1974. 
                The store specializes in authentic Kanchipuram silk sarees, bridal collections, and traditional nine-yard sarees.
                With its own handloom factory, they ensure the highest quality and craftsmanship in every saree.
                The store has been serving customers for four generations, offering a wide variety of sarees, including bridal, soft silk, and lightweight options.
                Known for its detailed artistry, A.S. Babu Sah is a popular destination for wedding shopping and festive attire. The store's dedication to quality and tradition has earned it a loyal customer base over the years.
                Located in the heart of Kanchipuram, it continues to be a trusted name for those seeking elegant and timeless silk sarees. Whether you're shopping for a wedding or a special occasion, A.S. Babu Sah remains a go-to choice for exquisite sarees.</font>
        </p>
    </body>
</html>

```

## OUTPUT

![Screenshot 2025-04-24 081749](https://github.com/user-attachments/assets/7c81251b-7f35-44e4-ae33-89b690da4621)
![Screenshot 2025-04-24 081831](https://github.com/user-attachments/assets/02231eb5-6494-4bb3-af9b-5721a19038b5)

![image](https://github.com/user-attachments/assets/460d3cba-f0ce-46f2-b8f9-7ec221d89dad)

![image](https://github.com/user-attachments/assets/a4420a1c-892d-486e-8e71-71025554b895)

![image](https://github.com/user-attachments/assets/b03d5d05-6e25-49de-8063-049f60689e6d)

![image](https://github.com/user-attachments/assets/216c6f28-77b0-4ef2-9813-cead5492b0c3)

![image](https://github.com/user-attachments/assets/60e91ae4-e610-4bb0-a439-85d519ff7f81)



## RESULT
The program for implementing image maps using HTML is executed successfully.
