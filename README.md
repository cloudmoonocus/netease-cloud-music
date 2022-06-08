## Cloudmoon[制作中]

### Vue@3.2.36+Vant@3.49+Vuex@4+VueRouter@4+Nprogress+Axios

<br>灰：rgb(122, 119, 119)
<br>网易云音乐红色：#e60026

<br>
https://cloudmoonocus.github.io
<br>
f356660222@foxmail.com
<br>

问题
<br>

-   刷新后底部按钮的判断，使用路由元信息，但不能及时获取
    -   若采用和下面问题的方法，颜色标识是从“发现”转为“某标签”，而不是直接转到“某标签”\*
-   跳转不同页面时候，通过路由元信息进行赋值，但是点击其他标签页面未切换
    -   通过 watch 监听 route 来进行赋值
-   畅销榜的对齐问题
    -   暂未解决\*
-   发现页的关注新歌未做
    -   调用 API 时再制作\*
-   发现-播客页的布局优化
    -   后期优化\*
-   CSS 实现简单的超过行数隐藏
    -   ```CSS
        // 超过x行隐藏
        overflow: hidden;
        display: -webkit-box;
        -webkit-line-clamp: "行数";
        -webkit-box-orient: vertical;
        ```
-   如何在播客页跳转任意指定标签页时候，使用 Vant 组件方法的 scrollTo 跳转
    -   暂未解决
