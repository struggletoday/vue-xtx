<script>
export default {
    data () {
        return {};
    },
    methods: {

    }
}
</script>
<template>
    <div class="footer">
        <div class="wrapper">
            <!-- 服务区域 -->
            <div class="service">
                <ul>
                    <li>
                        <i></i>
                        <span>价格亲民</span>
                    </li>
                    <li>
                        <i></i>
                        <span>物流快捷</span>
                    </li>
                    <li>
                        <i></i>
                        <span>品质新鲜</span>
                    </li>
                    <li>
                        <i></i>
                        <span>质量保证</span>
                    </li>
                </ul>
            </div>
            <!-- 帮助中心 -->
            <div class="help">
                <div class="left">
                    <dl>
                        <dt>购物指南</dt>
                        <dd><a href="#">购物流程</a></dd>
                        <dd><a href="#">购物流程</a></dd>
                        <dd><a href="#">购物流程</a></dd>
                    </dl>
                    <dl>
                        <dt>配送方式</dt>
                        <dd><a href="#">购物流程</a></dd>
                        <dd><a href="#">购物流程</a></dd>
                        <dd><a href="#">购物流程</a></dd>
                    </dl>
                    <dl>
                        <dt>关于我们</dt>
                        <dd><a href="#">购物流程</a></dd>
                        <dd><a href="#">购物流程</a></dd>
                        <dd><a href="#">购物流程</a></dd>
                    </dl>
                    <dl>
                        <dt>售后服务</dt>
                        <dd><a href="#">购物流程</a></dd>
                        <dd><a href="#">购物流程</a></dd>
                        <dd><a href="#">购物流程</a></dd>
                    </dl>
                    <dl>
                        <dt>服务热线</dt>
                        <dd><a href="#">在线客服</a></dd>
                        <dd><a href="#">客服电话 400-888-8888</a></dd>
                        <dd><a href="#">工作时间 周一至周六 8:00-22:00</a></dd>
                    </dl>
                </div>
                <div class="right">
                    <ul>
                        <li>
                            <img src="../uploads/qrcode.png" alt="微信公众号">
                            <p>微信公众号</p>
                        </li>
                        <li>
                            <img src="../uploads/qrcode.png" alt="微信公众号">
                            <p>微信公众号</p>
                        </li>
                    </ul>
                </div>
            </div>
            <!-- 版权区域 -->
            <div class="copyright">
                <p>
                    <a href="#">关于我们</a> |
                    <a href="#">帮助中心</a> |
                    <a href="#">售后服务</a> |
                    <a href="#">配送与验收</a> |
                    <a href="#">商务合作</a> |
                    <a href="#">搜索推荐</a> |
                    <a href="#">友情链接</a>
                </p>
                <p>CopyRight @ 小兔鲜儿</p>
            </div>
        </div>
    </div>
</template>
<style scoped>
.footer {
    height: 480px;
    background: #333;
}

.wrapper {}

/* 服务区域 */
.service {
    height: 158px;
    padding: 50px 0;
    border-bottom: 1px solid #fff;
}

.service ul {
    display: flex;
    justify-content: space-evenly;
}

.service li {
    display: flex;
    height: 58px;
}

.service li i {
    width: 58px;
    height: 58px;
    background: url(../images/sprites.png) 0 0;
    margin-right: 20px;
}

.service li:nth-child(2) i {
    background: url(../images/sprites.png) -130px 0;
}

.service li:nth-child(3) i {
    background: url(../images/sprites.png) -65px 0;
}

.service li span {
    line-height: 58px;
    font-size: 28px;
    color: #fff;
}

/* 帮助中心 */
.help {
    display: flex;
    justify-content: space-between;
}

.help .left {
    display: flex;
    padding-top: 50px;
}

.help .left dl {
    margin-right: 60px;
    color: #fff;
}

.help .left dl:last-child {
    margin-right: 0;
}

.help .left dt {
    font-size: 20px;
    margin-bottom: 20px;
}

.help .left a {
    font-size: 15px;
    margin-bottom: 10px;
    color: #fff;
    text-decoration: none;
}

.help .left a:hover {
    color: #27ba9b;
}

/* 二维码区域 */
.help .right ul {
    display: flex;
    padding: 60px 0;
}

.help .right li:first-child {
    margin-right: 55px;
}

.help .right ul img {
    width: 105px;
    height: 103px;
    padding: 6px;
    border: 1px solid white;
}

.help .right ul p {
    color: #999999;
    font-size: 14px;
    text-align: center;
}

/* 版权区域 */
.copyright {
    text-align: center;
    font-size: 14px;
    color: #999999
}

.copyright p {
    padding-bottom: 10px;
}

.copyright a {
    color: #999999;
    text-decoration: none;
    margin: 0 6px;
}

.copyright a:hover {
    color: #27ba9b;
}
</style>