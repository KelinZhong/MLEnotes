# Machine Learning Engineer Notes

Study notes for Machine Learning Engineer roles, organized as runnable Jupyter notebooks — from deep learning theory, through PyTorch and TensorFlow, to the MLE interview loop and production ML.

## How this book is organized

**Part I — Deep Learning Foundations.** How neural networks learn, training effectively, preventing overfitting, CNNs, sequence models, attention, and using pretrained models. Framework-agnostic theory with NumPy illustrations.

**Part II — Frameworks.** The same ideas implemented for real: a PyTorch guide (tensors, autograd, models, training loops, CNNs, RNNs, debugging, pretrained models, fine-tuning) and a parallel TensorFlow guide (building models, training, callbacks, data pipelines, CNNs, regularization, saving/deployment, transfer learning). The chapters mirror Part I — e.g. read DL4 (CNN theory), then P5/tf5 (CNN in code).

**Part III — Interview Rounds.** ML Coding (implement algorithms from scratch in NumPy: linear models, classic algorithms, neural nets with backprop, attention/transformers, metrics and losses), ML System Design (a 7-step framework plus four worked cases: recommendation, search/ads, trust & safety, LLM application), and MLE Interview Prep (project deep dives, 25 trade-off questions, debugging scenarios).

**Part IV — Production & LLMs.** MLOps (pipelines, training infra, serving, deployment patterns, monitoring, testing, infra tools) and LLM Engineering (transformer internals, pretraining and fine-tuning, inference optimization, RAG, prompting and agents, evaluation).

## How to use these notes

- Theory first, then implementation: each Part I chapter has matching chapters in Part II (DL6 attention → mlc4 from-scratch implementation → llm1 production internals).
- Each interview-round section opens with **What Interviewers Test** and ends with **Common Interview Questions** and **Key Takeaways**.
- Code cells are runnable and use only numpy, pandas, matplotlib, scikit-learn, scipy, PyTorch, and TensorFlow.

## Related books

- [LeetCode Prep Notes](https://github.com/KelinZhong/leetcode-prep) - Python DSA study guides and SQL query-pattern references for coding interviews
- [Data Science Interview Prep](https://github.com/KelinZhong/ds-interview-prep) - Python data libraries, business metrics, statistics, machine learning, A/B testing, causal ML, DS workflow, and business decisions
