📘 CGPA Calculator

A simple and interactive CGPA Calculator built using HTML, CSS, and JavaScript. This app allows students to calculate semester-wise GPA and overall CGPA efficiently based on credit hours and grade points.

🚀 Features
✅ Semester-wise GPA Calculation

- Add multiple courses per semester

- Enter credit hours and grade points

- Automatically computes GPA for each semester

✅ Overall CGPA Calculation

- Combine GPA values from multiple semesters

- Calculates CGPA using credit-based weighted average

✅ Dynamic & User-Friendly UI

- Clean, responsive design

- Real-time validation and instant output updates

- Lightweight and fast (no backend required)

🛠️ Tech Stack

- HTML5 – Structure of the app

- CSS3 – Styling and responsive layout

- JavaScript (ES6) – GPA & CGPA logic, dynamic DOM updates

📂 Project Structure

CGPA-Calculator/
│── index.html
│── style.css
│── script.js
└── README.md

📊 How It Works

🎓 1. Semester GPA (SGPA) Formula

For each semester:

SGPA = ∑( Grade Point × Course Credit) / ∑(Course Credit)
	​
Where:
Grade Point = numerical value assigned to the grade
(O=10, A+=9, A=8, B+=7, B=6, C=5, D=4)

Course Credit = credit hours of each subject

🎓 2. Overall CGPA Formula

CGPA is calculated using the weighted average of all semester SGPAs based on total credits:

CGPA = ∑(SGPA × Semester Credits) / ∑(Semester Credits )

Where:

SGPA = GPA of each semester

Semester Credits = total credits of that semester

▶️ Usage

- Open index.html in any browser.

- Add your courses with credit hours and grade points.

- Get instant Semester GPA.

- Add all semester GPAs to compute overall CGPA.

🖼️ Screenshots 

![Preview](CGPA.png)


🤝 Contributing

Pull requests are welcome!
Feel free to improve UI, add themes, or enhance calculation methods.

📄 License

This project is open-source and available under the MIT License.

## Clone the Repository
```bash
git clone https://github.com/Sivarahul04/CGPA.git
