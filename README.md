# Jianbin Chen 个人网站

主页：https://damonuc.github.io/

网站沿用 Academic Pages 模板。此仓库是线上网站的源文件。

## 日常修改入口

| 内容 | 文件 |
| --- | --- |
| 首页介绍和联系方式 | `_pages/about.md` |
| 研究标题、介绍、链接 | `_pages/research.md` |
| CV 网页文字 | `_pages/cv.md` |
| 下载的简历 PDF | `files/Jianbin_Chen_CV.pdf` |
| 侧栏姓名、邮箱、简介 | `_config.yml` 中的 `author:` |
| 顶部导航 | `_data/navigation.yml` |
| 新照片 | 放入 `images/`，然后在 `author:` 下设置 `avatar: "照片文件名.jpg"` |

首页正文邮箱与侧栏邮箱是两个位置；修改邮箱时一起检查。CV 网页与下载的 PDF 也是两份独立内容。

## 更新新简历

把新 PDF 命名为 `Jianbin_Chen_CV.pdf`，放入 `files/` 替换旧版，不需要改下载链接。

## 修改文字

打开 `.md` 文件，通常只修改第二条 `---` 后的正文。`##` 表示小标题，`**文字**` 表示加粗，`[文字](网址)` 表示链接。开头的 `layout` 和 `permalink` 通常不要更改。

## 上传并查看结果

保存修改后，在此仓库目录运行：

```bash
git add .
git commit -m "Update website"
git push origin main
```

在 https://github.com/damonuc/damonuc.github.io/actions 查看最新 Pages 任务。绿色勾表示发布成功，然后打开主页；仍显示旧内容时强制刷新。

## 不必日常修改的文件

- `_layouts/`、`_includes/`：原模板页面结构与组件。
- `_sass/`、`assets/`：原模板样式、图标与交互脚本。
- `_data/ui-text.yml`：模板按钮等界面文字。
- `Gemfile`：网站构建依赖；`package.json`：模板脚本的维护工具。
- `images/` 内 favicon 等文件：浏览器网站图标。
- `LICENSE`：原模板许可，须保留。

这些底层文件保留模板的通用能力，不代表每项功能当前都已启用。请不要仅凭名称删除。

## 本次已清理

多作者示例数据、JSON CV 数据及其独立模板和转换脚本、示例博客/论文/教学/报告/作品集、示例 PDF 和图片、地图演示和自动化、容器配置、上游反馈模板与教程页已删除。当前内容页面只有首页、Research、CV 和 404。

中文维护说明不会作为网站页面发布。模板来源：https://github.com/academicpages/academicpages.github.io
