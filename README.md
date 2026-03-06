<a href="https://github.com/rongchenggang/UNICBench"><img src="https://img.shields.io/badge/Status-Partially%20Released-orange" alt="Status"></a>
<a href="https://cvpr.thecvf.com/"><img src="https://img.shields.io/badge/Conference-CVPR%202026-blue" alt="Conference"></a>
<a href="https://huggingface.co/datasets/rongchenggang/UNICBench"><img src="https://img.shields.io/badge/🤗%20Dataset-Available-yellow" alt="Dataset"></a>
<a href="https://rongcg5620.github.io/UNICBench-Pages/"><img src="https://img.shields.io/badge/🏆%20Leaderboard-Live-orange" alt="Leaderboard"></a>

Official repository for **"UNICBench: UNIfied Counting Benchmark for MLLM"**.

## 📣 Latest News

* **[2026-03-06]** 🎉 Dataset and leaderboard are now live! Check out our [HuggingFace dataset](https://huggingface.co/datasets/rongchenggang/UNICBench) and [leaderboard](https://rongcg5620.github.io/UNICBench-Pages/). Code and evaluation toolkit coming soon!
* **[2026-02-25]** Repository created! We are organizing the code, dataset, and evaluation toolkit.
* **[2026-02-21]** Our paper has been accepted to **CVPR 2026**! 🎉

---

## 🔍 Abstract

Counting is a core capability of multimodal large language models (MLLMs), yet there remains a lack of unified counting datasets for rigorous evaluation across image, text, and audio modalities. We present UNICBench, a unified multi-modal, multi-level counting benchmark and evaluation toolkit with accurate ground-truth labels, deterministic numerical parsing, and hierarchical reporting capabilities. The corpus contains 5,300 images (5,508 QA pairs), 872 documents (5,888 QA pairs), and 2,069 audio clips (2,905 QA pairs), annotated with a three-level capability taxonomy and difficulty labels. Under a standardized protocol with fixed data splits, prompts, random seeds, and modality-specific matching rules, we evaluate 45 state-of-the-art MLLMs across modalities. Results show that models perform strongly on some basic counting tasks but exhibit significant gaps in reasoning tasks and the most challenging data splits, highlighting long-tail errors and substantial room for improving general counting capabilities. UNICBench provides a rigorous and comparable foundation for measurement and offers a public toolkit to accelerate research progress.

---

## 🚀 Quick Links

* 📦 **Dataset**: [HuggingFace](https://huggingface.co/datasets/rongchenggang/UNICBench)
* 🏆 **Leaderboard**: [Live Leaderboard](https://rongcg5620.github.io/UNICBench-Pages/)
* 📄 **Paper**: Coming soon on ArXiv
* 📧 **Contact**: unicbench@163.com

---

## 🛠️ Features

* **Multi-modal Coverage**: Comprehensive evaluation across Image, Text, and Audio modalities
* **Hierarchical Taxonomy**: Three-level capability classification with difficulty labels
* **Standardized Protocol**: Fixed data splits, prompts, and evaluation metrics
* **Deterministic Parsing**: Accurate numerical extraction and matching rules
* **Public Toolkit**: Evaluation scripts and adapter configurations for 45+ MLLMs (coming soon)

---

## 🖋️ Citation

If you use our work in your research, please consider citing:

```bibtex
@inproceedings{rong2026unicbench,
  title={UNICBench: UNIfied Counting Benchmark for MLLM},
  author={Rong, Chenggang and Han, Tao and Zhao, Zhiyuan and Fan, Yaowu and Wan, Jia and Guo, Song and Yuan, Yuan and Gao, Junyu},
  booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition},
  year={2026}
}
```

---

## 📮 Contact

For any questions, please submit an issue or contact the authors at unicbench@163.com.

---

## 📜 License

This project is licensed under the MIT License.
