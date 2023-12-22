<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>AVATAR | Movie Landing Page</title>
    <style>
    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}

header{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 40px 100px;
    z-index: 1000;
}

header .logo{
    
    max-width: 100px;
    margin-left: 14%;
    margin-top: 3.5%
    
  
}

header .toggle{

    max-width: 60px;
    cursor: pointer;
}

header .logo img,
header .toggle img 
{
    max-width: 100%;
    
}

.banner{
    position: relative;
    width: 100%;
    min-height: 100vh;
    padding: 0 100px;
    background: url(poster.jpg);
    background-position: center;
    background-size: contain;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

.banner .content {

    max-width: 500px;
}
.banner .content h2 {

    text-transform: uppercase;
    font-weight: 300;
    font-size: 1.8rem;
    letter-spacing: 0.1rem;
    margin-left: 30%;
    margin-bottom: 2%;
    margin-top: 7%;
    color: blue;
}
.banner .content h2  {

    font-weight: 800;
    font-family: 'Times New Roman';
}
.banner .content p{

    font-size: 1.2em;
    font-weight: 300;
    letter-spacing: 0em;
    line-height: 1.5em;
    color: red;
    margin-bottom: 10%;
    margin-right: 30px; 
    margin-left: 33%;
}
/* .banner .content a img{
    margin-left: 1%;
} */

.play{
    position: relative;
    display: inline-flex;
    justify-content: flex-start;
    align-items: center;
    color: blue;
    margin-left: 33%;
    margin-bottom: 3%;
    text-transform: uppercase;
    font-weight: 500;
    text-decoration: none;
    letter-spacing: 2px;
    font-size: 1.2em;
}

.play img{
    margin-right:500px;
    max-width: 500px;
}
.slide{
    position: absolute;
    bottom: 50px;
    left: calc(50% - 250px / 2);
    width: 300px;
    height: 200px;
    margin-left: 2%;
    background: url(vijay\ .png);
    background-size: cover;
    cursor: pointer;
    animation: animate 20s linear infinite;
}


{
    0%,100%
    {
        background-position: left;
    }
    45%,55%
    {
        background-position: right;
    }
}


{
    header {
        padding: 20px 50px;
    }
    header {
        padding: 20px 50px;
    }
    header .logo {
        max-width: 80px;
    }
    header .toggle {
        max-width: 40px;
    }
    .banner {
        padding: 500px 350px;
    }
    .banner .content h2
    {
        font-weight: 400;
        font-size: 2em;
        letter-spacing: 0.05em;
    }
    .banner .content p
    {
        font-size: 50em;
    }
    .slide
    {
        position: relative;
        bottom: initial;
        left: 25;
        width: 500px;
        height: 300px;
        margin: 80px 0;
    }
    .sci
    {
        position: absolute;
        top: initial;
        right: initial;
        margin-top: 40px;
        transform: translateY(-50%);
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: row;
    }
    .sci li
    {
        list-style: none;
        margin: 0.5px;
    }
    .AVATAR video{
        max-width: 90%;
        outline: none;
    }
}
</style>
</head>
<body>
    <header>
        <a href="#" class="logo"><img src="https://www.google.com/url?sa=i&url=https%3A%2F%2F1000logos.net%2Favatar-logo%2F&psig=AOvVaw24p0VCsInKjUaZ1V-w5gS_&ust=1700573565738000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCNC3mrHY0oIDFQAAAAAdAAAAABAD.jpg" alt=""></a>

        
    </header>

    <div class="banner">
        <div class="content">
            <h1> AVATAR is the most favourite movie in world.</h1>
             <h4>Avatar is the story of Jake Sully, a paraplegic marine, who replaces his brother on a secret mission to infiltrate the Na' vi,<br>
               the colony of beings that sit on the planet of Pandora, where there is a precious ore, that sells at a ridiculous amount.
            </h4>

        
        <a href="https://www.youtube.com/watch?v=5PSNL1qE6VY.mp4" class="play"><img src="https://1000logos.net/wp-content/uploads/2022/11/Avatar-Logo-2009.png">Watch Trailer</a>
        
        <div class="slide"></div>
        </div>

    </div>

   
    

    
</body>
</html>
