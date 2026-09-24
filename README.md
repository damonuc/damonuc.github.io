# Jianbin Chen 个人网站

主页：https://damonuc.github.io/

网站沿用 Academic Pages 模板。此仓库是线上网站的源文件。

## 日常修改入口

| 内容 | 文件 |
| --- | --- |
| 首页介绍和联系方式 | `_pages/about.md` |
| 研究标题、介绍、链接 | `_pages/research.md` |
| TA 经历和教学培训 | `_pages/teaching.md` |
| CV 页面预览和下载链接 | `_pages/cv.md` |
| 下载的简历 PDF | `files/Jianbin_Chen_CV.pdf` |
| 侧栏姓名、邮箱、简介 | `_config.yml` 中的 `author:` |
| 顶部导航 | `_data/navigation.yml` |
| 新照片 | 放入 `images/`，然后在 `author:` 下设置 `avatar: "照片文件名.jpg"` |

首页正文邮箱与侧栏邮箱是两个位置；修改邮箱时一起检查。CV 页面直接预览下载链接所指向的同一份 PDF，不再单独维护文字版履历。

## 更新新简历

把新 PDF 命名为 `Jianbin_Chen_CV.pdf`，放入 `files/` 替换旧版，不需要改预览或下载链接。推送并部署完成后，网页预览和下载都会更新。

如果使用不同文件名，请修改 `_pages/cv.md` 中 `assign cv_url` 那一行的路径；预览与两个链接共用这一个设置。手机无法显示内嵌 PDF 时，可点击新窗口打开链接。

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

多作者示例数据、JSON CV 数据及其独立模板和转换脚本、示例博客/论文/教学/报告/作品集、示例 PDF 和图片、地图演示和自动化、容器配置、上游反馈模板与教程页已删除。当前内容页面为首页、Research、Teaching、CV 和 404。

中文维护说明不会作为网站页面发布。模板来源：https://github.com/academicpages/academicpages.github.io

## 添加个人照片

1. 选择本人照片，建议 JPG 或 PNG，裁成方形或接近方形。
2. 将照片命名为 `profile.jpg`，放进 `images/`（如果是 PNG，用 `profile.png`，不要只改后缀）。
3. 打开 `_config.yml`，在 `author:` 下找到 `# avatar: "profile.jpg"`，去掉开头的 `#` 和其后的一个空格，保留与 `name:` 相同的两空格缩进。如果是 PNG，填写 `profile.png`。
4. 保存、提交、推送；部署后照片会出现在 About 和其他显示个人侧栏的页面左侧。

未放入照片前保持该行注释，页面不会显示破损图片。Teaching 的具体课程、学校、学期与职责尚待补充；不要把 TA 自动表述为课程主讲教师。
