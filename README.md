# FontFace-CDN

#### 介绍
用来存储我收藏的好看实用的字体并且将其通过CDN加速，可以在Web快速调用此url字体。

#### 使用说明

1.  定义fontface自定义字体
    ``` css
    @font-face {
      font-family: HarmonyOS;
      src: url(../font/HarmonyOS_Sans_SC_Medium.ttf);
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
