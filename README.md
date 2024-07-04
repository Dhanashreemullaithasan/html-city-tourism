# html-city-tourism
## Ex 1:
## AIM :
To Create the Table
## Code:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <table border="1" cellspacing="4">
        <tbody>
            <tr>
                <th colspan="2">My Day</th>
            </tr>
            <tr>
                <td>1.wake up early
                    <ul>
                        <li>5 AM</li>
                        <li>walk</li>
                        <li>jog</li>
                    </ul>
                </td>

                <td rowspan="3">
                    <table border="1">
                        <tbody>
                            <tr>
                                <th colspan="2">Things to watch

                                </th>
                            </tr>
                            <tr>
                                <td>
                                    <img src=" C:\Users\DHANASHREE M\Desktop\New folder\img1.png " width="150 " height="150 ">
                                </td>
                                <td>
                                    <img src="C:\Users\DHANASHREE M\Desktop\New folder\img2.png " width="150 " height="150 ">
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <img src=" C:\Users\DHANASHREE M\Desktop\New folder\img3.png " width="150 " height="150 ">
                                </td>
                                <td>
                                    <img src=" C:\Users\DHANASHREE M\Desktop\New folder\img4.png " width="150 " height="150 ">
                                </td>
                            </tr>

                        </tbody>

                    </table>
                </td>
            </tr>
            <tr>
                <td>2.breakfast
                    <ul>
                        <li>8 AM</li>
                        <li>egggs</li>
                        <li>coffee</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>3.go to Saveetha
                    <ul>
                        <li>8 AM</li>
                        <li>attend classes</li>
                        <li>to be continued</li>
                    </ul>
                </td>
            </tr>
        </tbody>
    </table>



</body>

