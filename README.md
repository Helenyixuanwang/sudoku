# Sudoku Master - Web Development Project 1

A static Sudoku game website built with pure HTML and CSS as part of a web development course at Northeastern University.

## 🎮 Project Overview

This is a mock Sudoku website featuring multiple pages, responsive design, and professional styling. The site demonstrates fundamental web development skills including semantic HTML, CSS layout techniques, and mobile-first design principles.

## 📁 Project Structure

```
sudoku-game/
├── index.html                 # Home page
├── css/
│   ├── common.css            # Shared styles, navbar, buttons
│   ├── home.css              # Home page styles
│   ├── selection.css         # Game selection page styles
│   ├── game.css              # Game board styles (9x9 and 6x6)
│   ├── rules.css             # Rules page styles
│   ├── highscores.css        # High scores page styles
│   └── auth.css              # Login/Register page styles
├── assets/
│   ├── images/               # Images and icons
│   └── fonts/                # Custom fonts
├── selection/
│   └── index.html            # Game selection page
├── game-hard/
│   └── index.html            # Hard difficulty (9x9 grid)
├── game-easy/
│   └── index.html            # Easy difficulty (6x6 grid)
├── rules/
│   └── index.html            # Rules and credits page
├── highscores/
│   └── index.html            # High scores leaderboard
├── login/
│   └── index.html            # Login page
└── register/
    └── index.html            # Registration page
```

## ✨ Features

### Pages
1. **Home Page** - Landing page with hero section and feature cards
2. **Selection Page** - List of available games with difficulty levels
3. **Hard Game Page** - 9x9 Sudoku grid with pre-filled cells
4. **Easy Game Page** - 6x6 Sudoku grid for beginners
5. **Rules Page** - Game instructions and credits section
6. **High Scores Page** - Leaderboard tables for different difficulty levels
7. **Login Page** - User authentication form
8. **Register Page** - New user registration form

### Design Features
- **Responsive navbar** - Fixed position with mobile hamburger menu
- **Mobile-friendly** - Optimized for iPhone 12 Pro and desktop
- **Modern design** - CSS Grid and Flexbox layouts
- **Interactive elements** - Hover effects and transitions
- **Clean URLs** - No .html extensions in paths

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with:
  - CSS Variables (custom properties)
  - Flexbox and Grid layouts
  - Media queries for responsiveness
  - Pseudo-elements and transitions
  - Custom animations

## 📋 HTML Elements Used

- div, span, a, img, p, head, body
- button, input (text, password, number)
- h1, h2, h3, h4, h5, h6
- ul, ol, table

## 🎨 CSS Properties Used

- font-family, background-color/background
- margin, padding
- position (fixed, relative)
- align-items, text-align
- flex, grid
- @media queries
- Pseudo-elements (:hover, :active, :first-child, :nth-child, etc.)
- transition, transform

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone [your-repo-url]
   ```

2. Navigate to the project folder:
   ```bash
   cd sudoku-game
   ```

3. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

4. Visit `http://localhost:8000` in your browser

## 📱 Mobile Testing

The site is optimized for mobile viewing. To test:
1. Open Chrome DevTools (F12)
2. Click the device toolbar icon (Ctrl+Shift+M)
3. Select "iPhone 12 Pro" from the device dropdown
4. Navigate through all pages

## 🎯 Project Requirements Met

- ✅ Working GitHub repository
- ✅ Clean URL structure (no .html in paths)
- ✅ 8 unique pages with appropriate content
- ✅ Fixed navbar with active state indication
- ✅ Mobile-friendly responsive design
- ✅ All required HTML elements
- ✅ All required CSS properties
- ✅ Professional design with good UX
- ✅ No JavaScript used
- ✅ No styling libraries (Bootstrap, etc.)

## 👥 Collaborators

Yixuan Wang

## 📝 Writeup Responses

### Most Challenging Piece
[Your response - at least 3 sentences]

### Mobile-Friendly Decisions
[Your response - at least 3 sentences]

### Design Considerations
[Your response - at least 3 sentences]

### Future Features
[Your response - at least 3 sentences]

### Time Spent
[Your response - number of hours]

## 📚 Resources Used

- Google Fonts (if used)
- Color palette inspiration: [source if any]
- Icon library: [if any]

## 📄 License

This project was created for educational purposes as part of CS coursework at Northeastern University.

---

**Note:** This is a static mock website. No actual game logic or authentication is implemented.
