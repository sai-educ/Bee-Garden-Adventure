🎮 Game Features:

Interactive Gameplay

Your mouse becomes a bee 🐝
Falling flowers and leaves from top to bottom
Collect good items (yellow/pink flowers) for points
Avoid bad items (brown leaves, wilted flowers) or lose lives


Educational Quiz System

Quiz pops up every 10 points
Questions about bee facts and biology
Multiple choice answers
Educational explanations for each answer


Scoring & Lives

Earn 1 point per good item collected
3 lives (lose one for each bad item)
Goal: Reach 50 points to win


Visual Effects

Garden background from Unsplash
Items pile up at the bottom
Smooth animations
Sound feedback for all actions


Fully Responsive - Works on desktop and mobile

📦 For GitHub/Vercel Deployment:
Create a simple file structure:
bee-garden-game/
├── index.html (the artifact above)
└── README.md

The game uses:

No external dependencies - pure HTML/CSS/JS
Unsplash for background (you can replace with your own)
Canvas API for smooth animations
Web Audio API for sound effects

🎨 Easy Customizations:
Change the background image:

#gameCanvas {
  background-image: url('YOUR_IMAGE_URL_HERE');
}

Add more quiz questions in the quizQuestions array:
{
  question: "Your question here?",
  options: ["Option 1", "Option 2", "Option 3"],
  correct: 0, // index of correct answer
  explanation: "Educational explanation!"
}

Adjust difficulty:

Change spawn rate: Math.random() * 1000 + 800 (line ~500)
Change fall speed: Math.random() * 2 + 1.5 (line ~283)
Change point goal: modify 50 in the win condition

Add any of the above items, and create a pull request. We will test and approve. 

