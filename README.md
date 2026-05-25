# AC3 Dataset – Citation Function Classification

This repository contains the **AC3 dataset** introduced in the following paper:

> Vodička, D., Kral, P., Cerisara, C., & Šmíd, J. (2026).  
> *Large Language Models for Citation Function Classification*.  
> In Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026) (pp. 2430–2439).  
> European Language Resources Association (ELRA).  
> https://doi.org/10.63317/4sb25z5kxz3q

---

# Citation

If you use this dataset in your research, please cite:

```bibtex
@inproceedings{vodika-etal-2026-large,
  title = {Large Language Models for Citation Function Classification},
  author = {Vodička, Daniel and Kral, Pavel and Cerisara, Christophe and Šmíd, Jakub},
  booktitle = {Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)},
  month = {May},
  year = {2026},
  pages = {2430--2439},
  address = {Palma, Mallorca, Spain},
  publisher = {European Language Resources Association (ELRA)},
  editor = {Piperidis, Stelios and Bel, Núria and van den Heuvel, Henk and Ide, Nancy and Krek, Simon and Toral, Antonio},
  doi = {10.63317/4sb25z5kxz3q},
  abstract = {Citation function classification plays a crucial role in understanding the relationships between scientific publications and advancing bibliometric analysis. This study presents one of the first comprehensive evaluations of multiple state-of-the-art (SOTA) large language models (LLMs) for citation function classification, achieving new SOTA results on the ACL-ARC dataset. We systematically compare five models (Mistral 7B, Orca 2-7B, LLaMA 3.1-8B, Falcon 7B, and SciBERT) across zero-shot, few-shot, and fine-tuning approaches. Our fine-tuned Falcon 7B model achieves a 73,3% macro F1 score on ACL-ARC, representing a significant improvement over previous methods. Additionally, we introduce AC3, a novel dataset featuring a seven-category annotation scheme that distinguishes between neutral acknowledgments and explicit evaluative stances (more opinion-oriented citations – criticizing, complimenting, contradicting). The dataset is implemented across four context extraction variants to systematically evaluate the impact of contextual scope on classification performance. We also provide detailed analysis of model performance, experimental configurations, and limitations to guide future research in this domain. To our knowledge, this is one of the first studies dedicated to comprehensive model comparison for citation function classification, addressing a gap identified in recent surveys.}
}
