# 💘 What Makes People Want a Second Date? — Speed-Dating Data Analysis

> Exploratory and statistical analysis of a real speed-dating experiment to understand **what drives a mutual match**, with recommendations for a dating app.
> *Jedha Data Science certification project — RNCP35288, Block 2 (exploratory, descriptive & inferential analysis).*

---

## 🎯 Business problem
Tinder's marketing team wants to understand **which factors lead two people to want to see each other again**, in order to improve its matching algorithm and user experience.

## 📊 Data
- Speed-dating experiments run by Columbia Business School (2002-2004)
- **8,378 rows × 196 columns** → **4,194 unique interactions** after de-duplication of mirrored pairs
- Participant profiles, stated preferences, ratings given to each partner, and each person's yes/no decision

## 🧹 Data quality work
- Audit of missing values: **83 columns have more than 30 % missing values**; follow-up survey columns are 75-93 % empty and were excluded
- Stated preferences use **different scales across waves** → analysis based on the more consistent **ratings given by partners**

## 🔍 Five research questions & findings
| # | Question | Finding |
|---|---|---|
| 1 | Which attributes matter most? | **Shared interests and being fun** show the largest gap between matches and non-matches, for both women and men |
| 2 | Do people value attractiveness as much as they say? | **No** — the importance people *declare* for attractiveness barely relates to who they actually say yes to |
| 3 | Shared interests vs same ethnic background? | Shared interests matter far more: match rate **34.3 %** with strong shared interests vs **13.2 %** otherwise; same ethnicity brings only a small gain |
| 4 | Do people know how others see them? | People rate themselves higher than their partners do. The overall correlation with matching is close to zero, but those who **underestimate** themselves match more often (**19.9 %** vs **13.1 %** for over-estimators) |
| 5 | Does the order of dates matter? | **No clear effect** (correlation −0.04) |

Also: match rate is the same for women and men (**16.5 %**), but men say "yes" more often (**47 % vs 37 %**).

## 💡 Recommendations
- **Don't rely on declared preferences** in the matching algorithm: use observed behaviour instead
- **Put shared interests at the heart of matching** (interest tags, common activities)
- Highlight personality signals (humour, fun) in profiles, not only photos

## 🧰 Tech stack
`Python` · `pandas` · `NumPy` · `matplotlib` · `seaborn` · `plotly`

## 📁 Repository
```
├── notebooks/Speed_dating_ds2.ipynb   # full analysis
├── Speed+Dating+Data.csv              # dataset
├── Slides                             # link to the presentation
└── requirements.txt
```

---
👤 **Nouman Malidi Mlimi** — Data Scientist / Data Analyst · [Portfolio](https://noumanmalidi7.github.io) · [LinkedIn](https://www.linkedin.com/in/nouman-malidi-a99276326/)
