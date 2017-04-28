

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
 <head>  
<style>
@charset "UTF-8";

html,body{
          padding:0;
          margin:0
}
        body {
            background: url(../img/bg3.jpg) no-repeat top center;
            font: 20px sans-serif;
        }
.clear{
    clear:both
}
        #content{margin: 0 auto;

    width: 460px;
    margin-top: 23px;
    margin-bottom: 25px;
}
     
        form {
    padding: 25px 35px 10px 45px;
}
        .spin {
    position: absolute;
    border-radius: 50%;
    background: #ed2553;
    color: #fff;
    width: 140px;
    text-align: center;
    margin-left: 380px;
    font-size: 60px;
    margin-top: 63px;
    height: 140px;
    box-shadow: 0px 1px 3px rgba(0,0,0,.25);
    border: 0 none;
    outline: none;
    cursor:pointer;
    top:0;
    z-index: 1
}
 h2{text-transform: uppercase;
    margin-left: -55px;
    line-height: 50px;
    padding-left: 53px;
    margin-bottom:0
        }
        .login h2{
    border-left: 5px solid #ee2553;
    color:#ee2553
}
   .register h2,.register .input-container input{
    color:#fff
}
        .register h2:before{
    border-left: 5px solid #fff;
content:"";
position:absolute;
height:50px;
margin-left:-53px
        }
.hidden {
    display: none;
}
.displayed .hidden{
    display: block;
}
.input-container {
    margin-top: 25px;
}
.input-container label {
    color: #b5b7b6;
        margin-bottom: -24px
}
.input-container input {
    border: 0 none;
    border-bottom: 2px solid rgba(197, 195, 195, 0.5);
    background: transparent;
    color: #585757;
    outline: none;
    font-size: 24px;
    width: 100%;
    line-height: 53px;
    margin-top: 17px;
}
@media screen and (-ms-high-contrast: active), (-ms-high-contrast: none) {
    .input-container input {
            line-height:29px;
    }
}
form a{
    color:#d1d0d0;
    text-align:center;
    text-decoration:none;
    width: 100%;
    float: left;
    margin: 31px 0 25px 0;
    font-size: 22px;
}
form a:hover {color: #ee2553}
.input-container div{
    width: 0;
    background:#ee2553;
    height:2px;
    margin-top: -2px;
    -webkit-transition: width 2s; /* Safari */
    transition: width 2s;
}
.input-container:hover div,.displayed div{
    width: 100%;
}
        input[type="submit"] {
            border: 3px solid #d1d0d0;
            color: #d1d0d0;
        }
   #go2.go{    margin: 52px 0 auto;
    width: 360px;
    border: 3px solid #fff;
   }
   #go2.go .circle{margin-top: -54%;
    margin-left: -18%;}
       .go,input[type="submit"]:hover,input[type="submit"]
        {   background: transparent;
            text-transform: uppercase;
            height: 73px;
            line-height: 65px;
            margin: 52px 15.5% auto;
            width: 245px;
            font-size: 24px;
            cursor:pointer;
            overflow:hidden;           
            outline:none
}
       .register input[type="submit"]{
           width:100%;
           background:#fff;
           margin: 52px 0 auto
       }
        .go,input[type="submit"]:hover,.register input[type="submit"]{
            border:3px solid #ee2553;
            color:#ee2553;
            font-weight:bold;
        }
  .tick{
          margin: 0;
    -webkit-animation-name: ticking; 
    -webkit-animation-duration: 1s; 
    animation-name: ticking;
    animation-duration: 1s;
        }
         @keyframes ticking {
    from { 
   transform:rotate(-90deg)
    }
    to { 
  transform:rotate(0deg)
    }
}
.R-change .input-container label {
    color: #fff;
}
.circle,.R-change .spin{
    background: #ee2553;
    box-shadow: 1px 2px 2px #ee2553;
    border-radius: 100%;
    color: white;
    text-align: center;
    font-size: 30px;
    padding: 20px;
    overflow: hidden;
    
    line-height: 400px;
    margin-top: -83%;
    margin-left: -47%;
    vertical-align: middle;

    -webkit-transition: visibility 5s, opacity 0.5s linear;
    -moz-transition: visibility 5s, opacity 0.5s linear;
    -o-transition: visibility 5s, opacity 0.5s linear;
    -ms-transition: visibility 5s, opacity 0.5s linear;
    transition: visibility 5s, opacity 0.5s linear;

}
.circle{
    -webkit-animation-name: go; 
    -webkit-animation-duration: 1s; 
    animation-name: go;
    animation-duration: 1s;
        -webkit-transform: scale( 1 );
    -moz-transform: scale( 1 );
    -o-transform: scale( 1 );
    -ms-transform: scale( 1 );
    transform: scale( 1 );
        width: 400px;
    height: 400px;
 }
       @keyframes go {
    from { 
   -webkit-transform: scale( 0 );
    -moz-transform: scale( 0 );
    -o-transform: scale( 0 );
    -ms-transform: scale( 0 );
    transform: scale( 0 );
    }
    to { 
    -webkit-transform: scale( 1 );
    -moz-transform: scale( 1 );
    -o-transform: scale( 1 );
    -ms-transform: scale( 1 );
    transform: scale( 1 );
    }
}
       .circle2{
           margin:0 auto;
           text-align:center;
           width: 55px;
    height: 55px;
        position: absolute;
    z-index: 2;
    color: #fff;
    font-size: 60px;
    margin-left: 422px;
    margin-top: 70px;
    cursor: pointer;
       }
