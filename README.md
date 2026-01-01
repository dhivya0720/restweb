# Ex.06 Restaurant Website
## Date:01/01/2026

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
dhivya.html
```
<html>
    <head>
        <title>DA ANDREA</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <div class="content">
           <a href="about.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="home">
            <div class="name">
                <h1>DA ANDREA</h1>
                <h2>Authentic Italian Dining in the Heart of NYC</h2>
                <div class="quote">Savours the flavors of Authentic Italian cuisine</div>
                <div class="desc">
                    <p>
                        A refined neighborhood Italian ristorante celebrating the elegance of
        traditional Italian cuisine. With a focus on fresh ingredients,
        time-honored recipes, and warm hospitality, Da Andrea offers a dining
        experience that is both sophisticated and inviting. Every dish is
        thoughtfully prepared to capture the authentic flavors of Italy,
        creating moments worth savoring.
                   </p>
                </div>
            </div>
        <div class="book">
            <div class="Outdoor Dining">
            <img src="outdoor dining.jpg" alt="outdoor dining">
            <h2>Make Reservation Here!</h2>
            <button>Book a Table</button>
            </div>
            <div class="Restaurant Interior">
            <img src="interior dining.jpg" alt="restarurant dining">
            <h2>Make Reservation Here!</h2>
            <button>Book a Table</button>
            </div>
        </div>
    </div>
</body>
</html>
```
style.css
```
body
{
    width: 1470px;
    height: 880px;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    background:url(backgroundorg.jpg)no-repeat center/contain;
    background-size:cover;
}
.content
{
    color: pink;
    font-size: larger;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-weight: bolder;
    padding:5px;
    justify-content: space-evenly;
    top:40px;
    right:40px;
    position:absolute;
}
.home
{
 
    color:rgb(255, 0, 72);
    font-family: Verdana;
    text-align:center;
    position:absolute;
    font-size: 10px;
    top:10px;
    font-size: small;
}
.name
{
    color:deepskyblue;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: medium;
    text-align: center;
    font-weight: bold;
}
.desc
{
    color: rgb(13, 216, 30);
    font-family: 'Times New Roman', Times, serif;
    font-size: 30px;
    font-weight: bold;
}

.Outdoor
{
    position: absolute;
    left: 80px;
    top: 300px;
    width: 200px;
}
.Interior
{
    position: absolute;
    right: 300px;
    top: 300px;
    width: 200px;
}

button
{
    border:5px;
    border-radius: 10px;
    background-color: darkorange;
    font-size: small;
    font-weight: bold;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
```
menu.html
```
<html>
    <head>
        <title>DA ANDREA</title>
        <link href="style3.css" rel="stylesheet">
    </head>
    <body>
        <div class="content">
           <a href="about.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    <div class="header">
        <h1>Our Menu</h1>
    </div>
     <div class="menu">
        <h2>Explore Our Delicious Dishes</h2>
        <div class="container">
             <div class="starter1">
                <img src="Bruschetta al Pomodoro.jpg" alt="Bruschetta al Pomodoro">
                <h3>Bruschetta al Pomodoro</h3>
                <p>Bruschetta al Pomodoro is a classic Italian starter made with slices of toasted rustic breadtopped with fresh tomatoes, basil, garlic, and extra-virgin olive oil.
                </p>
                <div class="price">Rs. 180</div>
             </div>

                <div class="starter2">
                <img src="caprese salad.jpg" alt="Caprese Salad">
                <h3>Caprese Salad</h3>
                <p>Fresh mozzarella paired with ripe tomatoes and fragrant basil, drizzled with extra-virgin olive oil for a light, refreshing start.</p>
                <div class="price">Rs. 220</div>
            </div>

            <div class="Pizza">
                <img src="Daviola Pizza.jpg" alt="Daviola Pizza">
                <h3>Daviola Pizza</h3>
                <p>Wood-fired pizza topped with spicy salami, rich tomato sauce, and melted mozzarella, finished with a touch of chili heat.</p>
                <div class="price">Rs. 220</div>
            </div>
            <div class="Pasta">
                <img src="spaghetti carbonara.jpg " alt="spaghetti carbonara">
                <h3>spaghetti carbonara</h3>
                <p>Classic Roman pasta with creamy egg yolk sauce, crispy pancetta, parmesan cheese, and cracked black pepper.</p>
                <div class="price">Rs. 340</div>
            </div>
            <div class="main-course">
                <img src="pollo alla.jpg" alt="Pollo alla Griglia">
                <h3>Pollo alle Griglia</h3>
                <p>Tender grilled chicken marinated in Italian herbs, garlic, and olive oil, served juicy and flavorful.</p>
                <div class="price">Rs. 420</div>
            </div>
            <div class="dish">
                <img src="steak.jpg" alt="steak">
                <h3>Steak</h3>
                <p>Perfectly grilled premium-cut steak seasoned with rosemary and olive oil, delivering rich flavor and tender texture.</p>
                <div class="price">Rs. 650</div>
            </div>
        </div>
     
    </body>
</html>
            
```
style3.css
```
body
{
    background: url(background.png)no-repeat center/contain;
    background-size:cover;
}
.content
{
    
    font-size: larger;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-weight: bolder;
    padding:5px;
    justify-content: space-evenly;
    top:40px;
    right:40px;
    position:absolute;
    align-items: center;
}
.header
{
    align-items: center;
    font-size: large;
    font-weight: bold;
}

.container
{

    display: grid;
     grid-template-columns: repeat(3, 1fr);
    gap: 30px;
    max-width: 1100px;
    margin: auto;
}
.menu
{
   background: rgba(255, 255, 255, 0.95);
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    height: auto;  
    width:100%;               
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.starter1
{
     background: rgba(226, 110, 168, 0.95);
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    height: 350px;  
    width:240px;               
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.starter1 img {
     width: 50%;
    height: 200px;                
    object-fit: cover;
    border-radius: 12px;
}
.price
{
     font-weight: bold;
    color:blueviolet;
}
.starter2
{
     background: rgba(226, 110, 168, 0.95);
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    height: 350px;  
    width:240px;               
    display: flex;
    flex-direction:column;
    justify-content: space-between;
}
.starter2 img {
     width: 50%;
    height: 200px;                
    object-fit: cover;
    border-radius: 12px;
}
.price
{
     font-weight: bold;
    color:blueviolet;
}
.pizza
{
     background: rgba(226, 110, 168, 0.95);
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    height: 350px;  
    width:240px;               
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.pizza img {
     width: 50%;
    height: 200px;                
    object-fit: cover;
    border-radius: 12px;
}
.price
{
     font-weight: bold;
    color:blueviolet;
}
.pasta
{
     background: rgba(226, 110, 168, 0.95);
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    height: 350px;  
    width:240px;               
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.pasta img {
     width: 50%;
    height: 200px;                
    object-fit: cover;
    border-radius: 12px;
}
.price
{
     font-weight: bold;
    color:blueviolet;
}
.main-course
{
     background: rgba(226, 110, 168, 0.95);
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    height: 350px;  
    width:240px;               
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.main-course img {
     width: 50%;
    height: 200px;                
    object-fit: cover;
    border-radius: 12px;
}
.price
{
     font-weight: bold;
    color:blueviolet;
}
.dish
{
     background: rgba(226, 110, 168, 0.95);
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    height: 350px;  
    width:240px;               
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.dish img {
     width: 50%;
    height: 200px;                
    object-fit: cover;
    border-radius: 12px;
}
.price
{
     font-weight: bold;
    color:blueviolet;
}
```
admin.html
```
<html>
    <head>
        <title>DA ANDREA</title>
        <link href="style4.css" rel="stylesheet">
    </head>
    <body>
       <div class="content">
           <a href="about.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    <div class="admin">
        <h1><b>ADMINISTRATION TEAM</b></h1>
      </div>
      <div class="admingrid">
        <div class="adminlist">
            <img src="dhivya.jpeg " width="130" height="250">
          <h1>DHIVYA DARSHNEE U</h1>
          <p class="post">CEO</p>
        </div>
        <div class="adminlist">
          <img src="vijay.jpg" width="130" height="250">
          <h1>VIJAY</h1>
          <p class="post">EXECUTIVE CHEF</p>
        </div>
        <div class="adminlist">
          <img src="deepika padukone.jpg" width="120" height="200">
          <h1>DEEPIKA PADUKONE</h1>
          <p class="post">GENERAL MANAGER</p>
        </div>
        <div class="adminlist">
          <img src="kendall.jpg " width="130" height="250">
          <h1>KENDALL JENNER</h1>
          <p class="post">FOOD AND BEVERAGE DIRECTORr</p>
        </div>
        <div class="adminlist">
          <img src="kylie jenner.jpg " width="130" height="250">
          <h1>KYLIE JENNER</h1>
          <p class="post">BRAND MANAGER</p>
        </div>
    </div>
      </div>
      <footer class="copyrights">&copy; DHIVYA DARSHNEE U(25009986)</footer>
    </div>
  </body>
</html>
```
style4.css
```
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(Background.jpg);
    background-size: cover;
}

.content
{
    color: pink;
    font-size: larger;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-weight: bolder;
    padding:5px;
    justify-content: space-evenly;
    top:40px;
    right:40px;
    position:absolute;
}

.admin {
    color:chocolate;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: 40px;
}

.admingrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.adminlist{
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.adminlist img {
    border-radius: 10px;
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 50% / 35%;
}

.adminlist h1 {
    font-size: 1.5em;
    color:aqua;
    margin-top: 15px;
}

.adminlist p {
    color:red;
    margin-bottom: 0px;
}

.copyrights {
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 30px;
    left: -20px;
    position: relative;
}
```
contact.html
```
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style5.css" />
  </head>
  <body>
    <div class="background">
      <div class="content">
           <a href="about.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
<header>
    <h1>Contact Us</h1>
</header>

<div class="contact">
    <h2>We'd Love to Hear from You!</h2>
    <form>
        <input type="text" name="name" placeholder="Your Full Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="tel" name="phone" placeholder="Your Phone Number (optional)">
        <textarea name="message" placeholder="Your Message..." required></textarea>
        <button type="submit">Send Message</button>
    </form>
</div>

</body>
</html>
```
style5.css
```
body
  {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: white;
 }
.content
{
    color: pink;
    font-size: larger;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-weight: bolder;
    padding:5px;
    justify-content: space-evenly;
    top:40px;
    right:40px;
    position:absolute;
}

 header 
 {
    text-align: center;
    background-color: white;
    padding: 20px;
}
        
.contact
 {
    padding: 30px;
    max-width: 600px;
    margin: auto;
    background: white;
     border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        
}
 h2 
 {
    text-align: center;
    margin-bottom: 20px;
}
form
 {
    display: flex;
    flex-direction: column;
    gap: 15px;

}
 input
  {
     padding: 10px;
     font-size: 16px;
     border: 1px solid whitesmoke;
     border-radius: 5px;
}
textarea
  {
     padding: 10px;
     font-size: 16px;
     border: 1px solid whitesmoke;
     border-radius: 5px;
}

.contact-section textarea 
{
    resize: none;
    height: 100px;
        
}

.button
  {
     padding: 10px;
     font-size: 16px;
     border: 1px solid whitesmoke;
     border-radius: 5px;
}
 button
  {
    background-color: #4a4a4a;
    color: white;
     cursor: pointer;
    
}
```

## OUTPUT:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
