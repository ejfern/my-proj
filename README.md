# my-proj
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="styles.css" />
    <title>Document</title>
</head>
<body>
    <h1>FISH FINDING FAMILIES</h1>
    <div>
        <img class="intro" src="https://engineering.tamu.edu/student-life/_files/_images/_content-images/westudents.jpg">
        <img class="intro" src="https://farm3.staticflickr.com/2634/4462120219_9cc1796f9c_o.jpg">
        <img class="intro" src="https://www.12thmanfoundation.com/assets/img/donor-impact/stories/kyle-field/kyle-1.jpg">
    </div>
    <p>blah</p>
    <div class="buttons">
        <div class="first">
            <button class = "icon-buttons">
                <img src = "https://cdn-icons-png.flaticon.com/128/1077/1077063.png" >
                Make a Profile!
            </button>
            <button class = "icon-buttons">
                <img src = "https://cdn-icons-png.flaticon.com/128/8073/8073854.png" >
                Find Friends!
            </button>
        </div>
        <div class="second">
            <button class = "icon-buttons">
                <img src = "https://cdn-icons-png.flaticon.com/128/864/864685.png">
                Resources
            </button>
            <button class = "icon-buttons">
                <img scr = "https://cdn-icons-png.flaticon.com/128/747/747310.png">
                Important Events
            </button>
        </div>
      </div>    
</body>
</html>














@import url('https://fonts.googleapis.com/css2?family=Raleway+Dots&display=swap');

html {
    background-color: #FFF0F5;
}

body {
    height: 600px;
}

p {
    font-size: 100px;
}

h1 {
    padding-top: 50px;
    padding-bottom: 25px;
    text-align: center;
    font-family: 'Raleway Dots', cursive;
    font-weight: 1000;
    font-size: 85px;
    color: #800000
  }

div {
    display: flex;
    flex-direction: row;
}

.intro {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 400px;
    height: 230px;
}

.buttons {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 50px;
}

.icon-buttons {
    text-align: center;
    padding-left: 50px;
    padding-right: 50px;
    padding-top: 50px;
    padding-bottom: 50px;
    width: 250px;
    color: #800000;
    background-color: white;
    font-weight: 100px;
}

.first {
    display: flex;
    flex-direction: row;
}

.second {
    display: flex;
    flex-direction: row;
}
