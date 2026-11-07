# Personal SVG Infographics

面向研究、设计与汇报的可编辑 SVG 信息图 Skill。将内容关系转化为叙事插画、比较图、流程图与结构图，而不是套用固定模板。

A text-based agent skill for native, editable SVG infographics, comparison charts, process diagrams and visual research presentations.

## 能做什么

- 按比较、阶段、路径、机制等内容关系选择构图。
- 用与主题有关的插画和小图解解释信息。
- 默认提供暖橙色叙事方向，也支持蓝色图鉴、浅蓝阶段、紫色交互与棕金机制方向。
- 保留文字与矢量图形的可编辑性，并要求渲染检查。
- 修改已有 SVG 时保留已确认的元素。

## 使用

本仓库根目录即 Skill 文件夹：入口为 `SKILL.md`，详细规则位于 `references/`。在支持 Skill 的代理工具中按该工具的方式加载此文件夹；也可以在任务中明确提供本地文件夹路径，要求先读取 `SKILL.md`。本项目没有自动安装脚本或额外运行依赖。

示例请求：

> 使用 personal-svg-infographics，根据以下内容生成 1920×1080 的原生可编辑 SVG。采用暖橙色叙事方向，根据内容选择构图，保留关键事实。生成后渲染检查，交付 SVG 和 PNG 预览，并说明未完成的验证。内容：【你的材料】

渲染和图像检查依赖所用代理环境；仓库本身不附带 SVG 渲染器。Figma 导入效果需实际验证。中文字体的可用性会影响显示与换行。

## 文件结构

```text
personal-svg-infographics/
├── SKILL.md
├── agents/openai.yaml
├── references/
│   ├── visual-language.md
│   ├── layout-system.md
│   └── reference-analysis.md
├── assets/style-examples/README.md
├── CONTRIBUTING.md
└── LICENSE
```

## 参考素材与数据

公开版仅包含文字规则，不附原始视觉参考图片、私人文件路径、真实受访者记录或早期测试作品。用户可以在本地 `assets/style-examples/` 添加自己有权使用的参考图；没有参考图时仍能按文字规则工作。该目录默认忽略图片，避免将个人资料随提交公开。

## 当前范围

这是首个公开候选版本。已完成的样例工作流包括读取内容、生成 SVG、渲染检查和数据核对；尚未在不同代理、渲染器和 Figma 环境中全面测试。不承诺每次输出相同构图或跨应用完全一致的字体显示。

## 贡献与许可

欢迎提供最小复现材料、经过授权或完全虚构的数据以及明确的修改建议，详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

仓库所含规则与文档采用 [MIT](LICENSE) 许可证。用户另行添加的素材及输入资料不因此自动获得 MIT 授权。
