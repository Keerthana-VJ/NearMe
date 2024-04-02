# Ex04 Places Around Me
## Date: 02.04.2024

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
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black">Tirupathur</font></h1>
        <h3 align="center">
            <font color="blue">KEERTHANA.V(212223220045)</font></h3>
        <center>
            <img src="map.png"  usemap="#MyCity" height="550" width="1300">
            <map name="MyCity">
                    <area shape="rect" coords="300,150,500,270" href="College.html" title="Sacred Heart College">     
                    <area shape="rect" coords="750,50,250,200" href="Hills1.html" title="Yelagiri Hills">
                    <area shape="rect" coords="800,300,800,350" href="Hills2.html" title="Jawadhu Hills">
                    <area shape="rect" coords="750,150,250,200" href="Temple.html" title="Jalakandeswarar Temple">
                    <area shape="rect" coords="850,50,150,05" href="Observatory.html" title="Vainu Bappu Telescope Observatory">
            </map>
        </center>

    </body>
</html>

College.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirupathur</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Sacred Heart College</font>
    </h3>
    <body bgcolor="yellow" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Sacred Heart College is an affiliated First Grade College of Thiruvalluvar University.It is a minority institution, established and administered by the Salesians of Don Bosco(SDB).The first care of the management is to give Higher Education to the Catholic youth in a Christian atmosphere of peace, justice and social responsibility with a preferential option for the poor among them. The College is also open to students of all castes and creeds other than Catholics. Their religious beliefs are respected in this institution.
        </font>
        </p>
    </body>
</html>

Hills1.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirupathur</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Yelagiri Hills</font>
    </h3>
    <body bgcolor="pink" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Yelagiri Hills is one of the hill stations of Tamil Nadu. Yelagiri hill top can be reached by a winding ghat road, that has 14 hairpin bends.
The seventh hairpin bend is significant, since it offers the view of the slop of the mountain and the green forest covering as a carpet of the hill. Punganur Lake which is an artificial lake made in an are of 56.706 square metres. Boating on the waters of this lake can be an enchanting experience. Other attractions are a children park.Near the Punganoor Lake, a Herbal Farm, is maintained by the forest Department with rare herbals used in the Siddha And Ayurvedic medical treatments.A Good Park is being formed at KODAI VIZHA THIDAL to entertain Tourists.
        </font>
        </p
    </body>
</html>

Hills2.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirupathur</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">Jawadhu Hills</font>
    </h3>
    <body bgcolor="blue" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Malayalee, (Mala means Hills and yalee means rulers) rules of Hills is one of the primitive tribes in India living in Jawadhu and Kalryan Hills of Tamil Nadu. At Keel Cheppli, we can find stone houses, constructed 5000 years before. Jawadhu Hills is spreaded over Tirupathur District and Tiruvannamalai District. Around 80 thousand population live in Jawadhu block. Out of this 98% are from Tribal community and 2% are from other caste, predominantly Dalits and Vanniyars. The hill is around 2315 to 3000 feet higher from sea level. This Jawadhu hills is popular for Sandalwood, Teakwood and Rosewood and different herbal species. Elephants, forest buffalows, monkeys, foxes and deers are availably in plenty as forest animals. These are three bus routes, one from Vellore ,one from Alangayam and another from Tiruvannamalai. From the main road, one has to walk for 3 kms to 10 kms to reach the hamlets. There are 11 panchayats and 229 hamlets with in the radius of 150 square kilometers.
        </font>
        </p>
    </body>
</html>

Temple.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirupathur</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">Jalakandeswarar Temple</font>
    </h3>
    <body bgcolor="purple" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Jalakandeswarar Temple is located in the city of Vellore, precisely within Vellore Fort. It is a Hindu place of worship in honour of Lord Shiva, who also goes by the name of Lord Jalakandeswarar. The temple is a magnificent representation of grand Vijayanagaram Architecture. Besides, one may also observe detailed sculptures dedicated to other Hindu deities such as Lord Vishnu, Goddess Mahalakshmi, Goddess Parvati, Lord Brahma, and Goddess Saraswathi.
The Jalakandeswarar Temple is a highly regarded landmark highlighting the architectural skill of ancient times, while showcasing the significance of special traditions upheld by the Hindu community, which invoke feelings of peace and a connection to the divine. A visit to this site is a delight for devotees, historians, and those who appreciate authentic art.
        </font>
        </p>
    </body>
</html>

Observatory.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirupathur</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="green" size="5.5">Vainu Bappu Telescope Observatory</font>
    </h3>
    <body bgcolor="orange" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The 2.34-m Vainu Bappu Telescope (VBT) is situated in the Javadi hills of Tamilnadu, at an elevation of about 750 m above the mean sea level. It is operated as a National Facility for optical astronomy. It has two foci, an f/3.5 prime focus (with an image scale of 27 arcsec/mm) and an f/13 Cassegrain focus (with a scale of 6.7 arcsec/mm). At the prime focus, CCD cameras are used for imaging with various filters. A high resolution Echelle spectrometer is in operation where the light is fed through an optical fibre from the prime focus directly to the spectrograph slit. A spectral resolution of 70000 has been achieved with the spectrograph in the visible range. By narrowing the slit, it is possible to obtain a spectral resolution better than 100,000. At the Cassegrain focus, an OMR spectrograph is used for low-to medium resolution spectroscopy. A Boller and Chivens CCD spectrograph earlier used for spectroscopy has been converted to a spectro-polarimeter.
        </font>
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Image 1.png>)

![alt text](<Image 2.png>)

![alt text](<Image 3.png>)

![alt text](<Image 4.png>)

![alt text](<Image 5.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
