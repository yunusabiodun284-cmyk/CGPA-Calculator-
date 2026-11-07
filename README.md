# EduCalc – Student Calculation Suite

## Student Information
- **Name:** Issa Yunus Abiodun
- **Matric Number:** 2025/HND/SWD/062
- **Course Code:** SWD 417
- **Project Title:** Design and Development of a Student Calculator
- **Project Type:** Front-end Web Application

## Project Description
EduCalc is a responsive student calculation website developed with HTML, CSS and JavaScript. It provides four tools in separate pages: a normal calculator, a scientific calculator, a semester GPA calculator and a cumulative GPA (CGPA) calculator.

## Project Objectives
1. Build a simple and accessible calculator interface for students.
2. Perform basic and scientific mathematical operations.
3. Calculate semester GPA using course credit units and grades.
4. Calculate updated CGPA from previous and current academic records.
5. Practise HTML, CSS, JavaScript, DOM manipulation and input validation.

## Main Features
### Normal Calculator
Addition, subtraction, multiplication, division, percentage, decimals, sign change, clear and delete.

### Scientific Calculator
Sine, cosine, tangent, common logarithm, natural logarithm, square root, square, powers, factorial, absolute value, reciprocal, pi, Euler's number, parentheses, and degree/radian selection.

### GPA Calculator
Add or remove courses, enter course names/codes, enter credit units, select grades and calculate semester GPA.

### CGPA Calculator
Enter previous CGPA and completed credit units together with current semester GPA and credit units to calculate updated CGPA.

## Grading Scale
This project is configured with the selected 4.0 scale:
| Grade | Grade Point |
|---|---:|
| A | 4 |
| B | 3 |
| C | 2 |
| D | 1 |
| F | 0 |

**Important:** Institutions may use different grade boundaries or grade-point mappings. Confirm the scale and rules with the student's department before relying on the result for official academic decisions.

## Calculation Formulas
**GPA** = Sum of (course credit units × course grade points) ÷ Sum of course credit units.

**Updated CGPA** = [(Previous CGPA × Previous credit units) + (Current GPA × Current credit units)] ÷ (Previous credit units + Current credit units).

## Technologies Used
- HTML5 – page structure and forms.
- CSS3 – styling, layout and responsive design.
- JavaScript – calculations, validation and interactive features.

## Folder Structure
```text
educalc-advanced/
├── index.html
├── scientific.html
├── gpa.html
├── cgpa.html
├── README.md
├── css/
│   └── style.css
└── js/
    ├── common.js
    ├── normal.js
    ├── scientific.js
    ├── gpa.js
    └── cgpa.js
```

## How to Run
1. Download and extract the project ZIP.
2. Open the extracted folder in Visual Studio Code.
3. Open `index.html` in a browser, or use VS Code Live Server.
4. Use the navigation bar to open the other calculator pages.

No database, PHP or server-side setup is required. An internet connection is only needed to load the optional Google Font; the application functionality runs in the browser.

## Author
**Issa Yunus Abiodun**  
**Matric Number:** 2025/HND/SWD/062  
**Course Code:** SWD 417