</html>
```
## output:

![Screenshot 2024-07-03 182933](https://github.com/Dhanashreemullaithasan/html-city-tourism/assets/94165415/729cc510-036b-4ffa-863a-57d9a13e11e8)
## RESULT:
 Thus, the table was created successfully.

## EX 2:
## AIM:
To create a website for the Tourism Sites of a given city.
## CODE:
### Home.html:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .float-container {
            overflow: hidden;
        }
        
        .float-left {
            float: left;
            margin: 20px;
            width: 50%;
        }
        
        .float-right {
            float: right;
            margin: 20px;
            width: 20%;
        }
        
        .image-container {
            text-align: center;
        }
    </style>
</head>

<body>
    <header>

        <img src="C:\Users\DHANASHREE M\Desktop\webpage\imlogo.jpg" alt="logo">
        <h1>Welcome to Jaipur</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="heritage.html">Heritage</a>
        <a href="hotel-booking.html">Hotel Booking</a>
        <a href="gallery.html">Gallery</a>
    </nav>
    <HR>
    <div class="image-container">
        <h2>About </h2>
        <p>Jaipur have most attracting architectural construction in the country </p>
        <HR>
        <img src="C:\Users\DHANASHREE M\Desktop\webpage\images (1).jpg" alt="image2">
        <p>The land of palace.</p>
    </div>
    <footer>
        &copy, 2024 Jaipur tourism.All rights reserved.
    </footer>
</body>

</html>
```
### Heritage.html:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heritage Sites - BANGALORE City</title>
    <link rel="stylesheet" href="css/styles.css">
    <style>
        /* Centered Image */
        
        .centered-image {
            text-align: center;
            margin: 20px;
            /* Add some margin for better visibility */
        }
        /* Floated Images */
        
        .float-container {
            overflow: hidden;
            /* This is required for floated elements to work properly */
        }
        
        .float-left {
            float: left;
            margin: 10px;
            width: 45%;
            /* Set image width to ensure they fit side-by-side */
        }
        
        .float-right {
            float: right;
            margin: 10px;
            width: 45%;
        }
        
        .image-container {
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <img src="C:\Users\DHANASHREE M\Desktop\webpage\imlogo.jpg" alt="City Logo">
        <h1>Welcome To Jaipur</h1>
    </header>

    <nav>
        <a href="home.html">Home</a>
        <a href="heritage.html">Heritage</a>
        <a href="hotel-booking.html">Hotel Booking</a>
        <a href="gallery.html">Gallery</a>
    </nav>

    <div class="image-container">
        <h2>Heritage Sites</h2>
        <ul>
            <li>
                <a href="site1.html"><img src="C:\Users\DHANASHREE M\Desktop\webpage\samode-haveli.jpg" alt="Heritage Site 1" weidth="100" height="100"></a>
            </li>
            <li>
                <a href="site2.html"><img src="C:\Users\DHANASHREE M\Desktop\webpage\amber palace.jpg" alt="Heritage Site 2" weidth="100" height="100"></a>
            </li>
            <li>
                <a href="site3.html"><img src="image/hawa mahal.jpg" alt="Heritage Site 3" weidth="100" height="100"></a>
            </li>
            <li>
                <a href="site4.html"><img src="image/Nahargarh fort.jpg" alt="Heritage Site 4" weidth="100" height="100"></a>
            </li>
        </ul>
    </div>

    <footer>
        &copy; 2024 Jaipur City Tourism. All rights reserved.
    </footer>

</body>

</html>
```
### Site1.html:
```
<!DOCTYPE html>
<html>

<head>
    <title>Page Title</title>
    <style>
        /* Centered Image */
        
        .centered-image {
            text-align: center;
            margin: 20px;
            /* Add some margin for better visibility */
        }
        /* Floated Images */
        
        .float-container {
            overflow: hidden;
            /* This is required for floated elements to work properly */
        }
        
        .float-left {
            float: left;
            margin: 10px;
            width: 45%;
            /* Set image width to ensure they fit side-by-side */
        }
        
        .float-right {
            float: right;
            margin: 10px;
            width: 45%;
        }
        
        .image-container {
            text-align: center;
        }
    </style>
</head>

<body>
    <nav>
        <a href="home.html">  Home  </a>
        <a href="heritage.html"> Heritage  </a>
        <a href="hotel-booking.html"> Hotel Booking  </a>
        <a href="gallery.html"> Gallery  </a>
    </nav>
    <h1>
        <b>Samode Palace</b></h1>
    <img src="C:\Users\DHANASHREE M\Desktop\webpage\samode-haveli.jpg" alt="Heritage Site 1" class="centered-image">
    <p>Samode Palace, Samode Haveli and Samode Bagh (Garden) are heritage monuments and structures built by the noble feudatory with the hereditary title of 'Maha Rawal' or 'Maha Sahe of the Amber and Jaipur principality in Rajasthan, India. All three have
        rich history of several hundred years and display a fusion of Mughal and Rajasthani art and architecture.They are now part of the Heritage group of hotels under the flagship name of "Samode" that are run by the hereditary owners of these structures.
        The Samode Palace is located 40 kilometres (25 mi) north of Jaipur city, the Samode Haveli is close to Jaipur (centrally located within city limits, 6 kilometres (3.7 mi) away from the city railway station) and the Samode Bagh or Garden, 4 kilometres
        (2.5 mi) from the palace which is also run as a luxury hotel. </p>
    <h2>Why visit Samode Palace:</h2>
    <p>
        <h1>Nowadays, Samode Haveli is a popular tourist attraction and a renowned heritage hotel. It is known not only for its historical significance but also for its hospitality, making it a prime destination for those looking to experience the regal heritage
            and culture of Rajasthan

        </h1>
        <h1>Samode Haveli : </h1>City Palace forms one of the most famous tourist attractions and a major landmark in Jaipur. The beautiful palace was built by Maharaja Sawai Jai Singh during his reign.

</body>

</html>
```
### Site2.html:
```<!DOCTYPE html>
<html>

<head>
    <title>Page Title</title>
    <style>
        /* Centered Image */
        
        .centered-image {
            text-align: center;
            margin: 20px;
            /* Add some margin for better visibility */
        }
        /* Floated Images */
        
        .float-container {
            overflow: hidden;
            /* This is required for floated elements to work properly */
        }
        
        .float-left {
            float: left;
            margin: 10px;
            width: 45%;
            /* Set image width to ensure they fit side-by-side */
        }
        
        .float-right {
            float: right;
            margin: 10px;
            width: 45%;
        }
        
        .image-container {
            text-align: center;
        }
    </style>
</head>

<body>
    <nav>
        <a href="home.html">  Home  </a>
        <a href="heritage.html"> Heritage  </a>
        <a href="hotel-booking.html"> Hotel Booking  </a>
        <a href="gallery.html"> Gallery  </a>
    </nav>
    <h1>Amber palace</h1>
    <img src="C:\Users\DHANASHREE M\Desktop\webpage\image\im2.jpg" alt="Heritage Site 2" class="centered-image">
    <p>One of the top tourist attractions of Jaipur, the huge Amer Palace Fort sits atop a small hill, and is located at a distance about 11 km from the main city. The magnificent Amer Fort is an extensive palace complex that has been built with pale yellow
        and pink sandstone, and with white marble.</p>

    <h1>
        <b>AMBER PALACE BEAUTIFUL MELANGE OF ARCHITECTURE</b></h1>
    <p>

        pOne of the top tourist attractions of Jaipur, the huge Amer Palace Fort sits atop a small hill, and is located at a distance about 11 km from the main city. The magnificent Amer Fort is an extensive palace complex that has been built with pale yellow
        and pink sandstone, and with white marble. The fort is divided into four main sections that are graced with their own courtyards.
    </p>
    <p>
        As you arrive at the Amer Fort, you will enter through the Suraj Pol; unless you arrive by car, then you enter via the Chand Pol. Both these gates open into the Jaleb Chowk, which is the main courtyard, where in earlier times, returning armies used to
        display their plunder to the people. The fort has a number of sections, including the King’s quarters, the zenana (where the women lived), gardens, temples, etc.

    </p>
```
### Site3.html:
```
<!DOCTYPE html>
<html>

<head>
    <title>Page Title</title>
    <style>
        /* Centered Image */
        
        .centered-image {
            text-align: center;
            margin: 20px;
            /* Add some margin for better visibility */
        }
        /* Floated Images */
        
        .float-container {
            overflow: hidden;
            /* This is required for floated elements to work properly */
        }
        
        .float-left {
            float: left;
            margin: 10px;
            width: 45%;
            /* Set image width to ensure they fit side-by-side */
        }
        
        .float-right {
            float: right;
            margin: 10px;
            width: 45%;
        }
        
        .image-container {
            text-align: center;
        }
    </style>
</head>

<body>
    <nav>
        <a href="home.html">  Home  </a>
        <a href="heritage.html"> Heritage  </a>
        <a href="hotel-booking.html"> Hotel Booking  </a>
        <a href="gallery.html"> Gallery  </a>
    </nav>
    <h1>
        <b>HAWA MAHAL</b></h1>
    <img src="C:\Users\DHANASHREE M\Desktop\webpage\image\hawa mahal.jpg " alt="Heritage Site 1 " class="centered-image ">
    <h2>
        <B>JAIPUR'S MAGNIFICENT ICONIC LANDMARK</B>
    </h2>
    <p>The Hawa Mahal in Jaipur is considered as one of the most iconic attractions of the city. The five-storey building looks like a honeycomb of a beehive and it is always windy inside, owing to the numerous windows and jharokhas. This amazing ventilation
        that the palace enjoys is the reason why it was named as the Hawa Mahal, which literally translates into the “Palace of the Winds”. </p>

    <p>
        The main purpose behind the construction of this palace was to allow the ladies of the royal family and the court to observe the busy streets of the Johari Bazaar from the many jharokhas of the palace, without being seen themselves. The Hawa Mahal is
        a five-storey building, and it is the tallest building in the world that has been built without a foundation. It has a curved architecture that leans at an 87 degree angle, and a pyramidal shape which has helped it stay erect for centuries.</p>


    <P>
        The Hawa Mahal is dedicated to Lord Krishna. It is said that the shape of the building resembles the crown of Krishna. More than a palace, the Hawa Mahal is also a cultural and architectural marvel that reflects a truly harmonious amalgamation of the
        Hindu Rajput and Islamic Mughal architectural styles. The Rajput style can be seen in the domes canopies and the fluted pillars, while the stone inlay filigree work and the arches are perfect depictions of the Mughal style of architecture.</P>

</body>

</html>
```
### Site4.html:
```
<!DOCTYPE html>
<html>

<head>
    <title>Page Title</title>
    <style>
        /* Centered Image */
        
        .centered-image {
            text-align: center;
            margin: 20px;
            /* Add some margin for better visibility */
        }
        /* Floated Images */
        
        .float-container {
            overflow: hidden;
            /* This is required for floated elements to work properly */
        }
        
        .float-left {
            float: left;
            margin: 10px;
            width: 45%;
            /* Set image width to ensure they fit side-by-side */
        }
        
        .float-right {
            float: right;
            margin: 10px;
            width: 45%;
        }
        
        .image-container {
            text-align: center;
        }
    </style>
</head>

<body>
    <nav>
        <a href="home.html">  Home  </a>
        <a href="heritage.html"> Heritage  </a>
        <a href="hotel-booking.html"> Hotel Booking  </a>
        <a href="gallery.html"> Gallery  </a>
    </nav>
    <h1>
        <b>NAHARGARH FORT</b></h1>
    <img src="C:\Users\DHANASHREE M\Desktop\webpage\image\Nahargarh fort.jpg" alt="Heritage Site 1 " class="centered-image ">
    <h2>
        <B>PRIDE OF THE ARAVALLI RANGE</B>
    </h2>
    <p>Nahargarh Fort sits proudly on a ridge of the Aravalli Hills, creating an impressive northern backdrop to the city of Jaipur. It was constructed during the reign of Jai Singh in 1734, and was later expanded in 1868. Nahargarh, which means abode of
        tigers, was a formidable barrier, defending Jaipur against attacking enemies. Within its walls, the fort houses Madhavendra Bhawan, the summer destination for the members of the royal family. Built by Sawai Madho Singh, the palace has 12 matching
        boudoirs for the queens, at the head of which is a suite for the king. They are all connected by corridors decorated with delicate murals. Even today the palace is a favoured spot for local picnickers. The fort looks brilliant when floodlit at
        night. Overlooking the city, it presents a glittering view of the city lights. </p>

    <p>
        The Nahargarh Fort is approximately 20 kilometres from the city railway station and bus stand. Since there is no public transport, hiring a taxi or renting a car for to & fro journey is the best and the safest option.</p>


</body>

</html>
```
### Hotel-Booking.html:
```
<!DOCTYPE html>
<html>

<head>
    <title>HOTEL BOOKINGS AND RESERVATIONS</title>
    <style>
        /* Optional styling for the form */
        
        label {
            display: block;
            margin-bottom: 5px;
            font: Arial;
        }
        
        @font-face {
            font-family: myFirstFont;
            src: url(sansation_light.woff);
        }
        
        input[type="text"],
        input[type="date"],
        select {
            width: 10%;
            padding: 5px;
        }
    </style>
</head>

<body>
    <nav>
        <a href="home.html">  Home  </a>
        <a href="heritage.html"> Heritage  </a>
        <a href="hotel-booking.html"> Hotel Booking  </a>
        <a href="gallery.html"> Gallery  </a>
    </nav>

    <h1>BOOKINGS</h1>
    <p>Bookings to be done and refund will be with terms and conditions.Please refer Hotel conditions before bookings.</p>
    <h1>Hotel Room Booking</h1>
    <form action="process_booking.php" method="post"> <label for="name">Guest Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required>

        <label for="check_in">Check-In Date:</label>
        <input type="date" id="check_in" name="check_in" required>

        <label for="check_out">Check-Out Date:</label>
        <input type="date" id="check_out" name="check_out" required>

        <label for="guests">Number of Guests:</label>
        <select id="guests" name="guests">
      <option value="1">1</option>
      <option value="2">2</option>
      <option value="3">3</option>
      <option value="4">4</option>
    </select>

        <label for="room_type">Room Type:</label>
        <select id="room_type" name="room_type">
      <option value="standard">Standard Room</option>
      <option value="deluxe">Deluxe Room</option>
      </select>

        <br>
        <input type="submit" value="Book Now">
    </form>
</body>

</html>
```
### Gallery.html:
```
<!DOCTYPE html>
<html>

<head>
    <title>Page Title</title>
</head>

<body>
    <nav>
        <a href="home.html">  Home  </a>
        <a href="heritage.html"> Heritage  </a>
        <a href="hotel-booking.html"> Hotel Booking  </a>
        <a href="gallery.html"> Gallery  </a>
    </nav>
    <h1>GALLERY</h1>
    <p>PLACE TO GET TOWARDS BEAUTIFUL MEMORIES!!!</p>
    <IMG src="C:\Users\DHANASHREE M\Desktop\webpage\image\IM3.jpg" alt="image">
    <h1>
        <IMG src="C:\Users\DHANASHREE M\Desktop\webpage\image\IM8.jpg" alt="image">
    </h1>
    <h1>
        <IMG src="C:\Users\DHANASHREE M\Desktop\webpage\image\im.jpg" alt="image">

    </h1>
</body>

</html>
```
## OUTPUT:

### HOME:
![Screenshot 2024-07-03 224922](https://github.com/Dhanashreemullaithasan/html-city-tourism/assets/94165415/4bd66425-ac68-4da4-b161-67effe6fa3ab)

### HERITAGE:

![Screenshot 2024-07-03 224939](https://github.com/Dhanashreemullaithasan/html-city-tourism/assets/94165415/ada0309e-5376-4f73-a13e-cd95eb1da97c)

### SITE1:

![Screenshot 2024-07-03 225015](https://github.com/Dhanashreemullaithasan/html-city-tourism/assets/94165415/fb53035b-2d7e-479b-ad0f-d6ea2e0dbe7b)

### SITE2:

![Screenshot 2024-07-03 225033](https://github.com/Dhanashreemullaithasan/html-city-tourism/assets/94165415/b5ba8b36-6624-498a-b77e-8007283b286b)

### SITE3:

![Screenshot 2024-07-03 225047](https://github.com/Dhanashreemullaithasan/html-city-tourism/assets/94165415/d2b76e26-8e9d-4ab8-9b16-33865b9b5644)

### SITE4:

![Screenshot 2024-07-03 230254](https://github.com/Dhanashreemullaithasan/html-city-tourism/assets/94165415/15581425-876c-4e51-ba89-3a177066a641)

### HOTEL-BOOKING:

![Screenshot 2024-07-03 225108](https://github.com/Dhanashreemullaithasan/html-city-tourism/assets/94165415/ab2ce13a-2632-401c-8288-b4bd0f076b08)

### GALLERY:

![Screenshot 2024-07-03 225125](https://github.com/Dhanashreemullaithasan/html-city-tourism/assets/94165415/1fc39ba5-e6d7-4de6-9d02-bd6f3989303b)
## Result:

Thus, a website for a given city's Tourism Sites was created successfully.
