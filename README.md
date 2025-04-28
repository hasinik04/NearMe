# Ex04 Places Around Me
# Date:05-10-2024
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
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Mapping</title>
</head>
<body>
<section class="header">
    <img src="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\Image.png" usemap="#image-map" alt="Map Image">

    <map name="image-map">
    <area target="" alt="Tirupati" title="Tirupati" href="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\tirupati.html" coords="526,179,393,217,399,272,570,214" shape="poly">
    <area target="" alt="Chennai" title="Chennai" href="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\chennai.html" coords="799,373,715,421,723,457,742,496,726,537,797,584,821,461,835,390" shape="poly">
    <area target="" alt="Vellore" title="Vellore" href="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\vellore.html" coords="329,503,284,500,289,549,343,593,437,535,380,479,333,463" shape="poly">
</map>
</section>
</body>
</html>
```
### Tirupati.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIRUPATI</title>
    <style>
        h1 {
            font-family: 'Times New Roman';
            color: rgb(0, 0, 0);
            text-align: center; 
        }
        img {
            display: block;   
            margin-left: auto;  
            margin-right: auto;
            width: 50%;  
            height: auto;  
        }
    </style>
</head>
<body>
    <h1 style="font-family: 'Times New Roman';color: rgb(0, 0, 0);">TIRUPATI</h1>
    <img src="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\tpt.jpg" > 
    <h2 style="font-family: 'Times New Roman'">Tirupati is a city in the Indian state of Andhra Pradesh. 
        It is the administrative headquarters of the Tirupati district.
        The city is home to the important Hindu shrine of Tirumala Venkateshwara Temple and other historic temples.
        It is located at a distance of 150 km from Chennai, 250 km from Bangalore, 406 km from Amaravati.
        It is one of the eight Svayam vyakta kshetras (Self-Manifested Temples) dedicated to Hindu deity Vishnu.
        Tirupati is a municipal corporation and the headquarters of Tirupati (urban) mandal, Tirupati (rural) mandal,
        and the Tirupati revenue division. It is the 7th most populous urban agglomeration in the state, with a population of 459,985 in 2011.
        As of 2011 census, it had a population of 287,035 making it the 9th most populous city in Andhra Pradesh.
        It is the second biggest city in Rayalaseema after Kurnool. 
        For the year 2012 – 2013, India's Ministry of Tourism named Tirupati as the "Best Heritage City".
        Tirupati has been selected as one of the hundred Indian cities to be developed as a smart city under Smart Cities Mission by Government of India.</h2> 
</body>
</html>
```
### Chennai.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CHENNAI</title>
    <style>
        h1 {
            font-family: 'Times New Roman';
            color: rgb(0, 0, 0);
            text-align: center; 
        }
        img {
            display: block;   
            margin-left: auto;  
            margin-right: auto;
            width: 50%;  
            height: auto;  
        }
    </style>
</head>
<body>
    <h1 style="font-family: 'Times New Roman';color: rgb(0, 0, 0);">CHENNAI</h1>
    <img src="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\chennai.jpg"> 
    <h2 style="font-family: 'Times New Roman'">Chennai formerly known as Madras,  
        capital city of Tamil Nadu, the southern most state of India. 
        It is the state's primate city and is located on the Coromandel Coast of the Bay of Bengal. 
        According to the 2011 Indian census, Chennai is the sixth-most populous city in India and forms the fourth-most populous urban agglomeration. Incorporated in 1688, 
        The Greater Chennai Corporation is the oldest municipal corporation in India and the second oldest in the world after London. </h2> 
</body>
</html>
```
### Vellore.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VELLORE</title>
    <style>
        h1 {
            font-family: 'Times New Roman';
            color: rgb(0, 0, 0);
            text-align: center; 
        }
        img {
            display: block;   
            margin-left: auto;  
            margin-right: auto;
            width: 50%;  
            height: auto;  
        }
    </style>
</head>
<body>
    <h1>VELLORE</h1> 
    <img src="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\vellore.jpeg" alt="Vellore Image">
    <h2 style="font-family: 'Times New Roman'">Vellore, also natively spelt as Velur, is a sprawling city and the administrative headquarters of Vellore district in the Indian state of Tamil Nadu. It is located on the banks of the Palar River in the northeastern part of Tamil Nadu and is separated into four zones that are further subdivided into 60 wards, covering an area of 76.09  km2 and housing a population of 315128 as reported by the 2011 census. It is located about 137.20 kilometres (85 mi) west of Chennai, and about 213.20 kilometres (132 mi) east of Bangalore. Vellore is located on the Mumbai – Chennai arm of the Golden Quadrilateral. Vellore is governed under a mayor and the Vellore Municipal Corporation. It is a part of both the Lok Sabha and state assembly constituencies of Vellore.
    Vellore is the home to Christian Medical College & Hospital, the Vellore Institute of Technology (VIT) and Sripuram Golden Temple.
        The Vellore region is the largest exporter of finished leather goods in the country. Leather exports from Vellore account for more than 37% of India's leather exports and leather-related products.</h2> 
</body>
</html>
```
# Output
![Screenshot (21)](https://github.com/user-attachments/assets/a13a5806-29b9-4136-8fae-2b2f96ed17f0)

![Screenshot (51)](https://github.com/user-attachments/assets/d51d3940-b146-4974-8baf-aa1db8de18e9)
![Screenshot (52)](https://github.com/user-attachments/assets/a116607c-2f23-4216-b940-42b5e3dc7496)
![Screenshot (53)](https://github.com/user-attachments/assets/a748c302-287a-43cd-b6a0-dca3d6d88f06)


# RESULT
The program for implementing image maps using HTML is executed successfully.
