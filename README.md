# 汇报型 PPT 图片 Prompt 开源版

这是一个专门用来把论文、报告、课程材料、商业方案、项目文档等内容，整理成“汇报型 PPT 图片”的提示词仓库。

它的目标很单纯：

- 先梳理材料主线，再谈版式
- 如果有模板，就先分析模板风格
- 如果没有模板，就使用默认的杂志海报编辑风
- 先给出完整设计方案，确认后再生成图片
- 第一次优先做 9 页九宫格预览
- 正式生成时每批最多 10 页

## 效果示意

横版适合 PPT，竖版适合海报。这个目录里的示例图已经按尺寸分成两组：

- 横版：4 张
- 竖版：12 张

### 横版（PPT）

<p align="center">
  <img src="assets/showcase/landscape/01.png" alt="横版示例 1" width="48%" />
  <img src="assets/showcase/landscape/02.png" alt="横版示例 2" width="48%" />
</p>

<p align="center">
  <img src="assets/showcase/landscape/03.png" alt="横版示例 3" width="48%" />
  <img src="assets/showcase/landscape/04.png" alt="横版示例 4" width="48%" />
</p>

### 竖版（海报）

<p align="center">
  <img src="assets/showcase/portrait/01.png" alt="竖版示例 1" width="31%" />
  <img src="assets/showcase/portrait/02.png" alt="竖版示例 2" width="31%" />
  <img src="assets/showcase/portrait/03.png" alt="竖版示例 3" width="31%" />
</p>

<p align="center">
  <img src="assets/showcase/portrait/04.png" alt="竖版示例 4" width="31%" />
  <img src="assets/showcase/portrait/05.png" alt="竖版示例 5" width="31%" />
  <img src="assets/showcase/portrait/06.png" alt="竖版示例 6" width="31%" />
</p>

<p align="center">
  <img src="assets/showcase/portrait/07.png" alt="竖版示例 7" width="31%" />
  <img src="assets/showcase/portrait/08.png" alt="竖版示例 8" width="31%" />
  <img src="assets/showcase/portrait/09.png" alt="竖版示例 9" width="31%" />
</p>

<p align="center">
  <img src="assets/showcase/portrait/10.png" alt="竖版示例 10" width="31%" />
  <img src="assets/showcase/portrait/11.png" alt="竖版示例 11" width="31%" />
  <img src="assets/showcase/portrait/12.png" alt="竖版示例 12" width="31%" />
</p>

## 这个 Prompt 适合什么

- 论文答辩
- 项目汇报
- 商业方案
- 课程展示
- 政策与研究报告

## 仓库内容

- [`prompt.md`](prompt.md)：可直接复制使用的完整提示词
- [`assets/showcase/landscape/`](assets/showcase/landscape/)：横版示意图
- [`assets/showcase/portrait/`](assets/showcase/portrait/)：竖版示意图
- 这些示意图全部来自你提供的 `D:\资料\GPT生成的图片\示例效果` 样图

## 使用方式

1. 打开 [`prompt.md`](prompt.md)
2. 把你的材料和模板一起发给模型
3. 先让模型输出逐页设计方案
4. 你确认后，再开始批量生成图片

## 默认视觉风格

如果没有提供模板，就使用以下方向：

- Editorial Design
- Swiss Poster
- Bold Typography
- Asymmetric Layout
- Print Magazine
- High Contrast

整体气质偏正式、克制、有秩序，不走可爱风，也不走网页风。

## 提交校验

仓库里提供了一个最小的提交信息校验 Hook。启用方式：

```powershell
git config core.hooksPath .githooks
```

提交信息建议使用 Conventional Commits，例如：

```text
docs: 补充开源说明
```

## 说明

- 这不是一个 PPT 生成程序仓库，而是一个 prompt 开源仓库。
- 示例图仅用于展示效果，不代表固定模板。
- 如果你要把它发布到 GitHub，可以直接把这个文件夹作为一个独立仓库推上去。
