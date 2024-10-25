

## 单位

1. Taro 中尺寸单位建议使用 px、 百分比 %，
2. Taro 默认会对所有单位进行转换。在 Taro 中书写尺寸按照 1:1 的关系来进行书写，即从设计稿上量的长度 100px，那么尺寸书写就是 100px
3. 当转成微信小程序的时候，尺寸将默认转换为 100rpx，当转成 H5 时将默认转换为以 rem 为单位的值。
4. 如果不希望被转化， px 单位中增加一个大写字母，例如 Px或者 PX 这样，则会被转换插件忽略。
5. Taro 默认以 750px 作为换算尺寸标准，如果设计稿不是以 750px 为标准，则需要在项目配置 config/index.js


https://taro-docs.jd.com/docs/next/env-mode-config

请注意，只有以 TARO_APP_ 开头的变量将通过 webpack.DefinePlugin 静态地嵌入到客户端侧的代码中。这是为了避免和系统内置环境变量冲突。

