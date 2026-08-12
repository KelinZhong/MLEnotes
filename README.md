# Machine Learning Engineer Notes

Study notes for Machine Learning Engineer roles, written as runnable Jupyter notebooks and
built with Jupyter Book.

**📖 Read the book:** https://kelinzhong.github.io/MLEnotes/

## Who this is for

Primarily people moving into an MLE role from an adjacent one — data science, analytics,
software engineering, research. It assumes Python and comfort with basic statistics, and does
not assume production ML experience.

## Contents

| Part | Covers |
|---|---|
| **I — ML Foundations** | Linear models, trees, clustering, SVM, evaluation, metrics & imbalance |
| **II — Deep Learning** | Backprop, training, regularization, CNNs, sequences, attention, transfer learning |
| **III — PyTorch** | Tensors through fine-tuning, plus `torch.compile`, AMP, and distributed training |
| **IV — Production ML** | Pipelines, training infra, serving, deployment, monitoring, testing, infra tools |
| **V — LLM Engineering** | Transformer internals, post-training, inference optimization, RAG, agents, evaluation |
| **VI — ML System Design** | A 7-step framework plus four worked case studies |
| **VII — Interview Prep** | The loop, project deep dives, trade-offs, debugging, ML coding round |
| **Appendix** | TensorFlow guide (reference) |

## Reading paths

**New to ML** — read Parts I → II → III in order, then IV.

**Coming from data science** — skim Part I (see ML0 for a self-check), read ML7 properly,
then Parts II, III, IV. Your experimentation background is a real asset in Part VI.

**Interviewing soon** — Part VII first, then Part VI, then the specific gaps those expose.

## Running the notebooks

```bash
pip install -r requirements.txt
jupyter lab
```

To build the book locally:

```bash
jupyter-book build .
```

## A note on freshness

Chapters marked with a ⏱️ timestamp are the *volatile layer* — model names, hardware constants,
tool landscapes. They are deliberately isolated so that updating them doesn't require touching
the durable material. `llm0` is the main one; re-verify it yearly.

## License

Personal study notes. Other notes: https://kelinzhong.github.io/StudyNotes/
