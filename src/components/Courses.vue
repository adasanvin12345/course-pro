<template>
    <div class="course-container">
        <p class="course-heading">Courses</p>
        <p class="course-desc">Out Most Popular Courses</p>
        <div class="course-content">
            <div class="course-content-card">
                <div class="image1 card-image"></div>
                <div class="course-info-section">
                    <p class="card-heading">Ultimate Business Intelligence Analyst A to Z Course 2021</p>
                    <p class="card-students">46,995 Student</p>
                    <div class="course-info">
                        <div class="clock small-icons"></div>
                        <p class="lecture-hours">11 hr 20 mins</p>
                        <div class="calender  small-icons"></div>
                        <p class="no-of-lectures">44 Lectures</p>
                    </div>
                    <div class="hor-rule"></div>
                    <div class="additional-info">
                        <div class="maker-image img1"></div>
                        <p class="maker-name">Albert Hitler</p>
                        <p class="cur-price">₹2000</p>
                        <p class="old-price">₹2000</p>
                    </div>
                </div>                
            </div>
            <div class="course-content-card">
                <div class="image2  card-image"></div>
                <div class="course-info-section">
                    <p class="card-heading">Adobe Photoshop Training: From Beginner to Pro</p>
                    <p class="card-students">6,995 Student</p>
                    <div class="course-info">
                        <div class="clock  small-icons"></div>
                        <p class="lecture-hours">6 hr 20 mins</p>
                        <div class="calender  small-icons"></div>
                        <p class="no-of-lectures">24 Lectures</p>
                    </div>
                    <div class="hor-rule"></div>
                    <div class="additional-info">
                        <div class="maker-image img2"></div>
                        <p class="maker-name">Albert Hitler</p>
                        <p class="cur-price">₹2000</p>
                        <p class="old-price">₹2000</p>
                    </div>
                </div>                
            </div>
            <div class="course-content-card">
                <div class="image3  card-image"></div>
                <div class="course-info-section">
                    <p class="card-heading">Ultimate Business Intelligence Analyst A to Z Course 2021</p>
                    <p class="card-students">46,995 Student</p>
                    <div class="course-info">
                        <div class="clock  small-icons"></div>
                        <p class="lecture-hours">11 hr 20 mins</p>
                        <div class="calender  small-icons"></div>
                        <p class="no-of-lectures">44 Lectures</p>
                    </div>
                    <div class="hor-rule"></div>
                    <div class="additional-info">
                        <div class="maker-image img3"></div>
                        <p class="maker-name">Albert Hitler</p>
                        <p class="cur-price">₹2000</p>
                        <p class="old-price">₹2000</p>
                    </div>
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
    .course-container{
        display: flex;
        flex-direction: column;
        /* justify-content: center; */
        align-items: center;
        /* width: 1920px; */
        width: 100%;
        margin: 0px;
        /* padding-left: 137px; */
        margin-top: 156px;
        margin-right: 0px;
    }
    .course-heading{
        margin-top: 0px;
        margin-bottom: 0px;
        /* width: 88px; */
        width: 4.5%;
        height: 34px;
        /* UI Properties */
        text-align: center;
        font-size: 25px;
        font-family: Noto Sans;
        font-style: italic;
        /* font: normal normal normal 25px/34px Noto Sans; */
        letter-spacing: 0px;
        color: #01CB63;
        opacity: 1;
    }
    .course-desc{
        margin-top: 15px;
        margin-bottom: 0px;
        margin-left: 0px;
        /* UI Properties */
        text-align: left;
        font-family: Noto Sans;
        font-style: bold;
        font-weight: 1000;
        font-size: 2rem;
        /* width: 522px; */
        width: 28.75%;
        height: 55px;
        text-align: center;
        /* font: normal normal bold 40px/54px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
        opacity: 1;
    }
    .course-content{
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        /* margin-left: 140px; */
        margin-left: 7.3%;
        margin-top: 60px;
        /* margin-right: 140px; */
        margin-right: 7.3%;
        /* width: 1920px; */
        width: 100%;
    }
    .course-content-card{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 0px;        
        /* width: 480px; */
        width: 25%;
        height: 480px;
        background: #FFFFFF 0% 0% no-repeat padding-box;
        border: 1px solid #E6E6E6;
        border-radius: 15px;
        opacity: 1;
    }
    .card-image{
        /* width: 280px; */
        width: 80%;
        height: 200px;
        border-radius: 15px 15px 0px 0px;
        opacity: 1;
    }
    .image1{
        background: transparent url('../assets/image1.jpg') 0% 0% no-repeat padding-box;
    }
    .image2{
        background: transparent url('../assets/image2.png') 0% 0% no-repeat padding-box;
    }
    .image3{
        background: transparent url('../assets/image3.jpg') 0% 0% no-repeat padding-box;
    }
    .course-info-section{
        display: flex;
        flex-direction: column;
        /* justify-content: flex-start; */
        align-items: flex-start;
        /* padding-left: 17px; */
        padding-left: 3%;
    }
    .card-heading{
        /* width: 460px; */
        width: 80%;
        height: 68px;
        text-align: left;
        font-family: Noto Sans;
        font-style: bold;
        font-weight: 1000;
        font-size: 1.25rem;
        /* font: normal normal bold 25px/34px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        opacity: 1;
        margin: 0px;
        margin-top: 20px;
    }
    .card-students{
        /* width: 109px; */
        width: 40%;
        height: 22px;
        text-align: left;
        letter-spacing: 0px;
        color: #1F2532;
        opacity: 1;
        font-weight: 500;
    }
    .course-info{
        display: flex;
        align-items: center;
        width: 100%;
    }
    .small-icons{
        width: 25px;
        /* width: 50%; */
        height: 25px;        
        opacity: 1;
    }
    .clock{
        background: transparent url('../assets/schedule-24px.png') 0% 0% no-repeat padding-box;
    }
    .calender{
        background: transparent url('../assets/date_range-24px.png') 0% 0% no-repeat padding-box;
        /* margin-left: 207px; */
        margin-left: 28%;
    }
    .lecture-hours{
        /* margin-left: 5px; */
        margin-left: 0%;
        width: 28%;
    }
    .no-of-lectures{
        /* margin-left: 5px; */
        width: 25%;
        margin-left: 0%;
    }
    .hor-rule{
        /* width: 460px; */
        width: 95%;
        height: 0px;
        border: 1px solid #E2E2E2;
        opacity: 1;
        /* margin-top: 5px; */
        margin-bottom: 10px;
    }
    .additional-info{
        display: flex;
        /* justify-content: center; */
        align-items: center;
        width: 100%;
    }
    .maker-image{
        width: 50px;
        /* width: 2.6%; */
        height: 50px;
        opacity: 1;
        border-radius: 50%;
    }
    .img1{
        background: transparent url('../assets/luis-villasmil-hh3ViD0r0Rc-unsplash.png') 0% 0% no-repeat padding-box;
    }
    .img2{
        background: transparent url('../assets/craig-mckay-jmURdhtm7Ng-unsplash.png') 0% 0% no-repeat padding-box;

    }
    .img3{
        background: transparent url('../assets/christopher-campbell-rDEOVtE7vOs-unsplash.png') 0% 0% no-repeat padding-box;

    }
    .maker-name{
        /* width: 124px; */
        width: 40%;
        height: 27px;
        text-align: left;
        font-family: Noto Sans;
        font-style: bold;
        font-weight: 1000;
        font-size: 20px;
        /* font: normal normal bold 20px/27px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        opacity: 1;
        /* margin-left: 10px; */
        margin-left: 2%;
    }
    .cur-price{
        /* width: 5`8px; */
        width: 15%;
        height: 27px;
        text-align: left;
        font-family: Noto Sans;
        font-style: bold;
        font-weight: 1000;
        font-size: 20px;
        /* font: normal normal bold 20px/27px Noto Sans; */
        letter-spacing: 0.2px;
        color: #01CB63;
        opacity: 1;
        /* margin-left: 180px; */
        margin-left: 9.37%;
    }
    .old-price{
        /* width: 41px; */
        width: 2%;
        height: 19px;
        text-align: left;
        text-decoration: line-through;
        font-family: Noto Sans;
        font-style: bold;
        font-weight: 1000;
        font-size: 14px;
        /* font: normal normal bold 14px/19px Noto Sans; */
        letter-spacing: 0.14px;
        color: #1F2532;
        opacity: 1;
    }
</style>