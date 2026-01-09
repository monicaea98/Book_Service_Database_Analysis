# 📚 SQL Project – Book Service Database Analysis

This project focuses on **SQL-based data analysis** of a book subscription service database. The study explores how user behavior, book characteristics, and publishing activity can inform the **value proposition for a new digital product** in the online reading market.

The context is inspired by the COVID-19 pandemic, when more people stayed at home and increased their consumption of books, creating new opportunities for startups in the digital reading ecosystem.

---

## 🎯 Study Objectives

The main objectives of this project are to:

* Explore the structure and relationships within a relational database
* Analyze books, authors, publishers, ratings, and reviews using SQL queries
* Extract meaningful insights to support **product and business decisions**
* Practice writing efficient and readable SQL queries

All analytical tasks are solved **exclusively using SQL**, with Pandas used only to display query results.

---

## 🗂️ Database Description

The database consists of five main tables:

### 📘 `books`

Contains information about books:

* `book_id` — book identifier
* `author_id` — author identifier
* `title` — book title
* `num_pages` — number of pages
* `publication_date` — publication date
* `publisher_id` — publisher identifier

### ✍️ `authors`

Contains information about authors:

* `author_id` — author identifier
* `author` — author name

### 🏢 `publishers`

Contains information about publishers:

* `publisher_id` — publisher identifier
* `publisher` — publisher name

### ⭐ `ratings`

Contains user ratings:

* `rating_id` — rating identifier
* `book_id` — book identifier
* `username` — user name
* `rating` — rating score

### 📝 `reviews`

Contains user-written reviews:

* `review_id` — review identifier
* `book_id` — book identifier
* `username` — user name
* `text` — review text

---

## 📊 Analytical Tasks

The following business questions were answered using SQL:

1. Determine the **number of books published after January 1, 2000**.
2. Calculate the **number of user reviews and the average rating for each book**.
3. Identify the **publisher with the highest number of books exceeding 50 pages** (excluding brochures and short publications).
4. Find the **author with the highest average book rating**, considering only books with **at least 50 ratings**.
5. Compute the **average number of text reviews written by users who rated more than 50 books**.

---

## 🛠️ Methodology

* Connected to the database using SQL
* Inspected tables by reviewing sample records
* Wrote individual SQL queries for each analytical task
* Used SQL functions and aggregations to simplify and optimize queries
* Stored and displayed results using Pandas
* Interpreted results and documented conclusions for each query

---

## 🧠 Key Insights

* Recent publications (post-2000) represent a significant portion of the catalog
* User engagement varies greatly across books, with some titles generating far more reviews and ratings
* Certain publishers dominate the market when focusing on full-length books
* Highly rated authors can be identified reliably by applying minimum rating thresholds
* Power users (those who rate many books) contribute a substantial portion of written reviews

---

## 🛠️ Tools & Technologies

* 🗄️ **SQL** — primary tool for data extraction and analysis
* 🐍 **Python** — used for database connection and result handling
* 📊 **Pandas** — displaying and storing SQL query outputs
* 📘 **Jupyter Notebook** — interactive analysis environment

---

## 📌 Key Takeaways

This project demonstrates how SQL can be used to efficiently analyze relational databases and extract insights that support product development and strategic decision-making. Strong querying skills enable analysts to work directly with raw data and answer complex business questions with clarity and precision.