.R-change .circle2{ 
    -webkit-animation-duration: 1s; 
    animation-duration: 1s;
    animation-name: ticking2;
    -webkit-animation-name: ticking2;
  -webkit-transform: rotate(45deg) translate(-125%, 50%);
    -moz-transform: rotate(45deg) translate(-125%, 50%);
    -o-transform: rotate(45deg) translate(-125%, 50%);
    -ms-transform: rotate(45deg) translate(-125%, 50%);
    transform: rotate(45deg) translate(-125%, 50%);
}
 @keyframes ticking2 {
     0%   {
    -ms-transform: translate(0, 0) rotate(0deg); /* IE 9 */
    -webkit-transform: translate(0, 0) rotate(0deg); /* Safari */
    transform: translate(0, 0) rotate(0deg);
       opacity:1
     }
     
      50%{
    -ms-transform: translate(-65%, 50%); /* IE 9 */
    -webkit-transform: translate(-65%, 50%); /* Safari */
    transform: translate(-65%, 50%);
        opacity:0
    }
    100% {
    -ms-transform: translate(-125%, 50%) rotate(45deg); /* IE 9 */
    -webkit-transform: translate(-125%, 50%) rotate(45deg); /* Safari */
    transform: translate(-125%, 50%) rotate(45deg);
       opacity:1
    }
}

 .L-change.scd-time .circle2{ 
      -webkit-animation-duration: 1s; 
    animation-duration: 1s;
    animation-name: ticking0;
    -webkit-animation-name: ticking0;
  -webkit-transform: rotate(0deg) translate(0%, 0%);
    -moz-transform: rotate(0deg) translate(0%, 0%);
    -o-transform: rotate(0deg) translate(0%, 0%);
    -ms-transform: rotate(0deg) translate(0%, 0%);
    transform: rotate(0deg) translate(0%, 0%);
}
@keyframes ticking0 {
     0% {
        -ms-transform: translate(-125%, 50%) rotate(45deg); /* IE 9 */
        -webkit-transform: translate(-125%, 50%) rotate(45deg); /* Safari */
        transform: translate(-125%, 50%) rotate(45deg);
        opacity: 1;
    }
    50% {
        -ms-transform: translate(-65%, 50%); /* IE 9 */
        -webkit-transform: translate(-65%, 50%); /* Safari */
        transform: translate(-65%, 50%);
        opacity: 0;
    }
     100% {
        -ms-transform: translate(0, 0) rotate(0deg); /* IE 9 */
        -webkit-transform: translate(0, 0) rotate(0deg); /* Safari */
        transform: translate(0, 0) rotate(0deg);
        opacity: 1;
    }
}

 .L-change.scd-time .spin {
     z-index: 2;
    -webkit-animation-duration: .5s;
    animation-duration: .5s;
    -webkit-transform:  scale( 1 ) translate(0%, 0%);
    -moz-transform:  scale( 1 ) translate(0%, 0%);
    -o-transform:  scale( 1 ) translate(0%, 0%);
    -ms-transform: scale( 1 ) translate(0%, 0%);
    transform: scale( 1 ) translate(0%, 0%);
    animation-name: go0, spin0, big0;
    -webkit-animation-name: go0, spin0, big0;
    box-shadow: 0 0 0 0;
           opacity:1;
}
 @keyframes big0 {
      0% {
     width: 1200px;
    height: 1200px;
    opacity:0
    }
    100% {
     width: 140px;
    height: 140px;
        opacity:1
    }
}
       @keyframes go0 {
     0% { 
    -webkit-transform: scale( 0 );
    -moz-transform: scale( 0 );
    -o-transform: scale( 0 );
    -ms-transform: scale( 0 );
    transform: scale( 0 );
    }
    100% { 
    -webkit-transform: scale( 1 );
    -moz-transform: scale( 1 );
    -o-transform: scale( 1 );
    -ms-transform: scale( 1 );
    transform: scale( 1 );
    }
}
      
