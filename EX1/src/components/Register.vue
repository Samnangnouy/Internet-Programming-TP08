<template>
    <div class="register">
        <form>
            <div class="signup">Sign up</div>
            <label for="">Email</label>
            <input type="text" name="" id="" placeholder="  Enter email">
            <label for="">Username</label>
            <input type="text" name="" id="" placeholder="  Username">
            <label for="">First name</label>
            <input type="text" name="" id="" placeholder="  First name">
            <label for="">Last name</label>
            <input type="text" name="" id="" placeholder="   Last name">
            <label for="">Password</label>
            <input type="text" name="" id="" placeholder="  Create your password">
            <p style="font-size: 0.7rem; margin: 0;">By creating an account your agree to our <a href="#"
                    style="text-decoration: none; color:rgb(0, 190, 215)">Term</a>&ensp;&&ensp;<a href="#"
                    style="text-decoration: none; color:rgb(0, 190, 215)">Privacy</a></p>
            <button class="btn">Sign up</button>
        </form>
    </div>
</template>

<style>
.register {
    width: 150%;
    height: 100%;
    display: flex;
    align-items: center;

}
.signup{
    font-size: 24px;
    font-weight: bold;
    color: rgb(43, 155, 43);
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
}
.register form {
    width: 100%;
    border: 1px solid gray;
    height: fit-content;
    padding: 3%;
    display: flex;
    flex-direction: column;
    row-gap: 4px;
}
.register form input {
    outline: none;
    margin-bottom: 10px;
    border: none;
    height: 40px;
    background-color: rgb(241, 241, 241);
}
.register .btn {
    border: none;
    height: 40px;
    width: 100%;
    color: white;
    background-color: rgb(16, 203, 88);
}
.register form button:hover {
    background-color: rgb(0, 177, 68);
}
.register form button:active {
    background-color: rgb(0, 93, 36)
}
</style>