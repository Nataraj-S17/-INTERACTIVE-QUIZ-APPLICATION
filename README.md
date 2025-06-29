# Interactive Quiz Application

![Quiz Application](https://img.shields.io/badge/Status-Complete-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 📋 Project Overview

**Company:** CODTECH IT SOLUTIONS  
**Developer:** NATARAJ S  
**Intern ID:** CT04DF2488 
**Domain:** Frontend Web Development  
**Duration:** 4 Weeks  
**Mentor:** NEELA SANTOSH  

A fully interactive and engaging web-based quiz application built with vanilla HTML, CSS, and JavaScript. This modern quiz platform offers a polished user experience with advanced features like timer functionality, score tracking, progress indication, random answer shuffling, and dark mode toggle.

## ✨ Features

### Core Functionality
- **Interactive Quiz Interface** - Clean, modern design with smooth animations
- **Timer System** - 5-minute countdown timer with real-time display
- **Progress Tracking** - Animated progress bar showing quiz completion status
- **Question Counter** - Clear indication of current question (e.g., "Question 3 of 10")
- **Random Question Selection** - 10 questions randomly selected from a larger pool
- **Answer Shuffling** - Options are randomized for each quiz attempt
- **Instant Feedback** - Visual feedback for correct/incorrect answers with animations

### User Experience
- **Dark/Light Mode Toggle** - Switch between themes with preference persistence
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Smooth Transitions** - CSS animations and transitions for enhanced UX
- **Navigation Controls** - Previous, Skip, and Next question functionality
- **Auto-advance** - Automatic progression after answer selection

### Results & Analytics
- **Comprehensive Results** - Detailed quiz summary including:
  - Total questions attempted
  - Number of correct answers
  - Final score percentage
  - Time taken to complete
- **Restart Functionality** - Easy quiz restart with fresh question set

## 🚀 Demo

### Light Mode
The application features a clean, modern interface with a light color scheme perfect for daytime use.

### Dark Mode
Toggle to dark mode for comfortable viewing in low-light environments with full theme consistency.

## 🛠️ Technologies Used

- **HTML5** - Semantic structure and accessibility
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)** - Interactive functionality and DOM manipulation
- **LocalStorage API** - Theme preference persistence
- **Google Fonts** - Inter font family for modern typography

## 📁 Project Structure

```
INTERACTIVE-QUIZ-APPLICATION/
├── quiz/
│   ├── quiz.html          # Main HTML structure
│   ├── quiz.css           # Styling and animations
│   └── quiz.js            # Quiz logic and interactivity
└── README.md              # Project documentation
```

## 🎯 Key Features Breakdown

### Timer System
- 5-minute countdown timer
- Real-time display in MM:SS format
- Automatic quiz submission when time expires
- Time tracking for performance analysis

### Question Management
- Pool of 12+ general knowledge questions
- Random selection of 10 questions per quiz
- Answer options shuffled for each attempt
- Support for multiple-choice questions

### Visual Feedback
- ✅ Green highlight and animation for correct answers
- ❌ Red highlight with correct answer display for wrong choices
- Smooth color transitions and hover effects
- Progress bar with animated stripes

### Responsive Design
- Mobile-first approach
- Flexible layouts using CSS Grid and Flexbox
- Optimized for screens from 320px to 1920px+
- Touch-friendly interface elements

## 🎨 Design Features

### Color Scheme
- **Light Mode:** Clean whites and blues with subtle shadows
- **Dark Mode:** Deep blues and grays with proper contrast ratios
- **Accent Colors:** Blue for primary actions, green for success, red for errors

### Typography
- **Font Family:** Inter (Google Fonts)
- **Weights:** 400, 500, 600, 700
- **Responsive sizing** for optimal readability

### Animations
- Fade transitions between questions
- Progress bar animation with moving stripes
- Button hover effects with subtle transforms
- Answer feedback animations (shake for incorrect, pulse for correct)

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation & Setup