@keyframes spin0{
   0%  {
    -ms-transform: translate(-195%, -196%); 
    -webkit-transform: translate(-195%, -196%); 
    transform: translate(-195%, -196%);
    }
 
      100%   {
    -ms-transform: translate(0, 0); 
    -webkit-transform: translate(0, 0); 
    transform: translate(0, 0);
     }
}
   
.R-change .spin {
    -webkit-animation-duration: .5s; 
    animation-duration: .5s;
   -webkit-transform: scale( 0 ) translate(25%, -6%);
    -moz-transform: scale( 0 ) translate(25%, -6%);
    -o-transform: scale( 0 ) translate(25%, -6%);
    -ms-transform: scale( 0 ) translate(25%, -6%);
    transform: scale( 0 ) translate(25%, -6%);

    animation-name: go2, spin, big;
    -webkit-animation-name: go2, spin, big;

    box-shadow: 0 0 0 0;

    -webkit-transition:all .1s ease-in-out;-moz-transition:all 2s ease-in-out;-ms-transition:all 2s ease-in-out;

    position: relative;
            float: right;
            margin-right: -80px;
    margin-top: 38px
}
@keyframes big {
    0% {
     width: 140px;
    height: 140px;
    }
    100% {
     width: 1200px;
    height: 1200px;
    }
}
       @keyframes go2 {
    0% { 
   -webkit-transform: scale( 0 );
    -moz-transform: scale( 0 );
    -o-transform: scale( 0 );
    -ms-transform: scale( 0 );
    transform: scale( 0 );
    }
   
    50% { 
    -webkit-transform: scale( 1 );
    -moz-transform: scale( 1 );
    -o-transform: scale( 1 );
    -ms-transform: scale( 1 );
    transform: scale( 1 );
    }
     100% { 
    -webkit-transform: scale( 0 );
    -moz-transform: scale( 0 );
    -o-transform: scale( 0 );
    -ms-transform: scale( 0 );
    transform: scale( 0 );
    }
}

@keyframes spin{
     0%   {
    -ms-transform: translate(0, 0); /* IE 9 */
    -webkit-transform: translate(0, 0); /* Safari */
    transform: translate(0, 0);
     }
    50%  {
    -ms-transform: translate(25%, 6%); /* IE 9 */
    -webkit-transform: translate(25%, 6%); /* Safari */
    transform: translate(25%, 6%);
    }
    100% {
    -ms-transform: translate(25%, -6%); /* IE 9 */
    -webkit-transform: translate(25%, -6%); /* Safari */
    transform: translate(25%, -6%);
    box-shadow: 0 0 0 0;
    }
}
.login{
        box-sizing: border-box;
    border-radius: 10px;
    box-shadow: 0 -14px 0px -7px rgba(255,255,255,.75), 0 4px 15px -2px rgba(0,0,0,.75);
    border: 10px solid #fff;
    background:#fff;
    height:532px
}
.R-change .login{
    -webkit-animation-name: login; 
    -webkit-animation-duration: 1s; 
    animation-name: login;
    animation-duration: 1s;

    -webkit-transition:  opacity 1s linear;
    -moz-transition:  opacity 1s linear;
    -o-transition:  opacity 1s linear;
    -ms-transition:  opacity 1s linear;
    transition:  opacity 1s linear;
    opacity:0;
   position:absolute;
    z-index: -2;
        width: 360px
}
     @keyframes login{
  from{
      opacity:1
   }
  to{
      opacity:0
   }
}
    .register {
         opacity:0;
         display:none;
         background: #ed2553;
         border: 10px solid #ed2553;
         border-radius: 10px;
     }
    #content.R-change{       border-radius: 10px; 
                          overflow:hidden;
                          height:555px;
                          box-shadow: 0 -14px 0 -7px #d6d6d6, 0 -25px 0 -12px rgba(255,255,255,.75), 0 4px 15px -2px rgba(0,0,0,.75);
     }
   .L-change.scd-time {
    -webkit-animation-duration: 2s;
    animation-duration: 2s;
    animation-name: position;
    -webkit-animation-name: position;
            overflow:hidden
}
 @keyframes position {
      0% {
            overflow:hidden!important
    }
      50%{   overflow:visible!important
}
    100% {
        overflow:hidden!important
    }
}

.R-change .register,.L-change.scd-time .login{
      height: 555px;
    width: 460px;
    box-sizing: border-box;
        
    -webkit-animation-name: register; 
    -webkit-animation-duration: 1s; 
    animation-name: register;
    animation-duration: 1s;
    
    -webkit-transition:  opacity 3s linear;
    -moz-transition:  opacity 3s linear;
    -o-transition:  opacity 3s linear;
    -ms-transition:  opacity 3s linear;
    transition:  opacity 3s linear;
    opacity:1;
    display:block;
        position: absolute;
        top: 23px;
            z-index: 1
}
     @keyframes register{
  from{
      opacity:0
   }
  to{
      opacity:1
   }
}

</style>
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
