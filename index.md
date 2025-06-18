---
# 📘 AI-Augmented SQL eBook - Interactive Platform
---

<style>
/* Modern card styling */
.intro-card {
  background: linear-gradient(135deg, #3498db, #2c3e50);
  color: white;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  margin-bottom: 2rem;
  text-align: center;
}

/* Exercise grid */
.exercise-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.exercise-card {
  background: white;
  border: 1px solid #ddd;
  padding: 1.5rem;
  border-radius: 8px;
  text-align: center;
  transition: all 0.3s ease;
  text-decoration: none;
  display: block;
  color: #333;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.exercise-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.2);
  border-color: #3498db;
}

.exercise-icon {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #3498db;
}

.progress-section {
  background: white;
  border-radius: 8px;
  padding: 1.5rem;
  margin: 2rem 0;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.progress-bar {
  height: 10px;
  background: #e0e0e0;
  border-radius: 5px;
  margin: 1rem 0;
  overflow: hidden;
}

.progress-fill {
  height: 100%;
  background: #2ecc71;
  width: 0%;
  transition: width 0.5s ease;
}

.progress-stats {
  display: flex;
  justify-content: space-between;
  margin-top: 1rem;
}

/* Make it match your exercise pages */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  max-width: 900px;
  margin: 0 auto;
  padding: 20px;
  background-color: #f5f7fa;
}

h1, h2, h3 {
  color: #2c3e50;
}

h2 {
  border-bottom: 2px solid #3498db;
  padding-bottom: 8px;
  margin-top: 30px;
}

/* Header to match other pages */
.site-header {
  background: #2c3e50;
  color: white;
  padding: 1rem 2rem;
  margin-bottom: 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.site-title {
  margin: 0;
  font-size: 1.5rem;
}

.site-nav a {
  color: white;
  text-decoration: none;
  margin-left: 1rem;
  padding: 0.5rem;
  border-radius: 4px;
  transition: background 0.3s;
}

.site-nav a:hover {
  background: rgba(255,255,255,0.1);
}

/* Responsive design */
@media (max-width: 768px) {
  .site-header {
    flex-direction: column;
    text-align: center;
  }
  
  .site-nav {
    margin-top: 1rem;
  }
  
  .site-nav a {
    margin: 0 0.5rem;
  }
  
  .exercise-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="site-header">
  <div class="site-title">📘 AI-Augmented SQL Learning</div>
  <div class="site-nav">
    <a href="#features">Features</a>
    <a href="#exercises">Exercises</a>
    <a href="#progress">Progress</a>
    <a href="notes.html">Reference</a>
  </div>
</div>

<div class="intro-card">
  <h1>Interactive SQL Learning Platform</h1>
  <p>Practice with live exercises and get AI-powered feedback on your queries</p>
</div>

## 🚀 <span id="features">Key Features</span>
- **Live SQL Editor** - Try queries directly in your browser
- **Instant Feedback** - Get AI-powered suggestions on your solutions
- **Progress Tracking** - Visual dashboard showing your learning journey
- **Comprehensive Reference** - Quick access to SQL syntax and examples

## 📝 <span id="exercises">Your Exercises</span>
<div class="exercise-grid"> 
  <a href="exercises/activity_4A_AI.html" class="exercise-card"> 
    <div class="exercise-icon">🔍</div>
    <h3>Exercise A</h3>
    <p>SELECT basics Conceptual Questions</p>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 75%"></div>
    </div>
  </a>
  
  <a href="exercises/activity_B_AI.html" class="exercise-card"> 
    <div class="exercise-icon">✏️</div>
    <h3>Exercise B</h3>
    <p>WHERE conditions queries</p>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 50%"></div>
    </div>
  </a>
  
  <a href="exercises/activity_4C_AI.html" class="exercise-card"> 
    <div class="exercise-icon">📊</div>
    <h3>Exercise C</h3>
    <p>ORDER BY practice queries</p>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 25%"></div>
    </div>
  </a>

  <a href="exercises/activity_4D.html" class="exercise-card"> 
    <div class="exercise-icon">🔗</div>
    <h3>Exercise D</h3>
    <p>JOINs queries</p>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 10%"></div>
    </div>
  </a>

  <a href="exercises/4E_AI_TRY.html" class="exercise-card"> 
    <div class="exercise-icon">🚗</div>
    <h3>Exercise E</h3>
    <p>CAR database queries</p>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 5%"></div>
    </div>
  </a>

  <a href="exercises/activity_F.html" class="exercise-card"> 
    <div class="exercise-icon">📈</div>
    <h3>Exercise F</h3>
    <p>GROUP BY and HAVING queries</p>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 0%"></div>
    </div>
  </a>
</div>

## 📚 SQL Quick Reference
<div class="exercise-grid">
  <a href="notes.html" class="exercise-card">
    <div class="exercise-icon">📚</div>
    <h3>Interactive SQL Reference</h3>
    <p>Complete syntax guide with examples</p>
  </a>
</div>

## 🏆 <span id="progress">Your Progress</span>
<div class="progress-section">
  <h3>Overall Completion</h3>
  <div class="progress-bar">
    <div class="progress-fill" style="width: 30%"></div>
  </div>
  <div class="progress-stats">
    <span>2 of 6 exercises completed</span>
    <span>30%</span>
  </div>
  
  <h3 style="margin-top: 2rem;">Recent Achievements</h3>
  <div class="exercise-grid" style="grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));">
    <div class="exercise-card">
      <div class="exercise-icon">🎯</div>
      <h4>First Steps</h4>
      <small>Completed Exercise A</small>
    </div>
    <div class="exercise-card">
      <div class="exercise-icon">🔍</div>
      <h4>Query Explorer</h4>
      <small>Attempted 5+ queries</small>
    </div>
  </div>
</div>

<div id="ai-assistant">
  <img src="/sql-ai-ebook/AI_lecturer.png" alt="AI Assistant Avatar" id="assistant-avatar" />
  <div id="chat-box">
    <p>Hi! I'm your SQL AI Assistant. Ready to practice some queries?</p>
    <button style="margin-top: 10px; padding: 5px 10px; background: #3498db; color: white; border: none; border-radius: 4px;">Start Exercise</button>
  </div>
</div>

<script>
// In a real implementation, you would load progress from localStorage or a database
document.addEventListener('DOMContentLoaded', function() {
  // Toggle AI assistant
  document.getElementById('assistant-avatar').addEventListener('click', function() {
    document.getElementById('ai-assistant').classList.toggle('active');
  });
  
  // Example of loading progress (would be replaced with real data)
  const savedProgress = localStorage.getItem('sqlProgress');
  if (savedProgress) {
    const progress = JSON.parse(savedProgress);
    // Update progress bars and stats
  }
});
</script>

<div style="text-align: center; margin-top: 2rem; color: #7f8c8d;">
  <small>AI-Augmented SQL eBook | © 2025</small>
</div>
