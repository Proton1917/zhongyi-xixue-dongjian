# 项目说明与日志

## 项目定位

- 本项目是“近代西学东渐下的中医转型”课程展示页。
- 目标部署形式为 GitHub Pages 静态站点，入口文件为 `index.html`。
- 页面风格采用近代史纲要相关的朱红、纸张、档案扫描与展陈视觉。

## 当前结构

- `index.html`：完整静态页面，包含 HTML、CSS 与少量滚动交互脚本。
- `assets/zhongxi-huitong-cover.jpg`：唐宗海《中西汇通医经精义》扫描图，用作页面视觉资产。
- `assets/acupuncture-chart.jpg`：针灸图谱，用于“影像档案”区。
- `assets/medicine-chest.jpg`：中医药箱图像，用于“影像档案”区。
- `assets/mukden-hospital-1900.jpg`：1900 年奉天医院图像，用于“影像档案”区。
- `assets/republic-era-medicine-debate.mp4`：用户提供的《民国时代的中西医之争》剪辑视频，用于“影像档案”区。
- `assets/republic-era-medicine-debate-poster.jpg`：从上述视频截取的封面图，用作视频区域兜底背景。

## 维护注意

- 继续保持纯前端静态实现，便于 GitHub Pages 直接部署。
- 文案应保持简明、连贯、有历史依据，避免堆砌长段论文式表述。
- 如新增参考文献，优先加入页面末尾“参考文献”区，并使用公开可访问链接。

## 2026-05-30 记录

- 创建课程展示页 `index.html`。
- 下载并使用《中西汇通医经精义》公有领域扫描图。
- 页面内容围绕西学东渐、中西汇通、民国医政、国医论争与中医现代转型展开。
- 追加“影像档案”区，先嵌入 Internet Archive 影像 `Bits of China`，并补充针灸图谱、中医药箱、奉天医院历史图像。
- 根据用户反馈调整文案流程：不由本助手直接改写具体句子，而是向 Cherry Studio 中的 `anthropic/claude-opus-4.1 | OpenRouter` 提交“页面槽位 + 大致意思/事实点”，再将其生成的对应句子回填到 `index.html`。
- 按用户要求将“影像档案”区视频替换为本地《民国时代的中西医之争》剪辑版，并移除未使用的 `Bits of China` 缩略图资产。
