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
  background: linear-gradient(135deg, #3498db, #2c3e50);
  color: white;
  padding: 1.5rem;
  border-radius: 8px;
  text-align: center;
  transition: transform 0.2s;
  text-decoration: none;
  display: block;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.exercise-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.2);
}

/* Progress section */
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
  width: 30%;
  border-radius: 5px;
}

.progress-stats {
  display: flex;
  justify-content: space-between;
  margin-top: 1rem;
  color: #7f8c8d;
}

/* Badge styling */
.badge {
  display: inline-block;
  background: #3498db;
  color: white;
  padding: 0.25rem 0.5rem;
  border-radius: 4px;
  font-size: 0.8rem;
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
}

/* Enhanced AI Assistant */
#ai-assistant {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 1000;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

#assistant-avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  cursor: pointer;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  transition: all 0.3s ease;
  animation: bounce 2s ease infinite;
}

#assistant-avatar:hover {
  transform: scale(1.1) rotate(5deg);
}

#speech-bubble {
  position: absolute;
  bottom: calc(100% + 10px);
  right: 0;
  background: white;
  color: #333;
  padding: 12px 15px;
  border-radius: 18px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.2);
  width: max-content;
  max-width: 200px;
  display: none;
  animation: pulse 2s infinite;
}

#speech-bubble:after {
  content: '';
  position: absolute;
  bottom: -10px;
  right: 20px;
  border-left: 10px solid transparent;
  border-right: 10px solid transparent;
  border-top: 15px solid white;
}

#chat-box {
  display: none;
  width: 280px;
  background: white;
  border-radius: 12px;
  padding: 15px;
  box-shadow: 0 6px 18px rgba(0,0,0,0.15);
  color: #333;
  animation: fadeIn 0.3s ease;
}

#ai-assistant.active #chat-box {
  display: block;
}

/* Animations */
@keyframes bounce {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}

@keyframes pulse {
  0% { transform: scale(1); opacity: 0.8; }
  50% { transform: scale(1.05); opacity: 1; }
  100% { transform: scale(1); opacity: 0.8; }
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(10px); }
  to { opacity: 1; transform: translateY(0); }
}

/* Mobile Responsiveness */
@media (max-width: 768px) {
  #ai-assistant {
    bottom: 15px;
    right: 15px;
  }
  
  #assistant-avatar {
    width: 60px;
    height: 60px;
  }
  
  #chat-box {
    width: 250px;
  }
  
  #speech-bubble {
    max-width: 160px;
    font-size: 0.9em;
    padding: 8px 12px;
  }
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
<div class="exercise-grid"> 
  <a href="exercises/activity_4A_AI.html" class="exercise-card"> 
    <div style="font-size: 1.5rem;">🔍</div> 
    <div style="font-weight: bold; margin: 0.5rem 0;">Exercise A</div> 
    <div style="font-size: 0.9em; opacity: 0.9;">SELECT basics Conceptual Questions</div>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 75%"></div>
    </div>
  </a>
  
  <a href="exercises/activity_B_AI.html" class="exercise-card"> 
    <div style="font-size: 1.5rem;">✏️</div> 
    <div style="font-weight: bold; margin: 0.5rem 0;">Exercise B</div> 
    <div style="font-size: 0.9em; opacity: 0.9;">WHERE conditions queries</div>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 50%"></div>
    </div>
  </a>
  
  <a href="exercises/activity_4C_AI.html" class="exercise-card"> 
    <div style="font-size: 1.5rem;">📊</div> 
    <div style="font-weight: bold; margin: 0.5rem 0;">Exercise C</div> 
    <div style="font-size: 0.9em; opacity: 0.9;">ORDER BY practice queries</div>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 25%"></div>
    </div>
  </a>

  <a href="exercises/activity_4D.html" class="exercise-card"> 
    <div style="font-size: 1.5rem;">🔗</div> 
    <div style="font-weight: bold; margin: 0.5rem 0;">Exercise D</div> 
    <div style="font-size: 0.9em; opacity: 0.9;">JOINs queries</div>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 10%"></div>
    </div>
  </a>

  <a href="exercises/4E_AI_TRY.html" class="exercise-card"> 
    <div style="font-size: 1.5rem;">🚗</div> 
    <div style="font-weight: bold; margin: 0.5rem 0;">Exercise E</div> 
    <div style="font-size: 0.9em; opacity: 0.9;">CAR database queries</div>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 5%"></div>
    </div>
  </a>

  <a href="exercises/activity_F.html" class="exercise-card"> 
    <div style="font-size: 1.5rem;">📈</div> 
    <div style="font-weight: bold; margin: 0.5rem 0;">Exercise F</div> 
    <div style="font-size: 0.9em; opacity: 0.9;">GROUP BY and HAVING queries</div>
    <div class="progress-bar">
      <div class="progress-fill" style="width: 0%"></div>
    </div>
  </a>
