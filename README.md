# Math 32: Probability and Statistics — Fall 2026 (UC Merced)

Jupyter notebooks that go with the Math 32 lectures. Each notebook makes every figure and simulation in its lecture's slides, so you can **change the numbers and re-run** to see the ideas in action.

## Notebooks

| Lecture | Topic | Open in Colab |
|---|---|---|
| 24 | The Law of Large Numbers & the Central Limit Theorem | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ssindiUCM/Fall2026_UCMerced_Math32/blob/main/Lecture24_LLN_and_CLT/Lecture24.ipynb) |
| 26 | The Central Limit Theorem in Action: Averages and Sums | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ssindiUCM/Fall2026_UCMerced_Math32/blob/main/Lecture26_CLT_Sums_and_Averages/Lecture26.ipynb) |
| 27 | Confidence Intervals | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ssindiUCM/Fall2026_UCMerced_Math32/blob/main/Lecture27_Confidence_Intervals/Lecture27.ipynb) |
| 28 | More Confidence Intervals | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ssindiUCM/Fall2026_UCMerced_Math32/blob/main/Lecture28_More_Confidence_Intervals/Lecture28.ipynb) |

These go with **Standard 10: Calculations with the Central Limit Theorem**.

## How to run the notebooks

**Easiest: Google Colab (nothing to install).** Click an "Open in Colab" badge above, sign in with your Google account, and choose *Runtime → Run all*. To keep your changes, use *File → Save a copy in Drive*.

**On your own computer.** You need Python 3 with Jupyter, NumPy and Matplotlib:

```
pip install -r requirements.txt
jupyter notebook
```

Then open the notebook you want. Figures are saved in a `figures/` folder next to each notebook.

## Tips

- Every code cell is **self-contained**: change a number (like `n`, the confidence level, or the random seed) and re-run just that cell.
- Look for the **Try it** suggestions above the code cells.

## AI disclosure

These notebooks were developed with the help of an AI assistant (Claude, made by Anthropic). The AI helped write code, draft explanations, and make figures. The instructor designed the lessons, chose the examples, and reviewed and edited all of the material, and is responsible for its content. If you spot an error, please let the instructor know!

Using AI in your own coursework? Follow the AI policy in the course syllabus.
