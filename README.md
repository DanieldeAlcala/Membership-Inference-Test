# 🧠 Membership Inference Test (MINT) Suite

This repository provides a unified collection of research works focused on **Membership Inference Testing (MINT)** — a family of techniques aimed at detecting whether specific data samples were used to train AI models. These methods serve as tools for auditing, improving transparency, and assessing privacy risks in machine learning systems.

This research is in line with other current research efforts towards a more controlled and easily auditable data-driven AI based on machine learning that can be seen with different names: [explainable AI](https://www.sciencedirect.com/science/article/pii/S1566253519308103), [machine behavior](https://www.nature.com/articles/s41586-019-1138-y), [AI forensics](https://research.ibm.com/blog/AI-forensics-attribution) and [AI safety](https://arxiv.org/abs/2501.17805).

---

## 📚 Projects Included

The repository currently includes three complementary works, each exploring MINT from a different perspective:

### [MINT](Membership%20Inference%20Test%20%28MINT%29/)
**"Membership Inference Test (MINT)"**  
The original MINT approach analyzes the activation patterns of AI models to determine training membership. It is validated on face recognition systems using over 22M images and achieves up to **90% accuracy**.

### [aMINT](Active%20Membership%20Inference%20Test%20%28aMINT%29/)
**"Active Membership Inference Test (aMINT)"**  
aMINT introduces a **multi-task training strategy** where the MINT model is trained alongside the Audited model to identify used training samples, leveraging activation maps. It achieves over **80% accuracy** across five benchmarks and various architectures.

### [gMINT](Gradient%20Membership%20Inference%20Test%20%28gMINT%29/)
**"Gradient-based Membership Inference Test (gMINT)"**  
gMINT utilizes **gradient-level information**, specifically Weight Modifiers, to infer membership. Experiments show **near-perfect detection (up to 100%)**, highlighting the effectiveness of gradient-based auditing.

### [Factors](Factors%20Impacting%20MINT/)
**"Factors Impacting MINT"**  
We analyze key training-related factors that impact the success of membership inference, improving detection accuracy up to 87% across large-scale face recognition datasets.

---

## 📌 Citation & Contact

Please refer to the individual subfolders for full code, paper links, and citation information for each method.

For questions or collaborations, contact: **daniel.dealcala@uam.es**

## Acknowledgement

This work has been supported by projects BBforTAI (PID2021-127641OB-I00 MICINN/FEDER), HumanCAIC (TED2021-131787B-I00 MICINN), M2RAI (PID2024-160053OB-I00 MICIU/FEDER) and Cátedra ENIA UAM-VERIDAS (NextGenerationEU PRTR TSI-100927-2023-2). Work conducted in the ELLIS Unit Madrid. D. DeAlcala is supported by a FPU Fellowship (FPU21/05785).


