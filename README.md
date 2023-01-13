# gym_html_css
#HTML AND CSS PART OF THE CODE
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Himanshu Fitness</title>
</head>

<link rel="stylesheet" href="css/style.css">
<style>
    /* CSS Reset */
    #CSS
    body {
        font-family: 'Baloo Bhai', cursive;
        color: rgb(15, 3, 246);
        margin: 0px;
        padding: 0px;
        background: url('IMAGE/OIP.jpg');
    }

    .left {
        display: inline-block;
        /* border: 2px solid red; */
        position: absolute;
        left: 60px;
        top: 20px;
    }

    .left img {
        width: 136px;
        filter: invert(100%);
    }

    .left div {
        color: rgb(249, 6, 6);
        line-height: 19px;
        font-size: 26px;
        text-align: center;
    }

    .mid {
        display: block;
        width: 36%;
        margin: 29px auto;
        /* border: 2px solid green; */
    }

    .right {
        position: absolute;
        right: 34px;
        top: 43px;
        display: inline-block;
        /* border: 2px solid yellow; */
    }

    .navbar {
        display: inline-block;
        
    }

    .navbar li {
        display: inline-block;
        font-size: 25px;
    }

    .navbar li a {
        color: rgb(199, 7, 7);
        /*text-decoration: none;*/
        padding: 34px 23px;

    }

    .navbar li a:hover,
    .navbar li a.active {
        text-decoration: underline;
        color: rgb(251, 7, 174);

    }

    .btn {
        font-family: 'Baloo Bhai', cursive;
        margin: 0px 9px;
        background-color: rgb(172, 36, 36);
        color: rgb(15, 13, 153);
        padding: 4px 14px;
        border: 2px solid rgb(189, 209, 133);
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: rgb(115, 206, 11);
    }

    .container {
        border: 2px solid rgb(201, 109, 109);
        margin: 106px 80px;
        padding: 75px;
        width: 33%;
        border-radius: 28px;
    }

    .form-group input {
        font-family: 'Baloo Bhai', cursive;
        text-align: center;
        display: block;
        width: 508px;
        padding: 1px;
        border: 2px solid rgb(20, 185, 62);
        margin: 11px auto;
        font-size: 25px;
        border-radius: 8px;
    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 74%;
        margin: 20px auto;
    }
</style>
#HTML
<body>
    <header class="header">
        <!-- Left box for logo -->
        <div class="left">
            <img src="IMAGE/OIP.jpg" alt="">
            <div>Himanshu Fitness Gym Center</div>
        </div>
        <!-- Mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </div>

        <!-- Right box for buttons -->
        <div class="right">
            <button class="btn">Call Us Now</button>
            <button class="btn">Email Us</button>
        </div>
    </header>
    <div class="container">
        <h1>Join the best gym of Haldia Township now</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Locality">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Email Id">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Phone Number">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>

</html>
