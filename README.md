````markdown
# 🕒 25 + 5 Clock React App

This project is a fully functional **25 + 5 Pomodoro Clock** built with **React**, fulfilling all **freeCodeCamp Front End Libraries Certification** requirements.

[Live Demo](https://25--5-clock.freecodecamp.rocks)

---

## 📋 Project Overview

This Pomodoro-style timer cycles between **25-minute work sessions** and **5-minute breaks**, letting you:

- Adjust session and break durations.
- Start, pause, and reset the timer.
- Get audible alerts when switching periods.

This project satisfies all **28 user stories** defined by freeCodeCamp’s project spec.

---

## ✅ User Stories (Requirements)

The app meets the following core requirements:

### Layout & Display

- `#break-label` and `#session-label` visible.
- `#break-length` (default `5`) and `#session-length` (default `25`) display correct values.
- `#timer-label` and `#time-left` (always `mm:ss` format) present.

### Controls

- Increment/decrement controls:
  - `#break-increment`, `#break-decrement`
  - `#session-increment`, `#session-decrement`
- Play/pause with `#start_stop`
- Reset button: `#reset`

### Behavior

- Adjust durations (1–60 minutes only).
- Countdown begins from current session value.
- Timer runs and updates every 1000ms.
- Toggle pause/resume with `#start_stop`.
- Cycles between sessions and breaks at `00:00`.
- Plays audio (`#beep`) at transitions.
- `#beep` resets when clicking `#reset`.

---

## 🔧 Technologies Used

- **React 18+**
- **JavaScript (ES6)**
- **HTML5 / CSS3**
- **Bootstrap 5** (optional for styling)
- **HTML5 `<audio>`** for alarm
- **freeCodeCamp test bundle**

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/25-5-clock.git
cd 25-5-clock
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the App

```bash
npm start
```

Then open `http://localhost:3000` in your browser.

---

## 🧪 Testing

To test your project against FCC's specifications:

### Use This CDN in `index.html`:

```html
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
```

This enables the FCC test suite in your browser.

### Testing Instructions:

* Click the **"Tests"** dropdown (bottom right).
* Select "**Front End Libraries Projects**" > "**25 + 5 Clock**".
* Click "**Run Tests**".
* Ensure **all 28/28 tests** pass.

---

## 🎵 Audio Requirements

* `#beep` audio clip must be ≥ 1 second.
* Audio must be triggered at timer transitions.
* On reset:

  * Pause and reset audio.

---

## 🧠 Notes

* React 18 may have compatibility issues with FCC’s test suite. Downgrading to **React 17** is a reliable workaround.
* Styling is up to you—add your own flair!
* Functional or class components are acceptable.
* No backend required.

---

## 📁 Folder Structure

```
25-5-clock/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── Timer.js
│   ├── App.js
│   ├── App.css
│   └── index.js
├── package.json
└── README.md
```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## ✍️ Author

**Jordan Leturgez**
Built for [freeCodeCamp](https://www.freecodecamp.org) Front End Libraries Certification.

```
