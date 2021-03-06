# 快速上手

安装 InPageEdit 十分简单，通常情况下只需要几秒就能完成。

## 个人 js 使用

在大多数 MediaWiki 网站上，都允许用户添加自定义的 JavaScript，您可以通过编辑个人 js 页面安装 InPageEdit。

1. 前往您的个人 js 页面，这个页面通常是`User:<你的用户名>/common.js`
2. 点击“编辑”按钮
3. 在编辑框中添加以下内容：

```js
mw.loader.load('https://cdn.jsdelivr.net/gh/dragon-fish/inpageedit-v2@master/script.min.js');
```

4. 点击“保存”按钮
5. 完成，请享用~

## 通过小工具开启

有一些 wiki 网站（例如[萌娘百科](https://zh.moegirl.org.cn/Special:%E5%8F%82%E6%95%B0%E8%AE%BE%E7%BD%AE#mw-prefsection-gadgets)）已经通过小工具（Gadget）安装了本插件，在这些网站上，我们推荐直接在设置里打钩启用它。

1. 前往`http://<wiki的网址以及路径>/Special:Preferences`或者通过网页上的`参数设置`链接进入“参数设置”页面
2. 从页面的导航条选中“小工具”
3. 找到带有“InPageEdit”字样的选择框，打钩选中它
4. 翻到页面底部，点击“保存”按钮
5. 完成，请享用~

## 通过浏览器扩展安装

有一些 MediaWiki 网站出于对安全的考虑，禁用了个人 js 功能，而且也没有通过小工具安装本插件（例如灰机 Wiki）。在这种情况下如果您想使用本插件，需要通过浏览器扩展来实现。

使浏览器运行 js 插件的扩展市面上有很多，在此不赘述具体实现方案，如果您愿意补充本文档，欢迎点击页底的链接进行扩充！
