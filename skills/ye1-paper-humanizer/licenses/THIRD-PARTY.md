# 第三方代码与许可

`scripts/check_marked_manuscript.py` 在上游版本基础上经本项目修改，增加普通批注及基本锚点保留核查，并明确主文档文字核验的限制；保留上游版权与 MIT 许可。

- `scripts/check_rewrite_fidelity.py`、`scripts/build_marked_manuscript.py` 和 `scripts/check_marked_manuscript.py` 来自 [Aperivue/medsci-skills v6.2.0](https://github.com/Aperivue/medsci-skills/releases/tag/v6.2.0)，提交 `cc462bc2069064b557c2fea12a1f83ed1fe67f66`，分别位于上游 `skills/humanize/scripts/` 和 `skills/sync-submission/scripts/`，遵循 [MEDSCI-MIT.txt](MEDSCI-MIT.txt)。
- `scripts/check_medical_fidelity.py` 是 [ecpp/humanize-medical-writing](https://github.com/ecpp/humanize-medical-writing/tree/5eceb6e4fd614e542f9e4f352cb717f07a54b30a) 的 `scripts/check_fidelity.py`，未修改代码，仅改名；遵循 [MEDICAL-HUMANIZER-MIT.txt](MEDICAL-HUMANIZER-MIT.txt)。
- `scripts/check_academic_invariants.py` 是 [Yila-AI academic-humanizer](https://github.com/Yila-AI/awesome-research-skills/tree/9457733ecf6dbef4cad8debf2e58cc3bbd378e79/skills/academic-humanizer) 的 `scripts/check_invariants.py`，未修改代码，仅改名；自然化指引参考该项目。随包保留 [Apache 2.0 许可](ACADEMIC-APACHE-2.0.txt)与[第三方声明](ACADEMIC-THIRD-PARTY.md)。
- `scripts/ye1_word.py`、`scripts/ye1_compare.py` 和 `scripts/ye1_pdf.py` 是 Ye1 为本项目编写的辅助代码。
