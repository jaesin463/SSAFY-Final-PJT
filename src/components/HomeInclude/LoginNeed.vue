<template>
    <div class="login-wrapper">
        <div id="login-form">
            <input type="text" name="userID" placeholder="아이디">
            <input type="password" placeholder="비밀번호">
            <input type="submit" id="login_btn" value="로그인">
        </div>
        <p>회원가입</p>
    </div>
</template>

<script setup>

</script>

<style scoped>
.login-wrapper {
    width: 100%;
    height: 100%;
    padding: 40px 40px 0px 40px;
    box-sizing: border-box;
}

#login-form input {
    width: 100%;
    height: 35px;
    padding: 0 10px;
    box-sizing: border-box;
    margin-bottom: 16px;
    border-radius: 6px;
    background-color: #F8F8F8;
}

#login-form input::placeholder {
    color: #D2D2D2;
}

#login-form #login_btn {
    color: #fff;
    font-size: 16px;
    background-color: #B5C99E;
    border-style: none;
    transition: 1s;
}

#login-form #login_btn:hover {
    background-color: #FFC0CB;
}

.login-wrapper p {
    width: 100%;
    text-align: center;
    font-size: small;
    color: #D2D2D2;
    cursor: pointer;
}

.login-wrapper p:hover{
    color:#aaaaaa
}
</style>