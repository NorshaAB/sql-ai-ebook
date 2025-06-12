---
# 📘 AI-Augmented SQL eBook - Interactive Platform
---

<style>
/* Hide GitHub elements */
.footer, .octocat { display: none !important; }

/* Modern card styling */
.intro-card {
  background: linear-gradient(135deg, #3498db, #2c3e50);
  color: white;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  margin-bottom: 2rem;
}

/* Exercise grid */
.exercise-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.exercise-card {
  background: #2188ff;
  color: white;
  padding: 1rem;
  border-radius: 6px;
  text-align: center;
  transition: transform 0.2s;
  text-decoration: none;
  display: block;
}

/* Interactive elements */
.sql-playground {
  width: 100%;
  height: 400px;
  border: 1px solid #ddd;
  border-radius: 8px;
  margin: 1.5rem 0;
}

.quick-note {
  background: #f8f9fa;
  border-left: 4px solid #3498db;
  padding: 1rem;
  margin: 1rem 0;
  border-radius: 0 8px 8px 0;
}

.badge-container {
  display: flex;
  gap: 0.5rem;
  margin: 1.5rem 0;
  flex-wrap: wrap;
}
</style>

<div class="intro-card">
Welcome to the <strong>Interactive SQL Learning Platform</strong>!<br>
Practice with live exercises and AI-powered feedback.
</div>

## 🚀 Key Features
- **Live SQL Editor** - Try queries directly in your browser
- **Quick Reference** - Expandable syntax examples
- **Progress Tracking** - Visualize your learning journey

## 📝 Your Exercises
<div class="exercise-grid"> <a href="exercises/activity_4C_AI.html" class="exercise-card"> <div style="font-size: 1.5rem;">📌</div> <div style="font-weight: bold; margin: 0.5rem 0;">Exercise 4C</div> <div style="font-size: 0.9em; opacity: 0.9;">CREATE TABLE practice</div> </a> <a href="exercises/4E_AI_TRY.html" class="exercise-card"> <div style="font-size: 1.5rem;">📌</div> <div style="font-weight: bold; margin: 0.5rem 0;">Exercise 4E</div> <div style="font-size: 0.9em; opacity: 0.9;">CAR database queries</div> </a> </div>

## 🏆 Your Progress
<div class="badge-container"> <img src="https://img.shields.io/badge/Exercises-2%20completed-brightgreen" alt="Progress"> <img src="https://img.shields.io/badge/Level-Intermediate-blue" alt="Level"> </div>
"The more you know, the more you realize you don't know."
— Aristotle (perfect for SQL learning!)

## 🛠️ Practice Now
<iframe src="https://sqliteonline.com/" class="sql-playground" title="SQL Practice"></iframe>
<small>Pro Tip: Try recreating exercises from this platform here!</small>

## 📚 Quick Notes
<div class="quick-note">
<details>
<summary><strong>🔍 WHERE vs. HAVING</strong></summary>

```sql
-- Filters individual rows BEFORE grouping
SELECT department, COUNT(*) 
FROM employees 
WHERE salary > 5000 
GROUP BY department;

-- Filters groups AFTER aggregation
SELECT department, AVG(salary) 
FROM employees 
GROUP BY department 
HAVING AVG(salary) > 5000;

</details> </div><div class="quick-note"> <details> <summary><strong>🔗 JOIN Types</strong></summary>
SELECT * FROM orders
INNER JOIN customers ON orders.cust_id = customers.id;

-- LEFT: All rows from left table + matches
SELECT * FROM products
LEFT JOIN inventory ON products.id = inventory.product_id;


<div style="text-align: center; margin-top: 2rem;"> <small>Made with ❤️ | © 2025 | <a href="https://github.com/norshaab/sql-ai-ebook">View on GitHub</a></small> </div>
