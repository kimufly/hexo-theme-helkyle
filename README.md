# hexo-theme-helkyle


我使用的hexo主题 [helkyle.com](http://helkyle.com)

## Features
### Fancybox

你可以使用markdown语法，或者fancybox插件的语法让你的图片支持fancybox。
```
![img caption](img url)
```
### 配置文章摘要    
如果需要，你可以在_post源文件顶部配置`summary`属性。

## Configuration
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

#放在header上的logo，正方形图片最佳
logo_img: http://7xlkda.com1.z0.glb.clouddn.com/avatar_helkyle.png

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

#Social（博客的社交信息）
social:
# key weibo/twitter/google/github/stackoverflow/linkedin/facebook/codepen
# value url
# e.g github: https://github.com/helkyle
  github: https://github.com/helkyle
  weibo: http://weibo.com/joueu
  codepen: http://codepen.io/HelKyle/

#Footer Social
footer_social: 
  enable: false

#Article Social
author_meta:
  ##是否启用文章作者详细
  enable: true
  author_name: HelKyle
  # 文章底部作者头像，非正方形也可以
  author_avatar: http://7xlkda.com1.z0.glb.clouddn.com/utah-thumb.gif
  ##是否打开社交logo
  social: true
  description: 我的第一个个人博客。

#blog since
since: 2014

```

## Todo
- [ ] 移动端兼容    
- [ ] 移动端导航栏重写
- [ ] 底部美化
- [ ] 增加多说评论数，文章创建时间，文章分类
- [ ] 多种颜色主题可选

还在持续开发中~