# ccpowers marketplace

Claude Code 中文核心技能库的插件 marketplace。

## 安装

在 Claude Code 中添加 marketplace：

```text
/plugin marketplace add chenaojun2/ccpowers-marketplace
```

安装插件：

```text
/plugin install ccpowers@ccpowers
```

## 本地测试

在发布到 GitHub 前，可以从本地目录测试：

```text
/plugin marketplace add /Users/chenaojun/AIPro/ccpowers-marketplace
/plugin install ccpowers@ccpowers
```

## 发布

把此目录推送到 GitHub 仓库：

```bash
cd /Users/chenaojun/AIPro/ccpowers-marketplace
git init
git add .
git commit -m "Add ccpowers marketplace"
git branch -M main
git remote add origin https://github.com/chenaojun2/ccpowers-marketplace.git
git push -u origin main
```

插件内容来自：

https://github.com/chenaojun2/ccpowers
