# UNICBench: 首个针对大模型的图文音跨模态统一计数基准

<p align="center">
<a href="[https://github.com/your-username/UNICBench](https://www.google.com/search?q=https://github.com/your-username/UNICBench)"><img src="[https://img.shields.io/badge/Status-Coming%20Soon-orange](https://www.google.com/search?q=https://img.shields.io/badge/Status-Coming%2520Soon-orange)" alt="Status"></a>
<a href="[https://cvpr.thecvf.com/](https://cvpr.thecvf.com/)"><img src="[https://img.shields.io/badge/Conference-CVPR%202026-blue](https://www.google.com/search?q=https://img.shields.io/badge/Conference-CVPR%25202026-blue)" alt="Conference"></a>
</p>

## 📣 最新消息 (News)

* **[2026-02-25]** 仓库已创建！我们正在加紧整理代码、数据集及评估工具包，敬请期待！
* **[2026-02-21]** 我们的论文已被 **CVPR 2026** 接收！ 🎉

---

## 🔍 摘要 (Abstract)

计数是多模态大语言模型（MLLMs）的核心认知能力，但此前缺乏一个能够严谨评估图像、文本和音频跨模态计数能力的统一基准。 本文提出了 **UNICBench**，这是一个包含准确真实标签、确定性数值解析和分层报告功能的统一多模态、多层级计数基准测试及评估工具包。

该基准涵盖：

* **5,300 张图像** (5,508 个问答)
* **872 份文档** (5,888 个问答)
* **2,069 段音频** (2,905 个问答)

所有样本均根据**三级能力分类体系**（模式 L1、语义 L2、推理 L3）和难度标签进行了标注。

---

## 🛠️ 即将发布 (Upcoming Features)

我们正致力于发布以下内容：

* [ ] **数据集 (Data)**：涵盖图、文、音三大模态的完整 UNICBench 数据集。
* [ ] **评估工具包 (Evaluation Toolkit)**：用于确定性数值解析和分层报告的标准协议。
* [ ] **评测模型 (Models)**：针对 45 款主流 MLLMs 的评测脚本与适配器配置。
* [ ] **论文 (Paper)**：ArXiv 版本及补充材料。

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

