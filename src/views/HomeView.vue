<template>
    <HeaderNav />
    <div class="root">
        <div class="layout_row_top">
            <div class="layout_column_left">
                <div class="layout_left_row_top">
                    <div class="board_box">
                        <BoardList/>
                    </div>
                </div>
                <div class="layout_left_row_bottom">
                    <div class="group_box">
                        <GroupList/>
                    </div>
                </div>
            </div>
            <div class="layout_column_right">
                <div class="layout_right_row_top">
                    <div class="login_box">
                        <LoginVue/>
                    </div>
                </div>
                <div class="layout_right_row_bottom">
                    <div class="friends_box">
                        <FriendList/>
                    </div>
                </div>
            </div>
        </div>
        <div class="layout_row_bottom">
            <div class="youtube_box">
                <youtubeList/>
            </div>
        </div>
    </div>
</template>

<script setup>
import HeaderNav from '../components/HeaderNav.vue';
import youtubeList from '../components/HomeInclude/YoutubeList.vue';
import FriendList from '../components/HomeInclude/FriendList.vue';
import LoginVue from '../components/HomeInclude/LoginNeed.vue';
import GroupList from '../components/HomeInclude/GroupList.vue';
import BoardList from '../components/HomeInclude/BoardList.vue';
</script>

<style scoped>
.root {
    width: 1260px;
    min-height: calc(100vh - 200px);
    display: block;
    margin: 0 auto;
    color: black;
    font-weight: bold;
}

.layout_row_top {
    width: 100%;
    min-height: 800px;
    display: flex;
    flex-direction: row;
}

.layout_row_top .layout_column_left {
    min-width: 70%;
    height: 800px;
}

.layout_left_row_top {
    width: 100%;
    height: 45%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.board_box {
    width: 95%;
    height: 90%;
    border-radius: 0.5em;
    background-color: #f5f5f5;
    box-shadow: inset 0 0 8px rgba(0, 0, 0, 0.1);
}

.layout_left_row_bottom {
    width: 100%;
    height: 55%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.group_box {
    width: 95%;
    height: 90%;
    border-radius: 0.5em;
    background-color: #f5f5f5;
    box-shadow: inset 0 0 8px rgba(0, 0, 0, 0.1);
}

.layout_row_top .layout_column_right {
    min-width: 30%;
    height: 800px;
}

.layout_right_row_top {
    width: 100%;
    height: 35%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.login_box {
    width: 90%;
    height: 88%;
    margin: 16px 20px;
    border-radius: 0.5em;
    background-color: #eeeeee;
    box-shadow: inset 0 0 8px rgba(0, 0, 0, 0.1);
}

.layout_right_row_bottom {
    width: 100%;
    height: 65%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.friends_box{
    width: 90%;
    height: 92%;
    margin: 16px 20px;
    border-radius: 0.5em;
    background-color: #f5f5f5;
    box-shadow: inset 0 0 8px rgba(0, 0, 0, 0.1);
}

.layout_row_bottom {
    width: 100%;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.youtube_box{
    width: 1228px;
    height: 90%;
    margin: 16px 20px;
    border-radius: 0.5em;
    background-color: #f5f5f5;
    box-shadow: inset 0 0 8px rgba(0, 0, 0, 0.1);
}

</style>