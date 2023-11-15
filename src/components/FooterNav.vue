<template>
    <footer>
        <div class="up-footer">
            <p>본 사이트는 싸피 10기 대전 3반의 관통프로젝트로 무단 전제, 복사, 배포 등을 금합니다.</p>
        </div>
        <div class="down-footer">
            <p>Copyrightⓒ Choi Sin All Rights Reserved.</p>
        </div>
    </footer>
</template>

<script setup>

</script>

<style scoped>

footer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: rgb(250, 250, 250);
    width: 100%;
    height: 80px;
    gap: 10px;
}

footer div {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.up-footer {
    gap: 8px;
}

#top-footer {
    flex-direction: row;
    gap: 10px;
}

#top-footer p {
    font-size: smaller;
}

.up-footer p {
    font-size: xx-small;
}

.down-footer p {
    font-size: x-small;
    font-weight: bold;
}
</style>