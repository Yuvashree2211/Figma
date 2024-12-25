# Ex09 Event Registration Web Application
# Date:10-10-2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
HTML
i-phone-14-plus-1

<div class="i-phone-14-plus-1">
  <img class="logo-1" src="logo-10.png" />
  <img class="logo-1-1" src="logo-1-10.png" />
  <div class="rectangle-1"></div>
  <div class="rectangle-2"></div>
  <div class="register">REGISTER</div>
  <div class="login">LOGIN</div>
</div>


i-phone-14-15-pro-max-1

<div class="i-phone-14-15-pro-max-1">
  <div class="ellipse-2"></div>
  <div class="sports-day-event">SPORTS DAY EVENT</div>
  <img class="star-1" src="star-10.svg" />
  <div class="kho-kho">KHO-KHO</div>
  <img class="star-2" src="star-20.svg" />
  <div class="kabaddi">KABADDI</div>
  <img class="star-3" src="star-30.svg" />
  <div class="cricket">CRICKET</div>
  <img class="star-4" src="star-40.svg" />
  <div class="bad-minton">BAD MINTON</div>
  <img class="star-5" src="star-50.svg" />
  <div class="long-jump">LONG JUMP</div>
</div>


i-phone-14-plus-2

<div class="i-phone-14-plus-2">
  <div class="event-registration-form">
    EVENT REGISTRATION FORM
    <br />
  </div>
  <div class="fill-the-form">Fill the form</div>
  <div class="rectangle-3"></div>
  <div class="full-name">Full name</div>
  <div class="rectangle-4"></div>
  <div class="gender">Gender</div>
  <div class="rectangle-5"></div>
  <div class="age">Age</div>
  <div class="rectangle-6"></div>
  <div class="rectangle-7"></div>
  <div class="department">Department</div>
  <div class="register-number">Register Number</div>
  <div class="rectangle-8"></div>
  <div class="phone-number">phone Number</div>
  <div class="rectangle-9"></div>
  <div class="event-to-book-now">Event to Book Now</div>
  <div class="ellipse-3"></div>
  <div class="registrer">Registrer</div>
</div>


i-phone-14-15-pro-max-2
<div class="i-phone-14-15-pro-max-2">
  <div class="ellipse-4"></div>
  <div class="thank-you">THANK YOU</div>
  <div
    class="contact-us-email-saveethaengineeringcollege-gmail-com-phone-no-9654201394"
  >
    contact us
    <br />
    Email:
    <br />
    saveethaengineeringcollege@gmail.com
    <br />
    phone No:
    <br />
    9654201394
  </div>
  <img class="sec-1" src="sec-10.png" />
</div>
```

```
css
.i-phone-14-plus-1,
.i-phone-14-plus-1 * {
  box-sizing: border-box;
}
.i-phone-14-plus-1 {
  background: #6fdbfb;
  height: 926px;
  position: relative;
  overflow: hidden;
}
.logo-1 {
  width: 428.01px;
  height: 85.61px;
  position: absolute;
  left: -1px;
  top: 26.33px;
  transform-origin: 0 0;
  transform: rotate(-0.197deg) scale(1, 1);
  object-fit: cover;
}
.logo-1-1 {
  border-radius: 342px;
  width: 276px;
  height: 250px;
  position: absolute;
  left: 76px;
  top: 194px;
  object-fit: cover;
}
.rectangle-1 {
  background: #d9d9d9;
  border-style: solid;
  border-color: #000000;
  border-width: 1px;
  width: 209px;
  height: 51px;
  position: absolute;
  left: 109px;
  top: 517px;
  filter: blur(2px);
}
.rectangle-2 {
  background: #d9d9d9;
  border-style: solid;
  border-color: #000000;
  border-width: 1px;
  width: 209px;
  height: 54px;
  position: absolute;
  left: 109px;
  top: 617px;
  filter: blur(2px);
}
.register {
  color: #000000;
  text-align: left;
  font-family: "IrishGrover-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 141px;
  top: 625px;
  width: 145px;
  height: 37px;
}
.login {
  color: #000000;
  text-align: left;
  font-family: "IrishGrover-Regular", sans-serif;
  font-size: 36px;
  font-weight: 400;
  position: absolute;
  left: 166px;
  top: 521px;
  width: 174px;
  height: 22px;
}


.i-phone-14-15-pro-max-1,

.i-phone-14-15-pro-max-1 * {
  box-sizing: border-box;
}
.i-phone-14-15-pro-max-1 {
  background: rgba(236, 42, 132, 0.94);
  height: 923px;
  position: relative;
  overflow: hidden;
}
.ellipse-2 {
  background: #d9d9d9;
  border-radius: 50%;
  width: 293px;
  height: 127px;
  position: absolute;
  left: 69px;
  top: 54px;
}
.sports-day-event {
  color: #000000;
  text-align: center;
  font-family: "InstrumentSans-Regular", sans-serif;
  font-size: 36px;
  font-weight: 400;
  position: absolute;
  left: 50%;
  translate: -50%;
  top: 82px;
  width: 246px;
  height: 52px;
}
.star-1 {
  width: 33px;
  height: 38px;
  position: absolute;
  left: 36px;
  top: 265px;
  overflow: visible;
}
.kho-kho {
  color: #ffffff;
  text-align: center;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 84px;
  top: 265px;
  width: 160px;
  height: 37px;
}
.star-2 {
  width: 32px;
  height: 42px;
  position: absolute;
  left: 36px;
  top: 339px;
  overflow: visible;
}
.kabaddi {
  color: #ffffff;
  text-align: center;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 83px;
  top: 339px;
  width: 153px;
  height: 38px;
}
.star-3 {
  width: 32px;
  height: 41px;
  position: absolute;
  left: 36px;
  top: 417px;
  overflow: visible;
}
.cricket {
  color: #ffffff;
  text-align: center;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 72px;
  top: 414px;
  width: 163px;
  height: 32px;
}
.star-4 {
  width: 32px;
  height: 40px;
  position: absolute;
  left: 36px;
  top: 486px;
  overflow: visible;
}
.bad-minton {
  color: #ffffff;
  text-align: center;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 52px;
  top: 486px;
  width: 273px;
  height: 39px;
}
.star-5 {
  width: 35px;
  height: 37px;
  position: absolute;
  left: 37px;
  top: 554px;
  overflow: visible;
}
.long-jump {
  color: #ffffff;
  text-align: center;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 72px;
  top: 554px;
  width: 216px;
  height: 42px;
}


