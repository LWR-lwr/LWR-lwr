<h1 align="center">LWR-lwr</h1>

---

## 🔬 Selected Work

### 🍅 Tomato Leaf Disease Diagnosis &amp; Grading
**[→ Repository](https://github.com/LWR-lwr/Tomato-Disease-Diagnosis)**

An improved YOLOv8 detector paired with an HSV-based severity grading pipeline, shipped as a Flask web app with SQLite history, ECharts dashboard, and PDF reports.

- **+2.78% mAP50-95** on YOLOv8n after introducing an EMA attention block (0.9242 → 0.9520)
- Testing CBAM / EMA / ECA / SimAM / CA on YOLOv8s showed **all of them below the baseline** — attention saturates on mid-size models. I wrote this up as a negative result rather than hiding it.
- Designed an **A/B grading strategy**: lesion-type and chlorosis-type diseases are handled separately, because coarse annotations make box-area ratios unreliable.
- Built the full stack — detection, grading, history, dashboard, PDF export.

`PyTorch` · `Ultralytics` · `OpenCV` · `Flask` · `SQLite` · `ECharts`

---

### 💬 Chinese E-commerce Review Sentiment Analysis
**[→ Repository](https://github.com/LWR-lwr/Chinese-Review-Sentiment-Analysis)**

TF-IDF + Multinomial Naive Bayes, extended with a rule engine for the short, slang-heavy text that classic models get wrong.

- **84.2%** accuracy vs. **69.2%** for the SnowNLP dictionary baseline
- Rule layer catches internet slang (`yyds`, `避雷`) that bag-of-words models miss
- Analyzed failure modes on irony and contrastive reviews

`scikit-learn` · `jieba` · `pandas` · `matplotlib`

---

## 🧰 Toolbox

| | |
| :-- | :-- |
| **Languages** | Python · SQL |
| **Deep Learning** | PyTorch · Ultralytics YOLOv8 |
| **CV &amp; NLP** | OpenCV · scikit-learn · jieba |
| **Web &amp; Data** | Flask · SQLite · ECharts · pandas |

---

## 📫 Contact

**raylaw26@163.com**
