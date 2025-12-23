# Ex08 Event Registration Web Application
## Date: 23/12/25

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:

```

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="event-evregistration">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Event
        EvRegistration
      </div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <p class="text-wrapper">Designed by Sowbarnika M P (25015490)</p>
      <img class="saveetha-logo" src="img/saveetha-logo-1.png" />
      <img class="whatsapp-image" src="img/whatsapp-image-2025-12-19-at-10-48-09-AM-1.png" />
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">HOSTEL EVENT</div>
      <img class="img" src="img/rectangle-5.svg" />
      <img class="text-on-a-path-2" src="img/image.svg" />
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">REGISTER</div>
      <img class="whatsapp-image-2" src="img/whatsapp-image-2025-12-19-at-11-42-04-AM-1.png" />
      <div class="rectangle-4"></div>
      <div class="text-wrapper-4">Event Registration</div>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 2155px;
  left: 24px;
  width: 436px;
  height: 92px;
}

.iphone-pro-max .event-evregistration {
  position: absolute;
  top: 73px;
  left: 21px;
  width: 533px;
  transform: rotate(0.62deg);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 92px;
  left: 554px;
  width: 38px;
  height: 39px;
  background-color: #d9d9d9;
}

.iphone-pro-max .div {
  position: absolute;
  top: 871px;
  left: 0;
  width: 440px;
  height: 87px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 902px;
  left: 26px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .saveetha-logo {
  position: absolute;
  top: 92px;
  left: 24px;
  width: 401px;
  height: 81px;
  aspect-ratio: 4.96;
  object-fit: cover;
}

.iphone-pro-max .whatsapp-image {
  position: absolute;
  top: 198px;
  left: 111px;
  width: 205px;
  height: 191px;
  aspect-ratio: 1.08;
  object-fit: cover;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 414px;
  left: 47px;
  width: 333px;
  height: 65px;
  background-color: #48adc3;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 427px;
  left: 94px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .img {
  position: absolute;
  top: 2716px;
  left: 72px;
  width: 103px;
  height: 100px;
}

.iphone-pro-max .text-on-a-path-2 {
  position: absolute;
  top: 2697px;
  left: 100px;
  width: 242px;
  height: 69px;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 521px;
  left: 92px;
  width: 242px;
  height: 55px;
  background-color: #48adc3;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 530px;
  left: 137px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .whatsapp-image-2 {
  position: absolute;
  top: 597px;
  left: 137px;
  width: 179px;
  height: 253px;
  aspect-ratio: 0.71;
  object-fit: cover;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 0;
  left: 27px;
  width: 413px;
  height: 79px;
  background-color: #28a092;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 20px;
  left: 96px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <div class="rectangle"></div>
      <div class="text-wrapper">Book Your Event</div>
      <img class="text-on-a-path" src="img/text-on-a-path-2.svg" />
      <div class="div"></div>
      <div class="text-wrapper-2">Volunteership</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-3">Vote Of Thanks</div>
      <img class="text-on-a-path" src="img/image.svg" />
      <img class="img" src="img/text-on-a-path.svg" />
      <div class="rectangle-5"></div>
      <div class="text-wrapper-4">Master Command</div>
      <div class="text-wrapper-5">Gymnastics</div>
      <div class="text-wrapper-6">Dance</div>
      <div class="rectangle-6"></div>
      <p class="p">Designed by Sowbarnika M P (25015490)</p>
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 433px;
  min-height: 956px;
  position: relative;
}

.iphone .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 80px;
  background-color: #28a092;
}

.iphone .text-wrapper {
  position: absolute;
  top: 21px;
  left: 92px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 2339px;
  left: -471px;
  width: 340px;
  height: 46px;
}

.iphone .div {
  position: absolute;
  top: 304px;
  left: 48px;
  width: 340px;
  height: 43px;
  background-color: #48adc3;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 304px;
  left: 103px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 412px;
  left: 51px;
  width: 337px;
  height: 46px;
  background-color: #48adc3;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 535px;
  left: 51px;
  width: 337px;
  height: 51px;
  background-color: #48adc3;
}

.iphone .rectangle-4 {
  position: absolute;
  top: 649px;
  left: 51px;
  width: 337px;
  height: 41px;
  background-color: #48adc3;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 651px;
  left: 100px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .img {
  position: absolute;
  top: 2364px;
  left: -472px;
  width: 340px;
  height: 43px;
}

.iphone .rectangle-5 {
  position: absolute;
  top: 209px;
  left: 48px;
  width: 339px;
  height: 52px;
  background-color: #48adc3;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 213px;
  left: 92px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 412px;
  left: 118px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 541px;
  left: 158px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-6 {
  position: absolute;
  top: 869px;
  left: -7px;
  width: 440px;
  height: 87px;
  background-color: #d9d9d9;
}

.iphone .p {
  position: absolute;
  top: 902px;
  left: 26px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="rectangle"></div>
      <div class="text-wrapper">Registration</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Register Number</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">Phone Number</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-4">Your Name</div>
      <div class="text-wrapper-5">REGISTER NOW</div>
      <div class="rectangle-5"></div>
      <p class="p">Designed by Sowbarnika M P (25015490)</p>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 436px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 436px;
  height: 82px;
  background-color: #28a092;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 22px;
  left: 118px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 277px;
  left: 70px;
  width: 294px;
  height: 73px;
  background-color: #48adc3;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 419px;
  left: 70px;
  width: 294px;
  height: 72px;
  background-color: #48adc3;
}

.iphone-pro-max .text-wrapper-2 {
  top: 436px;
  left: 89px;
  position: absolute;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 582px;
  left: 70px;
  width: 294px;
  height: 72px;
  background-color: #48adc3;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 596px;
  left: 96px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 740px;
  left: 70px;
  width: 294px;
  height: 67px;
  background-color: #e16919;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 289px;
  left: 126px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  top: 754px;
  left: 96px;
  position: absolute;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 869px;
  left: -4px;
  width: 440px;
  height: 87px;
  background-color: #d9d9d9;
}

.iphone-pro-max .p {
  position: absolute;
  top: 902px;
  left: 26px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

```



## OUTPUT:

![alt text](<Screenshot 2025-12-19 114522.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
