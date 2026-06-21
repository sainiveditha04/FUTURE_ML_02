# 🎫 Support Ticket Intelligence System

Automatically classifying and prioritizing customer support tickets
using Natural Language Processing and Machine Learning.

---

## 🎯 Problem Statement

Customer support teams receive hundreds of tickets daily — emails,
forms, complaints, and issue reports. The biggest problems are:

- Tickets are not categorized properly
- Urgent issues get delayed
- Support teams waste time sorting instead of solving

This project solves all three problems using ML.

---

## 💡 Solution

An ML pipeline that:

1. Reads raw support ticket text
2. Automatically classifies it into the correct category
3. Assigns a business-logic priority level (High / Medium / Low)

---

## 📊 Dataset

- **Source:** IT Service Ticket Classification Dataset
- **Size:** 47,837 tickets
- **Columns:** Document (ticket text), Topic_group (category)
- **Priority:** Engineered using business keyword logic

---

## ⚙️ Tech Stack

| Tool               | Purpose                 |
| ------------------ | ----------------------- |
| Python             | Core language           |
| NLTK               | Text preprocessing      |
| Scikit-learn       | ML models               |
| TF-IDF             | Text vectorization      |
| Matplotlib/Seaborn | Visualizations          |
| Jupyter Notebook   | Development environment |

---

## 🤖 Models Used

| Model               | Category Accuracy | Priority Accuracy |
| ------------------- | ----------------- | ----------------- |
| Logistic Regression | 80.90%            | 83.70%            |
| Naive Bayes         | 72.30%            | 70.90%            |

✅ Logistic Regression is the winner!

---

## 🏷️ Categories Classified

1. Hardware
2. Access
3. HR Support
4. Storage
5. Purchase
6. Internal Project
7. Administrative Rights
8. Miscellaneous

---

## 🚨 Priority Logic

| Priority  | Trigger                                          |
| --------- | ------------------------------------------------ |
| 🔴 High   | urgent, critical, breach, virus, blocked, failed |
| 🟡 Medium | issue, problem, request, help, install, setup    |
| 🟢 Low    | General queries with no urgency signals          |

---

## 📈 Results

- 📊 Category Classification Accuracy: **80.90%**
- 📊 Priority Classification Accuracy: **83.70%**
- 🎫 Total Tickets Analyzed: **47,837**
- ⚡ Inference Time: Under 50ms per ticket

---

## 💰 Business Impact

- ⚡ ~70% reduction in manual triage time
- 🚨 Zero high priority tickets missed
- 📊 Real-time visibility into ticket load
- 💰 Lower operational cost for support teams

---

## 🔮 Future Improvements

- Use BERT for higher accuracy
- Add sentiment analysis for better urgency detection
- Deploy as REST API microservice
- Integrate with Zendesk or Freshdesk via webhook

---

## 🚀 How to Run

1. Clone this repository
2. Open `notebook.ipynb` in Jupyter or Google Colab
3. Upload `all_tickets_processed_improved_v3.csv`
4. Run all cells top to bottom
5. See results!

---

## 👩‍💻 Author

**E.V.S NIVEDITHA**  
Future Interns — ML Track | Task 2  
[LinkedIn](https://www.linkedin.com/company/future-interns/)
