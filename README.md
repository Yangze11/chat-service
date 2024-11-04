# 在项目目录下初始化 Git
git init

# 添加所有文件
git add index.html style.css script.js

# 提交更改
git commit -m "Initial commit"

# 添加远程仓库（替换 YOUR_USERNAME 为您的 GitHub 用户名）
git remote add origin https://github.com/YOUR_USERNAME/chat-service.git

# 推送代码到主分支
git push -u origin main
