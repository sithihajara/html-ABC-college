# Assignment 1
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/e17d6ee3-417a-421a-86b8-e835bf1c78e1)
### main.html:
~~~
<!DOCTYPE html>
<html>
<head>
    <title>My Day</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            width: 50%;
            margin: 0 auto;
            border-style: double;
            padding: 10px;
        }
        .header {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            padding: 10px;
        }
        table {
            width: 100%;
            border-style:none;
        }
        td {
            border-style: double;
            padding: 20px;
            
        }
        .section-title {
            font-size: 22px;
            font-weight: bold;
        }
        .task-list {
            list-style-type: none;
            padding-left: 100px;
        }
        .task-list li {
            margin: 15px 0;
        }
        .subtask {
            margin-left: 20px;
        }
        .image-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .image-container img {
            width: 45%;
            margin: 5px 0;
            border: 2px solid #000;
        }
        .things-to-watch-title {
            border-style:double ;
            background-color: yellow;
            font-weight: bold;
            text-align: center;
            padding: 2px;
        }
        
    </style>
</head>
<body>

<div class="container">

    <div class="header">My Day</div>
    <table>
        <tr>
            <td style="width: 50%;">
                <div class="section-title">1. Wake up early</div>
                <ul class="task-list">
                    <li><b>5AM</b></li>
                    <li class="subtask">walk</li>
                    <li class="subtask">jog</li>
                </ul>
            </td>
            <td rowspan="3" style="width: 50%;">
                <div class="things-to-watch-title">Things to watch</div>
                <div class="image-container">
                    <img src="im1.jpg" alt="jogging">
                    <img src="im2.jpeg" alt="Breakfast">
                    <img src="im3.jpg" alt="Coffee">
                    <img src="im4.jpg" alt="Meeting">
                </div>
            </td>
        </tr>
        <tr>
            <td>
                <div class="section-title">2. Breakfast</div>
                <ul class="task-list">
                    <li><b>8AM</b></li>
                    <li class="subtask">eggs</li>
                    <li class="subtask">coffee</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>
                <div class="section-title">3. Go to Saveetha</div>
                <ul class="task-list">
                    <li><b>8AM</b></li>
                    <li class="subtask">attend classes</li>
                    <li class="subtask">to be continued</li>
                </ul>
            </td>
        </tr>
    </table>
</div>

