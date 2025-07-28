# 🧠 Membership Inference Test (MINT) Suite

This repository provides a unified collection of research works focused on **Membership Inference Testing (MINT)** — a family of techniques aimed at detecting whether specific data samples were used to train AI models. These methods serve as tools for auditing, improving transparency, and assessing privacy risks in machine learning systems.

---

## 📚 Projects Included

The repository currently includes three complementary works, each exploring MINT from a different perspective:

### 🔍 [MINT/](./MINT/)
**"Membership Inference Test (MINT)"**  
The original MINT approach analyzes the activation patterns of AI models to determine training membership. It is validated on face recognition systems using over 22M images and achieves up to **90% accuracy**.

### ⚙️ [aMINT/](./aMINT/)
**"Active Membership Inference Test (aMINT)"**  
aMINT introduces a **multi-task training strategy** where the MINT model is trained alongside the Audited model to identify used training samples, leveraging activation maps. It achieves over **80% accuracy** across five benchmarks and various architectures.

### 📉 [gMINT/](./gMINT/)
**"Gradient-based Membership Inference Test (gMINT)"**  
gMINT utilizes **gradient-level information**, specifically Weight Modifiers, to infer membership. Experiments show **near-perfect detection (up to 100%)**, highlighting the effectiveness of gradient-based auditing.

---

## 📌 Citation & Contact

Please refer to the individual subfolders for full code, paper links, and citation information for each method.

For questions or collaborations, contact: **daniel.dealcala@uam.es**




