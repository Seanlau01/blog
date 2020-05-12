# 学习方法
     解决一个问题的方法首先是立马着手去做
     主动交流，不能闭门造车，只会做事，不能推动其他人做事
     平时把实现一个问题的思路写在博客上
     平时养成自己的方法论和思维体系
     一个成熟的方法论包括四个板块：问题、解法、优点、缺点   
     多向大牛学习，通过大牛认识更多大牛，这里推荐阮一峰和张鑫旭
     多做项目
     多用谷歌搜索,多用MDN搜索JS和CSS的基础知识
     初级入门多看视频教程
     有问题多查Stackoverflow
# GitHub上传本地代码
    //初始化文件夹
       git init
    //初始化目录，把基本文件下载下来，如ignore文件
       git pull --rebase origin master
    //把当前目录下所有文件上传
       git add .
    //添加注释
       git commit -m "注释提交修改情况"
    //添加远程库
       git remote add origin git@github.com:Seanlau01/blog.git
    //拉取最新文件
       git pull origin master
    //向git推送文件
       git push -u origin master
