# DjangoTutorialByLiuJiang-HTML2PDF
Django的教程资料，将刘江的博客转化为PDF，方便阅读学习

个人认为django 写的比较好的教程资料。
刘江老师的blog地址：http://www.liujiangblog.com
该python脚本只是把Django教程转化成了PDF 文件，方便阅读。如有侵权则删

## 环境要求：
python中将html转化为pdf的常用工具是Wkhtmltopdf工具包，在python环境下，pdfkit是这个工具包的封装类。
所以要运行该脚本需要下载wkhtmltopdf安装包，并且安装到电脑上，在系统Path变量中添加wkhtmltopdf的bin路径，以便于pdfkit的调用（环境变量必须加进去）。
下载地址：https://wkhtmltopdf.org/downloads.html
