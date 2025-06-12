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

## 🔍 Exercises

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; margin: 2rem 0;">

<a href="exercises/activity_4C_AI.html" style="text-decoration: none;">
  <div style="background: #2188ff; color: white; padding: 1rem; border-radius: 6px; text-align: center; transition: transform 0.2s;">
    <div style="font-size: 1.5rem;">📌</div>
    <div style="font-weight: bold; margin: 0.5rem 0;">Exercise 4C</div>
    <div style="font-size: 0.9em; opacity: 0.9;">CREATE TABLE statements practice</div>
  </div>
</a>

<a href="exercises/4E_AI_TRY.html" style="text-decoration: none;">
  <div style="background: #2188ff; color: white; padding: 1rem; border-radius: 6px; text-align: center; transition: transform 0.2s;">
    <div style="font-size: 1.5rem;">📌</div>
    <div style="font-weight: bold; margin: 0.5rem 0;">Exercise 4E</div>
    <div style="font-size: 0.9em; opacity: 0.9;">CAR database queries practice</div>
  </div>
</a>

</div>
