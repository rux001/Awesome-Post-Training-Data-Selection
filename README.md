# Awesome-Post-Training-Data-Selection

A curated list of research papers on data selection methods for instruction tuning and preference alignment of Large Language Models.

## 📑 Table of Contents
- [Instruction Tuning](#instruction-tuning)
- [Preference Alignment Tuning](#preference-alignment-tuning)

---

## Instruction Tuning

### Superfiltering: Weak-to-Strong Data Filtering for Fast Instruction-Tuning
**Authors:** Ming Li, Yong Zhang, Shwai He, Zhitao Li, Hongyu Zhao, Jianzong Wang, Ning Cheng, Tianyi Zhou  
**Venue:** ACL 2024  
**Paper:** [Link](https://aclanthology.org/2024.acl-long.769.pdf)  
**Summary:** Proposes a weak-to-strong filtering approach for efficient instruction tuning data selection based on smaller model and larger model consistency.

### Smaller Language Models are capable of selecting Instruction-Tuning Training Data for Larger Language Models
**Authors:** Dheeraj Mekala, Alex Nguyen, Jingbo Shang  
**Venue:** ACL 2024  
**Paper:** [Link](https://aclanthology.org/2024.findings-acl.623.pdf)  
**Summary:** Demonstrates how smaller models can effectively select training data for larger models.

### MoDS: Model-oriented Data Selection for Instruction Tuning
**Authors:** Qianlong Du, Chengqing Zong, Jiajun Zhang  
**Venue:** arXiv 2023  
**Paper:** [Link](https://arxiv.org/pdf/2311.15653)  
**Summary:** Model-oriented approach to data selection for instruction tuning.

### From Quantity to Quality: Boosting LLM Performance with Self-Guided Data Selection for Instruction Tuning
**Authors:** Ming Li, Yong Zhang, Zhitao Li, Jiuhai Chen, Lichang Chen, Ning Cheng, Jianzong Wang, Tianyi Zhou, Jing Xiao  
**Venue:** NAACL 2024  
**Paper:** [Link](https://aclanthology.org/2024.naacl-long.421.pdf)  
**Summary:** Focuses on quality over quantity through self-guided data selection mechanisms.

### SelectIT: Selective Instruction Tuning for LLMs via Uncertainty-Aware Self-Reflection
**Authors:** Liangxin Liu, Xuebo Liu, Derek F. Wong, Dongfang Li, Ziyi Wang, Baotian Hu, Min Zhang  
**Venue:** NeurIPS 2024  
**Paper:** [Link](https://arxiv.org/pdf/2402.16705)  
**Summary:** Uses uncertainty-aware self-reflection for selective instruction tuning without requiring additional resources.

### Selective Reflection-Tuning: Student-Selected Data Recycling for LLM Instruction-Tuning
**Authors:** Ming Li, Lichang Chen, Jiuhai Chen, Shwai He, Jiuxiang Gu, Tianyi Zhou  
**Venue:** ACL, Findings 2024  
**Paper:** [Link](https://arxiv.org/pdf/2402.10110)  
**Summary:** Student-selected data recycling approach that combines teacher LLM's reflection with student model compatibility.

### Reflection-Tuning: Data Recycling Improves LLM Instruction-Tuning
**Authors:** Ming Li, Lichang Chen, Jiuhai Chen, Shwai He, Heng Huang, Jiuxiang Gu, Tianyi Zhou  
**Venue:** arXiv 2023  
**Paper:** [Link](https://arxiv.org/pdf/2310.11716)  
**Summary:** Data recycling through reflection for improved instruction tuning.

### IterSelectTune: An Iterative Training Framework for Efficient Instruction-Tuning Data Selection
**Authors:** Jielin Song, Siyu Liu, Bin Zhu, Yanghui Rao  
**Venue:** arXiv 2024  
**Paper:** [Link](https://arxiv.org/pdf/2410.13464)  
**Summary:** Presents an iterative framework for progressively refining instruction tuning data selection.

### LEAD: Iterative Data Selection for Efficient LLM Instruction Tuning
**Authors:** Xiaotian Lin, Yanlin Qi, Yizhang Zhu, Themis Palpanas, Chengliang Chai, Nan Tang, Yuyu Luo  
**Venue:** arXiv 2025  
**Paper:** [Link](https://arxiv.org/abs/2503.00186)  
**Summary:** Iterative approach for efficient data selection in LLM instruction tuning.

### Data Diversity Matters for Robust Instruction Tuning
**Authors:** Alexander Bukharin, Shiyang Li, Zhengyang Wang, Jingfeng Yang, Bing Yin, Xian Li, Chao Zhang, Tuo Zhao, Haoming Jiang  
**Venue:** EMNLP, Findings 2024  
**Paper:** [Link](https://aclanthology.org/2024.findings-emnlp.195.pdf)  
**Summary:** Investigates the importance of data diversity for robust instruction tuning.

### Diversity Measurement and Subset Selection for Instruction Tuning Datasets
**Authors:** Peiqi Wang, Yikang Shen, Zhen Guo, Matt Stallone, Yoon Kim, Polina Golland, Rameswar Panda  
**Venue:** arXiv 2024  
**Paper:** [Link](https://arxiv.org/pdf/2402.02318)  
**Summary:** Methods for measuring diversity and selecting subsets in instruction tuning datasets.

### Self-Evolved Diverse Data Sampling for Efficient Instruction Tuning
**Authors:** Shengguang Wu, Keming Lu, Benfeng Xu, Junyang Lin, Qi Su, Chang Zhou  
**Venue:** arXiv 2023  
**Paper:** [Link](https://arxiv.org/pdf/2311.08182)  
**Summary:** Self-evolutionary approach for diverse data sampling in instruction tuning.

### The Best Instruction-Tuning Data are Those That Fit
**Authors:** Dylan Zhang, Qirun Dai, Hao Peng  
**Venue:** arXiv 2025  
**Paper:** [Link](https://arxiv.org/pdf/2502.04194)  
**Summary:** Analysis of what constitutes the best instruction-tuning data.

### LESS: Selecting Influential Data for Targeted Instruction Tuning
**Authors:** Mengzhou Xia, Sadhika Malladi, Suchin Gururangan, Sanjeev Arora, Danqi Chen  
**Venue:** ICML 2024  
**Paper:** [Link](https://arxiv.org/pdf/2402.04333)  
**Summary:** Gradient-based approach for selecting influential data through Low-rank gradient Similarity Search.

### Improving Influence-based Instruction Tuning Data Selection for Balanced Learning of Diverse Capabilities
**Authors:** Qirun Dai, Dylan Zhang, Jiaqi W. Ma, Hao Peng  
**Venue:** arXiv 2025  
**Paper:** [Link](https://arxiv.org/pdf/2501.12147)  
**Summary:** Influence-based methods for balanced learning across diverse capabilities.

### MIG: Automatic Data Selection for Instruction Tuning by Maximizing Information Gain in Semantic Space
**Authors:** Yicheng Chen, Yining Li, Kai Hu, Zerun Ma, Haochen Ye, Kai Chen  
**Venue:** arXiv 2025  
**Paper:** [Link](https://arxiv.org/pdf/2504.13835)  
**Summary:** Information gain maximization in semantic space for automatic data selection.

### DELIFT: Data Efficient Language model Instruction Fine Tuning
**Authors:** Ishika Agarwal, Krishnateja Killamsetty, Lucian Popa, Marina Danilevsky  
**Venue:** International Conference on Learning Representations 2024  
**Paper:** [Link](https://arxiv.org/pdf/2411.04425)  
**Summary:** Data efficient approach to language model instruction fine-tuning.

### Maybe Only 0.5% Data is Needed: A Preliminary Exploration of Low Training Data Instruction Tuning
**Authors:** Haowen Chen, Yining Zhang, Qi Zhang, Hantao Yang, Xiaomeng Hu, Xuetao Ma, Yifan YangGong, J. Zhao  
**Venue:** arXiv 2024  
**Paper:** [Link](https://arxiv.org/pdf/2305.09246)  
**Summary:** Explores the possibility of effective instruction tuning with minimal training data.

---

## Preference Alignment Tuning

### Principled Data Selection for Alignment: The Hidden Risks of Difficult Examples
**Authors:** Chengqian Gao, Haonan Li, Liu Liu, Zeke Xie, Peilin Zhao, Zhiqiang Xu  
**Venue:** ICML 2025  
**Paper:** [Link](https://arxiv.org/pdf/2502.09650)  
**Summary:** Examines the hidden risks of using difficult examples in preference alignment data selection.
