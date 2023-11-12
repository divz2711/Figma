# Ex09 Event Registration Web Application
## Date: 14/11/23

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

##  PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
        }

        div {
            box-sizing: border-box;
        }

        /* Styles for the Home section */
        .Home {
            width: 360px;
            height: 640px;
            position: relative;
            background: rgba(111.35, 255, 125.72, 0.80);
        }

        .Home .SaveethaEngineerinngCollege {
            width: 313px;
            height: 23px;
            left: 22px;
            top: 27px;
            position: absolute;
            text-align: center;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-style: italic;
            font-weight: 700;
            word-wrap: break-word;
        }

        .Home .AffiliatedWithAnnaUniversity {
            width: 313px;
            height: 23px;
            left: 23px;
            top: 325px;
            position: absolute;
            text-align: center;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-style: italic;
            font-weight: 700;
            word-wrap: break-word;
        }

        .Home .NirfRankedAutonomousInstitution {
            width: 313px;
            height: 50px;
            left: 22px;
            top: 358px;
            position: absolute;
            text-align: center;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-weight: 900;
            word-wrap: break-word;
        }

        .Home .Line1,
        .Home .Line2 {
            width: 367px;
            height: 0px;
            position: absolute;
            border: 4px white solid;
        }

        .Home .Line2 {
            border: 1px white solid;
            top: 77px;
            left: -7px;
        }

        .Home .SecLogo1 {
            width: 174px;
            height: 175px;
            left: 89px;
            top: 102px;
            position: absolute;
            border-radius: 109.50px;
        }

        .Home .Group1 {
            width: 210px;
            height: 41px;
            left: 79px;
            top: 476px;
            position: absolute;
        }

        .Home .Group1 .Rectangle1 {
            width: 210px;
            height: 41px;
            left: 0px;
            top: 0px;
            position: absolute;
            background: #00A542;
            box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        }

        .Home .Group1 .Login {
            width: 210px;
            height: 31px;
            left: 0px;
            top: 10px;
            position: absolute;
            text-align: center;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-weight: 700;
            word-wrap: break-word;
        }

        /* Styles for the Login section */
        .Login {
            width: 360px;
            height: 640px;
            position: relative;
            background: #F4FF77;
        }

        .Login .SaveethaEngineerinngCollege {
            width: 313px;
            height: 23px;
            left: 23px;
            top: 27px;
            position: absolute;
            text-align: center;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-style: italic;
            font-weight: 700;
            word-wrap: break-word;
        }

        .Login .Line3 {
            width: 367px;
            height: 0px;
            left: -4px;
            top: 76px;
            position: absolute;
            border: 6px white solid;
        }

        .Login .SecLogo2 {
            width: 174px;
            height: 175px;
            left: 93px;
            top: 101px;
            position: absolute;
            border-radius: 109.50px;
        }

        .Login .Rectangle2,
        .Login .Rectangle3 {
            width: 263px;
            height: 45px;
            position: absolute;
            background: rgba(36.45, 157.04, 244.36, 0.88);
        }

        .Login .Rectangle2 {
            left: 48px;
            top: 342px;
        }

        .Login .Rectangle3 {
            left: 48px;
            top: 453px;
        }

        .Login .Username,
        .Login .Password {
            width: 252px;
            height: 32px;
            position: absolute;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-weight: 600;
            word-wrap: break-word;
        }

        .Login .Username {
            left: 52px;
            top: 294px;
        }

        .Login .Password {
            left: 48px;
            top: 404px;
        }

        .Login .Group2 {
            width: 210px;
            height: 41px;
            left: 75px;
            top: 523px;
            position: absolute;
        }

        .Login .Group2 .Rectangle1 {
            width: 210px;
            height: 41px;
            left: 0px;
            top: 0px;
            position: absolute;
            background: #00A542;
            box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        }

        .Login .Group2 .Submit {
            width: 210px;
            height: 31px;
            left: 0px;
            top: 10px;
            position: absolute;
            text-align: center;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-weight: 700;
            word-wrap: break-word;
        }

        /* Styles for the SecPage section */
        .SecPage {
            width: 360px;
            height: 640px;
            position: relative;
            background: #FC7C7C;
        }

        .SecPage .SaveethaEngineerinngCollege {
            width: 313px;
            height: 23px;
            left: 23px;
            top: 28px;
            position: absolute;
            text-align: center;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-style: italic;
            font-weight: 700;
            word-wrap: break-word;
        }

        .SecPage .Department {
            width: 313px;
            height: 23px;
            left: 23px;
            top: 296px;
            position: absolute;
            text-align: center;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-weight: 700;
            word-wrap: break-word;
        }

        .SecPage .Cse,
        .SecPage .It,
        .SecPage .Aiml {
            width: 313px;
            height: 23px;
            position: absolute;
            text-align: center;
            color: black;
            font-size: 20px;
            font-family: Inter;
            font-weight: 600;
            word-wrap: break-word;
        }

        .SecPage .Cse {
            left: 23px;
            top: 354px;
        }

        .SecPage .It {
            left: 23px;
            top: 412px;
        }

        .SecPage .Aiml {
            left: 23px;
            top: 470px;
        }

        .SecPage .Line4 {
            width: 367px;
            height: 0px;
            left: -4px;
            top: 75px;
            position: absolute;
            border: 6px white solid;
        }

        .SecPage .SecLogo3 {
            width: 174px;
            height: 175px;
            left: 93px;
            top: 98px;
            position: absolute;
            border-radius: 109.50px;
        }
    </style>
    <title>Your Page Title</title>
