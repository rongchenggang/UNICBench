**"UNICBench: UNIfied Counting Benchmark for MLLM"** 的官方代码仓库。

## 📣 最新消息 (Latest News)

* **[2026-02-25]** 仓库已创建！我们正在整理代码、数据集和评估工具包，敬请期待！
* **[2026-02-21]** 我们的论文已被 **CVPR 2026** 接收！ 🎉

---

## 🔍 摘要 (Abstract)

计数是多模态大语言模型（MLLMs）的核心能力，但目前仍缺乏统一的计数数据集来跨图像、文本和音频模态对其进行严谨评估。 我们提出了 UNICBench，这是一个统一的多模态、多层级计数基准和评估工具包，具有准确的真实标签、确定性的数值解析和分层报告功能。 该语料库包含 5,300 张图像（5,508 个问答）、872 份文档（5,888 个问答）和 2,069 段音频（2,905 个问答），并标注了三级能力分类体系和难度标签。 在具有固定数据划分、提示词、随机种子以及特定模态匹配规则的标准协议下，我们跨模态评估了 45 个最先进的 MLLM。 结果显示，模型在一些基础计数任务上表现强劲，但在推理任务和最难的数据划分中存在显著差距，突显了长尾错误以及提升通用计数能力的巨大空间。 UNICBench 为测量提供了严谨且具可比性的基础，并提供了公共工具包以加速研究进展。 

---

## 🛠️ 即将发布 (Upcoming Features)

我们正致力于发布以下内容：

* 
**数据集 (Data)**：涵盖图像、文本、音频三大模态的完整 UNICBench 数据集。 


* 
**评估工具包 (Evaluation Toolkit)**：包含确定性数值解析和分层报告的标准协议。 


* 
**模型评测 (Models)**：针对 45 款主流 MLLMs 的评测脚本与适配器配置。 


* **论文 (Paper)**：ArXiv 版本及补充材料。

---

## 🖋️ 引用 (Citation)

如果您在研究中使用了我们的工作，请考虑引用：

```bibtex
@inproceedings{rong2026unicbench,
  title={UNICBench: UNIfied Counting Benchmark for MLLM},
  author={Rong, Chenggang and Han, Tao and Zhao, Zhiyuan and Fan, Yaowu and Wan, Jia and Guo, Song and Yuan, Yuan and Gao, Junyu},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}

```

---

## 📮 联系我们 (Contact)

如有任何疑问，请提交 Issue 或联系作者。
