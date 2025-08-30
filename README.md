🎨 Background Color Changer (React + TailwindCSS)

This is a simple React project that allows users to change the background color of the entire screen by clicking on different color buttons. It is built using React and styled with TailwindCSS.

🚀 Features

Change the screen background by clicking on color buttons

Smooth transition effect (duration-200)

Responsive button layout with rounded, shadowed styling

Implemented using React useState hook for state management

🛠️ Tech Stack

React (Functional Components, Hooks)

TailwindCSS (for styling)

📂 Project Structure
.
├── src
│   ├── App.jsx       # Main component with color changer logic
│   ├── index.css     # Tailwind styles
│   └── main.jsx      # React DOM rendering
├── package.json
└── README.md

📖 How It Works

The app maintains a state variable color using useState.

On clicking a button, setColor updates the state with the selected color.

The background color of the screen is dynamically updated using inline styles.

🖼️ Demo Screenshot

(Add your screenshot here if you want)

⚡ Installation & Setup

Clone the repository

git clone https://github.com/your-username/background-color-changer.git
cd background-color-changer


Install dependencies

npm install


Run the development server

npm run dev


Open http://localhost:5173
 in your browser

📌 Example Code Snippet
const [color, setColor] = useState("olive");

<div className="w-full h-screen duration-200" style={{ backgroundColor: color }}>
  <button onClick={() => setColor("red")}>Red</button>
  <button onClick={() => setColor("blue")}>Blue</button>
</div>

🎯 Future Improvements

Add a custom color picker (<input type="color" />)

Save last selected color in localStorage

Add gradient background options

👨‍💻 Author

Sahil Rathore
