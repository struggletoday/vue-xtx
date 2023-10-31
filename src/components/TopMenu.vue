<script>
export default {
    data () {
        return {
            text: ''
        }
    },
    methods: {
        onInput (e) {
            this.text = e.target.value;
        },
        haha () {
            alert(this.text);
        }
    }
}
</script>
<template>
    <div class="menu wrapper">
        <div class="logo">
            <h1><img src="../images/logo.png"></h1>
        </div>
        <div>
            <ul>
                <li><a href="href" class="active">首页</a></li>
                <li><a href="href">生鲜</a></li>
                <li><a href="href">美食</a></li>
                <li><a href="href">炊具</a></li>
                <li><a href="href">电器</a></li>
                <li><a href="href">家居</a></li>
                <li><a href="href">洗护</a></li>
                <li><a href="href">孕婴</a></li>
                <li><a href="href">服装</a></li>
            </ul>
        </div>
        <div class="search">
            <input :value="text" @input="onInput" placeholder="请输入搜索内容">
            <button @click="haha"></button>
        </div>
        <div class="cart">
            <a href="#" alt="购物车"></a>
            <span>99</span>
        </div>
    </div>
</template>
<style scoped>
.menu {
    height: 100px;
    line-height: 100px;
    justify-content: space-between;
}

.wrapper {
    display: flex;
}

.logo img {
    width: 207px;
    height: 70px;
    vertical-align: middle;
}

.menu ul {
    display: flex;
}

.menu ul a {
    margin: 0 48px 0 0;
    padding-bottom: 4px;
    font-size: 16px;
    text-decoration: none;
}

.menu ul li:first-child a {
    margin-left: 40px;
}

.menu ul a:hover,
.menu ul .active {
    color: #27ba9b;
    border-bottom: 1px solid #27ba9b;
}

.search {
    display: flex;
    height: 30px;
    width: 172px;
    background: #f1efef;
    align-self: center;
    border-radius: 14px;
}

.search input {
    /* 浏览器优先生效input默认宽度；在处理时，需要先去除默认宽度；加 width：0； */
    width: 0;
    margin: 0 0 0 10px;
    width: 132px;
    background: rgba(255, 255, 255, 0);
    border: 0;
    /* 去除输入框选中时的边框 */
    outline: none;
}

/* 修改输入框内提示文字 */
.search input::placeholder {
    font-size: 14px;
}

.search button {
    width: 20px;
    height: 20px;
    border: none;
    background: url(../images/sprites.png) -79px -69px;
    transform: translate(20%, 30%);
}

.search button:hover {
    cursor: pointer;
}

.cart {
    position: relative;
    align-self: center;
}

.cart a {
    display: block;
    margin-right: 28px;
    width: 22px;
    height: 22px;
    text-decoration: none;
    background: url(../images/sprites.png) -120px -70px;
}

/* 购物车数字 */
.cart span {
    position: absolute;
    top: -10px;
    /* left左对齐，文字向右撑开 */
    left: 10px;
    /* right是右对齐，当文字多了，会向左撑开，会盖住其他内容 */
    /* right: 12px; */
    /* 不要宽度是因为，购物车数字是变化的，超过1位数之后，宽度会增大，所以让内容自然撑开宽度 */
    /* width: 20px; */
    height: 15px;
    padding: 0 6px;
    line-height: 15px;
    background: #e26237;
    color: white;
    border-radius: 8px;
    font-size: 13px;
    text-align: center;
}
</style>