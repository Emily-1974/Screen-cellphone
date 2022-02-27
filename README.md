# Screen-cellphone
 Screen-cellphone
 
 HTML Challenge 2
 
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="./styles.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <title>Signin</title>
</head>

<body>
    <div>
        <h1 class="login">Login</h1>
        <p class="paragraph-1">Enter your email adress and password to access your account </p>
        <br>
        <input placeholder="Email" type="email" name="personal-email">
        <br>
        <input class="input-password" placeholder="Password" type="password" name="personal-password">
        <br>
        <a href="" class="forgot-password"> Forgot Password?</a>
        <br>
        <button type="button"> Login</button>
        <br>
        <a class="dont" href="">Don’t have an account?<strong> Sign Up</strong> </a>
    </div>


</body>

</html>

CSS Challenge 2

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color:#FFFFFF;
    font-family: 'Roboto', sans-serif;
}
.login {
    display: block;
    font-style: normal;
    font-size: 32px;
    font-weight:500;
    margin: 128px 277px 12px 16px;
    line-height: 41px;
    color: #000000;
}
.paragraph-1 {
    font-style: normal; 
    margin-top: 12px;
    color: rgba(0, 0, 0, 0.5);
    font-size: 20px;
    margin-left: 16px;
    line-height: 26px;
    font-weight: normal;
    margin-right: 16px;
    display: block;
    letter-spacing: 0.41px;
    margin-bottom: 102px;
   
}
input {
    width: 343px;
    Height: 48px;
    border-radius: 6px;
    border: none;
    background-color: #F2F2F7 ; 
    margin-left: 16px; 
}
.input-password {
    margin-top: 12px;
}
input::placeholder {
    Width: 75px;
    Height: 22px;
    Top: 13px;
    Left: 14px;
    color: #929292;
    weight: 400;
    style: normal;
    size: 16px;
    line-height: 22px;
    padding-left: 14px; 
}
.forgot-password {
    Height: 22px;
    Top: 125px; 
    Size:16px;
    line-height: 22px;
    color: #007AFF;
    margin-left: 236px;
    margin-top: 16px;
    display: block;
    text-decoration: none;
}
button {
    background: rgba(0, 0, 0, 0.94);
    height: 48px;
    width: 343px;
    border-radius: 10px;
    margin: 16px;
    font-style: normal;
    size: 17px;
    line-height: 22px;
    text-align: center;
    color: #FFFFFF;
}
.dont {
    display: block;
    text-align: center;
    margin-top: 150px;
    text-decoration: none;
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 19px;
    color: rgba(0, 0, 0, 0.51);
    
}
strong {
    color: #007AFF;
}

IMAGE

![image](https://user-images.githubusercontent.com/98557510/155897486-b696d4f0-df6e-4178-8ae5-99a1fa34c4b4.png)