1. **Clone or Download** the repository
```bash
git clone [repository-url]
cd INTERACTIVE-QUIZ-APPLICATION
```

2. **Open the Application**
```bash
# Option 1: Open directly in browser
open quiz/quiz.html

# Option 2: Use a local server (recommended)
# Using Python
python -m http.server 8000

# Using Node.js (if you have live-server installed)
npx live-server quiz/

# Using PHP
php -S localhost:8000 -t quiz/
```

3. **Access the Quiz**
   - Navigate to `http://localhost:8000` (if using local server)
   - Or open `quiz/quiz.html` directly in your browser

## 🎮 How to Use

1. **Start Quiz** - The quiz begins automatically when the page loads
2. **Answer Questions** - Click on your chosen answer from the four options
3. **Navigate** - Use Previous/Next buttons or let auto-advance take you forward
4. **Skip Questions** - Use the Skip button if you're unsure
5. **View Results** - See your comprehensive results at the end
6. **Toggle Theme** - Switch between light and dark modes anytime
7. **Restart** - Click "Restart Quiz" to take the quiz again with new questions

## 📊 Quiz Content

The application includes a diverse set of general knowledge questions covering:
- Geography (capitals, countries, landmarks)
- Science (chemistry, biology, astronomy)
- History and Literature
- Nature and Animals
- Arts and Culture

### Sample Questions
- "What is the capital of France?"
- "Which planet is known as the Red Planet?"
- "What is the largest mammal in the world?"
- "Who painted the Mona Lisa?"

## 🔧 Customization

### Adding New Questions
Edit the `questionsPool` array in `quiz.js`:

```javascript
const questionsPool = [
    {
        question: "Your question here?",
        options: ["Option 1", "Option 2", "Option 3", "Option 4"],
        correctAnswer: 0 // Index of correct answer (0-3)
    },
    // Add more questions...
];
```

### Modifying Timer
Change the timer duration in `quiz.js`:

```javascript
let timeLeft = 300; // Change 300 to desired seconds
```

### Customizing Themes
Modify CSS variables in `quiz.css`:

```css
:root {
    --bg-color: #f8fafc;
    --text-color: #1e293b;
    --accent-color: #3b82f6;
    /* Modify colors as needed */
}
```

## 🌟 Advanced Features

### LocalStorage Integration
- Theme preference persistence
- Survives browser refresh and restart
- Automatic theme application on page load

### Performance Optimizations
- Efficient DOM manipulation
- CSS transitions for smooth animations
- Optimized image and font loading
- Minimal JavaScript bundle size

### Accessibility Features
- Semantic HTML structure
- ARIA labels for screen readers
- Keyboard navigation support
- High contrast color ratios

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔮 Future Enhancements

### Potential Improvements
- **Sound Effects** - Audio feedback for interactions
- **Backend Integration** - User data persistence and leaderboards
- **Multiple Categories** - Subject-specific quiz categories
- **Difficulty Levels** - Easy, Medium, Hard question sets
- **Social Features** - Share results on social media
- **Analytics Dashboard** - Detailed performance tracking
- **Question Bank Management** - Admin interface for question management

### Technical Enhancements
- **Progressive Web App (PWA)** - Offline functionality
- **API Integration** - External question databases
- **User Authentication** - Personal progress tracking
- **Multiplayer Mode** - Real-time competitive quizzes

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Contribution Guidelines
- Follow existing code style and conventions
- Add comments for complex functionality
- Test across multiple browsers
- Update documentation as needed

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Developer

**Joshwa. A**  
Frontend Web Development Intern  
CODTECH IT SOLUTIONS  

---

## 🙏 Acknowledgments

- **CODTECH IT SOLUTIONS** for the internship opportunity
- **NEELA SANTOSH** for mentorship and guidance
- **Google Fonts** for the Inter font family
- **CSS-Tricks** and **MDN Web Docs** for development resources

---

*This project represents a comprehensive learning journey in frontend web development, combining clean design principles with interactive functionality to create an engaging user experience.*
