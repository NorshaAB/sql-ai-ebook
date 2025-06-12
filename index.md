<style>
.footer, .octocat {
  display: none !important;
}

/* New styles for interactive elements */
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

# 📘 AI-Augmented SQL eBook

<div class="intro-card" style="
  background: linear-gradient(135deg, #3498db, #2c3e50);
  color: white;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  margin-bottom: 2rem;
">
Welcome to the Interactive SQL Learning Platform!<br>
Now with <strong>live SQL exercises</strong> and <strong>AI-powered quick notes</strong>.
</div>

## 🚀 New Features
- **Embedded SQL Playground** - Practice directly in your browser
- **Expandable Quick Notes** - Key concepts at your fingertips
- **Progress Tracking** - See your learning journey

## 🛠️ Live SQL Playground
<iframe src="https://sqliteonline.com/" class="sql-playground"></iframe>
<small>*Powered by SQLite Online - Works right in your browser!*</small>

## 📚 Quick Reference
<div class="quick-note">
<details>
<summary><strong>✨ WHERE vs. HAVING</strong> (Click to expand)</summary>

```sql
-- WHERE filters rows BEFORE aggregation
SELECT department, COUNT(*) 
FROM employees 
WHERE salary > 5000 
GROUP BY department;

-- HAVING filters AFTER aggregation
SELECT department, AVG(salary) 
FROM employees 
GROUP BY department 
HAVING AVG(salary) > 5000;
