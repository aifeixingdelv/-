## 📅2023.10.15
1. 将需要上传大文件model.h5放入本地仓库，然后在命令行输入 ``` git status ```
2. 从官网下载GIT LFS, 安装好之后在本地目录仓库下执行以下命令 ``` git lfs track "*.h5" ```,，此时会自动在项目目录中的.gitattributes文件中添加 *.h5 filter=lfs diff=lfs merge=lfs -text“
3. 再按照Desktop端常规步骤上传即可