# README

#### 介绍

我的博客网站，使用框架[Hexo](https://hexo.io/zh-cn/docs/)以及主题[maupassant](https://github.com/tufu9441/maupassant-hexo)进行搭建

#### 软件架构

软件架构说明
1.  doc仓库为本地日常草稿
2.  img仓库为文章在线图库
3.  web仓库为文章发布仓库

#### 安装教程

1.  `git clone git@github.com:VPDong/vpdong.github.io.git -b doc blog-doc`
2.  `cd ./blog-doc/hexo-blog`
3.  `npm install`

#### 使用说明

1.  hexo clean 文章清理

2.  hexo generate 文章生成

3.  hexo server -p 8080 & open http://localhost:8080 本地测试

4.  hexo deploy 推送部署

    > 此部署将 `public` 目录的文件推送至 `_config.yml` 指定的远端仓库，且**完全覆盖**该分支下的已有内容。
    >
    > git add . && git commit -m "init" && git push 常规的推送，需要gitpages中设置public目录。

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request
