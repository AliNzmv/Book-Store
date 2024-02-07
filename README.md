# Roshanan Café-Bookstore Data Analysis Project
Quera Data Analysis Bootcamp / Fall 2023 / Team G2

## 📌 Introduction

Located in the historical heart of Shiraz, *Roshanan* is a unique café-bookstore that provides an experience combining traditional beverage flavors with the intellectual pleasure of reading. Besides offering a variety of teas, syrups, and distilled drinks, the café has a bookstore section showcasing a vast range of literary and historical books. An added novelty is that each beverage is accompanied by a QR code. Scanning this code reveals personalized book recommendations, often tailored to the specific drink chosen by the guest!

## 🎯 Problem Statement

Despite the books being accessible to guests, the number of book-related transactions has been unsatisfactory. The café management aims to refine their sales strategy and formulate special offers to enhance the revenue stream from book sales.
After preliminary investigations, they've identified three primary customer categories to target:

1. **Young Couples & Romantic Dates**: By showcasing books from top romance authors, the chances of these guests purchasing romance novels are expected to increase.
2. **Students & Researchers**: These frequent visitors can become loyal customers if presented with a curated collection of quality books at affordable prices.
3. **Foreign Tourists**: Placing stands of historical books from top publishers can serve as an enticing memento for tourists exploring the rich cultural heritage of Shiraz.

## 🔍 Repository Structure

```
- __pycache__
  ├── [Cached Python files for faster execution]
- csv_file
  ├── [CSV files used in the project]
- analysis_test.ipynb [Notebook with exploratory data analysis and initial tests]
- crawl.py [Script for crawling data]
- crawl_functions.py [Utility functions for the crawl script]
- dashboard.py [Script to launch the project dashboard]
- db.ipynb [Notebook for database-related operations]
- quda_project_scenario.pdf [One-page project scenario description]
- requirements.txt
```

## 🚀 Getting Started

1. **Clone the Repository**:
```bash
git clone https://github.com/AliNzmv/Book-Store.git
```
2. **Installing required packages**:
```bash
pip install -r requirements.txt
```

4. **Install Dependencies**:
```bash
pip install -r requirements.txt
```

4. **Data Crawling**:
   - Run the `crawl.py` script to gather data.
   - Modify and utilize functions in `crawl_functions.py` as needed.

5. **Database Setup**:
   - Set up your preferred database system.
   - Open `db.ipynb` and configure the database connection as required.

6. **Launch Dashboard**:
   - Navigate to the main directory and run:
```bash
python dashboard.py
```
7. **Statistical Analysis & Hypothesis Testing**:
   - Run the `analysis_test.ipynb` as a jupyter notebook.
   - There are codes to provide client's orders and a few hypotheses while testing and evaluating.



## 🤝 Contribution

Your contributions and suggestions are heartily♡ welcome, be it small or big, as every little bit can help make this project even better. Let's collaborate!

## 🙏 Acknowledgments

- **Roshanan Café** for providing the inspiration and valuable data.
- [**Iran Ketab**](https://iranketab.ir/) for providing the crawlable data.
- Open-source libraries and tools used in this project.
- Mentor: [Sina Asghari](https://github.com/sinaaasghari) for his wisdom in leading and mentoring the team
- Contributors: [Ali](https://github.com/aliNzmv), [Amir](https://github.com/AmirRezaei-2023), [Mohamad](https://github.com/MohammadNasimi), and [Kaveh](https://github.com/kvmmn) for their diligent work and dedication.


---
© 2023 Quera Data Analysis Bootcamp / Team G2. All Rights Reserved.