.i-phone-14-plus-2,

.i-phone-14-plus-2 * {
  box-sizing: border-box;
}
.i-phone-14-plus-2 {
  background: #2769db;
  height: 926px;
  position: relative;
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
  overflow: hidden;
}
.event-registration-form {
  color: #ffffff;
  text-align: center;
  font-family: "JainiPurva-Regular", sans-serif;
  font-size: 40px;
  line-height: 10px;
  font-weight: 400;
  position: absolute;
  left: -38px;
  top: 89px;
  width: 503px;
  height: 20px;
}
.fill-the-form {
  color: #ffffff;
  text-align: center;
  font-family: "JimNightshade-Regular", sans-serif;
  font-size: 32px;
  line-height: 10px;
  font-weight: 400;
  position: absolute;
  left: -59px;
  top: 159px;
  width: 291px;
  height: 14px;
}
.rectangle-3 {
  background: #d9d9d9;
  width: 341px;
  height: 47px;
  position: absolute;
  left: 16px;
  top: 213px;
}
.full-name {
  color: #000000;
  text-align: left;
  font-family: "Kapakana-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 36px;
  top: 223px;
  width: 224px;
  height: 9px;
}
.rectangle-4 {
  background: #d9d9d9;
  width: 234px;
  height: 44px;
  position: absolute;
  left: 16px;
  top: 300px;
}
.gender {
  color: #000000;
  text-align: left;
  font-family: "Kapakana-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 36px;
  top: 306px;
}
.rectangle-5 {
  background: #d9d9d9;
  width: 234px;
  height: 43px;
  position: absolute;
  left: 16px;
  top: 384px;
}
.age {
  color: #000000;
  text-align: left;
  font-family: "Kapakana-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 36px;
  top: 389px;
}
.rectangle-6 {
  background: #d9d9d9;
  width: 294px;
  height: 45px;
  position: absolute;
  left: 16px;
  top: 463px;
}
.rectangle-7 {
  background: #d9d9d9;
  width: 338px;
  height: 42px;
  position: absolute;
  left: 16px;
  top: 548px;
}
.department {
  color: #000000;
  text-align: left;
  font-family: "Kapakana-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 36px;
  top: 553px;
}
.register-number {
  color: #000000;
  text-align: left;
  font-family: "Kapakana-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 36px;
  top: 469px;
}
.rectangle-8 {
  background: #d9d9d9;
  width: 325px;
  height: 42px;
  position: absolute;
  left: 16px;
  top: 626px;
}
.phone-number {
  color: #000000;
  text-align: left;
  font-family: "Kapakana-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 36px;
  top: 632px;
}
.rectangle-9 {
  background: #d9d9d9;
  width: 294px;
  height: 45px;
  position: absolute;
  left: 16px;
  top: 708px;
}
.event-to-book-now {
  color: #000000;
  text-align: left;
  font-family: "Kapakana-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 36px;
  top: 721px;
}
.ellipse-3 {
  background: #d9d9d9;
  border-radius: 50%;
  border-style: solid;
  border-color: #000000;
  border-width: 1px;
  width: 201px;
  height: 44px;
  position: absolute;
  left: 149px;
  top: 814px;
  box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
}
.registrer {
  color: #000000;
  text-align: left;
  font-family: "KaushanScript-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 193px;
  top: 813px;
}


.i-phone-14-15-pro-max-2,

.i-phone-14-15-pro-max-2 * {
  box-sizing: border-box;
}
.i-phone-14-15-pro-max-2 {
  background: #fcbf26;
  height: 926px;
  position: relative;
  overflow: hidden;
}
.ellipse-4 {
  background: #e1ecbb;
  border-radius: 50%;
  width: 318px;
  height: 101px;
  position: absolute;
  left: 56px;
  top: 300px;
}
.thank-you {
  color: #000000;
  text-align: left;
  font-family: "KaushanScript-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 118px;
  top: 327px;
}
.contact-us-email-saveethaengineeringcollege-gmail-com-phone-no-9654201394 {
  color: #000000;
  text-align: center;
  font-family: "KayPhoDu-Regular", sans-serif;
  font-size: 24px;
  font-weight: 400;
  position: absolute;
  left: -53px;
  top: 603px;
  width: 518px;
  height: 275px;
}
.sec-1 {
  width: 458px;
  height: 116px;
  position: absolute;
  left: -15px;
  top: 57px;
  object-fit: cover;
}

```

# OUTPUT:

![alt text](<Screenshot (48).png>)



# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
