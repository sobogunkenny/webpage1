<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Sample</title>
    <link href="https://fonts.google.com/specimen/Poppins" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
        }
        
        .landing {
            display: flex;
            background-color: hsl(0, 100%, 74%);
            padding: 0px;
            font-size: 16px;
            justify-content: center;
            font-family: Poppins;
        }
        
        .main {
            padding: 100px 20px 100px 50px;
            align-content: center;
        }
        
        .side {
            padding: 100px 10px 100px 20px;
        }
        
        .trial {
            display: block;
            background-color: hsl(248, 32%, 49%);
            text-align: center;
            padding: 5px;
            border-radius: 10px;
            margin-bottom: 10px;
            overflow: hidden;
        }
        
        .trial,
        .main {
            color: white;
        }
        
        .filled {
            background-color: whitesmoke;
            padding: 10px;
            text-align: center;
        }
        
        .put {
            text-indent: 20px;
        }
        
        a:link {
            color: red;
            text-decoration: none;
        }
        
        #claim {
            background-color: hsl(154, 59%, 51%);
            width: 385px;
            color: whitesmoke;
            padding: 10px;
            border-color: hsl(154, 59%, 51%);
        }
        
        @media screen and (max-width:375px) {
            .landing {
                flex-direction: column-reverse;
            }
            .main,
            .side {
                padding: 5px;
            }
        }
    </style>
</head>

<body>
    <div class="landing">
        <div class="main">
            <br>
            <br>
            <br>
            <h1>Learn to code by</h1>
            <h1>watching others</h1>
            <p> <small>See how experience developers solve problems in real-time.</small>
            </p>
            <p><small>Watching scripted tutorials is great, but understanding how</small>
            </p>
            <p><small>developers think is invaluable.</small></p>
        </div>



        <div class="side">
            <div class="trial">
                <p><b>Try it free 7 days</b> thn $20/mo. thereafter</p>
            </div>
            <div class="filled">
                <form action="/action_page.php">
                    <br>

                    <input type="text" class="put" name="fname" value="Jonathan" size="50"><br><br>

                    <input type="text" class="put" name="lname" value="Last Name" size="50"><br><br>

                    <input type="email" class="put" name="email" value="Email Adrress" size="50" required><br>
                    <br>
                    <input type="password" class="put" name="pwd" placeholder="Password" pattern="display" size="50" required><br><br>
                    <input type="submit" id="claim" value="CLAIM YOUR FREE TRIAL" size="50">
                </form>
                <p><small>By clicking the button you are agreeing to our
                    <a href="#Terms">Terms and Services</a></small></p>

            </div>


        </div>
</body>

</html>
