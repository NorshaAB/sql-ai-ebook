---
# 📘 AI-Augmented SQL eBook - Interactive Platform
---

<style>
/* Hide GitHub elements */
.footer, .octocat { display: none !important; }

/* Modern card styling - Keeping your original colors */
.intro-card {
  background: linear-gradient(135deg, #3498db, #2c3e50);
  color: white;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  margin-bottom: 2rem;
  text-align: center;
}

/* Exercise grid - Keeping your original gradient */
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

/* Progress section styling */
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

/* Your original AI assistant styling */
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
  color: #333;
}

#ai-assistant.active #chat-box {
  display: block;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .exercise-grid {
    grid-template-columns: 1fr;
  }
  
  #ai-assistant {
    bottom: 10px;
    right: 10px;
  }
  
  #assistant-avatar {
    width: 60px;
    height: 60px;
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
    <div style="font-size: 0.9em; opacity: 0.9;">Basics SQL Conceptual Questions</div>
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
    <div style="font-size: 0.9em; opacity: 0.9;">CALCULATIONS queries</div>
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
  <img src="/sql-ai-ebook/AI_lecturer.png" alt="AI Assistant Avatar" id="assistant-avatar" />
  <div id="chat-box">
    <p>Hi! I'm your SQL AI Assistant. Let's try some SQL exercises, and I'll guide you!</p>
  </div>
</div>

// In your index.md file, replace the script section with this:

<script>
// Progress Manager Class
class ProgressTracker {
  constructor() {
    this.progressData = this.loadProgress();
    this.init();
  }

  loadProgress() {
    // Load from localStorage or initialize defaults
    const defaultData = {
      version: 1,
      completedExercises: [],
      exerciseProgress: {},
      streak: 0,
      lastAccessDate: null,
      achievements: {
        firstSteps: false,
        queryExplorer: false,
        joinMaster: false,
        sqlChampion: false
      },
      stats: {
        queriesAttempted: 0,
        correctQueries: 0,
        timeSpent: 0 // in minutes
      }
    };
    
    const savedData = JSON.parse(localStorage.getItem('sqlLearningProgress')) || defaultData;
    return {...defaultData, ...savedData};
  }

  saveProgress() {
    localStorage.setItem('sqlLearningProgress', JSON.stringify(this.progressData));
  }

  updateStreak() {
    const today = new Date().toISOString().split('T')[0];
    const yesterday = new Date(Date.now() - 86400000).toISOString().split('T')[0];
    
    if (this.progressData.lastAccessDate === today) return;
    
    if (!this.progressData.lastAccessDate || 
        this.progressData.lastAccessDate === yesterday) {
      this.progressData.streak++;
    } else {
      this.progressData.streak = 1;
    }
    
    this.progressData.lastAccessDate = today;
    this.checkAchievements();
    this.saveProgress();
  }

  markExerciseComplete(exerciseId) {
    if (!this.progressData.completedExercises.includes(exerciseId)) {
      this.progressData.completedExercises.push(exerciseId);
    }
    this.progressData.exerciseProgress[exerciseId] = 100;
    this.updateStreak();
    this.checkAchievements();
    this.saveProgress();
  }

  updateExerciseProgress(exerciseId, percent) {
    this.progressData.exerciseProgress[exerciseId] = Math.max(
      percent, 
      this.progressData.exerciseProgress[exerciseId] || 0
    );
    this.saveProgress();
  }

  recordQueryAttempt(isCorrect) {
    this.progressData.stats.queriesAttempted++;
    if (isCorrect) this.progressData.stats.correctQueries++;
    this.checkAchievements();
    this.saveProgress();
  }

