<template>
    <main>
        <div class="text-top">Videos novos todas as <b>quintas</b> às <b>20h</b></div>

        <a href="https://youtube.com/wdevoficial" target="_blank">
            <img src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg" alt="inscreva-se" id="subscribe">
        </a>
        <div class="text-bottom">youtube.com/wdevoficial</div>

    </main>
</template>
<script>
export default{
    name: 'homePage'
}
</script>
<style scoped>
main{
    background-color: var(--color-background-home) ;
    align-items: center;
    justify-content: center;
}
.text-top{
    color: var(--color-text-light);
    font-size: 22px;
    margin-bottom: 20px;
}

#subscribe{
    width: 340px;
}
.text-bottom{
    color: var(--color-text-light);
    font-size: 18px;
    margin-top: 20px;
}

@media (min-width: 700px){
    #subscribe{
        width: 370px;   
    }
}
</style>