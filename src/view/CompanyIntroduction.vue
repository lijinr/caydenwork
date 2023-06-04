<template>
    <div id="CompanyIntroduction">
        <div class="banner container-fuild text-center">关于我们</div>
        <div class="container">
            <div class="row CompanyIntroduction-container">
                <div class="col-xs-12 col-sm-12 col-md-6 wow zoomIn">
                    <img class="img-responsive center-block" src="@/assets/img/about_img.png">
                </div>
                <div class="col-xs-12 col-sm-12 col-md-6">
                    <h3>Cayden工作室</h3>
                    <p class=".text-justify">欢迎来到Cayden工作室，我们是专注于AI领域的创新型团队，汇集了一群热衷于探索未来科技的精英人才。在这里，您将遇见来自不同职业背景的优秀团队成员，包括程序员、游戏美术、运营等多角色从业者，共同致力于开创AI领域的新篇章。</p>
                    <p class=".text-justify">我们的业务范围广泛且多元化，以满足客户不同需求。我们提供StableDiffusion LoRa模型和Checkout模型的定制服务，为您量身打造最适合的解决方案。同时，我们还提供SD和MJ教学以及一对一辅导服务，帮助您在AI领域持续成长和进步。</p>
                    <p class=".text-justify">此外，Cayden工作室还致力于工艺品原型设计，涵盖手机壳、衣服Logo等多个方面。我们的专业团队将为您精心打造独具特色的设计作品，让您的产品在市场中脱颖而出。</p>
                    <p class=".text-justify">在Cayden工作室，我们始终坚信创新是推动时代前进的核心力量。因此，我们将继续探索AI领域的新技术、新应用，为客户提供更优质的服务，共同开创美好未来。欢迎您随时联系我们，了解更多关于我们的信息。期待与您携手共创辉煌！</p>

                </div>
            </div>
        </div>
    </div>
</template>
<script>
import { WOW } from 'wowjs';
export default {
    name: 'CompanyIntroduction',
    data(){
        return{

        }
    },
    mounted(){
        var wow = new WOW();
        wow.init();
    }
}
</script>
<style scoped>
.banner{
    color: #fff;
    font-size: 30px;
    height: 150px;
    line-height: 150px;
    background-image: url('../assets/img/banner.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: scroll;
    background-position: center center;
}
.row{
    margin-right: 0;
    margin-left: 0;
}
.CompanyIntroduction-container{
    padding: 100px 0;
    color: #808080;
    transition: all ease 0.5s;
}
.CompanyIntroduction-container>div>p{
    font-size: 14px;
    line-height: 2.5rem;
}
@media screen and (max-width: 997px){
    .CompanyIntroduction-container{
    padding: 10px 0;
    color: #808080;
}
}
</style>

