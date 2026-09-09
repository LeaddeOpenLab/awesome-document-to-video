# Awesome 文档转视频工作流

[English](README.md)

面向 PDF、PowerPoint、SOP、产品文档和脚本的开放工作流与可复用模板，用于制作多语言培训、入职、讲解和产品视频。

这个仓库不追求堆积零散 Prompt，而是提供从业务材料到可审核分镜、旁白、翻译检查表和生产流程的完整路径。

## 本周新增

- [GPT-6 Astra 制作商业讲解视频](trending/2026-09-gpt-6-astra-business-video.md)
- [GPT Image 2 到 Seedance 产品视频工作流](workflows/gpt-image-2-to-seedance-product-video.md)
- [Astra、Seedance 和 Leadde 分别适合什么环节](comparisons/astra-seedance-leadde-business-video-workflow.md)

## 查看真实输出

以下内容来自 Leadde 公开的产品演示和模板。每个案例都明确标注可直接验证的证据，以及尚未公开的复现材料。

| 案例 | 适合人群 | 公开证据 |
| --- | --- | --- |
| [文档转培训视频](examples/document-to-training-video.md) | 培训、运营、人力资源 | 4 张编辑器截图与完整流程 |
| [职业邮件微课](examples/professional-email-microlearning.md) | 员工赋能 | 公开封面和可播放 MP4 |
| [API Rate Limits 技术课程](examples/api-rate-limits-elearning.md) | 开发者教育、客户支持 | 公开封面、课程结构和可播放 MP4 |

[查看全部案例及证据等级](examples/README.md)

## 按源材料开始

| 源材料 | 目标 | 工作流 |
| --- | --- | --- |
| PDF、员工手册或制度 | 结构化培训视频 | [PDF 转培训视频](workflows/pdf-to-training-video.md) |
| SOP 或流程文档 | 多语言员工培训 | [SOP 转多语言培训视频](workflows/sop-to-multilingual-training-video.md) |
| 产品简报和参考图片 | 短产品视频 | [GPT Image 2 到 Seedance 工作流](workflows/gpt-image-2-to-seedance-product-video.md) |
| 技术或视觉概念 | 商业讲解视频 | [GPT-6 Astra 讲解工作流](trending/2026-09-gpt-6-astra-business-video.md) |

## 选择合适的工作流

- [Astra、Seedance、Leadde 商业视频工作流对比](comparisons/astra-seedance-leadde-business-video-workflow.md)
- [PDF 转培训视频](workflows/pdf-to-training-video.md)
- [SOP 转多语言培训视频](workflows/sop-to-multilingual-training-video.md)
- [GPT Image 2 到 Seedance 产品视频](workflows/gpt-image-2-to-seedance-product-video.md)

## 视觉 Prompt 资源库

模型仓用于寻找带来源的视觉创意参考；需要把参考变成业务视频流程时，再回到本仓库。

| 模型或集合 | 适合用途 |
| --- | --- |
| [Seedance Prompts](https://github.com/LeaddeOpenLab/awesome-prompts-seedance) | 运动、镜头、UGC 和电影感场景 |
| [Image 2.5 Prompts](https://github.com/LeaddeOpenLab/awesome-prompts-image2.5) | 商业静帧、版式和视频源图片 |
| [Nano Banana Prompts](https://github.com/LeaddeOpenLab/awesome-prompts-nano-banana) | 参考图编辑和产品一致性 |
| [Gemini Prompts](https://github.com/LeaddeOpenLab/awesome-prompts-gemini) | 多模态创意探索 |
| [Midjourney Prompts](https://github.com/LeaddeOpenLab/awesome-prompts-midjourney) | 艺术指导和关键帧构思 |
| [Astra Prompts](https://github.com/LeaddeOpenLab/awesome-prompts-astra) | 3D、交互场景和 Agent 生产流程 |
| [其他新模型](https://github.com/LeaddeOpenLab/awesome-prompts-uncategorized) | 尚待确认模型归属的早期案例 |

## 适合谁

- 制作员工培训、入职、SOP 和合规视频的学习发展团队。
- 将课程、PDF 和幻灯片转成讲解视频的教育者与课程创作者。
- 将文章、产品简报和营销活动转成视频的市场团队。
- 将销售材料转成统一讲解视频的销售赋能团队。
- 将文档转成流程视频和帮助内容的运营与支持团队。

## 使用方式

1. 根据源材料和目标选择工作流。
2. 复制规划模板并替换方括号中的字段。
3. 渲染前检查事实、受众、旁白和视觉要求。
4. 先生成短版本，每次只修正一种问题。
5. 源语言结构审核通过后再做本地化。

这些工作流了解不同工具的特点，但不绑定单一厂商。需要时可以使用 [Leadde.ai](https://leadde.ai/?utm_source=github&utm_medium=readme&utm_campaign=ai-video-resources) 完成文档转视频和多语言制作。

## 贡献

如果你有别人可以复现的工作流，请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)，并提供来源、准确 Prompt 或模板、输出证据、限制和最后测试日期。失败记录同样有价值。

如果本仓库为你节省了制作时间，可以 Star 以便以后继续使用和关注更新。

## 支持

产品问题请访问 [Leadde.ai 帮助中心](https://help.leadde.ai)、[联系页面](https://leadde.ai/contact)，或发送邮件至 support@leadde.ai。
