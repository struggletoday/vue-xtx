<script>
export default {

}
</script>

<template>
    <div class="topNav">
        <div class="wrapper">
            <ul>
                <li><a href="href">请登录</a></li>
                <li><a href="href">免费注册</a></li>
                <li><a href="href">我的订单</a></li>
                <li><a href="href">会员中心</a></li>
                <li><a href="href">帮助中心</a></li>
                <li><a href="href">在线客服</a></li>
                <li><a href="href">手机版</a></li>
            </ul>
            <a href="#" class="cellphone"></a>
        </div>
    </div>
</template>
<style scoped>
.topNav {
    background: #333333;
    position: relative;
}

.topNav ul {
    display: flex;
    justify-content: end;
}

.topNav ul a {
    line-height: 50px;
    text-decoration: none;
    color: #dcdcdc;
    font-size: 16px;
    border-right: 2px solid #666666;
    padding: 0 16px;
}

.topNav ul a:hover {
    color: #27ba9b;
}

.topNav ul li:last-child a {
    border: none;
    margin-left: 34px;
    padding-left: 0px;
}

.topNav .cellphone {
    width: 11px;
    height: 16px;
    background-image: url(../images/sprites.png);
    background-position: -160px -70px;
    position: absolute;
    right: 18%;
    top: 20%;
    transform: translate(100%, 40%);
}
</style>