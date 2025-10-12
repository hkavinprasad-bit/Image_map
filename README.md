# Ex04 Places Around Me
# Date:12.10.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
'''
imagemap.html

<html>
    <head>
        <title>my college</title>
    </head>
    <body>
        <h1 align="center">Saveetha Engineering college</h1>
        <h3 align="center">H.Kavin prasad (25017492)</h3>
        <img src="college.png" style="width: 1500px;height: 610px;" usemap="#mymap"/>
        <map name="mymap">
            <area shape="rect" coords="500,350,570,515" title="SIMATS" href="simats.html">
            <area shape="rect" coords="777,12,850,152" title="SAVEETHA" href="saveetha.html">            
            <area shape="rect" coords="330,150,450,320" title="UNIVERSITY" href="university.html">
            <area shape="rect" coords="1050,12,1250,110" title="OTTO" href="otto.html">
            <area shape="rect" coords="150,12,330,110" title="CRICKET CLUB" href="cricket.html">
        </map> 
    </body>
</html>

saveetha.html

<html>
    <head>
        <title>Saveetha Engineering College</title>
    </head>
    <body>
        <h1 align="center">SAVEETHA ENGINEERING COLLEGE</h1>
        <p>Saveetha Engineering College is a co-educational Institution. The college is affiliated with Anna University, Chennai, the largest technical university in India.[1] Saveetha Engineering College is granted Autonomous status by University Grants Commission (UGC)., Affiliated to Anna University located in Chennai, India. It was founded in 2001 by the Saveetha Medical and Educational Trust, a registered charitable society. Approved by the All India Council for Technical Education (AICTE), a statutory body of the Government of India, and also by the Government of Tamil Nadu. The campus is facing Chembarambakkam lake on the Chennai-Bangalore National Highway (NH4), Thandalam, Kancheepuram District, Chennai, Pin: 602105. Located about 8 km (5.0 mi) from Poonamalee township.</p>
    </body>
</html>

simats.html

<html>
    <head>
        <title>SIMATS</title>
    </head>
    <body>
        <h1 align="center">SIMATS</h1>
        <p>Saveetha Institute of Medical and Technical Sciences (SIMATS), located in Chennai, is a private university established in 2005. The university has been accredited with an A++ grade by the National Assessment and Accreditation Council (NAAC) and is approved by the University Grants Commission (UGC).
Also Known As: SIMATS
Campus Size: 180+ acres
Establishment Year | Ownership Type: 2005 | Private
Location: Thandalam, Chennai</p>
    </body>
</html>

university.html

<html>
    <head>
        <title>Saveetha University</title>
    </head>
    <body>
        <h1 align="center">SAVEETHA UNIVERSITY</h1>
        <p>Saveetha Institute of Medical And Technical Sciences is a private and deemed-to-be-university located in Chennai, Tamil Nadu, India.It has nine disciplines of studies: Dental College, School of Management, School of Law, School of Engineering, College of Liberal Arts and Sciences, School of Physiotherapy, School of Nursing and Medical College. The first three disciplines are in Poonamalle while the rest are in Thandalam. Saveetha Engineering College is an Anna University-affiliated institution. Admissions are done through Class 12th Indian board examinations.</p>
    </body>
       
</html>

cricket.html

<html>
    <head>
        <title>cricket club</title>
    </head>
    <body>
        <h1 align="center">S11 CRICKET CLUB</h1>
        <p>​S11 Cricket club is a club run by the students of Saveetha Engineering College under the leadership of Mr. Jai mohan raj, who is also a initiator. The club is situated in Thandalam Saveetha Campus. The club won the MOON WALK TOURNAMENT that was held in Chennai and won a cash prize of 1,00,000Rs. It also hosts a lot of tournaments.</p>
    </body>
</html>

otto.html

<html>
    <head>
        <title>OTTO CLOTHING FACTORY</title>
    </head>
    <body>
        <h1 align="center">OTTO CLOTHING FACTORY</h1>
        <p>The Otto Group (Otto GmbH & Co. KGaA) is a German retail company based in Hamburg that operates companies worldwide in the retail, e-commerce, financing, logistics and mail order sectors.In 2023, the Group generated sales of €16.2 billion and had around 41,186 employees.</p>
        <p>The shares in the Group of Michael Otto and his son, Benjamin Otto, have been combined in a foundation since 2016.

The Group operates over 100 companies internationally,primarily in Germany, Europe, and the United States. The activities of the Otto Group's business include e-commerce, over-the-counter retail, and catalogue sales channels. In the 2023 financial year, the Otto Group generated revenue of €16.2 billion, of which around €12 billion was generated online, making the Otto Group one of the largest online retailers in the world.The following is an extract of some subsidiaries</p>
    </body>
</html>

'''
# OUTPUT
<img width="1035" height="436" alt="Screenshot 2025-10-12 193256" src="https://github.com/user-attachments/assets/ad7c2bd1-ea34-470f-83e6-1faaceb27ea7" />
<img width="1034" height="528" alt="Screenshot 2025-10-12 193458" src="https://github.com/user-attachments/assets/efd398a2-a43c-4437-89cc-4adf17c1bc2c" />
<img width="1035" height="524" alt="Screenshot 2025-10-12 193615" src="https://github.com/user-attachments/assets/c1ddfaea-da11-41cd-88f7-fa1de04ebc75" />
<img width="1036" height="527" alt="Screenshot 2025-10-12 163829" src="https://github.com/user-attachments/assets/3380fe10-730d-49b5-a3b0-6617824e5aa2" />
<img width="1032" height="521" alt="Screenshot 2025-10-12 193920" src="https://github.com/user-attachments/assets/9ec7d9ab-d3f4-4fc5-b54d-b995fac7e741" />
<img width="1032" height="526" alt="Screenshot 2025-10-12 193758" src="https://github.com/user-attachments/assets/b08cecfa-aeba-4e5b-b169-5871cc9e36c9" />
# RESULT
The program for implementing image maps using HTML is executed successfully.

