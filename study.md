github下载某个PR到本地
`git fetch upstream pull/123/head:pr123`
其中upstream是远程代码库（如`https://github.com/kubeedge/kubeedge.git`），123是PR的id，pr123是拉取下来新创建的分支名称，然后执行`git check out pr123` checkout过去就可以

证书：https://www.lixueduan.com/posts/grpc/04-encryption-tls/



git 合并多条commit记录
1. git rebase -i commitid
2. git rebase -i head~n, n代表要合并的commit数量

如果commit记录较多，可以使用 ":2,$s/pick/s"批量替换pick为s（squash），只保留第一个pick
