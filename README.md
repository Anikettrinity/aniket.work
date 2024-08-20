<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <link rel="stylesheet" href="web.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
  <style>
    body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #3b0606;
    background-image: url('monochh.png.jpg');
    background-size: cover; /* Cover the entire viewport */
    background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Prevent repeating the image */
    background-attachment: fixed; /* Fix the image in place (optional) */
}

header {
    
    color: #110f0f;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    color: #312b2b;
    text-decoration: none;
    text-decoration: underline;
    text-decoration-style: solid;
    text-decoration-thickness: 2px;
}

main {
    padding: 90px;
}

section {
    margin-bottom: 20px;
    background: #fff;
    padding: 20px;
    font: caption;
    font-size: medium;
    font-style: calc();
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #333;
    color: #fff;
}
.photo-container {
    text-align: center;
}

.mini-photo {
    width: 100px; /* Adjust the width to your desired size */
    height: auto; /* Maintain aspect ratio */
    border-radius: 8px; /* Optional: Add rounded corners */
    border: 2px solid #ddd; /* Optional: Add a border */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Optional: Add shadow */
}
.mini-photo:hover {
    background-color: #2980b9;
    transform: scale(1.05);
}
.mini-photo-icon {
    width: 20px;
    height: 20px;
    fill: #fff;
}
.left-aligned {
    text-align: left;
}
/* Reset default button styles */
button {
    border: none;
    cursor: pointer;
    outline: none;
}

/* Fancy button styles */
.fancy-button {
    display: inline-block;
    padding: 15px 30px;
    font-size: 16px;
    font-weight: bold;
    color: #fff;
    background: linear-gradient(135deg, #b1abab, #b1abab); /* Gradient background */
    border-radius: 8px; /* Rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3); /* Shadow effect */
    transition: all 0.3s ease; /* Smooth transition for effects */
    text-transform: uppercase; /* Uppercase text */
}

.fancy-button:hover {
    background: linear-gradient(135deg, #8a8585, #5e5757); /* Reverse gradient on hover */
    transform: scale(1.05); /* Slightly enlarge the button */
}

.fancy-button:active {
    background: #3b3838; /* Solid color on click */
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.3); /* Reduce shadow on click */
    transform: scale(0.98); /* Slightly shrink the button */
}

header {
    position: relative;
}

.logo {
    position: absolute;
    top: -100px; /* Adjust this value to control vertical position */
    left: 10px; /* Adjust this value to control horizontal position */
    width: 200px; /* Adjust the size of the logo */
    height: auto; /* Maintain aspect ratio */
}
.logo:hover {
    background-color: #2980b9;
    transform: scale(1.05);
}

.logo-icon {
    width: 20px;
    height: 20px;
    fill: #665b5b;
}
nav {
    background-color: #333;
    padding: 10px;
}

.nav-menu {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

.nav-menu li {
    margin: 0 10px;
}

.nav-button {
    display: inline-block;
    
    text-decoration: none;
    padding: 10px 20px;
    color: #fff;
    background-color: #565b61;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s, transform 0.2s;
}

.nav-button:hover {
    background-color: #575a5e;
    transform: scale(1.1);
}

.nav-button:active {
    background-color: #4f555c;
}
.search-container {
    position: relative;
    display: inline-block;
  }
  
  .search-container input {
    padding: 8px 40px 8px 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
  }
  
  .search-container i {
    position: absolute;
    right: 10px;
    top: 50%;
    transform: translateY(-50%);
    color: #888;
  }
  .search-container:hover {
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

.search-input {
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 50px;
    outline: none;
    flex: 1;
    transition: padding 0.3s ease;
}

.search-input::placeholder {
    color: #aaa;
}

.search-button {
    border: none;
    background-color: #3498db;
    padding: 10px 20px;
    border-radius: 50px;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
}

.search-button:hover {
    background-color: #2980b9;
    transform: scale(1.05);
}

.search-icon {
    width: 20px;
    height: 20px;
    fill: #fff;
}
p{
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.language-bar {
    display: flex;
    justify-content: flex-end;
    padding: 10px;
    font: bold;
}

.dropdown {
    position: relative;
    display: inline-block;
}

.dropbtn {
    background-color: #c21313;
    color: white;
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

.dropbtn:hover {
    background-color: #45a049;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    z-index: 1;
    border-radius: 5px;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {
    background-color: #f1f1f1;
}

.dropdown:hover .dropdown-content {
    display: block;
}

.dropdown:hover .dropbtn {
    background-color: #3e8e41;
}
  </style>
    <header>
        <h1>Trinity By Aniket</h1>
         <div class="language-bar">
        <div class="dropdown">
            <button class="dropbtn">Language</button>
            <div class="dropdown-content">
                <a href="#">English</a>
                <a href="#">Spanish</a>
                <a href="#">French</a>
                <a href="#">German</a>
            </div>
        </div>
    </div>
        <div class="search-container">
            <input type="text" placeholder="Search...">
            <i class="fas fa-search"></i>
        </div>
        <header>
        <img src="sevenlogo.jpg" alt="Logo" class="logo">
    </header><ul class="nav-menu">
        <li><a href="#home" class="nav-button">Home</a></li>
        <li><a href="#about" class="nav-button">About</a></li>
        <li><a href="#services" class="nav-button">Services</a></li>
        <li><a href="#contact" class="nav-button">Contact</a></li>
    </ul><br>
    <button class="fancy-button">Get Started</button>
</nav>
    
    </header>
    <main>
        <section>
            <h2>About Me</h2> 
            <div class="photo-container">
                <img src="mini-web.jpg.jpeg" alt="A description of the mini photo" class="mini-photo">
            </div>
            <p>

                Aniket is an accomplished coder whose passion for technology is matched only by his dedication to solving complex problems. With a keen eye for detail and a profound understanding of various programming languages, Aniket excels in creating efficient, innovative solutions. His journey began with a fascination for computers, which soon evolved into a deep commitment to mastering coding principles and techniques. Whether it's developing intricate algorithms, designing user-friendly interfaces, or optimizing code for performance, Aniket approaches every challenge with enthusiasm and precision. His collaborative spirit and willingness to share knowledge make him a valued asset in any development team. Always eager to learn and adapt, Aniket is not just a coder but a lifelong learner, continuously pushing the boundaries of what’s possible in the ever-evolving world of technology.
                
                ---
                
                Feel free to adjust or expand upon this to better fit Aniket’s specific experiences and achievements!</p>
        </section>
        <section>
            <h2>My Work</h2>
            <p>Coders and web developers are the architects behind the digital world, shaping how we interact with technology and the internet. Coders write the underlying code that powers software applications, websites, and various tech innovations, translating complex problems into efficient, functional solutions. Web developers, a specialized group of coders, focus on building and maintaining websites and web applications. They utilize languages like HTML, CSS, and JavaScript to create engaging, user-friendly interfaces and ensure seamless performance across different devices and browsers. In a rapidly evolving field, web developers are tasked with keeping up with the latest technologies and trends, such as responsive design and interactive features, to deliver optimal user experiences. Their work is crucial in making the internet accessible and enjoyable for everyone, bridging the gap between technical functionality and user interaction.</p>
        </section>
    </main>
    <footer>
        <p>Support</p>
        <p>Terms & Private Policies</p>
        <p>Rights</p>
        <p>&copy; 2024 Trinity Pvt Ltd</p>
    </footer>
</body>
</html>