</head>
<body>
    <div class="Home">
        <div class="SaveethaEngineerinngCollege">Saveetha Engineerinng College</div>
        <div class="AffiliatedWithAnnaUniversity">Affiliated with Anna University</div>
        <div class="NirfRankedAutonomousInstitution">NIRF Ranked<br/>AUTONOMOUS INSTITUTION</div>
        <div class="Line1"></div>
        <div class="Line2"></div>
        <img class="SecLogo1" src="https://via.placeholder.com/174x175" alt="Logo 1" />
        <div class="Group1">
            <div class="Rectangle1"></div>
            <div class="Login">LOGIN</div>
        </div>
    </div>

    <div class="Login">
        <div class="SaveethaEngineerinngCollege">Saveetha Engineerinng College</div>
        <div class="Line3"></div>
        <img class="SecLogo2" src="https://via.placeholder.com/174x175" alt="Logo 2" />
        <div class="Rectangle2"></div>
        <div class="Rectangle3"></div>
        <div class="Username">Username</div>
        <div class="Password">Password</div>
        <div class="Group2">
            <div class="Rectangle1"></div>
            <div class="Submit">SUBMIT</div>
        </div>
    </div>

    <div class="SecPage">
        <div class="SaveethaEngineerinngCollege">Saveetha Engineerinng College</div>
        <div class="Department">DEPARTMENT</div>
        <div class="Cse">CSE</div>
        <div class="It">IT</div>
        <div class="Aiml">AIML</div>
        <div class="Line4"></div>
        <img class="SecLogo3" src="https://via.placeholder.com/174x175" alt="Logo 3" />
    </div>
</body>
</html>

```

## OUTPUT:
![Screenshot 2023-11-12 170834](https://github.com/divz2711/Figma/assets/121245222/d4b1f25e-6f4d-43e8-8660-3628861d22eb)

![ho![![Screenshot 2023-11-12 170044](https://github.com/divz2711/Figma/assets/121245222/1dc6b908-4c25-483f-b6e8-5684144aaaea)


![login](https://github.com/divz2711/Figma/assets/121245222/5fb932ec-8493-4d7c-8c8b-12bb7f2d11bc)
![department](https://github.com/divz2711/Figma/assets/121245222/17a4d186-0a4e-4f53-abd6-450bed412c8e)
## RESULT:

The program to design, develop and deploy a web application for event registration is completed successfully.
