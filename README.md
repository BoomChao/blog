### 博客相关的配置

添加主题：进入到quickStart目录下
git submodule add git@github.com:adityatelange/hugo-PaperMod.git themes/PaperMod

主题ParperMod的配置和MarkDown配置参考如下:
https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-installation/


本地启动草稿查看:
hugo server -D --bind 0.0.0.0 -p 8080

上传到远端访问:
1. 执行命令: hugo 
2. 进入到public目录下,将里面的文件传入到github的仓库即可
git init
git add .
git commit -m ""
git remote add origin https://github.com/BoomChao/BoomChao.github.io.git
git push -u origin master