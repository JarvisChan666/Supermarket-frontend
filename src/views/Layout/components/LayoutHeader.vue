<script setup lang="ts">
    // 
</script>

<template>
    <header class="app-header">
        <div class="container">
            <h1 class="logo">
                <RouterLink to="/">小兔鲜</RouterLink>
            </h1>
            <ul class="app-header-nav">
                <li class="home">
                    <RouterLink to="/">首页</RouterLink>
                </li>
                <li>
                    <a href="#">美食</a>
                </li>
                <li>
                    <a href="#">餐厨</a>
                </li>
                <li>
                    <a href="#">艺术</a>
                </li>
                <li>
                    <a href="#">电器</a>
                </li>
                <li>
                    <a href="#">居家</a>
                </li>
                <li>
                    <a href="#">洗护</a>
                </li>
                <li>
                    <a href="#">孕婴</a>
                </li>
                <li>
                    <a href="#">服装</a>
                </li>
                <li>
                    <a href="#">杂货</a>
                </li>
            </ul>
            <div class="search">
                <i class="iconfont icon-search"></i>
                <input type="text" placeholder="搜一搜" />
            </div>
            <!-- 购物车 -->
            <div class="cart">
                <a class="curr" href="#">
                    <i class="iconfont icon-cart"></i>
                    <em>2</em>
                </a>
            </div>
        </div>
    </header>
</template>