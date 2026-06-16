# liaojingwu20041031.github.io

廖荆武的 GitHub Pages 个人主页，用于展示机器人、嵌入式、物联网和移动端项目能力。

## 内容来源

页面内容根据公开 GitHub 仓库与本地克隆代码整理：

- `ylhb-smart-retail-robot`
- `GX-Intelligent-Logistics-Silver`
- `FloraMind`
- `ylhb-robot-mobile`
- `ROS2-smart-car`
- `Godot_yxkf`
- `naruto-author-skill`

未在仓库或本地资料中找到的个人信息均以“待补充”标注，未编造学校、论文、实习或奖项。

## 本地预览

直接打开 `index.html` 即可预览。也可以启动一个静态服务器：

```bash
python -m http.server 8000
```

然后访问：

```text
http://127.0.0.1:8000
```

## 发布到 GitHub Pages

1. 在 GitHub 创建仓库：

```text
liaojingwu20041031.github.io
```

2. 在本目录初始化并提交：

```bash
git init
git add .
git commit -m "Initial personal homepage"
git branch -M main
git remote add origin https://github.com/liaojingwu20041031/liaojingwu20041031.github.io.git
git push -u origin main
```

3. 启用 Pages：

- 打开仓库 Settings。
- 进入 Pages。
- Source 选择 `Deploy from a branch`。
- Branch 选择 `main`，目录选择 `/root`。
- 保存后等待部署完成。

最终访问地址：

```text
https://liaojingwu20041031.github.io
```

## 后续需要补充

- 将正式简历 PDF 放到根目录并命名为 `resume.pdf`。
- 把 `index.html` 中 Resume 区域的下载链接改为 `resume.pdf`。
- 补充学校、年级、GPA/排名、科研/实习经历、导师推荐展示需要的信息。
- 如有项目演示视频/GIF，可替换 `assets/` 中的项目图片。
