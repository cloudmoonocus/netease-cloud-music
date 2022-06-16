## 网易云音乐

接口文档：[https://neteasecloudmusicapi.vercel.app/#/]

### Vue@3.2.36+Vant@3.49+Pinia+VueRouter+Nprogress+Axios

------

全局灰色：rgb(122, 119, 119)
网易云音乐红色：#e60026

<hr>

```powershell
├─public
└─src
    ├─Api (接口[未做])
    │
    ├─assets
    │  ├─icons (图标)
    │  └─images (图片)
    │      ├─Error
    │      └─Found
    │
    ├─components (组件)
    │  ├─MyFooter (底部标签页)
    │  ├─MyHeader (顶部标题栏，包含侧边栏)
    │  └─Tip (最底部提示)
    │
    ├─pages (页面)
    │  ├─Attention (关注)
    │  ├─CloudSquare (云村[未做，无接口])
    │  ├─Error (404)
    │  │
    │  ├─Found (发现页)
    │  │  ├─DailyRecommendation (每日推荐)
    │  │  │
    │  │  ├─DigitalAlbum (数字专辑)
    │  │  │  ├─AlbumBuy (已购[单曲])
    │  │  │  ├─HotList (畅销榜)
    │  │  │  └─MusicLanguage (语种风格馆)
    │  │  │
    │  │  ├─FocusNewMusic (关注新歌[未做，调用数据后再做])
    │  │  ├─MusicHouse (歌房[未做，无接口])
    │  │  ├─MusicList (歌单[只有八个选项])
    │  │  ├─PrivateFM (私人FM)
    │  │  ├─RankingList (排行榜[未做，无接口])
    │  │  └─SoundBook (有声书[未做，无接口])
    │  │
    │  ├─Index (登录[1])
    │  │  └─PhoneSignIn [手机登录]
    │  │
    │  ├─MyIndex (我的)
    │  │  ├─Buy (已购[单曲])
    │  │  ├─CloudPan (云盘[未做，无接口])
    │  │  ├─Collection-Praise (收藏和赞)
    │  │  ├─Friends (我的好友)
    │  │  ├─Index-Podcast (我的播客[未做，无接口])
    │  │  ├─Local-Download (本地/下载[未做，无接口])
    │  │  ├─MusicBottle (音乐罐子[未做，无接口])
    │  │  └─Rencently (最近播放)
    │  │
    │  ├─Podcast (播客[全部分类])
    │  │  ├─AllCategories (全部分类)
    │  │  ├─FM (广播电台[未做，无接口])
    │  │  ├─MyPodCast (我的播客[未做，无接口])
    │  │  ├─NightSleep (助眠解压[未做，无接口])
    │  │  ├─PodcastRankingList (排行榜[未做，无接口])
    │  │  └─SoundBook (有声书[未做，无接口])
    │  │
    │  └─Search (搜索)
    │
    ├─routers (路由)
    │
    └─store (仓库[未做])
        ├─Attention
        ├─Found
        ├─modules
        ├─MyIndex
        ├─Podcast
        └─Search
```
