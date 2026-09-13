# Dr. Sania — Nutrition & Diet Consultant Website

A responsive, static website for **Dr. Sania**, a nutrition and diet consultant, featuring an interactive **BMI, BMR & Daily Calorie Calculator**, an overview of her services, her professional background, and a WhatsApp-integrated appointment booking form.


## ✨ Features

- **Interactive BMI Calculator** — supports both metric (cm/kg) and imperial (ft, in) units
- **BMR Calculation** — estimates Basal Metabolic Rate using the Harris-Benedict equation
- **Daily Calorie Needs** — adjusted automatically based on activity level (sedentary to extra active)
- **Healthy Weight Range** — shows the ideal weight range for the user's height
- **Personalized Recommendations** — tailored health tips based on BMI category, age, and gender
- **Services Overview** — showcases the range of nutrition therapy services offered
- **About Section** — Dr. Sania's credentials, experience, and specializations
- **Appointment Booking** — a contact form that sends appointment requests directly via WhatsApp
- **Responsive Design** — fully adapts to desktop, tablet, and mobile screens
- **Smooth Scrolling Navigation** — animated in-page scrolling between sections
- **Floating WhatsApp Button** — always-visible quick-contact widget

## 🛠️ Built With

- **HTML5** — semantic page structure
- **CSS3** — custom properties (CSS variables), Flexbox, CSS Grid, media queries
- **JavaScript (Vanilla)** — DOM manipulation, form validation, calculations, and event handling
- **[Font Awesome](https://fontawesome.com/)** — icon library (via CDN)

No frameworks, build tools, or dependencies are required — it's a pure front-end project.

## 📁 Project Structure

```
├── index.html      # Main page markup (all sections)
├── style.css       # Styling, layout, and responsive design
├── script.js       # BMI/BMR calculator logic, form handling, and UI interactions
├── sania.png       # Logo used in the header and footer
└── README.md       # Project documentation
```

## 🚀 Getting Started

No installation or build step is needed.

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open the project folder
   ```bash
   cd <repo-name>
   ```
3. Open `index.html` in your browser — or use a live server extension (e.g. VS Code's **Live Server**) for the best experience.

## 🧮 How the Calculator Works

1. Select a height unit and fill in age, gender, height, weight, and activity level.
2. Click **Calculate BMI & Get Results**.
3. JavaScript reads the input values, computes BMI, BMR, healthy weight range, and daily calorie needs, then updates the results panel instantly — no page reload required.

## 📱 Appointment Requests

The contact form collects the visitor's name, email, phone, preferred service, and message, then opens a pre-filled WhatsApp chat so Dr. Sania's office can respond quickly.

## 📄 License

This project is open source and available for learning and personal use. Feel free to fork and customize it for your own needs.

## 👤 Author

Developed by **Asadullah**
Roll No: **BCSF24M006**
Subject: Web Technologies
