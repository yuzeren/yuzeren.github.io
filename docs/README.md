# 俞则人
My personal website.
## 2021年09月14日
- 把github page 搞起来了
- 把 github desktop 和本地仓库搞起来了
- 原来私有仓库不能发布成网站，把私有改公有了
- 选了一个Jekyll主题，还不清楚怎么自定义主题
- 原来自己写一个 index.html 文件是会把 Jekyll 自带的首页覆盖的
	- 写一个 index.md 文件可以只改变首页内容而不改变其样式
- 在设置里设置了 CNAME 解析，在文件里就加了个 CNAME 记录文件
- 设置成功了 blog.yuzeren.com，但顶级域名没成功，不知道是不是跟我设置了 nas.yuzeren.com 到我的群晖有关
## 2021年09月15日
- 搞定了顶级域名解析的问题
	- 在配置了二级域名的情况下，配置泛解析就是会失败，咨询了开发，说是泛解析是解析优先级最低的
- 使用了 minimal 这个 Jekyll 主题，但没搞明白在哪里修改网站标题和 favicon