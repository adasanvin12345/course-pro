<template>
    <div class="contact-container">        
        <p class="contact-heading">Contact Us</p>
        <p class="contact-heading-desc">Reach Out with any question you have</p>
        <div class="form-container">
            <div class="form-container-left">
                <p class="form-left-heading">Contact Information</p>
                <div class="form-left-container">
                    <div class="form-left-box">
                        <div class="form-left-image image1"></div>
                        <p class="form-left-info">contact@coursepro.com</p>
                    </div>
                    <div class="form-left-box">
                        <div class="form-left-image image2"></div>
                        <p class="form-left-info">1800-562-895, 1800-869-877</p>
                    </div>
                    <div class="form-left-box">
                        <div class="form-left-image image3"></div>
                        <p class="form-left-info">102 Street, India</p>
                    </div>
                </div>
                <p class="form-left-heading give-margin-top">Social Media Channel</p>
                                    
                <div class="social-media-logos">
                    <div class="social-media-icon facebook"></div>
                    <div class="social-media-icon twitter"></div>
                    <div class="social-media-icon github"></div>
                    <div class="social-media-icon linkedin"></div>
                </div>
                
            </div>
            <div class="form-container-right">
                <p class="form-right-heading">Fill up the form and our team will get back to you within 24 hours</p>
                <form action="" class="form-content">
                    <div class="form-row">
                        <input type="text" class="form-input-name input-data" placeholder="Name"/>
                        <input type="text" class="form-input-email input-data" placeholder="Email"/>
                    </div>
                    <div class="form-row">
                        <input type="text" class="form-input-phone input-data" placeholder="Phone"/>
                        <input type="text" class="form-input-subject input-data" placeholder="Subject"/>
                    </div>                    
                    <input type="text" class="form-input-message" placeholder="Message"/>
                    <button class="form-submit-button">Submit</button>
                </form>
            </div>
        </div>
    </div>
    
    
</template>

<script>
export default {
    name: 'Contact',
}
</script>

<style scoped>
    .contact-container{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        /* width: 1920px; */
        width: 100%;
        margin: 0px;
        /* padding-left: 137px; */
        margin-top: 150px;
        margin-right: 0px;
    }
    .contact-heading{
        margin-top: 0px;
        margin-bottom: 0px;
        /* width: 120px; */
        width: 10%;
        height: 34px;
        text-align: left;
        font-family: Noto Sans;
        font-style: bold italic;
        font-size: 25px;
        /* font: normal normal normal 25px/34px Noto Sans; */
        letter-spacing: 0px;
        color: #01CB63;
        opacity: 1;
    }
    .contact-heading-desc{
        margin-top: 8px;
        margin-bottom: 0px;
        margin-left: 0px;
        /* width: 410px; */
        width: 25%;
        height: 109px;
        text-align: center;
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
    .form-container{
        display: flex;
        /* width: 1920px; */
        width: 100%;
        height: 909px;
        /* UI Properties */
        background: #F8F9FB 0% 0% no-repeat padding-box;
        opacity: 1;
        padding-top: 90px;
        margin-top: 87px;
    }
    .form-container-left{
        display: flex;
        flex-direction: column;
        padding-left: 150px;
        /* width: 800px; */
        width: 35%;
    }
    .form-left-heading{
        /* width: 372px; */
        width: 100%;
        height: 47px;
        text-align: left;
        font-family: Noto Sans;
        font-style: bold ;
        font-size: 35px;
        font-weight: 1000;
        /* font: normal normal bold 35px/34px Noto Sans; */
        letter-spacing: 0.7px;
        color: #201F23;
        opacity: 1;
    }
    .form-left-container{
        display: flex;
        flex-direction: column;
        justify-content: center;
        /* align-items: center;         */
    }
    .form-left-box{
        display: flex;
        /* width: 450px; */
        width: 100%;
        /* justify-content: center; */
        align-items: center;
    }
    .form-left-image{
        /* width: 118px; */
        width: 20%;
        height: 118px;        
        opacity: 1;
    }
    .image1{
        background: transparent url('../assets/Group 10750.png') 0% 0% no-repeat padding-box;
    }
    .image2{
        background: transparent url('../assets/Group 10749.png') 0% 0% no-repeat padding-box;
    }
    .image3{
        background: transparent url('../assets/Group 10748.png') 0% 0% no-repeat padding-box;
    }
    .form-left-info{
        /* width: 322px; */
        width: 50%;
        height: 34px;
        text-align: left;
        font-family: Noto Sans;
        font-style: normal ;
        font-weight: 1000;
        font-size: 25px;
        /* font: normal normal bold 25px/34px Noto Sans; */
        letter-spacing: 0px;
        color: #201F23;
        opacity: 0.8;
        margin-left: 30px;
    }
    .give-margin-top{
        margin-top: 105px;
    }
    .social-media-logos{
        display: flex;
        /* justify-content: space-between; */
        align-items: center;
        /* width: 425px; */
        width: 100%;
    }
    .social-media-icon{
        width: 67px;
        height: 67px;
        opacity: 1;
        margin: 0px;
        margin-right: 8%;
    }
    .facebook{
        background: transparent url('../assets/Facebook.png') 0% 0% no-repeat padding-box;
    }
    .twitter{
        background: transparent url('../assets/Twitter.png') 0% 0% no-repeat padding-box;
    }
    .github{
        background: transparent url('../assets/Github.png') 0% 0% no-repeat padding-box;
    }
    .linkedin{
        background: transparent url('../assets/Linkedin.png') 0% 0% no-repeat padding-box;
    }
    .form-container-right{
        display: flex;
        flex-direction: column;
        align-items: center;
        /* justify-content: center; */
        margin-top: 0px;
        padding-top: 0px;
    }
    .form-right-heading{
        /* width: 570px; */
        width: 70%;
        height: 68px;
        text-align: center;
        font-family: Noto Sans;
        font-style: normal ;
        font-weight: 1000;
        font-size: 25px;
        /* font: normal normal bold 25px/34px Noto Sans; */
        letter-spacing: 0px;
        color: #201F23;
        opacity: 1;
    }
    .form-content{
        margin-top: 73px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 100%;
    }
    .form-row{
        width: 100%;
        /* display: flex;
        justify-content: center; 
        align-items: center;  */
    }
    .input-data{
        border: none;
        border-bottom: 2px solid #01CB63;
        background: #F8F9FB 0% 0% no-repeat padding-box;;
        /* width: 342px; */
        width: 42%;
        height: 30px;
    }
    .form-input-name{
        margin-right: 10%;
    }
    .form-input-email{
        /* margin-top: 61px; */
    }
    .form-input-phone{
        margin-right: 10%;
        margin-top: 61px;
    }
    .form-input-subject{
        margin-top: 61px;
    }
    .form-input-message{
        margin-top: 61px;
        /* width: 792px; */
        width: 100%;
        height: 272px;
        border: 2px solid #01CB63;
        border-radius: 2px;
        opacity: 1;
    }
    .form-submit-button{
        /* width: 242px; */
        width: 30%;
        height: 70px;
        background: #000000 0% 0% no-repeat padding-box;
        border-radius: 10px;
        opacity: 1;
        margin-top: 70px;
        color: white;
        font-family: Noto Sans;
        font-style: italic ;
        /* font-weight: 1000; */
        font-size: 25px;
        /* font: normal normal normal 25px/50px Noto Sans; */
        letter-spacing: 0.5px;
        color: #FFFFFF;
        opacity: 1;
        cursor: pointer;
    }
</style>