</body>
</html>
~~~
![image](https://github.com/sithihajara/html-ABC-college/assets/94219582/438674e9-6723-4dfc-b019-a15b6eddd05e)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/868d7794-6929-4f06-938d-c5f13174a436)

### home.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Saveetha Engineering College</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

<header>
    <img src="image/logo.jpg" alt="College Logo" style="max-width: 50px; vertical-align: middle;">
    <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
</header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="index.html">Home</a> |
    <a href="academics.html">Academics</a> |
    <a href="admission.html">Admission</a> |
    <a href="gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <img src="image/H1.jpg" alt="Gallery Image 1" style="width: 100%; max-width: 600px;">
    <h2>Description</h2>
    <p>Welcome to SEC - Saveetha Engineering College (Autonomous), a distinguished institution established in 2001 under the visionary leadership of Dr. N. M. Veeraiyan— a committed medical professional and philanthropist par excellence. With over 35 years of unwavering commitment to excellence in education, our college has emerged as the forefront of engineering education and research.</p>
    
</section>

</body>
<footer>
    &copy; 2024 Saveetha Engineering College. All rights reserved.
</footer>
</html>
~~~
### academics.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Computer Science - College Name</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

<header>
    <img src="image/logo.jpg" alt="College Logo" style="max-width: 50px; vertical-align: middle;">
    <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
</header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="index.html">Home</a> |
    <a href="academics.html">Academics</a> |
    <a href="admission.html">Admission</a> |
    <a href="gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <h2>Science</h2>
    <a href="../Assignment_2/courses/Computer_Science.html">Computer Science</a><br>
    <a href="../Assignment_2/courses/Mathematics.html">Mathematics</a>
    <h2>Arts</h2>
    <a href="../Assignment_2/courses/English.html">English</a><br>
    <a href="../Assignment_2/courses/Sociology.html">Sociology</a>
    <h2>Commerce</h2>
    <a href="../Assignment_2/courses/Economics.html">Economics</a><br>
    <a href="../Assignment_2/courses/Business.html">Business Management</a>

    
</section>

</body>
<footer>
    &copy; 2024 Saveetha Engineering College. All rights reserved.
</footer>
</html>
~~~
### admission.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Admission - College Name</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

<header>
    <img src="image/logo.jpg" alt="College Logo" style="max-width: 50px; vertical-align: middle;">
    <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
</header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="index.html">Home</a> |
    <a href="academics.html">Academics</a> |
    <a href="admission.html">Admission</a> |
    <a href="gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <h2>Admission Form</h2>
    <form action="#" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name"><br><br>
        
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br><br>
        
        <label for="phone">Phone:</label><br>
        <input type="tel" id="phone" name="phone"><br><br>
        
        <label for="course">Course:</label><br>
        <select id="course" name="course">
            <option value="computer-science">Computer Science</option>
            <option value="mathematics">Mathematics</option>
            <option value="english">English</option>
            <option value="sociology">Sociology</option>
            <option value="economics">Economics</option>
            <option value="business-management">Business Management</option>
        </select><br><br>
        
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
        
        <input type="submit" value="Submit">
    </form>
</section>

</body>
<footer>
    &copy; 2024 Saveetha Engineering College. All rights reserved.
</footer>
</html>
~~~
### gallery.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Gallery - College Name</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

<header>
    <img src="image/logo.jpg" alt="College Logo" style="max-width: 50px; vertical-align: middle;">
    <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
</header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="index.html">Home</a> |
    <a href="academics.html">Academics</a> |
    <a href="admission.html">Admission</a> |
    <a href="gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <h2>Gallery</h2>
    <img src="image/H1.jpg" alt="Gallery Image 1" style="width: 100%; max-width: 600px;">
    <img src="image/H2.jpg" alt="Gallery Image 2" style="width: 100%; max-width: 600px;">
    <img src="image/H3.jpg" alt="Gallery Image 3" style="width: 100%; max-width: 600px;">
    <img src="image/H4.jpg" alt="Gallery Image 4" style="width: 100%; max-width: 600px;">
</section>

</body>
<footer>
    &copy; 2024 Saveetha Engineering College. All rights reserved.
</footer>
</html>
~~~
### Computer_Science.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Computer Science - College Name</title>
</head>
<body style="background-color: #f4f4f9; font-family: Arial, sans-serif;">

    <header>
        <img src="logo.jpg" alt="College Logo" style="max-width: 50px; vertical-align: middle;">
        <h1 style="display: inline; margin: 0; vertical-align: middle;">Saveetha Engineering College</h1>
    </header>

<nav style="text-align: center; margin-top: 20px;">
    <a href="../index.html">Home</a> |
    <a href="../academics.html">Academics</a> |
    <a href="../admission.html">Admission</a> |
    <a href="../gallery.html">Gallery</a>
</nav>

<section style="padding: 20px;">
    <h2>Computer Science</h2>
    <p>The Computer Science course offers an in-depth understanding of computer systems, programming, and data structures. This course prepares students for careers in software development, data analysis, and more.</p>
    <h3>Teachers</h3>
    <ul>
        <li>Dr. John Doe</li>
        <li>Prof. Jane Smith</li>
    </ul>
    <h3>Timetable</h3>
    <ul>
        <li>Monday: 9:00 AM - 11:00 AM</li>
        <li>Wednesday: 1:00 PM - 3:00 PM</li>
        <li>Friday: 10:00 AM - 12:00 PM</li>
    </ul>
</section>

</body>
</html>
~~~
![image](https://github.com/sithihajara/html-ABC-college/assets/94219582/38b4436c-5e41-40c4-823c-59fd44632bf6)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/193b7f57-1f4e-45cb-9af6-6b4f62dc67bc)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/3dc002a5-90ba-49cc-bab3-8531ea6e3298)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/2746a310-2cd0-4509-95f6-f33cbcfe80a8)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/40fb84f8-3768-4557-a664-5c7f5cf473a8)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/e6c77df9-b9ee-4d2f-ac31-bfaa9486546c)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/c343b24f-60f5-4db3-8d71-12636cb07fa0)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/92db4009-e0f9-4d11-b9a8-033aca633861)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/1fa4aa30-660e-4ec1-aec7-a9832301a708)
![image](https://github.com/RanjithD18/html-ABC-college/assets/93427221/7ca9cfd6-37fe-4d03-9385-5c5ed93fa908)









