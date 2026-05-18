# calc-interactive

An interactive web-based learning tool for **AP Calculus AB**: Critical Points and the First Derivative Test.

## 🎯 About

This is an elegant, interactive educational web app that teaches students how to:
- **Find critical points** of functions
- **Apply the First Derivative Test** to classify local extrema
- **Visualize** the relationship between f(x) and f'(x)

## ✨ Features

### 📊 Interactive Graph Explorer
- Real-time visualization of polynomial functions f(x) = x³ + ax² + bx
- Simultaneous display of f(x) and f'(x) curves
- Automatic detection and labeling of critical points
- Sign chart that updates as you adjust coefficients

### 🎛️ Interactive Sliders
- Adjust coefficients **a** and **b** to see how the function changes
- Watch critical points move in real time
- See how the First Derivative Test applies dynamically

### 📚 Educational Content
1. **Core Concepts** — Definitions and the First Derivative Test
2. **Interactive Explorer** — Experiment with polynomial functions
3. **Worked Examples** — Two detailed step-by-step solutions
4. **Practice Problems** — 5 quiz questions with instant feedback

### 🧪 Built-in Quiz
- Multiple choice and numerical answer questions
- Instant feedback with explanations
- Score tracking (0/5 to 5/5)
- "Show solution" button for each problem

## 🚀 Live Demo

Visit: **https://kingakki787-dev.github.io/calc-interactive**

## 🛠️ Technology Stack

- **HTML5** — Semantic markup
- **CSS3** — Modern styling with custom properties
- **Vanilla JavaScript** — Interactive graph rendering using Canvas API
- **MathJax 3** — LaTeX math rendering
- **Canvas API** — Dynamic graph visualization

## 📁 File Structure

```
calc-interactive/
├── index.html          # Main application file
└── README.md          # This file
```

## 💡 How It Works

### Graph Rendering
The Canvas API renders:
- Coordinate grid and axes
- The function curve f(x)
- The derivative curve f'(x) (dashed)
- Critical points with color-coded classification (max/min/neither)

### Critical Point Detection
JavaScript algebraically solves the quadratic equation derived from f'(x) = 0 to find all critical points, then classifies each using the First Derivative Test.

### Sign Chart
Automatically generates a sign analysis chart showing:
- Intervals where f'(x) is positive/negative
- Location of critical points
- Classification of each point (local max, min, or neither)

## 🎓 Educational Use

Perfect for:
- AP Calculus AB students
- Self-directed learners
- Calculus teachers looking for interactive demos
- Flipped classroom resources

## 📝 Learning Outcomes

After using this tool, students can:
✅ Identify critical points (where f'(x) = 0 or undefined)  
✅ Construct sign charts for derivatives  
✅ Apply the First Derivative Test correctly  
✅ Classify local extrema with confidence  
✅ Understand the visual relationship between a function and its derivative  

## 🔧 Customization

The app uses a cubic polynomial f(x) = x³ + ax² + bx by default. To modify:

1. Edit the `paramA` and `paramB` initial values in the script
2. Modify the `f(x)` and `fp(x)` functions to use different polynomials
3. Adjust slider ranges in the HTML to change coefficient bounds

## 🌟 Design Philosophy

- **Dark theme** for reduced eye strain
- **Minimal, elegant design** focusing on mathematical clarity
- **Real-time interactivity** for immediate visual feedback
- **Responsive layout** that works on tablets and laptops
- **Accessible math notation** using MathJax

## 📄 License

Open source — feel free to use and modify for educational purposes.

---

**Built for AP Calculus AB · Critical Points & First Derivative Test**

Questions or suggestions? Feel free to open an issue or contribute!
