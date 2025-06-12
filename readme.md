🌐 **Live Report**: [Click here to view the HTML version](https://jirawanph.github.io/titanic-survival-analysis/)


# 🛳 Titanic Survival Analysis

This project explores survival patterns in the Titanic dataset using R. The analysis focuses on how **gender**, **passenger class**, and **family presence** influenced the likelihood of survival.

It demonstrates end-to-end data analysis skills including:
- Data cleaning and transformation
- Feature engineering
- Exploratory data analysis
- Visualization with `ggplot2`
- Insight communication in a portfolio-ready format

---

## 📁 Project Structure

```
titanic-survival-analysis/
├── data/
│   └── titanic.csv              # Raw dataset
├── R/
│   └── titanic_analysis.Rmd     # Full analysis in R Markdown
├── outputs/
│   └── titanic_analysis.html    # Knit HTML report
├── README.md                    # Project overview
└── LICENSE                      # MIT
```

---

## 📊 Key Questions Explored

1. Did gender affect the likelihood of survival?
2. Did passenger class affect the likelihood of survival?
3. Was traveling with family linked to a higher survival rate?

---

## 🔍 Findings (Summary)

- **Gender:** Female passengers had a significantly higher survival rate than males, consistent with "women and children first" evacuation.
- **Passenger Class:** 1st class passengers had the highest survival rate; 3rd class the lowest — suggesting a socioeconomic influence.
- **Family:** Passengers traveling with family were more likely to survive than those traveling alone.

---

## 📦 Dataset

- Source: [Titanic CSV (Datasciencedojo GitHub)](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- 891 rows, 12 columns
- Includes variables like `Survived`, `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, and `Embarked`

---

## 🛠 Tools Used

- **Language:** R
- **Libraries:** `dplyr`, `ggplot2`, `readr`
- **Output Format:** R Markdown → HTML

---

## 🚀 How to Run

1. Open `R/titanic_analysis.Rmd` in RStudio
2. Click `Knit` to generate the full report
3. The output HTML will appear in the `outputs/` folder

---

## 👤 Author

Jirawan Phromtawepong  
Linkedin : www.linkedin.com/in/jirawan-phromtawepong
GitHub : https://github.com/jirawanph

---

## 📄 License

This project is shared under the MIT License

MIT License

Copyright (c) 2025 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.






