# Ex.07 Restaurant Website
## Date: 07.10.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
rest.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HIVE RESTAURANT | Home</title>
  <link rel="stylesheet" href="rest.css">
</head>
<body>
  <header>
    <h1>HIVE RESTAURANT</h1>
    <p class="tagline">"Every Food has a Unique Story"</p>
 
    
    <nav>
      <ul>
        <li><a href="rest.html" class="active">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="home">
    
    <h2></color>HIVE RESTAURANT </h2>
    <p align="left"> </p>
    <img src=hive.jpg height="350" width="50">
  </section>

  <footer>
    <p>© HIVE RESTAURANT | Designed by <strong>SANJAY (25016505)</strong></p>
  </footer>
</body>
</html>

rest.css

body {
  background-image: url(hive.jpg);
  font-family: Arial, sans-serif;
  background-color: rgb(60, 19, 19);
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: rgb(60, 19, 19);
  padding: 20px;
  border-bottom: 3px solid goldenrod;
}
.tagline {
    position: relative;
  color: peachpuff;
  font-size: 16px;
  margin-top: 5px;
  font-style: italic;
  letter-spacing: 1px;
  right:30%;
}

h1 {
    position:relative;
  color: goldenrod;
  right:30%;
  top:20%;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  position: relative;
  left:30%;
  
}

nav a.active,
nav a:hover {
  color: goldenrod;
  position: relative;
  left:30%;
}


.home {
  padding: 40px;
}

.home img {
  width: 500px;
  border-radius: 10px;
  margin-top: 20px;
  border: 3px solid goldenrod;
}

footer {
  background-color: #111;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid goldenrod;
}

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu | hive</title>
  <link rel="stylesheet" href="menu.css">
</head>
<body>
  <header>
    <h1>SPECIAL MENU</h1>
    <nav>
      <ul>
        <li><a href="rest.html">Home</a></li>
        <li><a href="menu.html" class="active">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <h2>Food Items</h2>
    <div class="menu-items">
      <div class="item"><img src="chicken.jpg"><p>Chicken Biriyani - Rs.250</p></div>
      <div class="item"><img src="noodels1.jpg"><p>Noodles - Rs.150</p></div>
      <div class="item"><img src="meals.jpg"><p>Meals - Rs.200</p></div>
      <div class="item"><img src="parotta.jpg"><p>Parotta - Rs.120</p></div>
      <div class="item"><img src="f.jpg"><p>Fish Curry - Rs.320</p></div>
      
    </div>
  </section>

  <footer>
    <p>© HIVE RESTAURANT | Designed by <strong>SANJAY (25016505)</strong></p>
  </footer>
</body>
</html>

menu.css

body {
  font-family: Arial, sans-serif;
  background-color: #111;
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: black;
  padding: 20px;
  border-bottom: 3px solid moccasin;
}

h1 {
  color: moccasin;
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color:moccasin;
}

.menu {
  padding: 40px;
}

.menu-items {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.item {
  background-color: black;
  border: 2px solid moccasin;
  border-radius: 10px;
  padding: 10px;
  width: 200px;
}

.item img {
  width: 100%;
  border-radius: 8px;
}

footer {
  background-color: #111;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid moccasin;
}

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <header>
        <h1>Administration Team</h1>
        <nav>
            <ul>
                <li><a href="rest.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html" class="active">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>Team Members</h2>

        <div class="team">
            <div class="member">
                <img src="san.jpg" alt="SANJAY">
                <h3>SANJAY</h3>
                <p>CEO</p>
            </div>

            <div class="member">
                <img src="h1.jpg" alt="JOSHWA">
                <h3>JOSHWA</h3>
                <p>Marketing Manager</p>
            </div>

            <div class="member">
                <img src="h2.jpg" alt="NIMI">
                <h3>NIMI</h3>
                <p>Operations Manager</p>
            </div>

            <div class="member">
                <img src="h3.jpg" alt="WILTON">
                <h3>WILTON</h3>
                <p>HR Manager</p>
            </div>

            <div class="member">
                <img src="h4.jpg" alt="CASSIM">
                <h3>CASSIM</h3>
                <p>Executive Chef</p>
            </div>

            <div class="member">
                <img src="h6.jpg" alt="SUMATHI">
                <h3>SUMATHI</h3>
                <p>Customer Service Manager</p>
            </div>
        </div>
    </main>

    <footer>
        <p>© HIVE RESTAURANT | Designed by <strong>SANJAY (25016505)</strong></p>
    </footer>
</body>
</html>

admin.css

 body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #fff;
}

/* Header */
header {
    background-color:brown;
    color: rgb(236, 226, 226);
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 10px 0 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: 600;
}

nav ul li a.active {
    text-decoration: underline;
}

/* Main Section */
main {
    text-align: center;
    padding: 40px 20px;
}

main h2 {
    color: #110810;
    font-size: 1.9em;
    margin-bottom: 40px;
}

/* Team Cards */
.team {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.member {
    background-color: #130d23;
    color: white;
    border-radius: 12px;
    width: 150px;
    padding: 20px;
    transition: transform 0.3s;
}

.member:hover {
    transform: translateY(-8px);
}

.member img {
    width: 80%;
    height: 230px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid grey;
}

.member h3 {
    margin-top: 15px;
    color: #fff;
    font-size: 1.2em;
}

.member p {
    color: #38362f;
    font-weight: 500;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 10px;
    font-size: 0.9em;
}

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | HIVE RESTAURANT</title>
  <link rel="stylesheet" href="contact.css">
</head>
<body>
  <header>
    <h1>CONTACT US</h1>
    <nav>
      <ul>
        <li><a href="rest.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html" class="active">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  
   
  <section class="contact">
    <h2>Contact Us</h2>
    <p> No. 31 CM Nagar, Tamil Nadu, India</p>
    <p> 9876543210</p>
    <p> hive@gmail.com</p>
  </section>

  <footer>
    <p>© HIVE RESTAURANT | Designed by <strong>SANJAY (25016505)</strong></p>
  </footer>
</body>
</html>

contact.css

body {
  font-family: Arial, sans-serif;
  background-color: black;
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: black;
  padding: 20px;
  border-bottom: 3px solid rgb(194, 182, 229);
}

h1 {
  color: rgb(194, 182, 229);
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color: rgb(194, 182, 229);
}

.contact {
  padding: 50px;
}


footer {
  background-color: #111;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid rgb(194, 182, 229);
}

```

## OUTPUT:
![alt text](<Screenshot 2025-10-07 202125.png>)
![alt text](<Screenshot 2025-10-07 202224.png>)
![alt text](<Screenshot 2025-10-07 202620.png>)
![alt text](<Screenshot 2025-10-07 202634.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
