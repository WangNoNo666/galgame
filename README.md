# 两款 OI 题材视觉小说

在线玩：
- **机房里的 26 度**（XTBT × lzy）→ `lzy/`　※ 在线版使用**柚子社风格 ADV 外壳**（固定 16:9 舞台、底部文字窗、右键菜单、语音朗读、按住 Ctrl 快进、外观面板）
- **大麦子**（XTBT × mzt）→ `mzt/`　※ 同样是 ADV 外壳（语音 / Ctrl 快进）

## 是什么

两个单文件 HTML 视觉小说，纯静态、零依赖、无外部资源（连立绘和界面都是内联 SVG/CSS）：

- 点击 / 空格推进，自动播放、快进、历史记录
- 选项与心动值（影响结局与彩蛋解锁）
- 3 个本地存档位（`localStorage`）
- 结局一览与彩蛋

## 目录

```
index.html          入口页（两张卡片）
lzy/index.html      机房里的 26 度
lzy/preview/*.png   截图
mzt/index.html      大麦子
mzt/preview/*.png   截图
.nojekyll           让 GitHub Pages 原样发布（跳过 Jekyll）
```

## 本地打开

直接双击 `index.html`，或在目录里起一个静态服务器：

```bash
python -m http.server 8000
```

## 部署到 GitHub Pages

把本目录推到任意仓库的默认分支，在 **Settings → Pages** 里把 Source 设为 `Deploy from a branch` + `/(root)` 即可。
若是用户站点仓库 `<用户名>.github.io`，推送后无需任何设置，直接访问 `https://<用户名>.github.io/`。

## 说明

人物、情节、账号均为虚构，与现实中的任何真实人物或账号无关。
