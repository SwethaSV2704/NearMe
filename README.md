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
```
map.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body>
        <h1 align="center">WALAJAPET</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>image E (23016303)</b></font>
        </h3>
        <center>
            <img src="image.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="trends" title="trends" href="" coords="1026,535,1179,611" shape="rect">
                <area target="" alt="arignar anna govt arts &amp; science college" title="arignar anna govt arts &amp; science college" href="" coords="1274,607,1528,673" shape="rect">
                <area target="" alt="bhavani temple" title="bhavani temple" href="" coords="245,541,441,603" shape="rect">
                <area target="" alt="woodbee toys" title="woodbee toys" href="" coords="1573,595,1760,678" shape="rect">
                <area target="" alt="spk mahal" title="spk mahal" href="" coords="680,51,851,140" shape="rect">
            </map>
        </center>
      
    </body>
</html>

trends.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trends</title>
    <style>
        body {
            background-color: #f9f9f9; /* Light background */
            font-family: 'Arial', sans-serif; /* Custom font for the body */
            margin: 0;
            padding: 0;
        }

        .content {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background-color: #eda3d8; /* White background for content */
            border-radius: 8px; /* Rounded corners */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* Light shadow effect */
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .heading {
            color: #ff5733; /* Trendy red-orange color */
            font-size: 36px;
            font-weight: bold;
            font-family: 'Georgia', serif; /* Serif font for the heading */
        }

        .text {
            font-size: 18px;
            color: #333;
            line-height: 1.6;
            font-family: 'Arial', sans-serif; /* Font for the text */
        }
    </style>
</head>
<body>

    <div class="content">
        <p class="heading">Trends</p>
        <p class="text">
            Trends are constantly changing in various fields such as fashion, technology, and entertainment.<br>
            Staying updated with the latest trends is essential for staying competitive.<br>
            Social media plays a significant role in shaping modern trends.<br>
            Many trends are influenced by cultural and societal shifts.<br>
            Understanding trends helps in making informed decisions, whether personal or professional.
        </p>
    </div>

</body>
</html>


toys.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Woodbee Toys</title>
    <style>
        body {
            background-color: #9dce7d; /* Light gray background */
            font-family: 'Verdana', sans-serif; /* Custom font */
            margin: 0;
            padding: 0;
        }

        .content {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background-color: #ffffff; /* White background for content */
            border-radius: 10px; /* Rounded corners */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow effect */
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .heading {
            color: #4CAF50; /* Green color */
            font-size: 36px;
            font-weight: bold;
            font-family: 'Georgia', serif; /* Serif font for the heading */
        }

        .text {
            font-size: 18px;
            color: #555;
            line-height: 1.6;
            font-family: 'Arial', sans-serif; /* Sans-serif font for the body text */
        }
    </style>
</head>
<body>

    <div class="content">
        <p class="heading">Woodbee Toys</p>
        <p class="text">
            Woodbee Toys is a renowned brand known for its handcrafted wooden toys.<br>
            Each toy is made from natural, sustainable materials.<br>
            The company emphasizes eco-friendly and safe products for children.<br>
            Woodbee Toys combines creativity with craftsmanship.<br>
            Their toys are designed to help in the cognitive and motor skills development of kids.
        </p>
    </div>

</body>
</html>

college.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College</title>
    <style>
        body {
            background-color: #4c8ec7; /* Light blue background */
            font-family: 'Verdana', sans-serif; /* Custom font for body text */
            margin: 0;
            padding: 0;
        }

        .content {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background-color: #ffffff; /* White background for content */
            border-radius: 8px; /* Rounded corners */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* Light shadow */
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .heading {
            color: #2e8b57; /* Sea green color for the heading */
            font-size: 36px;
            font-weight: bold;
            font-family: 'Georgia', serif; /* Serif font for the heading */
        }

        .text {
            font-size: 18px;
            color: #333;
            line-height: 1.6;
            font-family: 'Arial', sans-serif; /* Font for the text */
        }
    </style>
</head>
<body>

    <div class="content">
        <p class="heading">College</p>
        <p class="text">
            College is a place for higher education and personal growth.<br>
            Students come here to learn new skills and build their careers.<br>
            It offers various academic programs and extracurricular activities.<br>
            College life is an exciting time for meeting new people and making memories.<br>
            It plays a crucial role in shaping a person's future and career path.
        </p>
    </div>

</body>
</html>


spk.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SPK Mahal</title>
    <style>
        body {
            background-color: #dada7a; /* Light background color */
            font-family: 'Arial', sans-serif; /* Custom font for body text */
            margin: 0;
            padding: 0;
        }

        .content {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background-color: #ffffff; /* White background for content */
            border-radius: 10px; /* Rounded corners */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Light shadow effect */
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .heading {
            color: #ff6347; /* Tomato color for heading */
            font-size: 36px;
            font-weight: bold;
            font-family: 'Georgia', serif; /* Serif font for the heading */
        }

        .text {
            font-size: 18px;
            color: #333;
            line-height: 1.6;
            font-family: 'Arial', sans-serif; /* Font for the text */
        }
    </style>
</head>
<body>

    <div class="content">
        <p class="heading">SPK Mahal</p>
        <p class="text">
            SPK Mahal is a renowned venue for various events and gatherings.<br>
            It is known for its beautiful architecture and grand interiors.<br>
            The Mahal offers spacious halls for weddings and cultural events.<br>
            Located in a serene area, it provides a peaceful atmosphere.<br>
            SPK Mahal is a popular choice for hosting important ceremonies and celebrations.
        </p>
    </div>

</body>
</html>


bavani.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bhavani Temple</title>
    <style>
        /* Set background color for the whole page */
        body {
            background-color: #e473c4; /* Light blue background */
            font-family: 'Verdana', sans-serif; /* Custom font */
            margin: 0;
            padding: 0;
        }

        /* Center the content and add some margin */
        .content {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background-color:white; /* White background for content */
            border-radius: 10px; /* Rounded corners */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow effect */
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        /* Styling the heading */
        .heading {
            color: #ff6347; /* Tomato color */
            font-size: 36px;
            font-weight: bold;
            font-family: 'Georgia', serif; /* Serif font for the heading */
        }

        /* Styling the content text */
        .text {
            font-size: 18px;
            color: #333;
            line-height: 1.6;
            font-family: 'Arial', sans-serif; /* Different font for the body text */
        }
    </style>
</head>
<body>

    <div class="content">
        <p class="heading">Bhavani Temple</p>
        <p class="text">
            Bhavani Temple is one of the most revered religious sites in the region.<br>
            It is located in a serene and peaceful environment.<br>
            The temple is dedicated to the goddess Bhavani, who is believed to grant blessings.<br>
            The architecture of the temple reflects ancient Indian styles.<br>
            Pilgrims from across the country visit to seek divine blessings.
        </p>
    </div>

</body>
</html>



```

## OUTPUT

![Screenshot (30)](https://github.com/user-attachments/assets/68935d3e-703e-454d-8e98-a3b9d736d025)

![Screenshot (33)](https://github.com/user-attachments/assets/d7ab0bd0-30ca-43f0-a4c1-ac1d20b6602b)

![Screenshot (32)](https://github.com/user-attachments/assets/756c3629-0270-4a02-a8a6-ab5e48c57e91)

![Screenshot (34)](https://github.com/user-attachments/assets/5cef3bcb-3f54-4319-bab4-17a15986408c)

![Screenshot (35)](https://github.com/user-attachments/assets/92c3fe20-3679-4bd6-910e-767785002884)

![Screenshot (31)](https://github.com/user-attachments/assets/a75ec910-3c68-4ba2-9978-10f14db709eb)


## RESULT
The program for implementing image maps using HTML is executed successfully.
