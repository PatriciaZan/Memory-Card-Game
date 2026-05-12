# Memory Card Game

![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

An elegant and interactive memory game developed with React 19 and Vite. Test your perception and speed by finding all the matching card pairs in the shortest time possible!

## 📸 Demonstration

<div align="center">
  <img src="prints/1.png" alt="Interface do Jogo" width="400px" style="border-radius: 10px">
  <img src="prints/2.png" alt="Mensagem de Vitória" width="400px" style="border-radius: 10px">
</div>

## 🚀 Technologies Used

This project was built using the the Frontend ecosystem:

**React 19**:\*\* Main library for building the interface.

**Vite**:\*\* Ultra-fast tooling for the development and build environment.

**ESLint**:\*\* Code standardization and quality.

**Custom Hooks**:\*\* Game logic decoupled from the interface for better maintainability.

## 🎮 The Game

The objective is simple: find all pairs of identical icons.

### Main Features:

- **Complex State Control:** Management of flipped cards, pairs found, and attempts.

- **Visual Feedback:** Flip animations and victory messages.

- **Responsive Design:** Play smoothly on any screen size.

- **Custom Hooks:** Use of `useGameLogic` to isolate the business logic from the visual component.

## 🛠️ How to Run the Project

Follow the steps below to run the project locally:

1. **Clone the repository:**

```
git clone https://github.com/PatriciaZan/Memory-Card-Game.git
```

2. **Access the project folder:**

```
cd Memory-Card-Game
```

3. **Install the dependencies:**

```
npm install
```

4. **Start the development server:**

```
npm run dev
```

5. **Access in your browser:**

Open the link displayed in the terminal (usually `http://localhost:5173`).

## 📁 Folder Structure

```
src/
├── components/       # Visual components (Card, WinMessage, etc.)
├── hooks/            # Logic extracted (useGameLogic.js)
├── public/           # Static assets (SVG for page icons)
├── App.jsx           # Main component
└── main.jsx          # React entry point
```

## ✒️ Author

Developed with ❤️ by **Patrícia Zan**.

---

_This project is for the purpose of studying and practicing advanced concepts of React Hooks and state manipulation._
