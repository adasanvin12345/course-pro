<template>
    <div class="testimonials-container">
        <div class="testimonials-inner_container">
            <p class="testimonials-heading">Testimonials</p>
            <p class="testimonials-desc">Check Out What Our Students Think About Us</p>            
            <div class="testimonials-content">
                <div class="testimonials-box">
                    <p class="testimonials-content-desc">It's a comprehensive online learning platform for everyone looking to learn and course pro. provinding this platform which is very beneficial for practicals. Students can revise everything at home like dissection and slides</p>
                    <div class="testimonials-box-desc">
                        <div class="box-desc-image image1"></div>
                        <div class="desc-box">
                            <p class="name">Anshul Jain</p>
                            <p class="day">Yesterday</p>
                        </div>
                        <div class="comma-image" ></div>
                    </div>
                </div>
                <div class="testimonials-box">
                    <p class="testimonials-content-desc">It's A Comprehensive Online Learning Platform For Everyone Looking To Learn And Course Pro. Provinding This Platform Which Is Very Beneficial For Practicals. Students Can Revise Everything At Home Like Dissection And Slides</p>
                    <div class="testimonials-box-desc">
                        <div class="box-desc-image image2"></div>
                        <div class="desc-box">
                            <p class="name">Rajkumar Jain</p>
                            <p class="day">Yesterday</p>
                        </div>
                        <div class="comma-image" ></div>
                    </div>
                </div>
                
            </div>
        </div>
    </div>
    
    
</template>

<script>
export default {
    name: 'Refer',
}
</script>

<style scoped>
    .testimonials-container{
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 1920px;
        margin: 0px;
        /* padding-left: 137px; */
        margin-top: 216px;
        margin-right: 0px;
    }
    .testimonials-inner_container{
        margin-top: 0px;
        margin-left: 140px;
        margin-right: 140px;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    .testimonials-heading{
        margin-top: 0px;
        margin-bottom: 0px;
        width: 131px;
        height: 34px;
        /* UI Properties */
        text-align: left;
        font-size: 25px;
        font-family: Noto Sans;
        font-style: italic;
        letter-spacing: 0px;
        color: #01CB63;
        opacity: 1;
    }
    .testimonials-desc{
        margin-top: 12px;
        margin-bottom: 0px;
        margin-left: 0px;
        width: 490px;
        height: 109px;
        /* UI Properties */
        text-align: left;
        font-family: Noto Sans;
        font-style: bold italic;
        font-weight: 1000;
        font-size: 40px;
        /* letter-spacing: 54px; */
        /* font: normal normal bold 40px/54px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
        opacity: 1;
    }
    .testimonials-content{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 103px;
        padding-left: 39px;
    }
    .testimonials-box{
        width: 720px;
        height: 354px;
        /* UI Properties */
        background: #FFFFFF 0% 0% no-repeat padding-box;
        box-shadow: 0px 20px 30px #1F25321A;
        border-radius: 15px;
        opacity: 1;
        display: flex;
        flex-direction: column;
        /* justify-content: center; */
        /* align-items: center; */
        padding-left: 45px;
        /* padding-right: 45px; */
    }
    .testimonials-content-desc{
        width: 664px;
        height: 171px;
        margin: 0px;
        margin-top: 68px;
        text-align: left;
        font-family: Noto Sans;
        font-style: italic;
        font-size: 23px;
        /* font: normal normal normal 23px/35px Noto Sans; */
        letter-spacing: 0px;
        color: #000000;
        text-transform: capitalize;
        opacity: 0.7;
    }
    .testimonials-box-desc{
        display: flex;
        margin: 0px;
        margin-top: 25px;
        align-items: center;
        justify-content: start;
    }
    .box-desc-image{
        width: 52px;
        height: 52px;
        /* UI Properties */       
        border-radius: 50%;
        opacity: 1;
        border-radius: 50%;
    }
    .image1{
        background: transparent url('../assets/luis-villasmil-hh3ViD0r0Rc-unsplash.png') 0% 0% no-repeat padding-box;
    }
    .image2{
        background: transparent url('../assets/craig-mckay-jmURdhtm7Ng-unsplash.png') 0% 0% no-repeat padding-box;
    }
    .desc-box{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: center;
        margin-left: 12px;
    }
    .name{
        /* width: 101px; */
        height: 24px;
        /* UI Properties */
        text-align: left;
        font-family: Noto Sans;
        font-style: bold;
        font-size: 18px;
        /* font: normal normal bold 18px/24px Noto Sans; */
        letter-spacing: 0px;
        color: #10182F;
        opacity: 1;
        margin: 0px;
    }
    .day{
        width: 67px;
        height: 22px;
        margin: 0px;
        margin-top: 5px;
        /* UI Properties */
        text-align: left;
        font-family: Noto Sans;
        /* font-style: bold italic; */
        font-size: 16px;
        /* font: normal normal normal 16px/22px Noto Sans; */
        letter-spacing: 0px;
        color: #545D7A;
        opacity: 1;
    }
    .comma-image{
        width: 45px;
        height: 36px;
        margin-left: 435px;
        margin-right: 0px;
        /* UI Properties */
        background: transparent url('../assets/right-quotation-sign.png') 0% 0% no-repeat padding-box;
        opacity: 0.5;
    }
</style>