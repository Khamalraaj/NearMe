# Ex04 Places Around Me
## Date: 29.11.2024

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

<font color="red"><b>Ambattur</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>Khamalraaj S (24901015)</b></font>

</h3>

<center>

I

<img src="ambattur map..png" usemap="#MyCity" height="833" width="1096">

<map name="MyCity">

<area shape="rect" coords="997,165,1059,230" href="home.html" title="My Home Town">
<area shape="rect" coords="461,499,616,700" href="lake.html" title="Ambattur Lake">
<area shape="circle" coords="816,274,7" href="park.html" title="Thangal park">
<area shape="circle" coords="351,139,20" href="temple.html" title="pachaiamman temple">
</map>

</center>

</body>

</html>

home.html

<html>

<head>

<title>MY TOWN</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>Kalliluppam</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>my area</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
    Kallikuppam has developed from being a rural area along the Ambattur - Redhills high road to become one of the important residential localities of Ambattur and Closer to Villivakkam, Korattur, Anna Nagar, Madhavaram, Puzhal, Padi and Avadi, . It was a part of the erstwhile Ambattur Municipality till October 2011.Now as per a G.O., Kallikuppam has become a part of the zone 7, Ambattur, of the Chennai Corporation. Kallikuppam has escalated itself from being a less-known suburb to a decent suburban centre with many iconic projects such as Lake Dugar Towers project Opp Tata Communications and is fast developing on par with the other localities like Anna Nagar. For instance proper roads with reflectors (seen only on ECR) have been completed and the Corporation of Chennai has been carrying on various infrastructure projects
</p>

</body>

</html>

lake.html

<html>

<head>

<title>lake</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>Ambattur</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>Lake</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
    Ambattur aeri, or Ambattur lake, is a rain-fed reservoir which reaches top levels during the monsoon seasons. In November 2008, incessant monsoon rain filled the lake and encroachments on the north and south banks of the lake were demolished. It also caters to the drinking water needs of the Chennai city after Poondi and Chembarambakkam Lake.

    Ambattur Lake is one of a chain of three water bodies, including Korattur Lake and Madhavaram Lake, where surplus water from one is transported to another.

</p>

</body>

</html>

park.html

<html>

<head>

<title>Park</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>Thangal Eri Park</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>Stress buster</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
    Thangal Park is a park located in Chennai, Tamil Nadu. The average rating of this place is 4.30 out of 5 stars based on 2172 reviews. The street address of this place is 45F5+RQQ, Pudur Main Road, Ambattur, Chennai, Tamil Nadu 600053, India. It is about 1.05 kilometers away from the Ambattur railway station.


It has been located in the middle of. 5 Villages. So, many of the people are using this park for the improvement of their health. One small pond is situated in the middle of this park. Can walk, can do exercises by using the objects fixed there. Flower plants, Trees are also planted here to give shelter for the people who are coming here. Altogether, this park is very useful to the public/families, living near the park.

</p>

</body>

</html>

temple.html

<html>

<head>

<title>Temple</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>Ambattur</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>Pachaiamman Temple-Devotional Centre</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">

    Pachaiamman Temple at Thirumalaivayal is located at the northeast of Arunachala hill, it has the best ambiance of all Amman temples. This temple is built amidst a lush forest area with many water bodies running nearby. This temple not only serves as a religious spot but, also a place of tranquility and serenity.
    About 120 years back, this temple was built and recently it is modified. The outer premise of the temple is adorned with 14 statues of guardian angles, even the animals which had helped Goddess Pachai Amman were revered in this temple. There are effigies of an elephant, five horses, and a dog. It is a wide belief that even today, these animals are the watching guardians of Pachai Amman. The temple’s fame reached all over Tamilnadu, after the visit of Sri Ramana Maharishi. 

</p>

</body>

</html>

```


## OUTPUT

![alt text](<Screenshot 2024-11-29 205824.png>)
![alt text](<Screenshot 2024-11-29 205839.png>)
![alt text](<Screenshot 2024-11-29 205846.png>)
![alt text](<Screenshot 2024-11-29 205902.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
