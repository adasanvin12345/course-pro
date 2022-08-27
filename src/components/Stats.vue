<template>
    <div class="stats_container">
        <div class="stats_box">
            <p class="stats_text_1">Total Students</p>
            <p class="stats_text_2">5140</p>            
        </div>
        <div class="stats_box">
            <p class="stats_text_1">Partners</p>
            <p class="stats_text_2">4123</p>            
        </div>
        <div class="stats_box">
            <p class="stats_text_1">Affiliate Distributions</p>
            <p class="stats_text_2">4.18 Lac</p>            
        </div>
    </div>
    
    
</template>

<script>
export default {
    name: 'Stats',
}
</script>

<style scoped>
    .stats_container{
        margin-top: 780px;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        /* top: 893px; */
        /* left: 0px; */
        /* margin: 0px; */
        width: 1920px;
        width: 100%;
        height: 349px;
        background: transparent url('../assets/Group 12141.png') 0% 0% no-repeat padding-box;
        opacity: 1;
    }
    .stats_box{
        /* margin-top: 100px; */
        
        width: max-content;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .stats_text_1{
        /* width: 251px; */
        /* height: 47px; */
        /* UI Properties */
        margin-top: 14px;
        margin-bottom: 0px;
        text-align: left;
        font-family: Noto Sans;
        font-style: normal ;
        font-weight: 1000;
        font-size: 35px;
        /* font: normal normal bold 35px/47px Noto Sans; */
        letter-spacing: 0px;
        color: #86919D;
        opacity: 1;
    }
    .stats_text_2{
        /* width: 149px; */
        /* height: 88px; */
        margin-top: 14px;
        margin-bottom: 6px;
        text-align: left;
        font-family: Noto Sans;
        font-style: normal ;
        font-weight: 1000;
        font-size: 65px;
        /* font: normal normal bold 65px/88px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        opacity: 1;
        border-bottom: 7px solid #01CB63;
    }
</style>