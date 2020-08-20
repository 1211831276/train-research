# Git / sourcetree 使用说明

## 1、工具

- Git - 版本管理
- sourcetree - 可视化git工具，简化git命令行的操作

## 2、使用

可参考： [git使用](https://www.cnblogs.com/xiuxingzhe/p/9303278.html)

- 下载安装
- git 秘钥生成

```shell
ssh-keygen -t rsa -C "your_email@youremail.com"
```

- 一路enter，生成的秘钥会放在 C/Users/xx/.ssh 里面的 id_rsa.pub 里面
- 拷贝出来，给我放到github 的里面
- 拉取git:  在目标文件夹的bash/shell：  git clone git@github.com:1211831276/train-research.git
- 可以看到相关的文件

## 3、提交等git操作

- 文件一般几个状态
  - 未暂存
  - 暂存未保存
  - 已保存
- git status ： 查看文件状态
- git add  暂存文件
- git commit  提交，将以此修改的内容作为一个提交，取一个名字，之后可以推送到远端仓库，这样可以知道是谁在什么时候提交的，也可以回退
- git push  推送命令，将已保存的文件提交到远端
- git pull 拉取，别人修改的文章，你拉下来看看别人改了什么
- 更多的操作可以查看git官网

## 4、sourcetree 

- 这是一个可视化的git 工具，很好用，不用命令行，也很方便的查看提交内容和提交的信息
- 回退、遴选等比命令行更好用
- 上面拉取到项目后添加到sourcetree即可，具体的操作很简单

