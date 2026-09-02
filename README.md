# dtkfolio ⚡️ [![GitHub](https://img.shields.io/github/license/kusal-tharindu/portfolio?color=blue)](https://github.com/kusal-tharindu/portfolio/blob/main/LICENSE) ![GitHub stars](https://img.shields.io/github/stars/kusal-tharindu/portfolio) ![GitHub forks](https://img.shields.io/github/forks/kusal-tharindu/portfolio) 
## A minimal portfolio template for Developers!

<h2 align="center">
  <img src="images/demo.gif" alt="dtkfolio" width="600px" />
  <br>
</h2>

## Features
In this project I created personal portfolio website using HTML CSS and JavaScript. You can use this website to make your online resume or CV.

⚡️ Modern UI Design + Reveal Animations\
⚡️ Dark theme\
⚡️ One Page Layout\
⚡️ Styled with HTML + CSS +JavaScript\
⚡️ Fully Responsive\
⚡️ Valid HTML5 & CSS3\
⚡️ add contact info and contact form.\
⚡️ Your can receive the contact form data on your google sheets\
⚡️ Well organized documentation

To view the demo: **[click here](https://kusal-tharindu.github.io/portfolio/)**

---

## Why do you need a portfolio? 🤷‍♀️

- Professional way to showcase your work to digital word
- Increases your visibility and online presence
- Shows you’re more than just a resume

---
## Getting Started 🚀 

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites 📋

You'll need [Git](https://git-scm.com) and IDE(Integrated development environment) [Visual Studio Code](https://code.visualstudio.com/download) installed on your computer.

 ### Download 👇

 - [Git](https://git-scm.com)  
 - IDE ( Integrated development environment ) [Visual Studio Code](https://code.visualstudio.com/download)


---

## How To Use 🔧

From your command line, first clone DTKfolio:

### 1. Download code
- Method-01
```bash
# Clone the repository
$ git clone https://github.com/kusal-tharindu/DTKfolio

```
- Method-02

Download directly from github.
<h2 align="center">
  <img src="images\download-2.png" alt="Simplefolio" width="300px" height="300px" />
  <br>
</h2>
<!-- photo -->

### 2. Open code via IDE
You start DIE and open the download floder(portfolio-main) with it and edit it with your details. I am using VS Code for this demo.

### 3. Open the html file via your localhost and view

download [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension. Once your server has started, open ***index.html*** file via Live Server extension.

<h2 align="center">
  <img src="images/demo.gif" alt="Simplefolio" width="600px" />
  <br>
</h2>

---

## Template Instructions:


Go to `index.html` and put your information, there are several sections:

###  <span style= "color: #00c1ff">**(1) Head** </span>


- Search below `html` code in `head` section
- Replace *Kusal Tharindu* with you name 

```html
<!-- head -->
<title>Kusal Tharindu</title>
```

###  <span style= "color: #00c1ff">**(2) Side-menu** </span>

- Repale `sidemenu` infomation and `header text` with you details
- Change image in the `img src="images/logo.png" class="logo"` html code.

```html
<!-- sidemenu -->
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/logo.png" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">My services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()"></i>
            </nav>

            <div class="header-text">
                <p>Network Engineer</p>
                <h1>I'm <span>Kusal</span><br> from Sri lanka</h1>
            </div>

        </div>
    </div>
```

###  <span style= "color: #00c1ff">**(3) About** </span>

- Repale `ABOUT` infomation and `skills` with you details.
- Change image in the `img src="images/user.png"` html code.

```html
<div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/user.png">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About me</h1>
                    <p>This site focuses on cyber security and network engineering. Knowledge of the these 
                        fields goes beyond the ordinary and we are tempted to present it in
                         a new dimension and different way.</p>

                         <div class="tab-titles">
                            <p class="tab-links active-link" onclick="opentab('skills')" >Skills</p>
                            <p class="tab-links" onclick="opentab('experience')" >Experiences</p>
                            <p class="tab-links" onclick="opentab('education')" >Education</p>
                         </div>

                         <div class="tab-contents active-tab" id="skills">
                            <ul>
                                <li><span>Networking</span><br>configuer the routers</li>
                                <li><span>Cyber Securety</span><br>wireshark configuratiuon</li>
                            </ul>
                         </div>

                         <div class="tab-contents" id="experience">
                            <ul>
                                <li><span>2021- currnt</span><br>diolog</li>
                                <li><span>2020-2021</span><br>MIT</li>
                            </ul>
                         </div>

                         <div class="tab-contents" id="education" >
                            <ul>
                                <li><span>Networking</span><br>Harvard University</li>
                                <li><span>Cyber Securety</span><br>CISCO</li>
                            </ul>
                         </div>
                </div>
            </div>
        </div>
    </div>
```
###  <span style= "color: #00c1ff">**(4) Services** </span>

- Repale `services` infomation  with you details.
- Add you personal link for that specific Services in the `<a href="#">` htlm code.

```html
<!-- Services -->

<div id="services">
    <div class="container">
        <h1 class="sub-title">My services</h1>
        <div class="services-list">
            <div>
                <i class="fa-solid fa-server"></i>
                <h2>Networking</h2>
                <p>Networking Essentials ( Version 2) Pretest Exam answers</p>
                <a href="#">Learn more</a>
            </div>

            <div>
                <i class="fa-solid fa-user-secret"></i>
                <h2>Cyber security</h2>
                <p>Cyber security is the application of technologies, processes, 
                    and controls to protect systems, networks, programs</p>
                <a href="#">Learn more</a>
            </div>

            <div>
                <i class="fa-solid fa-code"></i>
                <h2>Programming</h2>
                <p>Programming involves tasks such as analysis, generating algorithms, profiling algorithms'
                     accuracy and resource consumption</p>
                <a href="#">Learn more</a>
            </div>
        </div>
    </div>
</div>
```

###  <span style= "color: #00c1ff">**(5) Portpolio** </span>

- Repale `portfolio` infomation  with you details.
- Add you personal link for that specific portfolio in the `<a href="#">` htlm code.

```html
<!-- portpolio -->
<div id="portfolio">
    <div class="container">
        <h1 class="sub-title">My work</h1>
        <div class="work-list">
            <div class="work">
                <img src="images/work-1.png">
                <div class="layer">
                    <h3>Social app</h3>
                    <p>Create app and make up to $1000 monthly passive income. Absolutely free 
                        forever. No monthly charges, fees or paid features</p>
                        <a href="#"><i class="fa-solid fa-link"></i></a>
                </div>
            </div>

            <div class="work">
                <img src="images/work-2.png">
                <div class="layer">
                    <h3>Mucic app</h3>
                    <p>Create app and make up to $1000 monthly passive income. Absolutely free 
                        forever. No monthly charges, fees or paid features</p>
                        <a href="#"><i class="fa-solid fa-link"></i></a>
                </div>
            </div>

            <div class="work">
                <img src="images/work-3.png">
                <div class="layer">
                    <h3>Online app</h3>
                    <p>Create app and make up to $1000 monthly passive income. Absolutely free 
                        forever. No monthly charges, fees or paid features</p>
                        <a href="#"><i class="fa-solid fa-link"></i></a>
                </div>
            </div>
        </div>

        <a href="#" class="btn">See more</a>
    </div>
</div>

```

###  <span style= "color: #00c1ff">**(6) Contect** </span>

- Repale `contect` infomation  with you details.
- Add you social-media link for that specific portfolio in the `<a href="#">` htlm code.

```html
<!-- ********contect*******-->

<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact me</h1>
                <p><i class="fa-solid fa-envelope"></i> contact@example.com</p>
                <p><i class="fa-solid fa-square-phone"></i> 011345678</p>
                <div class="social-icons">
                    <a href="#"><i class="fa-brands fa-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-twitter-square"></i></a>
                    <a href="#"><i class="fa-brands fa-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
    
                </div>

                <a href="Documents/my_cv.pdf" download class="btn btn2">Download CV</a>

            </div>
            <div class="contact-right">
                <form  name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your name" required>
                    <input type="email" name="email" placeholder="Your Email",required>
                    <textarea name="Massage"  rows="6" placeholder="Your Massage"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>

                <span id="msg"></span>
            </div>

        </div>
        
    </div>

    <div class="copyright">
        <p>copyright <i class="fa-regular fa-copyright"></i> kusal.Tharindu</p>
    </div>
</div>
```
###  <span style= "color: #00c1ff">**(7) how Send contact form data on Google sheets?** </span>


- You can set-up `google_scrpits` and connect with your form.
- Step by step guide: [Easy Tutorials](https://www.youtube.com/watch?v=0YFrGy_mzjY&t=6473s)

```javascript
<script>
    /* How to Send contact form data on Google sheets,  
    reference: "https://www.youtube.com/watch?v=0YFrGy_mzjY&t=6473s" */

    const scriptURL = 'https://script.google.com/macros/s/your_google_scrpits'
    const form = document.forms['submit-to-google-sheet']
  
    const msg =document.getElementById("msg")

    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
            msg.innerHTML= "Message sent successfully"
            setTimeout(function(){
                msg.innerHTML=""
            }, 5000)
            form.reset()
        })
        .catch(error => console.error('Error!', error.message))
    })
  </script>
```
---
## Deployment 📦

Once you finish your setup. You need to put your website online!

I highly recommend to use [Cloudflare pages](https://pages.cloudflare.com/) because it is super easy. By default you can get yourname.pages.dev domain. also you can set custom domain name.

---
## Authors

- **`Kusal Tharindu`** - [https://github.com/kusal-tharindu](https://github.com/kusal-tharindu)
---

## License 📄

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/kusal-tharindu/portfolio/blob/main/LICENSE) file for details.

---
## Acknowledgments 🎁

I was motivated to create this project because I wanted to contribute on something useful for the dev community.

Many thanks to [Easy Tutorials](https://www.youtube.com/@EasyTutorialsVideo).
