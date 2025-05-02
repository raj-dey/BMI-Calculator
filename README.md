# BMI Calculator

A responsive and interactive Body Mass Index (BMI) calculator built using **HTML**, **CSS**, and **JavaScript**. This application helps users calculate their BMI using either **Metric** or **Imperial** units and offers educational content on healthy living and the limitations of BMI as a health indicator.

---
## 🚀 Features

- 🔄 **Unit Switching**: Supports both **Metric (cm/kg)** and **Imperial (ft/in, st/lbs)** systems.
- ⚙️ **Live BMI Calculation**: Instantly calculates BMI and displays ideal range info.
- 📚 **Health Tips**: Offers advice on diet, exercise, and sleep.
- ⚠️ **BMI Limitations Section**: Explains why BMI isn't a one-size-fits-all health measure.
- 📱 **Fully Responsive**: Adapts to all screen sizes and devices.

---

## 📂 File Structure

```
📁 BMI-Calculator/
├── index.html          # Main HTML structure
├── style.css           # Styling with responsive design
├── calculator.js       # JavaScript logic for BMI computation
└── images/             # Icons and images used in the interface
```

---

## 💡 How It Works

1. **Select Unit System** (Metric or Imperial).
2. **Enter Height and Weight** values.
3. **BMI is calculated** based on:
   - **Metric**: `BMI = weight (kg) / (height (m))²`
   - **Imperial**: `BMI = 703 × weight (lbs) / (height (in))²`
4. **Result is shown** with guidance and ideal BMI range.

---

## 🛠️ Tech Stack

- **HTML5** – Semantic structure
- **CSS3** – Responsive layout and custom styles
- **Vanilla JavaScript** – DOM manipulation and BMI logic

---

## 📸 Screenshots

![image alt](https://github.com/raj-dey/BMI-Calculator/blob/fd449ab4e8dd2e0885c7020b4095bb572536f5e2/images/indeximg.png)

Visite the site ---> https://raj-dey.github.io/BMI-Calculator/

---

## 🔧 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/bmi-calculator.git
   cd bmi-calculator
   ```

2. **Run locally**:
   - Open `index.html` in your browser.

3. **No additional setup or libraries required.**

---

## ✍️ Authors

- *** RAJ DEY

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Inspired by modern wellness apps and health calculators.

---

## 📖 Project Description

The **BMI Calculator** is a modern, responsive web application that enables users to calculate their **Body Mass Index (BMI)** — a commonly used indicator to assess whether a person is underweight, at a healthy weight, overweight, or obese based on their height and weight. Built using **HTML**, **CSS**, and **vanilla JavaScript**, this project demonstrates practical front-end development skills with a real-world use case.

### 🧠 Purpose

The goal of this application is twofold:

1. To provide a quick and reliable tool for calculating BMI using standard formulas.
2. To educate users about the importance and limitations of BMI as a health metric.

This calculator goes beyond the numbers by offering insights into healthy lifestyle habits and informing users about the factors that can affect BMI accuracy, such as muscle mass, age, gender, pregnancy, and ethnicity.

---

### ⚙️ How It Works

Users can select between two unit systems:

- **Metric** (height in cm, weight in kg)
- **Imperial** (height in feet/inches, weight in stone/pounds)

The BMI is calculated using the following formulas:

- **Metric Formula**:
  ```
  BMI = weight (kg) / (height (m))²
  ```

- **Imperial Formula**:
  ```
  BMI = 703 × weight (lbs) / (height (in))²
  ```

Once the data is entered, the app instantly calculates the BMI and displays it along with an interpretation (e.g., "Healthy weight") and ideal BMI range information.

---

### ✨ Key Features

- 🔄 **Unit Switching** – Easily switch between metric and imperial units.
- ⚡ **Real-Time Calculation** – BMI is calculated as soon as the user inputs their data.
- 📚 **Informative Results** – The result section not only shows your BMI but also includes health guidance and ideal ranges.
- 📱 **Fully Responsive** – Designed to work smoothly on mobile, tablet, and desktop screens.
- 🎨 **Clean & Modern UI** – Styled with CSS to offer a polished and accessible user experience.
- ⚠️ **BMI Limitations Section** – Provides context around when BMI may not be a reliable health measure.

---

### 🛠️ Technologies Used

- **HTML5** – Structured and semantic markup.
- **CSS3** – Responsive layouts, gradients, and styled components.
- **JavaScript (Vanilla)** – Handles input logic, DOM updates, and BMI calculations.

---

### 💡 Why This Project?

This project is perfect for:

- Front-end developers looking to strengthen their skills in JavaScript and responsive design.
- Health and wellness platforms that want to embed a simple BMI tool.
- Educational institutions teaching basic health metrics or web development.

It shows how real-life tools can be built using foundational web technologies without relying on frameworks or libraries.

---

### 📌 Additional Notes

- The BMI Calculator includes images, icons, and informative visuals to enhance user engagement.
- All calculations are performed on the client side for quick and smooth user interaction.
- Input fields are validated for number types and styled for usability.
