---
seo_title: 示例博客
cover: true
sidebar: []

---

<center>
{% span large red, 示 %}
{% span large yellow, 例 %}
{% span large green, 博 %}
{% span large blue, 客 %}
</center>
<br>

## 社区维护团队的博客

{% sitegroup %}
{% site xaoxuu, url=https://xaoxuu.com, screenshot=https://i.loli.net/2020/08/21/VuSwWZ1xAeUHEBC.jpg, avatar=https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/avatar/avatar.png, description=简约风格 %}
{% site MHuiG, url=https://blog.mhuig.top, screenshot=https://i.loli.net/2020/08/22/d24zpPlhLYWX6D1.png, avatar=https://cdn.jsdelivr.net/gh/MHuiG/imgbed@master/data/p.png, description=字文述描的站网个这于关段一是这 %}
{% site Colsrch, url=https://colsrch.cn, screenshot=https://i.loli.net/2020/08/22/dFRWXm52OVu8qfK.png, avatar=https://cdn.jsdelivr.net/gh/Colsrch/images/Colsrch/avatar.jpg, description=愿多年以后，我可以酌一杯清酒，烂醉如泥，梦中回到我们的曾经。 %}
{% site inkss, url=https://inkss.cn, screenshot=https://i.loli.net/2020/08/21/Vzbu3i8fXs6Nh5Y.jpg, avatar=https://cdn.jsdelivr.net/gh/inkss/common@master/static/web/avatar.jpg, description=这不是一段关于这个网站的描述文字啊喂 %}
{% site Linhk1606, url=https://linhk1606.github.io, screenshot=https://i.loli.net/2020/08/21/3PmGLCKicnfow1x.png, avatar=https://i.loli.net/2020/02/09/PN7I5RJfFtA93r2.png, description=这是一段关于这个网站的描述文字 %}
{% site W4J1e, url=https://www.hin.cool, screenshot=https://7.dusays.com/2020/12/13/bc50e8dab935e.jpg, avatar=https://gitee.com/W4j1e/pic/raw/master/img/duola.jpg, description=偏爱不务正业 %}
{% site Test Site, url=https://volantis-x.js.org/, screenshot=https://7.dusays.com/2021/01/26/308758c15420f.png, avatar=https://cdn.jsdelivr.net/gh/volantis-x/cdn-org/blog/favicon/apple-touch-icon.png, description=Test Site For Development %}
{% endsitegroup %}


<br>

{% issues sites | api=https://api.github.com/repos/volantis-x/examples/issues?sort=updated&state=open&page=1&per_page=100 | group=version:版本：^4.0,版本：^3.0,版本：^2.0 %}

<br>


<!-- more -->

<br><br>

{% timeline 如何添加自己的博客链接 %}

{% timenode 第一步：新建 [Issue](https://github.com/volantis-x/examples/issues/) 按照格式填写并提交 %}

```json
{
    "title": "",
    "description": "",
    "screenshot": "",
    "url": "",
    "avatar": "",
    "version": "版本：^4.0"
}
```

为了提高图片加载速度，建议优化图片尺寸：
1. 打开 [压缩图](https://www.yasuotu.com/) 上传自己的截图，将图片的高度调整到 `360px` 后下载。
2. 将压缩后的图片上传到 [去不图床](https://7bu.top/) 并使用此图片链接作为截图链接。

{% endtimenode %}

{% timenode 第二步：刷新 %}

回来刷新即可生效。

{% endtimenode %}

{% endtimeline %}

{% p h2, 如何更新自己的博客链接 %}

- 如果是自己创建的 issue ，可以自己修改。
- 如果是管理员创建的，请自己重新创建一份，然后让管理员删掉旧的。
