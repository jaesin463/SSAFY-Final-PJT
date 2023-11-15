<template>
    <div class="friendlist_box">
        <p id="title">친구 목록</p>
        <div class="list">
            <ul>
                <li>이재신</li>
                <li>최은희</li>
            </ul>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.friendlist_box {
    margin: 20px 15px;
}

.list{
    background-color: #eeeeee;
    width: 100%;
    height: 420px;
    border-radius: 0.5em;
}

ul{
    list-style: none;
}

li{
    transition: 0.5s;
    margin: 6px;
}

li:hover{
    font-size: large;
    cursor: pointer;
}

#title{
    color:#98ab82;
    font-weight: bold;
}
</style>