</div>

## 📚 SQL Quick Reference
<div class="exercise-grid">
    <a href="notes.html" class="exercise-card">
        <div style="font-size: 1.5rem;">📚</div>
        <div style="font-weight: bold; margin: 0.5rem 0;">Interactive SQL Reference</div>
        <div style="font-size: 0.9em; opacity: 0.9;">Click to view the complete guide</div>
    </a>
</div>

## 🏆 Your Progress
<div class="progress-section">
  <div style="display: flex; justify-content: space-between; align-items: center;">
    <h3 style="margin: 0;">Your Learning Journey</h3>
    <span class="badge">2 of 6 completed</span>
  </div>
  <div class="progress-bar">
    <div class="progress-fill"></div>
  </div>
  <div class="progress-stats">
    <span>Current streak: 3 days</span>
    <span>30% complete</span>
  </div>
  
  <div style="margin-top: 1.5rem;">
    <h4>Recent Achievements</h4>
    <div>
      <span class="badge">First Steps</span>
      <span class="badge">Query Explorer</span>
    </div>
  </div>
</div>

<div id="ai-assistant">
  <div id="speech-bubble">Click me for a quick demo!</div>
  <img src="/sql-ai-ebook/AI_lecturer.png" alt="AI Assistant Avatar" id="assistant-avatar" />
  <div id="chat-box">
    <p>Hello! Here's how the platform works:</p>
    <div style="margin: 15px 0; text-align: center;">
      <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 8px;">
        <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
                src="https://www.youtube.com/embed/jXBfQCEsuyE?rel=0" 
                frameborder="0" 
                allowfullscreen></iframe>
      </div>
    </div>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  // ===== PROGRESS TRACKING ===== (Your existing code)
  const progressData = JSON.parse(localStorage.getItem('sqlProgress')) || {
    completed: 2,
    total: 6,
    streak: 3,
    exercises: {
      A: 75,
      B: 50,
      C: 25,
      D: 10,
      E: 5,
      F: 0
    }
  };
  
  // Update progress bars
  document.querySelector('.progress-fill').style.width = `${(progressData.completed / progressData.total) * 100}%`;
  
  // Update exercise progress bars
  Object.entries(progressData.exercises).forEach(([exercise, percent]) => {
    const exerciseElement = document.querySelector(`a[href*="activity_${exercise}"] .progress-fill`);
    if (exerciseElement) {
      exerciseElement.style.width = `${percent}%`;
    }
  });
  
  // Update stats
  document.querySelector('.badge').textContent = `${progressData.completed} of ${progressData.total} completed`;
  document.querySelector('.progress-stats span:last-child').textContent = 
    `${Math.round((progressData.completed / progressData.total) * 100)}% complete`;

  // ===== AI ASSISTANT + DEMO VIDEO ===== (New enhanced functionality)
  const assistant = document.getElementById('ai-assistant');
  const avatar = document.getElementById('assistant-avatar');
  
  // Toggle chat box with animation
  avatar.addEventListener('click', function(e) {
    e.stopPropagation(); // Prevent immediate close when clicking avatar
    assistant.classList.toggle('active');
  });
  
  // Close when clicking outside
  document.addEventListener('click', function(e) {
    if (!assistant.contains(e.target)) {
      assistant.classList.remove('active');
    }
  });

  // Optional: Add button functionality
  const startButton = document.querySelector('#chat-box button');
  if (startButton) {
    startButton.addEventListener('click', function() {
      window.location.href = "exercises/activity_4A_AI.html"; // Link to first exercise
    });
  }
});
</script>

<div style="text-align: center; margin-top: 2rem;"> <small>AI-Augmented SQL eBook | © 2025</small> </div>
