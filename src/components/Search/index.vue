<template>
    <div class="search_body">
        <div class="search_input">
            <div class="search_input_wrapper">
                <i class="iconfont icon-search"></i>
                <input type="text" name="" id="">
            </div>
        </div>
        <div class="search_result">
            <h3>电影/电视剧/综艺</h3>
            <ul>
                <li>
                    <div class="img">
                        <img src="@/images/movie1.jpg" alt="">
                    </div>
                    <div class="info">
                        <p><span>无名之辈</span><span>8.5</span></p>
                        <p>A Cool Fish</p>
                        <p>剧情，喜剧，犯罪</p>
                        <p>2020-2-20</p>
                    </div>
                </li>
                <li>
                    <div class="img">
                        <img src="@/images/movie2.jpg" alt="">
                    </div>
                    <div class="info">
                        <p><span>无名之辈</span><span>8.5</span></p>
                        <p>A Cool Fish</p>
                        <p>剧情，喜剧，犯罪</p>
                        <p>2020-2-20</p>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name:'search'
}
</script>

<style scoped>
.search_body{
    flex: 1;
    overflow: auto;
}
.search_input{
    padding: 8px 10px;
    background-color: #f5f5f5;
    border-bottom: 1px solid #e5e5e5;
}
.search_input_wrapper{
    padding: 0 10px;
    border:1px solid #e6e6e6;
    border-radius: 5px;
    background-color: #fff;
    display: flex;
    line-height: 30px;
}
.search_input_wrapper i{
    font-size: 16px;
    padding: 4px 0;
}
.search_input_wrapper input{
    border: none;
    font-size: 13px;
    color: #333;
    padding: 4px 0;
    outline: none;
    margin-left: 5px;
    width: 100%;
}
.search_result h3{
    font-size: 15px;
    color: #999;
    padding: 9px 15px;
    border-bottom: 1px solid #e6e6e6;
}
.search_result li{
    border-bottom: 1px #c9c9c9 dashed;
    padding: 10px 15px;
    box-sizing: border-box;
    display: flex;
}
.search_result .img{
    width: 60px;
    float: left;
}
.search_result .img img{
    width: 100%;
}
.info{
    float: left;
    margin-left: 15px;
    flex: 1;
}
.info p{
    height: 22px;
    display: flex;
    line-height: 22px;
    font-size: 12px;
}
.info p:nth-of-type(1) span:nth-of-type(1){
    font-size: 18px;
    flex: 1;
}
.info p:nth-of-type(1) span:nth-of-type(2){
    font-size: 16px;
    color: #fc7103;
}
</style>
