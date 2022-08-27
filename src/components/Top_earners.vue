<template>
    <div class="earners-container">
        <div class="earners-inner_container">
            <p class="earners-heading">Top Earners</p>
            <p class="earners-desc">Tranforming Your Ideas Into Reality</p>
            <!-- <p class="earners-desc"></p> -->
            <div class="earners-content">
                <div class="earners-individual">
                    <div class="earner-image earner-image_1"></div>
                    <div class="earner-earning">
                        <p class="earner-earnings">$800000</p>
                    </div>
                </div>
                <div class="earners-individual">
                    <div class="earner-image earner-image_2"></div>
                    <div class="earner-earning">
                        <p class="earner-earnings">$600000</p>
                    </div>                </div>
                <div class="earners-individual">
                    <div class="earner-image earner-image_3"></div>
                    <div class="earner-earning">
                        <p class="earner-earnings">$500000</p>
                    </div>
                </div>
                <div class="earners-individual">
                    <div class="earner-image earner-image_4"></div>
                    <div class="earner-earning">
                        <p class="earner-earnings">$450000</p>
                    </div>
                </div>
            </div>
        </div>
        
    </div>
    
    
</template>

<script>
export default {
    name: 'Top_earners',
}
</script>

<style scoped>
    .earners-container{
        display: flex;
        flex-direction: column;
        justify-content: center;
        /* width: 1920px; */
        width: 100%;
        margin: 0px;
        /* padding-left: 137px; */
        margin-top: 150px;
        margin-right: 0px;
    }
    .earners-inner_container{
        margin-top: 0px;
        /* margin-left: 140px; */
        margin-left: 5.5%;
        /* margin-right: 140px; */
        /* margin-right: 7.3%; */
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    .earners-heading{
        margin-top: 0px;
        margin-bottom: 0px;
        /* width: 131px; */
        width: 20%;
        height: 34px;
        /* UI Properties */
        text-align: left;
        font-family: Noto Sans;
        font-style: italic;
        /* font-weight: 1000; */
        font-size: 25px;
        /* font: normal normal normal 25px/34px Noto Sans; */
        letter-spacing: 0px;
        color: #01CB63;
        opacity: 1;
    }
    .earners-desc{
        margin-top: 12px;
        margin-bottom: 0px;
        margin-left: 0px;
        /* width: 490px; */
        width: 35%;
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
    .earners-content{
        display: flex;
        margin-top: 70px;
        justify-content: space-between;
        align-items: center;
        width: 100%;
    }
    .earners-individual{
        display: flex;
        flex-direction: column;
        width: 24%;
    }
    .earner-image{
        /* margin: 5px; */
        /* width: 360px; */
        width: 100%;
        height: 360px;
        border-radius: 5px;
        opacity: 1;
    }
    .earner-image_1{
        background: transparent url('../assets/luis-villasmil-hh3ViD0r0Rc-unsplash.png') 0% 0% no-repeat padding-box;
    }
    .earner-image_2{
        background: transparent url('../assets/craig-mckay-jmURdhtm7Ng-unsplash.png') 0% 0% no-repeat padding-box;
    }
    .earner-image_3{
        background: transparent url('../assets/christopher-campbell-rDEOVtE7vOs-unsplash.png') 0% 0% no-repeat padding-box;
    }
    .earner-image_4{
        background: transparent url('../assets/jonas-kakaroto-mjRwhvqEC0U-unsplash.png') 0% 0% no-repeat padding-box;
    }
    .earner-earning{
        margin: 0px;
        margin-top: 10px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        /* align-items: center; */
        height: 60px;
        border-left: 10px solid #01CB63;
    }
    .earner-earnings{
        /* width: 114px; */
        width: 10%;
        height: 34px;
        /* padding-left: 10px; */
        margin: 0px;
        margin-left: 3%;
        
        /* margin-top: 10px; */
        /* UI Properties */
        text-align: left;
        font-family: Noto Sans;
        font-style: normal ;
        font-weight: 1000;
        font-size: 25px;
        /* font: normal normal bold 25px/35px Noto Sans; */
        letter-spacing: 0px;
        color: #1F2532;
        opacity: 1;
        
    }
</style>