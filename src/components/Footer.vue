<template>
    <div class="footer-container">
        <p class="copyright">2021-2022 © Course Pro Private Limited</p>
        <p class="terms">Term & Condition</p>
        <p class="privacy">Privacy Policy</p>
    </div>    
</template>

<script>
export default {
    name: 'Refer',
}
</script>

<style scoped>
    .footer-container{
        display: flex;  
        /* justify-content: center; */
        align-items: center;    
        margin-top: 82px;  
        margin-bottom: 58px;
    }
    .copyright{
        width: 489px;
        height: 34px;
        text-align: left;
        font-family: Noto Sans;
        /* font-style: bold; */
        font-weight: 1000;
        font-size: 25px;
        /* font: normal normal bold 25px/34px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
        opacity: 1;
        margin: 0px;
        margin-left: 140px;
    }
    .terms{
        width: 191px;
        height: 30px;
        text-align: left;
        font-family: Noto Sans;
        /* font-style: bold; */
        font-weight: 1000;
        font-size: 22px;
        /* font: normal normal bold 22px/30px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
        opacity: 1;
        margin: 0px;
        margin-left: 758px;
    }
    .privacy{
        width: 151px;
        height: 30px;
        text-align: left;
        font-family: Noto Sans;
        /* font-style: bold; */
        font-weight: 1000;
        font-size: 22px;
        /* font: normal normal bold 22px/30px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
        opacity: 1;
        margin: 0px;
        margin-left: 51px;
    }
</style>