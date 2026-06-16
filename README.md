# liaojingwu20041031.github.io

廖荆武的 GitHub Pages 个人主页，用于展示机器人、嵌入式、物联网、边缘 AI 和移动端项目能力。

## 内容来源

页面内容根据公开 GitHub 仓库、本地克隆代码和正式简历整理：

- `ylhb-smart-retail-robot`
- `GX-Intelligent-Logistics-Silver`
- `FloraMind`
- `ylhb-robot-mobile`
- `ROS2-smart-car`
- `Godot_yxkf`
- `naruto-author-skill`
- `D:\学习文件\课程文件\就业指导\简历\廖荆武-简 历 .docx`

未在仓库或简历中找到的个人信息不写入页面；电话等隐私信息未放在公开主页正文中。

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

## 当前页面内容

- 首页 Hero：姓名、学校、专业方向、GPA/排名和国家级奖项概览。
- About：教育背景、技术路线、微专业、证书和学生工作。
- Skills：机器人系统、嵌入式控制、视觉与 AI、应用工具。
- Projects：5 个 GitHub 代表项目。
- Experience：教育背景、竞赛奖项、学生工作和工程项目经历。
- Resume：下载 `resume.docx`。
- Contact：邮箱和 GitHub。

## 后续可继续补充

- 如需要 PDF 下载入口，可将简历另存为 `resume.pdf` 并把 Resume 按钮链接改为 `resume.pdf`。
- 如有项目演示视频/GIF，可继续替换 `assets/` 中的项目图片。
