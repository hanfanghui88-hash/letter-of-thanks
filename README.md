# 使用说明

这一版把两张照片直接打包进了 index.html 里面（base64 内嵌），
所以现在只有 index.html 这一个文件，不需要额外的 images 文件夹了，
不管是本地打开、预览还是传到 GitHub Pages 都会自动显示背景轮播。

## 上传到 GitHub 的步骤

1. 把 index.html 上传到你的仓库 `hanfanghui88-hash/letter-of-thanks` 根目录
   （直接覆盖旧文件即可，之前的 images 文件夹可以删掉不要了）。
2. 打开 GitHub 仓库 → Settings → Pages，Source 选对应分支 / root，保存。
3. 几分钟后即可通过下面这个链接访问：
   https://hanfanghui88-hash.github.io/letter-of-thanks/

## 之后想换/加照片

打开 index.html，搜索 `background-image:url('data:image/jpeg;base64,`，
把对应那一长串 base64 换成你新照片转出来的 base64 即可（把 jpeg 换成 png 记得同步改 `image/jpeg` 为 `image/png`）。
如果嫌麻烦，也可以随时把新照片发给我，我直接帮你重新打包。
