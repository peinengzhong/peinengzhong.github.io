# peinengzhong.github.io

个人学术主页，通过 [GitHub Pages](https://peinengzhong.github.io/) 发布。

## 目录结构

```
.
├── index.html              # 站点入口（GitHub Pages 根目录）
├── README.md
└── assets/
    ├── css/
    │   └── main.css        # 样式
    ├── js/
    │   └── main.js         # 交互（灯箱等）
    └── images/
        ├── profile/        # 头像、个人形象
        ├── news/           # News 相册
        └── honors/         # 荣誉证书
```

## 本地预览

```bash
python3 -m http.server 8080
```

浏览器打开 `http://localhost:8080`。

## 维护说明

- 新增 News 图片：放入 `assets/images/news/`，并在 `index.html` 的 `.gallery-track` 中引用（需成对添加以实现无缝滚动）。
- 新增荣誉证书：放入 `assets/images/honors/`，在 Honors 区块增加 `.honor-card`。
- 样式与脚本分别编辑 `assets/css/main.css` 与 `assets/js/main.js`。
