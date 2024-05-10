# Ex.07 Software Product Company Website
## Date:26/04/2024
## Name : H Vishinu 
## Reg.No : 212223220124

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
home.html
```
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="home.css">
</head>
<body>
    <div class="nav">
        <h2>Innovatech Solutions</h2>
        <div class="logo"><img src="image.png" alt="logo" height="60px"></div>
            <li><a href="./home.html">Home</a></li>
            <li><a href="person.html">People</a></li>
            <li><a href="./product.html">Products</a></li>
            <li><a href="./contact.html">Contacts</a></li>
    </div>
    <div class="home">
        <div class="head">
            <h1>Welcome to our <br>Software Agency!</h1>
            <p class="quote">"Innovation is the ability to see change as an opportunity - not a threat." - Steve Jobs</p>
        </div>
        <div class="login">
            <h2 class="log">Login Here</h2> 
            <div class="logbox">
                <input type="text" placeholder="Username or Email" class="but"><br><br>
                <input type="text"  placeholder="Password" class="but"><br><br>
                <button type="submit" class="bute">Login</button><br><br>
                <hr id="loge">
            </div>
            <p style="text-align: center;">Don't have an account? <br><span>Sign up</span> here.</p>
        </div>
    </div>
    <footer>
        <div class="colored-line">
            <h5>Design and developed by Vishinu H (212223220124)</h5>
        </div>
    </footer>
</body>
</html>


```
home.css
```
.nav {
    display: flex;
    align-items: center;
    gap: 50px; 
    margin-top: 25px;
}

.nav h2 {
    margin-right: 400px; 
    font-size: 34px; 
    color: #4682b4;
}



li {
    list-style: none;
    font-weight: 100px;
}

body {
    background-color: #f5f5f5;
}

* {
    font-size: 20px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 10px;
}

.home {
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 80vh;
    gap: 250px;
}

.login {
    background-color: #5f9ea0;
}

.log {
    padding: 5px;
    background-color: #ffb6c1;
}

.but {
    border-radius: 10px;
}

.bute {
    border-radius: 10px;
    background-color: #8a2be2;
}

#loge {
    border-color: #ffb6c1;
}

h1 {
    color: red;
    font-size: 50px;
}

.join {
    border-radius: 10px;
    background-color: #8a2be2;
}

.quote {
    font-style: italic;
}

footer {
    position: fixed; 
    bottom: 0; 
    width: 100%; 
    text-align: center; 
}

.colored-line {
    height: 25px;
    background-color: #8a2be2; 
}

```
person.html
```
<html>
    <head>
        <link rel="stylesheet" href="person.css">
    </head>
    <body>
        <div class="nav">
            <h2>Innovatech Solutions</h2>
            <div class="logo"><img src="image.png" alt="logo" height="60px"></div>
                <li><a href="./home.html">Home</a></li>
                <li><a href="person.html">People</a></li>
                <li><a href="./product.html">Products</a></li>
                <li><a href="./contact.html">Contacts</a></li>
        </div>
        <div class="person">
            <li> <img src="vishnu.jpg" class="bod"><br><span>Vishinu</span><p>CEO</p></li>
            <li> <img src="image5.jpg"  class="bod"><br><span>Mike</span><p>Founder</p></li>
            <li> <img src="image3.png" class="bod"><br><span>Vik</span><p>Co-Founder</p></li>
            <li> <img src="image4.jpg"class="bod" ><br><span>Felix</span><p>Director</p></li>
            <li> <img src="image1.jpg" class="bod"><br><span>Joe</span><p>Assistant Director</p></li>
        </div>
        <footer>
            <div  class="colored-line">
                <h5>Design and developed by Vishinu H (212223220124)</h5>
            </div>
        </footer>
    </body>
</html>

```
person.css
```
.nav {
    display: flex;
    align-items: center;
    gap: 50px; 
    margin-top: 25px;
}

.nav h2 {
    margin-right: 400px; 
    font-size: 34px; 
    color: #4682b4;
}


li {
    list-style: none;
    font-weight: 100px;
}

body {
    background-color: #f5f5f5;
    margin: 0; /* Resetting default margin */
    padding-bottom: 50px; /* Adding padding at the bottom to accommodate the footer */
}

* {
    font-size: 20px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 60px;
}

.person {
    display: flex;
    margin-top: 230px;
    justify-content: center;
    gap: 20px;
}

.bod {
    height: 100px;
    border: 3px solid #ff6347;
}

span {
    font-size: 20px;
    font-weight: 1000;
    text-indent: 20px;
}

footer {
    position: fixed; 
    bottom: 0; 
    width: 100%; 
    text-align: center; 
}

.colored-line {
    height: 25px;
    background-color: #8a2be2; 
}

```
product.html
```
<html>
    <head>
        <link rel="stylesheet" href="person.css">
    </head>
    <body>
        <div class="nav">
            <h2>Innovatech Solutions</h2>
            <div class="logo"><img src="image.png" alt="logo" height="60px"></div>
                <li><a href="./home.html">Home</a></li>
                <li><a href="person.html">People</a></li>
                <li><a href="./product.html">Products</a></li>
                <li><a href="./contact.html">Contacts</a></li>
        </div>
        <div class="person">
            <li> <img src="vishnu.jpg" class="bod"><br><span>Vishinu</span><p>CEO</p></li>
            <li> <img src="image5.jpg"  class="bod"><br><span>Mike</span><p>Founder</p></li>
            <li> <img src="image3.png" class="bod"><br><span>Vik</span><p>Co-Founder</p></li>
            <li> <img src="image4.jpg"class="bod" ><br><span>Felix</span><p>Director</p></li>
            <li> <img src="image1.jpg" class="bod"><br><span>Joe</span><p>Assistant Director</p></li>
        </div>
        <footer>
            <div  class="colored-line">
                <h5>Design and developed by Vishinu H (212223220124)</h5>
            </div>
        </footer>
    </body>
</html>

```
product.css
```
.nav {
    display: flex;
    align-items: center;
    gap: 50px; 
    margin-top: 25px;
}

.nav h2 {
    margin-right: 400px; 
    font-size: 34px; 
    color: #4682b4;
}

li {
    list-style: none;
    font-weight: 100px;
}

body {
    background-color: #f5f5f5;
}

* {
    font-size: 20px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 10px;
}

.imge {
    border-radius: 10px;
    height: 550px;
    margin-top: 100px;
    margin-left: 450px;
}

.colored-line {
    width: 100%;
    height: 25px;
    background-color: #8a2be2;
}
footer {
    position: fixed; 
    bottom: 0; 
    width: 100%; 
    text-align: center; 
}

```
contact.html
```
<html>
    <head>
        <link rel="stylesheet" href="contact.css">
    </head>
    <body>
        <div class="nav">
            <h2>Innovatech Solutions</h2>
            <div class="logo"><img src="image.png" alt="logo" height="60px"></div>
                <li><a href="./home.html">Home</a></li>
                <li><a href="person.html">People</a></li>
                <li><a href="./product.html">Products</a></li>
                <li><a href="./contact.html">Contacts</a></li>
        </div>
        <div class="contact">
            <div class="detail">
                <h1>Contact Us</h1>
                <br>
                <input type="text" placeholder="Your Name"> <br><br>
                <input type="text" placeholder="Your Email"> <br><br>
                <input type="text" placeholder="Your Message" class="comment"> <br><br>
                <button type="submit" class="submit">Submit</button>
            </div>
            <div class="info">
                <h1>Contact Information</h1>
                <br>
                <span><strong>Address:</strong></span> Thandalam, Kancheepuram, Chennai-600028 <br>
                <span><strong>Email:</strong></span> vishinuexample@gmail.com <br>
                <span>
            </div>
            <footer>
                <div class="colored-line">
                    <h5>Design and developed by Vishinu H (212223220124)</h5>
                </div>
            </footer>

```
contact.css
```
.nav {
    display: flex;
    align-items: center;
    gap: 50px; 
    margin-top: 25px;
}
.nav h2 {
    margin-right: 400px; 
    font-size: 34px; 
    color: #4682b4;
}
li {
    list-style: none;
    font-weight: 100px;
}
body {
    background-color: #f5f5f5;
}
* {
    font-size: 20px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 10px;
}
.contact {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    gap: 300px;
}
.comment {
    padding: 50px;
}
.submit {
    background-color: #8a2be2;
}
.info {
    background-color: #ffb6c1;
    padding: 10px;
    border: 3px solid #ff6347;
    border-radius: 30px;
}
.detail {
    background-color: #ffb6c1;
    padding: 10px;
    border: 3px solid #ff6347;
    border-radius: 30px;
}
footer {
    position: fixed; 
    bottom: 0; 
    width: 100%; 
    text-align: center; 
}
.colored-line {
    height: 25px;
    background-color: #8a2be2; 
}

```

## OUTPUT:
### Home
![Screenshot 2024-05-08 141735](https://github.com/VisHinu24/softweb/assets/144244396/f5a55b07-d8cb-4aa6-9235-9c21c08f9305)
### Person
![Screenshot 2024-05-08 141745](https://github.com/VisHinu24/softweb/assets/144244396/f9c132c7-57ba-4fca-a12e-54f3628fbd2e)


### Product
![Screenshot 2024-05-08 141750](https://github.com/VisHinu24/softweb/assets/144244396/c941102a-be5f-4536-88b2-0bbe32c7776d)

### Contact
![Screenshot 2024-05-08 141756](https://github.com/VisHinu24/softweb/assets/144244396/7b4e5a4b-316b-42e8-9d6e-706cc5655956)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
