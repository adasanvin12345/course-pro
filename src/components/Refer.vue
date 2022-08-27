<template>
    <div class="refer-container">
        <div class="refer-inner_container">
            <p class="refers-heading">Refer</p>
            <p class="refers-desc">How It's Work</p>            
        </div>
        <div src="" alt="" class="refer-image"></div>
    </div>
    
    
</template>

<script>
export default {
    name: 'Refer',
}
</script>

<style scoped>
    .refer-container{
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 1920px;
        margin: 0px;
        /* padding-left: 137px; */
        margin-top: 216px;
        margin-right: 0px;
    }
    .refer-inner_container{
        margin-top: 0px;
        margin-left: 140px;
        margin-right: 140px;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    .refers-heading{
        margin-top: 0px;
        margin-bottom: 0px;
        width: 131px;
        height: 34px;
        /* UI Properties */
        text-align: left;
        font-family: Noto Sans;
        font-style: italic ;
        /* font-weight: 1000; */
        font-size: 25px;
        /* font: normal normal normal 25px/34px Noto Sans; */
        letter-spacing: 0px;
        color: #01CB63;
        opacity: 1;
    }
    .refers-desc{
        margin-top: 12px;
        margin-bottom: 0px;
        margin-left: 0px;
        width: 490px;
        height: 109px;
        /* UI Properties */
        text-align: left;
        font-family: Noto Sans;
        font-style: normal ;
        font-weight: 1000;
        font-size: 40px;
        /* font: normal normal bold 40px/54px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
        opacity: 1;
    }
    .refer-image{
        width: 1759px;
        height: 796px;
        /* UI Properties */
        background: transparent url('../assets/Group 12142.png') 0% 0% no-repeat padding-box;
        opacity: 1;
    }
</style>