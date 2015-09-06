# hexo-theme-helkyle


我使用的hexo主题 [helkyle.com](http://helkyle.com)

##Features
###Fancybox

你可以使用markdown语法，或者fancybox插件的语法让你的图片支持fancybox。
```
![img caption](img url)

{% fancybox img_url [img_thumbnail] [img_caption] %}
```

##Configuration
``` yml
# Header
menu:
  主页: /
  归档: /archives
  标签: /tags
  关于: /about
rss: /atom.xml

# Miscellaneous
favicon: /favicon.ico

version: 0.0.1

#头像url
avatar_url: http://7xlkda.com1.z0.glb.clouddn.com/avatar_helkyle.png

# 多说
duoshuo:
	shortname: helkyle

#阅读更多文字以及最大长度
excerpt_link: 更多...
excerpt_length: 600

#打开fancybox
fancybox: true

#百度统计
baidu_tongji: 3640c17e94957cdf51170baa0f8f14e1

#Social（暂时只有底部用到）
social:
# key weibo/twitter/google/github/stackoverflow/rss/linkedin/facebook
# value url
# e.g github: https://github.com/helkyle
  github: https://github.com/helkyle
  rss: /atom.xml
  weibo: http://weibo.com/joueu

```
还在持续开发中~