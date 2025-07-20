# Test
Test some operations

1. GitHub 网页端上传文件
   <p>
   1.1 步骤: 仓库页面 → Add file → Upload files → 从文件资源管理器 OR IDEA 拖拽文件( 文件夹、单个文件 )上传到仓库
   <p>
   1.2 上传的文件如果和仓库已有文件路径相同,会被视为相同文件,上传失败
   <p>
   1.3 网页端只能重命名文档( .txt, .md, .java ... )而不能重命名文件夹
   <p>
   1.4 网页端似乎不可以移动文件夹的文件到另一个文件夹
2. 分支
   <p>
   2.1 新建分支: 会把 main 分支上的文件复制一份到新分支 => 1 个项目多个分支相当于平行宇宙,也可以看成 1 个仓库使用多个分支就相当于多个仓库了
   <p>
   2.2 修改一个分支不会影响、同步另一个分支，比如修改 new-branch 分支的 README.md，不会将 main 分支的 README.md 同步修改
   <p>
   2.3 合并分支: Pull requests → New pull request → create pull request → 没有检查出冲突的话就可以进行 Merge pull request → 2 个分支的文件合并在一起
   <p>
   2.4 项目文件夹里面至少添加 1 个占位文件( 如 .gitkeepd 或 README.md )，确保目录被 Git 跟踪，否则合并分支时可能会忽略该项目文件夹
3. 删除文件: 点击某个文件 → 进去后，可以点击右上部分的 3 个点 → delete directory → 会删除当前页面所有文件
4. 补充仓库的 .gitignore 文件后，拖拽文件上传仍然不会忽略某些文件( out/ 文件夹、.iml 文档 )，不过上传文件夹时，网页会把它拆成多份文件，可以手动删除
5. 使用 MarkDown 语法完善 README.md 文档
6. 
   
