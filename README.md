GitHub CLI Serverless-Devs Extension
=====================================

# 如何使用?

* 安装Github CLI: https://cli.github.com/manual/installation
* 安装Github CLI Serverless-Devs扩展： `gh extension install Serverless-Devs/gh-s`
* 查看帮助:  `g s --help`

# 特性

### 基于repo template创建项目

```
gh s create -p xxx
```

* 基于repository template创建一个项目
* 设置Serverless-Devs相关的secrets
* 执行git clone到本地进行开发

### 触发Github Actions进行站点发布

执行 `gh s deploy` 相当于调用 `gh workflow run Serverless-Devs`

# 参考

* GitHub CLI: https://docs.github.com/en/github-cli
* gh actions: https://cli.github.com/manual/gh_actions
* Creating GitHub CLI extensions: https://docs.github.com/en/github-cli/github-cli/creating-github-cli-extensions
