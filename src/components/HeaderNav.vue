<template>
    <header>
        <div class="search-group">
            <div class="search_input_box">
                <input id="query" class="search_input" name="query" type="search" placeholder="검색어를 입력해 주세요." maxlength="255">
            </div>
            <button class="search-button">
                <img src="../assets/search-icon.png" style="width: 50px; height: 50px;">
            </button>
        </div>
    </header>
</template>

<script setup>

</script>

<style scoped>
header {
    height: 120px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    background-color: white;
}

.search-group {
    width: 600px;
    height: 50px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    border: 2px solid #B5C99E;
    border-radius: 1.75em;
}

.search_input_box {
    width: 480px;
    height: 50px;
    background-color: rgba(0, 0, 0, 0);
    display: flex;
    align-items: center;
}

.search-button {
    background-color: rgba(0, 0, 0, 0);
    width: 60px;
    height: 50px;
    cursor: pointer;
    border-style: none;
}

header .search-group .search_input_box .search_input{
    width: 100%;
    height: 70%;
    background-color: rgba(0, 0, 0, 0);
    border-style: none;
    outline: none;
    font-size: 1.5rem;
    line-height: 20px;
    font-weight: 600;
}

.search_input::placeholder{
    color: rgba(0, 0, 0, 0);
}

header .search-group .search_input_box .search_input:focus::placeholder{
    color: rgb(179, 179, 179);
    font-size: 1.5rem;
    font-weight: 500;
}
</style>