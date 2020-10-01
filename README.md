# Html-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="project2.css">
    <link rel="stylesheet" media="only screen and (max-width: 1200px)" href="phone.css">
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhaina+2&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Thambi+2&display=swap" rel="stylesheet">
    <title>Order Food Online | MyOnlineMeal.com</title>
</head>
<body>
    <nav id="navbar">
        <div class="logo">
            <img src="https://cdn.pixabay.com/photo/2012/04/13/01/51/hamburger-31775_960_720.png" alt="MyOnlineMeal">
            MyOnlineMeal
        </div>
        <ul>
            <li class="item"><a href="#">Home</a></li>
            <li class="item"><a href="#container">Services</a></li>
            <li class="item"><a href="#container2">Our Clients</a></li>
            <li class="item"><a href="#container3">Contact Us</a></li>
        </ul>
    </nav>
    <section id="home">
        <h2 class="heading">Welcome to MyOnlineMeal</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque optio libero temporibus quisquam atque minima!</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, earum.</p>
        <button class="btn">Order Now!</button>
    </section>
    <section id="container">
        <div id="ourservices">
            <h2 class="primary">Our Services</h2>
            <div class="boxmajor">
                <div class="box">
                    <img src="https://cdn.pixabay.com/photo/2017/12/10/14/47/piza-3010062_960_720.jpg" alt="">
                    <h2 class="secondary">Food Ordering</h2>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corrupti ex placeat nemo laborum perspiciatis dolorem, dolores repudiandae fugiat repellat ipsum recusandae, debitis, consequatur blanditiis atque nobis magnam porro temporibus tempore.</p>
                </div>
                <div class="box">
                    <img src="https://cdn.pixabay.com/photo/2016/02/20/19/23/hamburger-1212625_960_720.jpg" alt="">
                    <h2 class="secondary">Food Catering</h2>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corrupti ex placeat nemo laborum perspiciatis dolorem, dolores repudiandae fugiat repellat ipsum recusandae, debitis, consequatur blanditiis atque nobis magnam porro temporibus tempore.</p>
                </div>
                <div class="box">
                    <img src="https://cdn.pixabay.com/photo/2014/10/19/20/59/hamburger-494706_960_720.jpg" alt="">
                    <h2 class="secondary">Bulk Ordering</h2>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corrupti ex placeat nemo laborum perspiciatis dolorem, dolores repudiandae fugiat repellat ipsum recusandae, debitis, consequatur blanditiis atque nobis magnam porro temporibus tempore.</p>
                </div>
            </div>
        </div>
    </section>
    <section id="container2">
        <h2 class="primary">Our Clients</h2>
        <div id="clients">
            <div class="client_item">
                <img src="https://cdn.pixabay.com/photo/2017/01/19/09/11/logo-google-1991840_960_720.png" alt="">
            </div>
            <div class="client_item">
                <img src="https://cdn.pixabay.com/photo/2018/05/08/21/08/apple-3383931_960_720.png" alt="">
            </div>
            <div class="client_item">
                <img src="https://cdn.pixabay.com/photo/2013/01/29/09/52/facebook-76536_960_720.png" alt="">
            </div>
            <div class="client_item">
                <img src="https://cdn.pixabay.com/photo/2016/11/18/11/16/social-1834013_960_720.png" alt="">
            </div>
        </div>
    </section>
    <section id="container3">
        <h2 class="primary">Contact Us</h2>
        <div id="contact">
            <form action="#">
                <div class="contact_item">
                    <label for="name">Name:</label><br>
                    <input type="text" name="name" id="name" placeholder="Enter your name">
                </div>
                <div class="contact_item">
                    <label for="phone">Contact Number:</label><br>
                    <input type="tel" name="phone" id="phone" placeholder="Enter your contact number">
                </div>
                <div class="contact_item">
                    <label for="email">Email:</label><br>
                    <input type="email" name="email" id="email" placeholder="Enter your email address">
                </div>
                <div class="contact_item">
                    <label for="textarea">Write about yourself:</label><br>
                    <textarea name="textarea" id="textarea" cols="30" rows="10" placeholder="Write here"></textarea>
                </div>
                <div class="contact_item">
                    <button class="btn1">Submit</button>
                </div>
            </form>
        </div>
    </section>
    <footer>
        Copyright &copy; All rights reserved.
    </footer>
</body>
</html>
