- bilibili-api-python
  - [\_\_init\_\_.py](/modules/bilibili_api.md) **根模块**
    - [_const_ dict HEADERS](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=const-dict-headers) **访问 bilibili 视频下载链接等内部网址用的 HEADERS**
    - [def set_session()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-set_session) **用户手动设置 Session**
    - [def get_session()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-get_session) **获取当前模块的 httpx.AsyncSession 对象，用于自定义请求**
    - [class Credential](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=class-credential) **凭据类，用于各种请求操作的验证。**
      - [def \_\_init\_\_()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-__init__)
      - [def get_cookies()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-get_cookies) **获取请求 Cookies 字典**
      - [def has_sessdata()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-has_sessdata) **是否提供 sessdata。**
      - [def has_bili_jct()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-has_bili_jct) **是否提供 bili_jct。**
      - [def has_buvid3()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-has_buvid3) **是否提供 buvid3。**
      - [def has_dedeuserid()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-has_dedeuserid) **是否提供 dedeuserid。**
      - [def raise_for_no_sessdata()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-raise_for_no_sessdata) **没有提供 sessdata 则抛出异常。**
      - [def raise_for_no_bili_jct()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-raise_for_no_bili_jct) **没有提供 bili_jct 则抛出异常。**
      - [def raise_for_no_buvid3()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-raise_for_no_buvid3) **没有提供 buvid3 则抛出异常。**
      - [def raise_for_no_dedeuserid()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-raise_for_no_dedeuserid) **没有提供 dedeuserid 则抛出异常。**
    - [def sync()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-sync) **同步执行异步函数**
    - [def aid2bvid()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-aid2bvid) **AV 号转 BV 号。**
    - [def bvid2aid()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-bvid2aid) **BV 号转 AV 号。**
    - [_async_ def get_real_url()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=async-def-get_real_url) **用于获取一个跳转url的目标。**
    - [class ResourceType](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=class-resourcetype) **链接类型类。**
      - **Extends: enum.Enum**
      - VIDEO: 视频
      - BANGUMI: 番剧
      - EPISODE: 番剧剧集
      - FAVORITE_LIST: 视频收藏夹
      - CHEESE: 课程
      - CHEESE_VIDEO: 课程视频
      - AUDIO: 音频
      - AUDIO_LIST: 歌单
      - ARTICLE: 专栏
      - USER: 用户
      - LIVE: 直播间
      - CHANNEL_SERIES: 合集与列表
    - [_async_ def parse_link()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=async-def-parse_link) **获取链接对应的对象。**
    - [class DmMode](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=class-dmmode) **弹幕模式**
      - **Extends: enum.Enum**
      - FLY: 飞行弹幕
      - TOP: 顶部弹幕
      - BOTTOM: 底部弹幕
      - REVERSE: 反向弹幕
    - [class DmFontSize](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=class-dmfontsize) **弹幕字体大小**
      - **Extends: enum.Enum**
      - EXTREME_SMALL: 最小
      - SUPER_SMALL: 非常小
      - SMALL: 小
      - NORMAL: 中等
      - BIG: 大
      - SUPER_BIG: 非常大
      - EXTREME_BIG: 最大
    - [class Danmaku](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=class-danmaku) **弹幕类**
      - [def \_\_init\_\_()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-__init__-1)
      - [def crack_uid()](https://nemo2011.github.io/bilibili-api/#/modules/bilibili_api?id=def-crack_uid)
  - [app.py](/modules/app.md)
    - 手机 APP 相关
  - [article.py](/modules/article.md)
    - 专栏相关
  - [ass.py](/modules/ass.md)
    - 有关 ASS 文件的操作
  - [audio.py](/modules/audio.md)
    - 音频相关
  - [bangumi.py](/modules/bangumi.md)
    - 番剧相关
  - [channel.py](/modules/channel.md)
    - 频道相关操作
  - [cheese.py](/modules/cheese.md)
    - 有关 bilibili 课程的 api
  - [comment.py](/modules/comment.md)
    - 评论相关
  - [dynamic.py](/modules/dynamic.md)
    - 动态相关
  - [favorite_list.py](/modules/favorite_list.md)
    - 收藏夹操作
  - [homepage.py](/modules/homepage.md)
    - 主页相关操作
  - [interactive_video.py](/modules/interactive_video.md)
    - 互动视频相关操作
  - [live.py](/modules/live.md)
    - 直播相关
  - [login_func.py](/modules/login_func.md)
    - 登录相关函数
  - [login.py](/modules/login.md)
    - 登录
  - [rank.py](/modules/rank.md)
    - 和哔哩哔哩视频排行榜相关的 API
  - [search.py](/modules/search.md)
    - 搜索
  - [settings.py](/configuration.md)
    - 这里是配置模块的地方
  - [user.py](/modules/user.md)
    - 用户相关
  - [video_uploader.py](/modules/video_uploader.md)
    - 上传视频
  - [video.py](/modules/video.md)
    - 视频相关操作
  - [vote.py](/modules/vote.md)
    - 投票相关操作