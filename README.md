<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Faizyab Quran Academy.com</title>
    </head>
    <style>
         body {
            font-family: Arial, sans-serif;
            margin-left: 22.5px;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #90EE90;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            margin: 0 auto;
            max-width: 1200px;
            padding: 0 1rem;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: rgb(8, 8, 8);
            text-decoration: none;
        }
        .container {
            margin: 0 auto;
            max-width: 1200px;
            padding: 1rem;
            width: 200%;
            background-color:#90EE90;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .service-card {
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1rem;
            flex: 1 1 calc(33.333% - 2rem);
            box-sizing: border-box;
        }
        .service-card h2 {
            font-size: 1.5rem;
            margin-top: 0;
        }
        .pricing {
            margin: 2rem 0;
        }
        .pricing-table {
            width: 100%;
            border-collapse: collapse;
        }
        .pricing-table th, .pricing-table td {
            border: 1px solid #070707;
            padding: 1rem;
            text-align: center;
        }
        .contact {
            margin: 2rem 0;
        }
        footer {
            background-color: #6fcc6f;
            color: white;
            text-align: center;
            width: 100%;
        }
        .button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 5px;
            margin: 0.5rem;
        }
        .button:hover {
            background-color: #45a049;
        }
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.4);
            padding-top: 60px;
        }
        .modal-content {
            background-color: #fefefe;
            margin: 5% auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
            max-width: 600px;
            border-radius: 8px;
        }
        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }
        .close:hover,
        .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }
        .modal input[type="text"], .modal input[type="email"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .modal button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 5px;
        }
        .modal button:hover {
            background-color: #45a049;
        }
        .privacy-policy {
            margin-top: 1rem;
            font-size: 0.9rem;
        }
        .privacy-policy a {
            color: #0a0a0a;
            text-decoration: none;
        }
        .privacy-policy a:hover {
            text-decoration: underline;
        }
    </style>
    <body>
        <header>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#pricing">Pricing</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><button class="button" id="loginBtn">Login</button></li>
                    <li><button class="button" id="signupBtn">Sign Up</button></li>        
                </ul>
            </nav>
            <h1>Faizyab Quran Academy</h1>        
        </header>
        <hr>
        <main background-color="#90EE90">
            <div class="container">
                <section id="home">
                    <h2>Welcome to Faizyab Quran Academy</h2>
                    <p>We offer a range of Quranic education services tailored to your needs. Our qualified tutors are here to help you with recitation, memorization, and understanding of the Quran.</p>
                </section>
            
                <section id="services">
                    <h2>Our Services</h2>
                    <div class="services">
                        <div class="service-card">
                            <h2>Qaida Course</h2>
                            <p>Learn the basics of Quranic reading and pronunciation in this foundational course.</p>
                        </div>
                        <div class="service-card">
                            <h2>Recitation Course</h2>
                            <p>Improve your Quranic recitation with proper Tajweed rules and practice.</p>
                        </div>
                        <div class="service-card">
                            <h2>Hifz (Memorization) Course</h2>
                            <p>Memorize the entire Quran with our structured memorization program, including translation and Tajweed.</p>
                        </div>
                    </div>
                </section>
            
                <section id="pricing">
                    <h2>Pricing</h2>
                    <table class="pricing-table">
                        <thead>
                            <tr>
                                <th>Course</th>
                                <th>Duration</th>
                                <th>Price (Per Month)<p><b> Save 20% </b></p></th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>Qaida Course</td>
                                <td>2 months</td>
                                <td>( 59 $ )  <del> 79 $ </del></td>
                            </tr>
                            <tr>
                                <td>Recitation Course</td>
                                <td>6 months</td>
                                <td>( 149 $ )  <del> 179 $ </del></td>
                            </tr>
                            <tr>
                                <td>Hifz Course</td>
                                <td>2 years</td>
                                <td>( 199 $ )  <del> 239 $ </del></td>
                            </tr>
                        </tbody>
                    </table>
                </section>
            
                <section id="contact">
                    <h2>Contact Us</h2>
                    <p>Email: <a href="mailto:muhammadfaizyab16@gmail.com">muhammadfaizyab16@gmail.com</a></p>
                    <p>Phone: +92 335 2811970</p>
                    <p>Address: Karachi, Pakistan</p>
                </section>
            </div>            
        </main>
        <hr>
        <footer background-color="#90EE90">
            <br>
            <nav>
                <h4>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#pricing">Pricing</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
                </h4>
            </nav>
            <h1>Faizyab Quran Academy</h1>
            <p>&copy; 2024 Online Quran Academy. All rights reserved.</p>
            <p class="privacy-policy">By using our services, you agree to our <a href="#"> Privacy Policy</a>.</p>
        <br>
        </footer>
        
        <!-- Login Modal -->
<div id="loginModal" class="modal">
    <div class="modal-content">
        <span class="close" id="closeLogin">&times;</span>
        <h2>Login</h2>
        <button class="button" style="background-color: #4285F4; margin-bottom: 1rem;">Continue with Google</button>
        <form>
            <input type="email" placeholder="Email" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
        <p class="privacy-policy">By logging in, you agree to our <a href="#">Privacy Policy</a>.</p>
    </div>
</div>

<!-- Sign Up Modal -->
<div id="signupModal" class="modal">
    <div class="modal-content">
        <span class="close" id="closeSignup">&times;</span>
        <h2>Sign Up</h2>
        <button class="button" style="background-color: #4285F4; margin-bottom: 1rem;">Continue with Google</button>
        <form>
            <input type="text" placeholder="Name" required>
            <input type="email" placeholder="Email" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Sign Up</button>
        </form>
        <p class="privacy-policy">By signing up, you agree to our <a href="#">Privacy Policy</a>.</p>
    </div>
</div>

<script>
    // Get the modal elements
    var loginModal = document.getElementById("loginModal");
    var signupModal = document.getElementById("signupModal");
    
    // Get the buttons that open the modals
    var loginBtn = document.getElementById("loginBtn");
    var signupBtn = document.getElementById("signupBtn");
    
    // Get the <span> elements that close the modals
    var closeLogin = document.getElementById("closeLogin");
    var closeSignup = document.getElementById("closeSignup");
    
    // When the user clicks the button, open the modal
    loginBtn.onclick = function() {
        loginModal.style.display = "block";
    }
    
    signupBtn.onclick = function() {
        signupModal.style.display = "block";
    }
    
    // When the user clicks on <span> (x), close the modal
    closeLogin.onclick = function() {
        loginModal.style.display = "none";
    }
    
    closeSignup.onclick = function() {
        signupModal.style.display = "none";
    }
    
    // When the user clicks anywhere outside of the modal, close it
    window.onclick = function(event) {
        if (event.target == loginModal) {
            loginModal.style.display = "none";
        }
        if (event.target == signupModal) {
            signupModal.style.display = "none";
        }
    }
</script>
    </body>
</html>