  checkAchievements() {
    // First Steps - Completed first exercise
    if (this.progressData.completedExercises.length > 0 && !this.progressData.achievements.firstSteps) {
      this.progressData.achievements.firstSteps = true;
      this.showAchievementNotification("First Steps", "Completed your first exercise!");
    }
    
    // Query Explorer - Attempted 10+ queries
    if (this.progressData.stats.queriesAttempted >= 10 && !this.progressData.achievements.queryExplorer) {
      this.progressData.achievements.queryExplorer = true;
      this.showAchievementNotification("Query Explorer", "Attempted 10+ SQL queries!");
    }
    
    // Join Master - Completed JOIN exercises
    const joinExercises = ['D', 'E']; // Adjust based on your exercise IDs
    if (joinExercises.every(ex => this.progressData.completedExercises.includes(ex)) && 
        !this.progressData.achievements.joinMaster) {
      this.progressData.achievements.joinMaster = true;
      this.showAchievementNotification("Join Master", "Completed all JOIN exercises!");
    }
    
    // SQL Champion - Completed all exercises
    if (this.progressData.completedExercises.length >= 6 && !this.progressData.achievements.sqlChampion) {
      this.progressData.achievements.sqlChampion = true;
      this.showAchievementNotification("SQL Champion", "Completed all exercises!");
    }
  }

  showAchievementNotification(title, message) {
    // Create and show a notification (customize this to match your UI)
    const notification = document.createElement('div');
    notification.className = 'achievement-notification';
    notification.innerHTML = `
      <div style="background: #2ecc71; color: white; padding: 15px; border-radius: 8px; 
                  position: fixed; bottom: 20px; left: 20px; z-index: 1000; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
        <div style="font-weight: bold; font-size: 1.2rem;">🏆 ${title}</div>
        <div>${message}</div>
      </div>
    `;
    document.body.appendChild(notification);
    setTimeout(() => notification.remove(), 5000);
  }

  init() {
    this.updateStreak();
    this.renderProgress();
  }

  renderProgress() {
    // Update UI elements with current progress
    const totalExercises = 6; // Update this based on your actual count
    
    // Overall progress
    const completionPercent = Math.round(
      (this.progressData.completedExercises.length / totalExercises) * 100
    );
    document.querySelector('.progress-fill').style.width = `${completionPercent}%`;
    document.querySelector('.progress-stats span:last-child').textContent = 
      `${completionPercent}% complete`;
    
    // Exercise-specific progress
    const exercises = ['A', 'B', 'C', 'D', 'E', 'F'];
    exercises.forEach(ex => {
      const progress = this.progressData.exerciseProgress[ex] || 0;
      const element = document.querySelector(`a[href*="activity_${ex}"] .progress-fill`);
      if (element) element.style.width = `${progress}%`;
    });
    
    // Streak counter
    document.querySelector('.progress-stats span:first-child').textContent = 
      `Current streak: ${this.progressData.streak} days`;
    
    // Badges
    const badgeContainer = document.querySelector('.badge-container');
    if (badgeContainer) {
      badgeContainer.innerHTML = '';
      if (this.progressData.achievements.firstSteps) {
        badgeContainer.innerHTML += '<span class="badge">First Steps</span>';
      }
      if (this.progressData.achievements.queryExplorer) {
        badgeContainer.innerHTML += '<span class="badge">Query Explorer</span>';
      }
      // Add more badges as needed
    }
  }
}

// Initialize when page loads
document.addEventListener('DOMContentLoaded', function() {
  // Initialize progress tracker
  const progressTracker = new ProgressTracker();
  
  // Toggle AI assistant (keep your existing functionality)
  document.getElementById('assistant-avatar').addEventListener('click', function() {
    document.getElementById('ai-assistant').classList.toggle('active');
  });
  
  // For demonstration - in real usage, call these from your exercise pages
  window.markExerciseComplete = (id) => progressTracker.markExerciseComplete(id);
  window.updateExerciseProgress = (id, percent) => progressTracker.updateExerciseProgress(id, percent);
  window.recordQueryAttempt = (isCorrect) => progressTracker.recordQueryAttempt(isCorrect);
});
</script>

<div style="text-align: center; margin-top: 2rem;"> <small>AI-Augmented SQL eBook | © 2025</small> </div>
