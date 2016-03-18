# Git备忘录

---
## 配置相关：
### git初始配置：
    git config (--global) user.name "XXX"
    git config (--global) user.email "xxx@xxx"

### 检查git配置信息
    git config --list

---
### git初始化提交项目

    git init
    git add README.md
    git commit -m "init"
    git remote add origin http://......
    git push -u origin master
### 查看当前文件状态
    git status
    git status -s
---

## 忽略文件
创建.gitignore文件  
忽略列表详见  
**https://github.com/github/gitignore**
