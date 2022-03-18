<DOCTYPE html>
<html lang="en">

<head>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #0d191ce5;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
        
        .regform {
            width: 400px;
            overflow: hidden;
            margin: auto;
            margin: 20 20 10 450px;
            padding: 80px;
            background: rgba(16, 6, 6, 0.535);
            border-radius: 15px;
        }
        
        span {
            color: white;
            font-size: 17px;
        }
        
        label {
            color: white;
            font-size: 25px;
        }
        
        #fullname {
            width: 300px;
            height: 30px;
            border: none;
            border-radius: 3px;
            padding-left: 8px;
        }
        
        #mnum {
            width: 300px;
            height: 30px;
            border: none;
            border-radius: 3px;
            padding-left: 8px;
        }
        
        #log {
            width: 300px;
            height: 25px;
            border: none;
            border-radius: 20px;
            padding-left: 4px;
            color: blue;
        }
        
        a {
            float: right;
            background-color: white;
        }
        
        #log:hover {
            background-color: black;
        }
        
        h2 {
            text-align: center;
            color: white;
            padding: 20px;
            font-size: 22px;
        }
    </style>

    <meta charset="UTF-8">
    <title>reg form</title>
</head>

<body>
    <h2> log in here</h2>
    <div class="regform">
        <form action="reg form.php" id="reg form" method="get">
            <label><i><b>FULLNAME</b></i></label>
            <br><input type="text" name="fullname" id="fullname" placeholder="BELLO YUSUF ALANI">
            <br><br><label><i><b>MATRIC NUMBER</b></i></label>
            <br><input type="password" name="mnum" id="mnum" placeholder="2020ECE0x9">
            <br><br>
            <input type="checkbox">
            <span>agree to term and condition</span>
            <br><br>
            <input type="button" name="log" id="log" value="Proceed">
            <br><br>
            <a href="form.html">fresher</a>

        </form>
    </div>
</body>

</html>
