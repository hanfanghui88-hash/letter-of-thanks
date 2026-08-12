# 使用说明

图片已经放进 `images` 文件夹了（photo1.jpg、photo2.jpg，就是你发我的两张毕业照），
背景会在这两张之间来回淡入淡出循环播放，不用再改。

如果之后想换图或加图，只要把文件替换/新增到 `images` 里，
再去 index.html 里 `.bg-slide` 那部分照着格式加一行 `<div class="bg-slide" ...>`，
并把 CSS 里 `animation: bgCycle 16s` 的秒数按图片数量等比调大（比如3张调成24s）即可。

## 上传到 GitHub 的步骤

1. 把这个文件夹里的 `index.html` 和 `images` 文件夹（含两张照片）一起上传到你的仓库
   `hanfanghui88-hash/letter-of-thanks` 的根目录，分支用于 GitHub Pages（一般是 main）。
2. 打开 GitHub 仓库 → Settings → Pages，Source 选 main 分支 / root，保存。
3. 几分钟后即可通过下面这个链接访问：
   https://hanfanghui88-hash.github.io/letter-of-thanks/
