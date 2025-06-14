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
/* Exercise grid */
.exercise-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.exercise-card {
  background: linear-gradient(135deg, #3498db, #2c3e50); 
  color: white;
  padding: 1rem;
  border-radius: 6px;
  text-align: center;
  transition: transform 0.2s;
  text-decoration: none;
  display: block;
}

.exercise-card:nth-child(2) {
   background: linear-gradient(135deg, #3498db, #2c3e50);
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

  .notes-image {
  width: 100%;
  max-width: 800px;
  border: 1px solid #ddd;
  border-radius: 8px;
  margin: 1.5rem auto;
  display: block;
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

## 📚 SQL Quick Reference
<div class="exercise-grid">
    <a href="notes.html" class="exercise-card">
        <div style="font-size: 1.5rem;">📚</div>
        <div style="font-weight: bold; margin: 0.5rem 0;">Interactive SQL Reference</div>
        <div style="font-size: 0.9em; opacity: 0.9;">Click to view the complete guide</div>
    </a>
</div>

## 🏆 Your Progress
<div class="badge-container"> <img src="https://img.shields.io/badge/Exercises-2%20completed-brightgreen" alt="Progress"> <img src="https://img.shields.io/badge/Level-Intermediate-blue" alt="Level"> </div>
"The more you know, the more you realize you don't know."
— Aristotle (perfect for SQL learning!)


<div id="ai-assistant">
  <img src="AI_lecturer.PNG" alt="AI Assistant Avatar" id="assistant-avatar" />
  <div id="chat-box">
    <p>Hi! I'm your SQL AI Assistant. How can I help you today?</p>
  </div>
</div>

<style>
  #ai-assistant {
    position: fixed;
    bottom: 20px;
    right: 20px;
    z-index: 1000;
    text-align: center;
  }

  #assistant-avatar {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    cursor: pointer;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
  }

  #assistant-avatar:hover {
    transform: scale(1.1);
  }

  #chat-box {
    display: none;
    position: absolute;
    bottom: 100px;
    right: 0;
    width: 250px;
    background: #f9f9f9;
    border: 1px solid #ccc;
    border-radius: 10px;
    padding: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    color: #333; /* Added for better text contrast */
  }

  #ai-assistant.active #chat-box {
    display: block;
  }
</style>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    document.getElementById('assistant-avatar').addEventListener('click', function () {
      document.getElementById('ai-assistant').classList.toggle('active');
    });
  });
</script>

<div style="text-align: center; margin-top: 2rem;"> <small>AI-Augmented SQL eBook | © 2025</small> </div>
