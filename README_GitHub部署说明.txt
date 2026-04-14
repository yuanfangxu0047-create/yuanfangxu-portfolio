GitHub Pages 部署建议：

1. 将当前文件夹中的全部文件上传到一个 GitHub 仓库根目录。
2. 仓库名建议使用：yuanfangxu-portfolio
3. 在仓库 Settings -> Pages 中，选择：Deploy from a branch
4. 分支选择：main；目录选择：/(root)
5. 部署完成后，网址通常为：
   https://你的GitHub用户名.github.io/yuanfangxu-portfolio/
6. 二维码入口会自动根据当前 GitHub Pages 地址生成，不需要手动修改域名。

文件清单：
- index.html：主页
- qr/index.html：二维码入口页
- yuan_fangxu_resume.docx：简历下载文件
- .nojekyll：GitHub Pages 静态站点标记
- _redirects：可忽略，对 GitHub Pages 不生效
