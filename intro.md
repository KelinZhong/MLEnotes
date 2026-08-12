# Machine Learning Engineer Notes

Study notes for Machine Learning Engineer roles, organized as runnable Jupyter notebooks —
from classic ML and deep learning theory, through PyTorch, to production systems, LLM
engineering, and the interview loop.

To read other notes, visit [Study Notes](https://kelinzhong.github.io/StudyNotes/).

## Who this book is for

Primarily people moving into an MLE role from an adjacent one. It assumes Python and basic
statistics; it does not assume production ML experience.

If you're coming from a **data science or analytics background**, a lot of Part I is already
yours — and that's an advantage, not wasted pages. What's usually missing is not the modeling.
It's everything around it: serving, monitoring, cost, and the systems thinking that turns a
notebook result into something that runs at 3am under load. Read ML0 for a self-check, then
spend your time in Parts III–VI.

## How this book is organized

**Part I — ML Foundations.** Linear and logistic regression, evaluation and generalization,
data preparation, unsupervised learning, tree-based models, similarity and margins, and
metrics under class imbalance. The models here still do more production work than neural
networks do.

**Part II — Deep Learning.** How networks learn, training effectively, preventing overfitting,
CNNs, sequences, attention and the modern transformer stack, and transfer learning.
Framework-agnostic theory with NumPy illustrations.

**Part III — Building Models in PyTorch.** Tensors, autograd, models, training loops, CNNs,
RNNs, debugging, pretrained models, fine-tuning — and then `torch.compile`, mixed precision,
and distributed training, which is where a working loop becomes a production one.

**Part IV — Production ML.** Pipelines and reproducibility, training infrastructure, serving
and latency, deployment patterns, monitoring, testing, and the Docker/Kubernetes surface an
MLE is expected to operate.

**Part V — LLM Engineering.** Transformer internals at inference, post-training (SFT,
preference optimization, RLVR), inference optimization and the serving stack, RAG, agents,
and evaluation.

**Part VI — ML System Design.** A 7-step framework plus four worked cases: recommendation,
search and ads, trust and safety, and an LLM application.

**Part VII — Interview Preparation.** The loop by company type, project deep dives, trade-off
questions, debugging scenarios, and the ML coding round.

**Appendix.** A TensorFlow guide, kept as reference. Learn PyTorch first — it's what Part III
uses and what most teams write today. Read the appendix if you inherit a Keras codebase.

## How to use these notes

- **Theory then implementation.** Part I → Part V (ML coding) re-implements the same
  algorithms from scratch; Part II's DL6 → Part V's llm1 does the same for attention.
- **Each chapter opens with "Why This Matters"** and closes with Common Interview Questions
  and Key Takeaways.
- **Chapters marked ⏱️ are the volatile layer** — model names, hardware numbers, tool
  landscapes. They're isolated deliberately so the durable material around them stays clean.
  Re-verify them yearly.
- Code cells run on numpy, pandas, matplotlib, scipy, scikit-learn, PyTorch, TensorFlow, and
  the gradient-boosting libraries listed in `requirements.txt`.
