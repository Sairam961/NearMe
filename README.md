# Ex04 Places Around Me
## Date: 

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

     <html>
     <head>
        <title>
            MY CITY
        </title>
    </head>
    <body>
        <h1 align="center">
        <font color="blue"><b>Chennai</b></font>
    </h1>
    <h3 align="center">
        <font color="red"><b>R SAIRAM(25000694)</b></font>
    </h3>
    <center>
        <img src="map.png" usemap="#mycity" alt="mycity" height="610" width="1450">
        <map name="mycity">
            <area shape="rect" coords="700,250,850,400" href="river.html" title="thamirabarani river">
            <area shape="rect" coords="300,200,450,350" href="school.html" title="My School">
            <area shape="rect" coords="1000,200,1150,350" href="temple.html" title="Murugar temple">
            <area shape="rect" coords="900,400,1050,550" href="park.html" title="Anna Nagar Tower park">
        </map>
    </center>
    </body>
    </html>
    
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Description of a Murugan Temple</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
            color: #333;
        }
        h1 {
            color: #CC0000; /* Traditional red color */
            text-align: center;
        }
        img {
            display: block;
            margin: 0 auto 20px auto;
            max-width: 100%;
            height: auto;
            border: 3px solid #FFD700; /* Gold border */
            border-radius: 5px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
    </head>
    <body>
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Keins Matric Hr. Sec. School - Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f9;
        }
        .container {
            max-width: 700px;
            margin: 0 auto;
            padding: 20px 30px;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #004d99;
            text-align: center;
            margin-bottom: 15px;
        }
        h2 {
            color: #1a75ff;
            font-size: 1.2em;
            border-bottom: 1px solid #e0e0e0;
            padding-bottom: 5px;
            margin-top: 20px;
        }
        p {
            text-align: justify;
            margin-bottom: 10px;
        }
        ul {
            list-style-type: square;
            margin-left: 25px;
            padding-left: 0;
        }
        li {
            margin-bottom: 5px;
        }
    </style>
     </head>
     <body>

    <div class="container">
        <h1>Keins Matric Hr. Sec. School</h1>

        <p>
            *Keins Matric Hr. Sec. School* is a well-established educational institution located in the Tirunelveli District, India.
        </p>

        <h2>History and Foundation</h2>
        <p>
            Founded in *1979* by the Ken-a-z Educational and Industrial Society (KEINS), the school has served the community for over three decades, becoming a pioneer in the Vallioor region.
        </p>

        <h2>Mission and Curriculum</h2>
        <p>
            The school's mission centers on the *all-round development* of its students, emphasizing discipline, strong character, and leadership qualities. It offers a quality academic preparation for pupils from pre-school through the Plus Two level, adhering to the Matriculation and Higher Secondary curriculum (State Board affiliation).
        </p>

        <h2>Key Features</h2>
        <ul>
            <li>A focus on *Indian ethos and values*.</li>
            <li>The provision of *advanced infrastructure*, including modern science and computer labs, and digital classrooms.</li>
            <li>A commitment to both academic excellence and *holistic development* through mandatory co-curricular activities like yoga, arts, and crafts.</li>
        </ul>
    </div>

    </body> 
    </html>

    river.html

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thamirabarani River - Short Note</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 20px;
            line-height: 1.5;
            color: #2c3e50;
            background-color: #ecf0f1;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
            border-left: 5px solid #3498db; /* Blue accent color */
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #2980b9;
            text-align: center;
            margin-bottom: 10px;
        }
        p strong {
            color: #c0392b; /* Red accent for emphasis */
        }
    </style>
    </head>
    <body>

    <div class="container">
        <h2>The Thamirabarani River</h2>
        
        <p>
            The Thamirabarani (also known as Porunai) is the *only perennial river in Tamil Nadu, flowing approximately **128 km*.
        </p>
        <p>
            It originates from the *Pothigai Hills* of the Western Ghats and flows eastward through the Tirunelveli and Thoothukudi districts before draining into the *Gulf of Mannar*. </p>

     <!DOCTYPE html>
     <html lang="en">
    <head>
    <meta charset="UTF-8">
    <title>Tirunelveli Park Description</title>
    </head>
    <body>

    <div id="park-description">
        <h2>VOC Park, Tirunelveli</h2>
        <p>
            VOC Park is a popular public park located in the heart of Tirunelveli, near the Palayamkottai area. 
            It is a well-maintained green space offering a serene environment for morning walks, jogging, and 
            leisure activities. The park features lush lawns, walking paths, and usually includes a children's 
            play area, making it a favorite spot for families and residents to relax and socialize.
        </p>
    </div>

    </body>
    </html>




## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
