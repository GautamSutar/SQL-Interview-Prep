# 🎯 SQL-Interview-Prep

> **Crack the database interview.** 💼 A curated collection of real SQL queries asked in technical interviews — complete with optimal solutions, schema setups, and explanations. Built for CS students and developers ready to dominate their next data round.

<br>

![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-brightgreen?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL-blue?style=flat-square&logo=postgresql)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
![Questions](https://img.shields.io/badge/Interview%20Questions-50%2B-purple?style=flat-square)
![Maintained](https://img.shields.io/badge/Maintained-Yes-success?style=flat-square)

---

## 📖 About the Project

Landing a backend role today means more than knowing how to write a `SELECT` statement. Interviewers at top companies consistently probe candidates on **complex joins**, **window functions**, **query optimization**, **indexing strategies**, and **schema design** — skills that separate strong engineers from the rest.

This repository was born out of real interview experiences. As a backend developer working with **Python and Django**, I kept a running log of every SQL question I encountered across technical screenings — and turned that log into this structured, open resource.

**What makes this repo different:**

- 📌 **Real questions** — sourced from actual technical interviews, not textbook theory
- ✅ **Optimal answers** — each solution is annotated and aims for performance, not just correctness
- 🏗️ **Schema-first** — every problem includes the table setup so you can practice hands-on
- 📊 **Concept-driven structure** — questions are organized by SQL topic, making it easy to target your weak spots
- 🔍 **Explanation-focused** — solutions explain *why* a query works, including indexing hints and optimization notes

Whether you're preparing for a FAANG screening, a startup's take-home test, or brushing up your database fundamentals — this repo has you covered.


---

## 🚀 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/SQL-Interview-Prep.git
cd SQL-Interview-Prep
```

### 2. Set Up Your Database

This repo supports both **PostgreSQL** and **MySQL**. Pick your preferred environment.

**PostgreSQL (recommended):**
```bash
# Create a dedicated practice database
psql -U postgres -c "CREATE DATABASE sql_prep;"
psql -U postgres -d sql_prep
```

**MySQL:**
```bash
mysql -u root -p -e "CREATE DATABASE sql_prep;"
mysql -u root -p sql_prep
```

### 3. Load a Question Schema

Navigate into any question folder and load the schema to populate your database with the test data:

```bash
# PostgreSQL
psql -U postgres -d sql_prep -f Joins/q01_inner_vs_outer/schema.sql

# MySQL
mysql -u root -p sql_prep < Joins/q01_inner_vs_outer/schema.sql
```

### 4. Read the Question

Open `question.md` to read the problem statement. Try to solve it yourself first — that's the whole point! ✍️

```bash
cat Joins/q01_inner_vs_outer/question.md
```

### 5. Write and Test Your Query

Open your SQL client (pgAdmin, DBeaver, TablePlus, or the CLI) and write your solution against the loaded schema. Time yourself — interviewers often watch the clock.

### 6. Check the Answer

Once you're done (or stuck), compare your approach against the provided solution:

```bash
cat Joins/q01_inner_vs_outer/answer.sql
```

Don't just copy the answer — read the comments. Understanding **why** a query is structured a certain way (e.g., why a `LEFT JOIN` outperforms a subquery here, or why this column needs an index) is exactly what interviewers probe during follow-up questions.

### 7. Run the Answer Directly (Optional)

```bash
# PostgreSQL
psql -U postgres -d sql_prep -f Joins/q01_inner_vs_outer/answer.sql
```

---

## 🤝 Contributing

This project thrives on community contributions! If you've recently come out of a technical interview with a SQL question that stumped you (or one you aced), **please share it here** — you'll be helping hundreds of future candidates.

### How to Contribute

1. **Fork** this repository
2. **Create a new branch** for your question:
   ```bash
   git checkout -b add/window-functions-q4-percentile
   ```
3. **Follow the folder structure** outlined above — include `question.md`, `schema.sql`, and `answer.sql`
4. **Open a Pull Request** with a brief description of the question source (company name is optional/anonymous)

### Contribution Ideas

- 🆕 **New interview questions** — with schema and solution
- ⚡ **Alternate optimized solutions** — a more performant version of an existing answer
- 🐛 **Bug fixes** — incorrect query logic or broken schema files
- 📝 **Improved explanations** — clearer comments or additional context in `answer.sql`
- 🌍 **Dialect variations** — MySQL/PostgreSQL-specific syntax alternatives

> Please ensure your SQL is tested and your `question.md` clearly states the expected output or result format. Check the [Contributing Guidelines](CONTRIBUTING.md) *(coming soon)* for full details.

---

## 📬 Connect with Me

I'm always open to networking, feedback, and collaboration. Let's connect!

| Platform | Link |
|---|---|
| 🐙 GitHub | [@GautamSutar](https://github.com/GautamSutar) |
| 💼 LinkedIn | [Gautam Sutar](https://www.linkedin.com/in/gautamsutar/) |
| 🐦 Twitter / X | [@Gautamsutarr](https://x.com/Gautamsutarr) |
| 📧 Email | gautamsutar.in@gmail.com |

---

## ⭐ Show Your Support

If this repo helped you land an offer, ace a round, or simply taught you something new — **give it a star!** ⭐ It helps other developers discover it and motivates continued updates.

```
Every star is a developer better prepared for their next interview. 🙌
```

---

<div align="center">

**Built with 💻 + ☕ by a backend developer who's been through the grind.**

*Happy querying — and good luck on that interview!* 🚀

</div>