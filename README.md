# 10td-Compiler

## upload git repo to ipfs

[install ipfs](https://docs.ipfs.io/install/command-line/#system-requirements)

> for small repos

```
git clone --bare https://github.com/repo.git
cd repo.git
git update-server-info
ipfs add -r --raw-leaves=true .
```

[for large repos](https://docs.ipfs.io/how-to/command-line-quick-start/#initialize-the-repository)
