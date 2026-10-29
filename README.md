# 🔐 OTP Timer & Verification – React

A sleek, responsive, and fully functional OTP verification UI featuring a built-in countdown timer. Built with **React.js** and **Vite**, this project showcases practical implementations of modern React Hooks, interval management, and clean UI/UX design.

## 🚀 Features

- ⏱️ **Dynamic Timer:** 2-minute countdown (02:00) that updates in real-time.
- 🔄 **Smart Interval Management:** Automatically decreases every second and safely clears the interval at 00:00.
- 📥 **Intuitive Input:** Seamless and responsive OTP input fields.
- 🔁 **Resend Functionality:** 'Resend OTP' button that resets the timer instantly.
- ⚛️ **Modern React:** Built purely with Functional Components, `useState`, and `useEffect`.
- 🎨 **Custom Styling:** Clean, modern, and mobile-friendly design using CSS3.

## 🛠️ Technologies Used

- **React.js** (Hooks architecture)
- **Vite** (Lightning-fast build tool)
- **JavaScript** (ES6+)
- **CSS3 & HTML5**
- 
```markdown
## 📂 Project Structure

```text
src/
├── Components/
│   ├── OtpPage.jsx
│   └── OtpPage.css
├── App.jsx
├── App.css
├── main.jsx
└── index.css

```

## ⚙️ Installation and Setup

1. **Clone the repository:**
```bash
git clone [https://github.com/aadiyadav8155/Otp-page.git](https://github.com/aadiyadav8155/Otp-page.git)

```


2. **Navigate to the project folder:**
```bash
cd Otp-page

```


3. **Install dependencies:**
```bash
npm install

```


4. **Start the development server:**
```bash
npm run dev

```


5. Open the local URL (usually `http://localhost:5173/`) displayed in your terminal.

## 🧠 React Concepts Practiced

* **`useState`**: Storing and updating the remaining countdown time seamlessly.
* **`useEffect`**: Mounting the timer logic, managing side effects, and preventing memory leaks.
* **`setInterval()` & `clearInterval()**`: Handling browser timing events safely within React's lifecycle.
* **Time Formatting**: Using `Math.floor()` and modulo (`%`) to dynamically convert raw seconds into a formatted `MM:SS` string.
* **Functional State Updates**: Ensuring the countdown accurately updates based on the previous state to avoid rendering bugs.

## 📌 Future Improvements

* [ ] Add auto-focus behavior that jumps to the next input box automatically.
* [ ] Disable the 'Resend OTP' button visually and functionally while the timer is still running.
* [ ] Implement error handling and success messages for incorrect/correct OTP entries.
* [ ] Connect the frontend UI to a live backend API for real OTP generation and validation.

## 👨‍💻 Author

**ADITYA YADAV**

*Full Stack Web Development*

GitHub: [@aadiyadav8155](https://www.google.com/search?q=https://github.com/aadiyadav8155)

```

```
