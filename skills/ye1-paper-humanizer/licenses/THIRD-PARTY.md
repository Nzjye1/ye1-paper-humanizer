# 第三方代码与许可

- 自然化指导参考 [Yila-AI academic-humanizer](https://github.com/Yila-AI/awesome-research-skills/tree/9457733ecf6dbef4cad8debf2e58cc3bbd378e79/skills/academic-humanizer)，保留 [Apache 2.0 许可](ACADEMIC-APACHE-2.0.txt)与[第三方声明](ACADEMIC-THIRD-PARTY.md)。
- `scripts/ye1_word.py`、`scripts/ye1_compare.py` 和 `scripts/ye1_pdf.py` 是 Ye1 为本项目编写的辅助代码。

`scripts/ye1_fidelity_audit.py` 为本项目新编写的本地文本标记核对工具。

`scripts/ye1_compare.py` 和 `scripts/ye1_revision_check.py` 是本次新编写的 Word 比较和修订核查工具，分别依赖本机 Microsoft Word 和 OOXML 文档结构。设计和能力核对时参考了 MedSci 的 Word 比较及修订检查方案；为保留溯源，随包保留 [MEDSCI-MIT.txt](MEDSCI-MIT.txt)。

## 保留的兼容工具

`scripts/check_rewrite_fidelity.py` 来自 MedSci v6.2.0，遵循 [MEDSCI-MIT.txt](MEDSCI-MIT.txt)；`scripts/check_medical_fidelity.py` 来自 [ecpp/humanize-medical-writing](https://github.com/ecpp/humanize-medical-writing/tree/5eceb6e4fd614e542f9e4f352cb717f07a54b30a)，遵循 [MEDICAL-HUMANIZER-MIT.txt](MEDICAL-HUMANIZER-MIT.txt)；`scripts/check_academic_invariants.py` 来自 [Yila-AI academic-humanizer](https://github.com/Yila-AI/awesome-research-skills/tree/9457733ecf6dbef4cad8debf2e58cc3bbd378e79/skills/academic-humanizer)，遵循 [ACADEMIC-APACHE-2.0.txt](ACADEMIC-APACHE-2.0.txt) 和 [ACADEMIC-THIRD-PARTY.md](ACADEMIC-THIRD-PARTY.md)。后两项原脚本只改名。
