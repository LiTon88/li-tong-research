# Li Tong 科研项目网页

论文项目页：**Planning for Dynamic Aerial Grasping Based on Discrete Variational Mechanics and Complementarity Constraints**。

## 在 Windows 本地打开

1. 解压 ZIP 文件。
2. 双击 `start-local.bat`，或直接双击 `index.html`。
3. 网页会在默认浏览器中打开。

这是纯 HTML/CSS 项目，不需要安装 Node.js、npm 或其他依赖。

## 修改网页

- 修改文字和页面结构：编辑 `index.html`。
- 修改颜色、字体和布局：编辑 `styles.css`。
- 将图片和视频放入 `assets/` 文件夹，然后在 `index.html` 中替换占位区域。

推荐使用 Visual Studio Code 编辑。修改后保存文件，刷新浏览器即可看到结果。

## 使用本地服务器（可选）

如果电脑安装了 Python，可在项目目录运行：

```powershell
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 发布到 GitHub Pages

项目附带 `.github/workflows/pages.yml`。上传到 GitHub 仓库后，在 **Settings → Pages** 中将 Source 设置为 **GitHub Actions**。之后每次推送到 `main` 都会自动更新网站。

预期网址：`https://liton88.github.io/li-tong-research/`

页面结构参考 [RoboDuet](https://locomanip-duet.github.io/)，实现代码和飞行机械臂内容均为独立编写。
