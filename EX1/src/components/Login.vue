<template>
    <div class="login">
        <div class="content"> 
            <div style="height: 50%;">
                <img src="../assets/profile.png" style="height: 130px; margin-top: 20%;">
            </div>
            <form>
                <label>Email</label>
                <input type="text" name="" id="email" placeholder="  Enter email">
                <label>Password</label>
                <input type="text" name="" id="password" placeholder="  Enter passwrd">
                <button id="submit">Login</button>
            </form>
        </div>
        <div style="margin-left: auto; margin-right:5%;"> Forgot 
            <a href="#" style="color:green; text-decoration:none">password?</a>
        </div>
    </div>
</template>

<style>
    .login {
        width: 250%;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    #login,
    #register {
        border: none;
        margin: 1px;
        height: 30px;
        width: 80px;
        font-weight: bold;
    }
    #login:focus,
    #register:focus {
        color: rgb(16, 203, 88);
    }
    input:focus::placeholder {
        color: transparent;
    }
    #login:hover,
    #register:hover {
        background-color: rgb(233, 233, 233);
    }
    .login .content{
        width: 90%;
        height: 70%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        border: 2px solid black;
    }
    .login form {
        width: 90%;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    .login #email,
    .login #password {
        height: 15%;
        width: 100%;
        margin-bottom: 20px;
        outline: none;
        border: 1px solid black;
        border-radius: 4px;
    }
    .login #submit {
        height: 17%;
        width: 100%;
        border: none;
        background-color: rgb(16, 203, 88);
        font-size: 16px;
        font-weight: bold;
        color: white;
    }
    .login #submit:hover {
        background-color: rgb(0, 177, 68);
    }
    .login #submit:active {
        background-color: rgb(0, 93, 36);
    }
</style>
