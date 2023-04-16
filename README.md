<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Portfolio</title>
        <link rel="stylesheet" href="stylesheet.css">
        <script src="https://kit.fontawesome.com/cfb3667222.js" crossorigin="anonymous"></script>
    </head>
    <body>
        <div id="header">
            <div class="container">
                <nav>
                    <img src="images/logo.png" class="logo">
                    <ul id="sidemenu">
                        <li><a href="#header">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#portfolio">Portfolio</a></li>
                        <li><a href="#contact">Contact</a></li>
                        <i class="fa-solid fa-circle-xmark" onclick="closemenu()"></i>
                    </ul>
                    <i class="fa-solid fa-bars" onclick="openmenu()"></i>
                </nav>

                <div class="header-text">
                    <p>UI/UX Designer</p>
                    <h1>Hi, I'm <span>Ikhsan Maulana</span><br>From Indonesia</h1>
                </div>
            </div>
        </div>
<!----------------------------------About----------------->
        <div id="about">
            <div class="container">
                <div class="row">
                    <div class="about-col-1">
                        <img src="images/user.jpg">
                    </div>
                    <div class="about-col-2">
                        <h1 class="sub-title">About Me</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus cum distinctio, quasi perspiciatis saepe, nam sed officia at incidunt tempore ad iure labore nisi dolore deleniti sapiente rerum culpa harum?</p>

                        <div class="tab-titles">
                            <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                            <p class="tab-links" onclick="opentab('experience')">Experience</p>
                            <p class="tab-links" onclick="opentab('education')">Education</p>
                        </div>

                        <div class="tab-contents active-tab" id="skills">
                            <ul>
                                <li><span>UI/UX</span><br>Designing Web/App interfaces</li>
                                <li><span>Web Development</span><br>Web/App Development</li>
                                <li><span>App Development</span><br>Building Android/iOS apps</li>
                            </ul>
                        </div>

                        <div class="tab-contents" id="experience">
                            <ul>
                                <li><span>2019 - 2020</span><br>UI/UX design Training at ITB Institute</li>
                                <li><span>2020 - 2021</span><br>Team Head at Starapp</li>
                                <li><span>2022 - Current</span><br>Building Android/iOS apps</li>
                            </ul>
                        </div>

                        <div class="tab-contents" id="education">
                            <ul>
                                <li><span>UIN Ar-Raniry Banda Aceh 2013 - 2018</span><br>Arabic Language and Literature</li>
                                <li><span>Web Development</span><br>Web/App Development</li>
                                <li><span>App Development</span><br>Building Android/iOS apps</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
<!-----------------------Services--------------->
        <div id="services">
            <div class="container">
                <h1 class="sub-title">My Services</h1>
                <div class="services-list">
                    <div>
                        <i class="fa-solid fa-code"></i>
                        <h2>Web Design</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium sunt iste beatae impedit dolore cupiditate explicabo, debitis recusandae optio placeat eveniet ex fuga saepe, nisi quis, temporibus necessitatibus aliquam aliquid.</p>
                        <a href="#">Learn more</a>
                    </div>

                    <div>
                        <i class="fa-solid fa-crop"></i>
                        <h2>UI/UX Design</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium sunt iste beatae impedit dolore cupiditate explicabo, debitis recusandae optio placeat eveniet ex fuga saepe, nisi quis, temporibus necessitatibus aliquam aliquid.</p>
                        <a href="#">Learn more</a>
                    </div>

                    <div>
                        <i class="fa-brands fa-app-store-ios"></i>
                        <h2>App Design</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium sunt iste beatae impedit dolore cupiditate explicabo, debitis recusandae optio placeat eveniet ex fuga saepe, nisi quis, temporibus necessitatibus aliquam aliquid.</p>
                        <a href="#">Learn more</a>
                    </div>
                </div>
            </div>
        </div>
<!----------------------------------Portfolio----------------->
        <div id="portfolio">
            <div class="container">
                <h1 class="sub-title">My Work</h1>
                <div class="work-list">
                    <div class="work">
                        <img src="images/work-1.jpg">
                        <div class="layer">
                            <h3>Al Qur'an App</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum facilis accusantium voluptas excepturi optio animi repellat, repellendus harum adipisci ex nisi quidem eius assumenda ipsa praesentium? Doloremque dolorum pariatur voluptate?</p>
                            <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                        </div> 
                    </div>

                    <div class="work">
                        <img src="images/work-2.jpg">
                        <div class="layer">
                            <h3>Tilawah App</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum facilis accusantium voluptas excepturi optio animi repellat, repellendus harum adipisci ex nisi quidem eius assumenda ipsa praesentium? Doloremque dolorum pariatur voluptate?</p>
                            <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                        </div>
                    </div>

                    <div class="work">
                        <img src="images/work-3.jpg">
                        <div class="layer">
                            <h3>Ngaji Bareng App</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum facilis accusantium voluptas excepturi optio animi repellat, repellendus harum adipisci ex nisi quidem eius assumenda ipsa praesentium? Doloremque dolorum pariatur voluptate?</p>
                            <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                        </div>
                    </div>
                </div>
                <a href="" class="btn">See More</a>
            </div>
        </div>
        <!----------------------------------Contact Form----------------->
        <div id="contact">
            <div class="container">
                <div class="row">
                    <div class="contact-left">
                        <h1 class="sub-title">Contact Me</h1>
                        <p><i class="fa-solid fa-paper-plane"></i>ikhsanmou95@gmail.com</p>
                        <p><i class="fa-solid fa-phone-volume"></i>+6281214710491</p>
                        <div class="social-icons">
                            <a href="https://facebook.com/"><i class="fa-brands fa-facebook"></i></a>
                            <a href="#"><i class="fa-brands fa-twitter-square"></i></a>
                            <a href="#"><i class="fa-brands fa-instagram"></i></a>
                            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                        </div>
                        <a href="images/CV.pdf" download class="btn btn2">Download CV</a>
                    </div>

                    <div class="contact-right">
                        <form>
                            <input type="text" name="Name" placeholder="Your Name" required>
                            <input type="email" name="Email" placeholder="Your Email" required>
                            <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                            <button type="submit" class="btn btn2">Submit</button>
                        </form>
                    </div>
                </div>
            </div>
            <div class="copyright">
                <p>Copyright <i class="fa-sharp fa-regular fa-copyright"></i>ikhsan, made with <i class="fa-sharp fa-solid fa-heart"></i> by Ikhsan Maulana</p>
            </div>
        </div>

        <script>

            var tablinks = document.getElementsByClassName("tab-links");
            var tabcontents = document.getElementsByClassName("tab-contents");
            
            function opentab(tabname) {
                for(tablink of tablinks){
                    tablink.classList.remove("active-link");
                }
                for(tabcontent of tabcontents){
                    tabcontent.classList.remove("active-tab");
                }
                event.currentTarget.classList.add("active-link");
                document.getElementById(tabname).classList.add("active-tab");
            }

        </script>

        <script>

            var sidemenu = document.getElementById("sidemenu");

            function openmenu(){
                sidemenu.style.right = "0";
            }
            function closemenu(){
                sidemenu.style.right = "-200px";
            }

        </script>
    </body>
</html>
