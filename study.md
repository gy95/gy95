github下载某个PR到本地
`git fetch upstream pull/123/head:pr123`
其中upstream是远程代码库（如`https://github.com/kubeedge/kubeedge.git`），123是PR的id，pr123是拉取下来新创建的分支名称，然后执行`git check out pr123` checkout过去就可以
