# gitbook
# 介绍
GitBook是一个命令行工具（Node.js库），我们可以借用该工具使用Github/Git和Markdown来制作精美的图书
# 支持输出多种格式

GitBook支持输出多种文档格式，如：

静态站点: 默认格式. 创建一个完全交互式的静态网站，可以发布到GitHub Pages等网站.  
eBook: 图书完成后可以使用它创建电子书. 创建命令: 	```gitbook ebook ./myrepo```. 你需要安装 ebook-convert. 输出格式可以是 PDF, ePub 或 MOBI.  
单页网页: 可以生成一个单页的HTML网页。这个格式可以用来转换PDF或者eBook. 创建命令: ```gitbook build ./myrepo -f page```.  
JSON: 此格式用来调试或者抽取图书的元数据. 创建命令: gitbook build ./myrepo -f json.

# 官网
> <https://www.gitbook.com/>