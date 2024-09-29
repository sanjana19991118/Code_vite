# Vite


React vite installation steps
==================
1) npm create vite@latest my-react-app --template react
Or 
npm create vite@latest 

OR 
npx legit user/project#main my-project 

cd my-project
npm install
npm run dev



Manual installation :  ->
------------------------- 
npm install -D vite
.html
<p>jhfsd</p>
vite
index.html will be served on -> http://localhost:5173


when you are ready to build app for production : 

npm run build

To test the production build locally : 
npm run serve 



To install tailwind css  
------------------------
1) Install Tailwind css and DEpendencies : Install Tailwind CSS PostCss, Autoprefixer : npm install -D tailwindcss postcss autoprefixer
2) Generate the tailwind.config.js and postcss.config.js files : 
npx tailwindcss init -p



3) Configure Template Paths: In your tailwind.config.js, add the paths to your template files (e.g., index.html, React components):

// tailwind.config.js
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};


4) Add Tailwind Directives to Your CSS: In your main CSS file (e.g., index.css), include the Tailwind directives:

/* index.css */
@tailwind base;
@tailwind components;
@tailwind utilities;

5) Use Tailwind Classes in Your Components: Now you can use Tailwind’s utility classes to style your React components. For example:

// src/App.jsx
export default function App() {
  return (
    <h1 className="text-3xl font-bold underline">
      Hello, world!
    </h1>
  );
}


npm create vite@latest
( enter details )

