# Ex04 Places Around Me
## Date: 16/04/2025

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
trichy.html
<html>
    <head>
        <title>Trichy</title>
    </head>
    <body>
    <center>
        <h1><font color="red">Famous places in Trichy</font></h1>
        <img src="/static/image.png" usemap="#image-map">
        <map name="image-map">
            <area target="" alt="river" title="river" href="river.html" coords="678,350,831,429" shape="rect">
            <area target="" alt="temple" title="temple" href="srirangam.html" coords="550,118,88" shape="circle">
            <area target="" alt="ganesh" title="ganesh" href="rockfort.html" coords="507,546,616,546,629,601,520,611" shape="poly">
        </map>
    </center>
    </body>
</html>

rockfort.html
<!DOCTYPE html>
<html>
    <head>
        <title>Rock fort</title>
    </head>
    <body bgcolor="teal">
    <center>
        <h1><font color="white">Trichy Rock fort</font></h1><br>
        <img src="/static/image/image1.webp" width="800px" height="400px"><br><br>
        <p><font color="white">The Rockfort is a famous historical and religious landmark located in 
        the heart of Trichy (Tiruchirapalli), Tamil Nadu. Built on a massive ancient rock that is over 3.8 billion years old, 
        it offers a breathtaking view of the city from the top. The fort complex includes two important temples: the Ucchi Pillayar 
        Temple dedicated to Lord Ganesha and the Thayumanaswamy Temple dedicated to Lord Shiva. Climbing the 400+ stone steps to reach 
        the top is a popular activity among visitors and devotees. The Rockfort has great historical significance, having witnessed many 
        battles, especially during the Carnatic Wars. The architecture of the temples and the fort reflects the skill and craftsmanship of 
        ancient builders. It is one of the most visited tourist attractions in Trichy. The Rockfort area is also a bustling commercial center, 
        filled with shops and local life. It combines natural beauty, spirituality, and history in one place. 
        A visit to Trichy is incomplete without experiencing the Rockfort’s grandeur.</font></p>
    </center>
    </body>
</html>

srirangam.html
<!DOCTYPE html>
<html>
    <head>
        <title>Srirangam</title>
    </head>
    <body bgcolor="#33FF99">
    <center>
        <h1>Trichy Srirangam</h1><br>
        <img src="/static/image/srirangam.jpg" width="800px" height="400px"><br><br>
        <p><b>Srirangam</b> is a beautiful and sacred island town located in Trichy, Tamil Nadu. 
        It is surrounded by the Kaveri River and its tributary, the Kollidam, making it a unique and serene place. 
        The town is world-famous for the Sri Ranganathaswamy Temple, one of the largest functioning Hindu temples in the world. 
        This temple is dedicated to Lord Vishnu and is a major pilgrimage site for Vaishnavites. 
        Srirangam is not just a religious spot but also rich in culture, tradition, and heritage. 
        The temple complex has magnificent architecture with tall gopurams (temple towers), intricate carvings, 
        and historical significance. Devotees and tourists visit throughout the year, especially during the Vaikunta Ekadasi festival. 
        The peaceful atmosphere, combined with spiritual energy, makes Srirangam a divine place to experience. 
        It is also home to ancient scriptures, religious scholars, and traditional arts.</p>
    </center>
    </body>
</html>

river.html
<!DOCTYPE html>
<html>
    <head>
        <title>Kaveri river</title>
    </head>
    <body bgcolor="#33FF99">
    <center>
        <h1>Trichy Samayapuram</h1><br>
        <img src="/static/image 3.webp" width="800px" height="400px"><br><br>
        <p><b>The Kaveri River</b> is one of the most important rivers in southern India, and 
        it flows gracefully through the historic city of Trichy (Tiruchirapalli) in Tamil Nadu. 
        In Trichy, the river plays a vital role in supporting agriculture and providing water for daily use. 
        The scenic beauty of the Kaveri enhances the charm of the city, especially near the famous Srirangam Temple, 
        which is located on an island formed by the river. The Kaveri is not just a river but a symbol of life and culture in the region. 
        It supports irrigation for vast stretches of paddy fields and is a key resource for farmers. During festivals like Aadi Perukku,
         people gather along its banks to offer prayers and celebrate. The river’s calm yet powerful flow brings a sense of peace to the locals. 
         Several bridges across the Kaveri connect important parts of Trichy. The river also attracts tourists and nature lovers.
         Overall, the Kaveri River holds spiritual, cultural, and economic importance in Trichy.</p>
    </center>
    </body>
</html>
```
## OUTPUT
![Screenshot 2025-04-22 162534](https://github.com/user-attachments/assets/314da6c2-bf33-4c42-9581-22796b9af2b2)
![Screenshot 2025-04-21 144337](https://github.com/user-attachments/assets/551fb4c4-d8c5-4f9c-b88c-1b66697e1a10)
![Screenshot 2025-04-21 144425](https://github.com/user-attachments/assets/e8a89918-12d0-4659-9391-e87f719cc491)
![Screenshot 2025-04-21 144400](https://github.com/user-attachments/assets/3dc4f0d1-8765-448f-bd36-f205c9ce0aad)

## RESULT
The program for implementing image maps using HTML is executed successfully.
