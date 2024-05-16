# Gmeek 超轻量级个人博客框架

这是一个博客框架，超轻量级个人博客模板。完全基于 Github Pages 、 Github Issues 和 Github Actions。
不需要本地部署，从搭建到写作，只需要18秒，2步搭建好博客，第3步就是写作。

开源地址：https://github.com/Meekdai/Gmeek
DEMO：https://blog.meekdai.com

# 安装步骤

## 创建仓库

首先点击模板创建仓库，建议使用仓库名称为 xxx.github.io，其中 xxx 为你的 github 用户名。

## 启用 Pages

在仓库的 Settings 中 Pages -> Build and deployment -> Source 下面选择 Github Actions。

## 开始写作

首先打开一篇 issue，开始写作，并且必须至少添加一个标签 Lable，再保存 issue 后会自动创建博客内容。
片刻之后，便可以通过该网址——https://xxx.github.io 进行访问（可进入 Actions 页面查看构建进度）。

## 手动全局生成

这个步骤只有载修改 config.json 文件或者出现奇怪问题的时候，需要执行。
通过 Actions -> build Gmeek -> Run workflow -> 里面的按钮全局重新生成一次。

原文地址：https://github.com/Meekdai/Gmeek