
<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title>login page</title>
    <link href="css/style.css" rel="stylesheet">    

</head>
<body>
    
    <div id="content" class="L-change">
        <button class="spin">
        </button>
        <div id="spin" class="circle2" onclick="toggleClass()"> +</div>
        <form class="login" name="login-form" action="" onsubmit="return validateForm()">
            <h2>Login</h2>
            <div class="input-container" onkeydown="this.className += ' displayed'">
                <label class="hidden">Username</label>
                <input type="text" placeholder="Username" name="usr1" required />
                <div></div>
            </div>
            <div class="input-container" onkeydown="this.className += ' displayed'">
                <label class="hidden">Password</label>
                <input type="password" placeholder="Password" name="pwd1" required />
                <div></div>
            </div>
            <input id="submit" type="submit" value="GO">
            <button id="go" class="go hidden" value="GO">
                <div class="circle">
                    <p class="tick">
                        <span>&#x2714;</span>
                    </p>
                </div>
            </button>
            <a href="#">Forgot your password?</a>

        </form>

        <form class="register" name="login-form" action="" onsubmit="return validateForm2()">
            <h2>register</h2>
            <div class="input-container" onkeydown="this.className += ' displayed'">
                <label class="hidden">Username</label>
                <input type="text" placeholder="Username" name="usr2" required />
                <div></div>
            </div>
            <div class="input-container" onkeydown="this.className += ' displayed'">
                <label class="hidden">Password</label>
                <input type="password" placeholder="Password" name="pwd2" required />
                <div></div>
            </div>
            <div class="input-container" onkeydown="this.className += ' displayed'">
                <label class="hidden">Repeat Password</label>
                <input type="password" placeholder="Password" name="pwd3" required />
                <div></div>
            </div>
            <input id="next" type="submit" value="NEXT">
            <button id="go2" class="go hidden" value="GO">
                <div class="circle">
                    <p class="tick">
                        <span>&#x2714;</span>
                    </p>
                </div>
            </button>
        </form>
        <div class="clear"></div>
    </div>

    <script>
    function validateForm() {
        event.preventDefault();// sarah`s note:temporarly, not transfering to new page untill creating the home page
        document.getElementById('submit').style.display = 'none';
        document.getElementById('go').style.display = 'block';
    }

    function validateForm2() {
        event.preventDefault();// sarah`s note: not transfering to new page untill creating the home page temporarly
        document.getElementById('next').style.display = 'none';
        document.getElementById('go2').style.display = 'block';
    }

    function toggleClass() {
        var myButtonClasses = document.getElementById("content").classList;

        if (myButtonClasses.contains("L-change")) {
            myButtonClasses.remove("L-change");
        } else {
            myButtonClasses.add("L-change");
        }
        if (myButtonClasses.contains("R-change")) {
            myButtonClasses.remove("R-change");
        } else {
            myButtonClasses.add("R-change");
        }

        setTimeout(function () {
            document.getElementById("content").className += ' scd-time';//sarah`s note: to avoid animated objects in default status
        },
       1000);
    }
    </script>

</body>
</html>
