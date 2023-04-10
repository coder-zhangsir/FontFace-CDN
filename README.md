# FontFace-CDN

#### 介绍
用来存储我收藏的好看实用的字体并且将其通过CDN加速，可以在Web快速调用此url字体。

#### 使用说明

1.  定义fontface自定义字体
    ``` css
    @font-face {
      font-family: HarmonyOS;
      /* https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径 */
      src: url(https://cdn.jsdelivr.net/gh/coder-zhangsir/FontFace-CDN@v1.0/HarmonyOS/Sans_SC_Medium.ttf);
    }
    ```
2.  愉快玩耍
    ``` css
    /* body主体部分默认配置 */
    body {
      font-family: HarmonyOS, -apple-system, BlinkMacSystemFont, segoe ui, Roboto, helvetica neue, Arial, noto sans, sans-serif, apple color emoji, segoe ui emoji, segoe ui symbol, noto color emoji;
      color: #333;
    }
    ```
