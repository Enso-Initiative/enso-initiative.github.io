# Enso Initiative 应手 网站

## 上线步骤（GitHub Pages）
1. 用 ensoinitiative@outlook.com 注册 GitHub，用户名建议用 `ensoinitiative`。
2. 新建一个公开（Public）仓库，名字必须是 `ensoinitiative.github.io`（前半部分要和你的用户名一模一样）。
3. 点 "Add file → Upload files"，把 `index.html` 和 `julia.jpg` 两个文件一起拖进去，点 "Commit changes"。
4. 等一两分钟，打开 https://ensoinitiative.github.io 就能看到网站。
   如果打不开，进仓库的 Settings → Pages，确认 Source 选的是 "Deploy from a branch"、分支是 main。

## 以后怎么改
- 在 GitHub 网页上点开 `index.html`，点铅笔图标就能直接改文字，改完点 "Commit changes"。
- 中英文成对出现：`class="zh"` 是中文，`class="en"` 是英文，两边都要改。
- 加新作品：复制 `<article class="work">` 到 `</article>` 这一整段，粘在它下面，改名字和故事。
- 「探访岩羊」那一节的九张照片，文件名是 `bluesheep-1.jpg` 到 `bluesheep-9.jpg`，和 `index.html` 一起上传；按编号对应 3×3 拼图从左到右、从上到下的位置，想换位置就互换文件名。
- 「探访天云」那一节的七张照片，文件名是 `tianyun-1.jpg` 到 `tianyun-7.jpg`，也要和 `index.html` 一起上传。前两张是竖图，并排放在最上面，换图时尽量用同样比例（3:4）的竖图。
- 换照片：上传一张同名的新 `julia.jpg` 覆盖就行。
