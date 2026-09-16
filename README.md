# Background Color Changer

A simple and interactive web project that allows users to change the background color of a webpage by clicking buttons or selecting different color options.

## 📌 Project Overview

The **Background Color Changer** is a beginner-friendly frontend project built using HTML, CSS, and JavaScript. It demonstrates how JavaScript can interact with the DOM to dynamically change the background color of a webpage.

This project is useful for understanding event handling, DOM manipulation, and JavaScript functions.

## ✨ Features

* **Change Background Color** – Change the webpage background with a click.
* **Multiple Color Options** – Select from different predefined colors.
* **Random Color Generator** – Generate a random background color (if implemented).
* **Reset Color** – Restore the default background color (if implemented).
* **Interactive Buttons** – Each button applies a different color.
* **Responsive Design** – Works on desktop, tablet, and mobile devices.
* **Simple User Interface** – Clean and easy-to-use design.

## 🛠️ Technologies Used

| Technology     | Purpose                                 |
| -------------- | --------------------------------------- |
| **HTML5**      | Structure of the webpage                |
| **CSS3**       | Styling and layout                      |
| **JavaScript** | Color-changing logic and event handling |

## 📂 Project Structure

```text id="q8k4v2"
background-color-changer/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash id="h3j8q1"
git clone https://github.com/your-username/background-color-changer.git
```

### 2. Open the Project Folder

```bash id="m5n2r8"
cd background-color-changer
```

### 3. Run the Project

Open `index.html` in your browser.

You can also use **VS Code Live Server**:

1. Open the project in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

## ⚙️ How It Works

```text id="p2d7x4"
User clicks a color button
            ↓
JavaScript detects the click event
            ↓
Selected color is applied to the body
            ↓
Background color changes instantly
```

## 💻 Example JavaScript

```javascript id="v8s1k3"
const buttons = document.querySelectorAll(".color-btn");

buttons.forEach((button) => {
  button.addEventListener("click", () => {
    document.body.style.backgroundColor = button.dataset.color;
  });
});
```

### Example HTML

```html id="n4r6t2"
<button class="color-btn" data-color="red">Red</button>
<button class="color-btn" data-color="blue">Blue</button>
<button class="color-btn" data-color="green">Green</button>
```

## 🎯 Learning Objectives

This project helps practice:

* HTML buttons and attributes
* CSS styling
* JavaScript DOM manipulation
* `querySelectorAll()`
* `forEach()`
* Event handling
* `addEventListener()`
* `dataset`
* Functions
* Dynamic styling
* Basic frontend project structure

## 🔮 Future Improvements

* Add a color picker
* Generate random HEX colors
* Display the selected color code
* Add copy-to-clipboard functionality
* Add gradient background support
* Add dark and light themes
* Save the selected color using LocalStorage

## 📸 Screenshots

Add screenshots of your project here:

```markdown
![Background Color Changer Screenshot](screenshots/preview.png)
```

## ⚠️ Disclaimer

This project is created for **educational and demonstration purposes**.

## 👨‍💻 Author

**Rishi kumar**

## 📄 License

This project is open-source and available for educational use.
