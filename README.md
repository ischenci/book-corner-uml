# 进入项目文件夹
cd C:\Users\23929\OneDrive\文档\实验\项目管理\book-corner-uml

# 初始化本地Git仓库
git init

# 将本地仓库与远程的GitHub仓库关联起来
git remote add origin https://github.com/ischemci/book-corner-uml.git

# 创建README.md文件
echo "# 图书角管理系统 UML 设计" > README.md
echo "本项目包含"图书角"管理系统的用例图和类图。" >> README.md

# 查看当前文件状态
git status

# 将README.md文件添加到暂存区
git add README.md

# 进行第一次提交
git commit -m "feat: initialize project with README"

# 如果远程仓库是空的，可能需要先拉取或设置上游分支
git branch -M main
git push -u origin main
