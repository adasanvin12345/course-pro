<template>
    <div>
        <div class="header_container">
            <div class="header_nav">
                <div class="group-3_icon"></div>
                <a href="" class="header_login_link">Login</a>
                <button class="header_register_button">Register</button>
            </div>
            <div class="header_content">
                <div class="header_content_left">
                    <p class="header_content_left_1">Anytime, Anywhere Learn On Your Schedule From Any Device</p>
                    <p class="header_content_left_2">We believe everyone has the capacity to be creative Course Pro is a place where people develop their own potential</p>
                    <button class="header_content_left_button">Let's Get Start</button>
                </div>
                <div class="header_content_right">
                    <div class="header_content_right_image"></div>
                </div>
            </div>
        </div>
    </div>
    
    
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>
    .header_container {
        margin: 0px;
        width: 1920px;
        height: 110px;
        background: #FFFFFF 0% 0% no-repeat padding-box;
        opacity: 1;
    }
    .header_nav{
        margin: 0px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .group-3_icon{
        margin-top: 31px;
        margin-left: 140px;
        margin-bottom: 24px;
        width: 212px;
        height: 55px;
        /* UI Properties */
        background: transparent url('../assets/Group 3.png') 0% 0% no-repeat padding-box;
        opacity: 1;
    }
    .header_login_link{
        margin-top: 42px;
        margin-left: 1172px;
        margin-bottom: 41px;
        width: 56px;
        height: 27px;
        text-align: left;
        font-family: Noto Sans;
        font-style: normal bold;
        font-weight: 1000;
        font-size: 20px;
        /* font: normal normal bold 20px/27px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        opacity: 1;
    }
    .header_register_button{
        margin-top: 25px;
        margin-left: 56px;
        margin-bottom: 25px;
        margin-right: 0px;
        width: 144px;
        height: 60px;
        /* UI Properties */
        background: #01CB63 0% 0% no-repeat padding-box;
        box-shadow: 0px 5px 15px #01CB6359;
        border-radius: 10px;
        opacity: 1;
    }
    .header_content{
        /* width: 1920px; */
        height: 783px;
        background: #01CB63 0% 0% no-repeat padding-box;
        opacity: 1;
        display: flex;
    }
    .header_content_left{
        display: flex;
        flex-direction: column;
        justify-content: center;
        /* align-items: center; */
    }
    .header_content_left_1{        
        margin-left: 140px;
        margin-top: 139px;
        margin-bottom: 0px;
        margin-right: 153px;
        width: 655px;
        height: 225px; 
        text-align: left;
        font-family: Noto Sans;
        font-style: normal ;
        font-weight: 1000;
        font-size: 55px;
        /* font: normal normal bold 55px/75px Noto Sans; */
        letter-spacing: 0px;
        color: #FFFFFF;
        text-transform: capitalize;
        opacity: 1;
    }
    .header_content_left_2{
        margin-left: 140px;
        /* margin-top: 35px; */
        width: 667px;
        height: 141px;
        /* UI Properties */
        text-align: left;
        font-family: Noto Sans;
        font-style: italic;
        font-weight: 500;
        font-size: 30px;
        /* font: normal normal normal 30px/50px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
    }
    .header_content_left_button{
        margin-left: 140px;
        margin-bottom: 138px;
        width: 242px;
        /* height: 70px; */
        padding-top: 18px;
        padding-bottom: 18px;
        padding-left: 34px;
        padding-right: 48px;
        background: #1F2532 0% 0% no-repeat padding-box;
        border-radius: 10px;
        text-align: left;
        font-family: Noto Sans;
        font-style: normal ;
        /* font-weight: 1000; */
        font-size: 25px;
        /* font: normal normal normal 25px/50px Noto Sans; */
        letter-spacing: 0.5px;
        color: #FFFFFF;
        opacity: 1;
    }
    .header_content_right_image{
        margin: 0px;
        width: 960px;
        height: 783px;
        background: transparent url('../assets/Rectangle 25.png') 0% 0% no-repeat padding-box;
        mix-blend-mode: multiply;
        opacity: 0.55;
    }
</style>