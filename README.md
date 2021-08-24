GitHub CLI Serverless-Devs Extension
=====================================

# Features

### 基于repo template创建项目

```
gh s create -p xxx
```

* 基于repository template创建一个项目
* 设置Serverless-Devs相关的secrets
* 执行git clone到本地进行开发

### 触发Github Actions进行站点发布

执行 `gh s deploy` 相当于调用 `gh workflow run Serverless-Devs`

# References

* GitHub CLI: https://docs.github.com/en/github-cli
* gh actions: https://cli.github.com/manual/gh_actions
* Creating GitHub CLI extensions: https://docs.github.com/en/github-cli/github-cli/creating-github-cli-extensions
