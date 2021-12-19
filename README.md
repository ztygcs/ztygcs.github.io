# ztygcs.github.io
我的hugo博客部署

## 本地运行
在`/blog`目录下运行指令
```bash
hugo server -D
```

## 打包到public文件夹
```bash
hugo -D
```

## pull到指定分支（或master分支）
进入`/blog/public`文件夹执行命令
```bash
git add .
git commit -m 'feature:发布博客'
git pull
git push
```

## 合入master
- 如果pull到其他分支还需在GitHub中将代码合入master
- 如果直接合入的是master分支则无需此操作

> commit规范说明

|字段|说明|
|:-:|:-:|
|feature|新功能|
|fix|修改bug|
|docs|文档|
|style|格式（不影响代码运行的变动）|
|refactor|重构（即不是新增功能，也不是修改bug的代码变动）|
|test|增加测试|
|chore|构建过程或辅助工具的变动|
