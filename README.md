# AI 生成 PPT 及海报 Prompt 开源版

这是一个专门用来把论文、报告、课程材料、商业方案、项目文档等内容，整理成适合 AI 生成 PPT 和海报图片的提示词仓库。

推荐优先使用 `GPT-image-2`，因为它对中文文字、版式理解和整体设计语言的把握通常更稳，更适合做正式感较强的 PPT 和海报页面。

它更偏向正式、现代、信息密度可控的视觉表达，目标是让生成出来的页面更接近杂志感、编辑感和信息图感。尤其是 PPT 页面，会主动预留参考材料里的图表、表格、截图和流程图位置，方便后续再手动替换进去。

它的目标很单纯：

- 先梳理材料主线，再谈版式
- 如果有模板，就先分析模板风格
- 如果没有模板，就使用默认的杂志海报编辑风
- 先给出完整设计方案，确认后再生成图片
- 第一次优先做 9 页九宫格预览
- 正式生成时每批最多 10 页
- PPT 页面会尽量预留图表、表格和原文截图的位置，方便后期补图

## 效果示意

横版适合 PPT，竖版适合海报。这个目录里的示例图已经按尺寸分成两组：

- 横版：10 张
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

<p align="center">
  <img src="assets/showcase/landscape/05.png" alt="横版示例 5" width="48%" />
  <img src="assets/showcase/landscape/06.png" alt="横版示例 6" width="48%" />
</p>

<p align="center">
  <img src="assets/showcase/landscape/07.png" alt="横版示例 7" width="48%" />
  <img src="assets/showcase/landscape/08.png" alt="横版示例 8" width="48%" />
</p>

<p align="center">
  <img src="assets/showcase/landscape/09.png" alt="横版示例 9" width="48%" />
  <img src="assets/showcase/landscape/10.png" alt="横版示例 10" width="48%" />
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
- 海报与信息图

## 仓库内容

- [`prompt.md`](prompt.md)：可直接复制使用的完整提示词
- [`assets/showcase/landscape/`](assets/showcase/landscape/)：横版示意图
- [`assets/showcase/portrait/`](assets/showcase/portrait/)：竖版示意图
- [`LICENSE`](LICENSE)：开源协议
- 示例图均为整理后的样例素材，仅作效果展示

## 适用模型

这套 prompt 主要面向 `GPT-image-2` 这类图像生成场景设计，尤其适合生成正式的 PPT 单页图、海报图和信息图。

如果使用 ChatGPT 网页端或手机端，也可以直接把 `prompt.md` 里的内容复制进去，再补充材料和模板，让模型先输出设计方案，再继续生成图片。

## 使用方式

1. 打开 [`prompt.md`](prompt.md)
2. 将材料和模板一并提供给模型
3. 先让模型输出逐页设计方案
4. 确认后，再开始批量生成图片

## 默认视觉风格

如果没有提供模板，就使用以下方向：

- Editorial Design
- Swiss Poster
- Bold Typography
- Asymmetric Layout
- Print Magazine
- High Contrast

整体气质偏正式、克制、有秩序，不走可爱风，也不走网页风。

## 说明

- 这不是一个 PPT 生成程序仓库，而是一个 prompt 开源仓库。
- 示例图仅用于展示效果，不代表固定模板。
- 这套提示词的核心价值是稳定输出高质量的 PPT 和海报图片；后续如果要进一步自动化，可以再把它封装成工作流或工具。

## 许可证

本仓库采用 `MIT License`，见 [`LICENSE`](LICENSE)。
