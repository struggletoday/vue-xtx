<script>
export default {
    data () {
        return {}
    },
    methods: {

    }
}
</script>
<template>
    <div class="banner">
        <div class="wrapper">
            <!-- 左侧导航菜单 -->
            <div class="left">
                <ul>
                    <li class="menuChecked">
                        <div>
                            <a href="#" class="oneClass">生鲜</a>
                            <a href="#">水果</a>
                            <a href="#">蔬菜</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                    <li>
                        <div>
                            <a href="#" class="oneClass">生鲜</a>
                            <a href="#">水果</a>
                            <a href="#">蔬菜</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                    <li>
                        <div>
                            <a href="#" class="oneClass">家居</a>
                            <a href="#">床品</a>
                            <a href="#">四件套</a>
                            <a href="#">被枕</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                    <li>
                        <div>
                            <a href="#" class="oneClass">生鲜</a>
                            <a href="#">水果</a>
                            <a href="#">蔬菜</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                    <li>
                        <div>
                            <a href="#" class="oneClass">生鲜</a>
                            <a href="#">水果</a>
                            <a href="#">蔬菜</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                    <li>
                        <div>
                            <a href="#" class="oneClass">生鲜</a>
                            <a href="#">水果</a>
                            <a href="#">蔬菜</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                    <li>
                        <div>
                            <a href="#" class="oneClass">生鲜</a>
                            <a href="#">水果</a>
                            <a href="#">蔬菜</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                    <li>
                        <div>
                            <a href="#" class="oneClass">生鲜</a>
                            <a href="#">水果</a>
                            <a href="#">蔬菜</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                    <li>
                        <div>
                            <a href="#" class="oneClass">生鲜</a>
                            <a href="#">水果</a>
                            <a href="#">蔬菜</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                    <li>
                        <div>
                            <a href="#" class="oneClass">生鲜</a>
                            <a href="#">水果</a>
                            <a href="#">蔬菜</a>
                        </div>
                        <div>
                            <a href="#">
                                <span class="iconfont icon-arrow-right"></span>
                            </a>
                        </div>
                    </li>
                </ul>
            </div>
            <div class="right">
                <!-- 轮播图 -->
                <ul>
                    <li>
                        <a href="#">
                            <img src="../uploads/banner_1.png">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../uploads/banner_1.png">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../uploads/banner_1.png">
                        </a>
                    </li>
                </ul>
                <!-- 箭头区域 -->
                <div class="arrow">
                    <a href="#" class="leftArrow iconfont icon-arrow-left"></a>
                    <a href="#" class="rightArrow iconfont icon-arrow-right"></a>
                </div>
                <!-- 圆点指示器 -->
                <div class="dot">
                    <ol>
                        <li>
                            <a href="#" class="active"></a>
                        </li>
                        <li>
                            <a href="#"></a>
                        </li>
                        <li>
                            <a href="#"></a>
                        </li>
                        <li>
                            <a href="#"></a>
                        </li>
                        <li>
                            <a href="#"></a>
                        </li>
                    </ol>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.banner {
    height: 500px;
    background: #f1eeee;
    /* overflow: hidden; */
}

.wrapper {
    /* 父级设置相对定位 */
    position: relative;
}

/* 左侧菜单 */
.left {
    /* 左侧菜单设置绝对定位 */
    position: absolute;
    width: 250px;
    background: rgba(0, 0, 0, 0.6);
}

.left ul li {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 50px;
    line-height: 50px;
    padding-left: 30px;
}

.left ul li:hover {
    background: #27ba9b;
}

/* 先设置所有a都是小字，然后单独控制大分类a标签样式即可 */
.left ul a {
    text-decoration: none;
    font-size: 14px;
    color: white;
    margin-right: 5px;
}

.left .oneClass {
    font-size: 18px;
    margin-right: 20px;
}

.left ul span {
    font-size: 11px;
}

.left .menuChecked {
    background: #27ba9b;
}

.left .iconfont {
    margin-right: 20px;
}

/* 右侧商品轮播图 */

.right ul {
    display: flex;
    width: 1240px;
    overflow: hidden;
}

.right img {
    height: 500px;
    vertical-align: middle;
}

/* 左右翻页箭头样式 */
.arrow a {
    width: 45px;
    height: 45px;
    position: absolute;
    top: 50%;
    background: rgba(0, 0, 0, 0.4);
    text-decoration: none;
    color: #fff;
    border-radius: 50%;
    text-align: center;
    line-height: 45px;
    font-size: 22px;
}

.arrow .leftArrow {
    left: 24%;
    transform: translate(-80%, -50%);
}

.arrow .rightArrow {
    right: 1%;
    transform: translateY(-50%);
}

/* 底部轮播图圆点 */
.right .dot ol {
    height: 10px;
    position: absolute;
    display: flex;
    bottom: 30px;
    left: 54%;
}

.right .dot ol a {
    display: block;
    width: 10px;
    height: 10px;
    margin: 0 8px;
    background: rgba(255, 255, 255, 0.4);
    border-radius: 50%;
}

.right .dot .active {
    background: white;
}
</style>