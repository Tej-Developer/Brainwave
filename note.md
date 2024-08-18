<div align="center">
  <br />
    <a href="https://youtu.be/kRQbRAJ4-Fs" target="_blank">
      <img src="https://i.postimg.cc/37PnQw8n/Image-from.png" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Three_JS-black?style=for-the-badge&logoColor=white&logo=threedotjs&color=000000" alt="three.js" />
    <img src="https://img.shields.io/badge/-GSAP-black?style=for-the-badge&logoColor=white&logo=greensock&color=88CE02" alt="greensock" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>

  <h3 align="center">Brainwave</h3>

   <div align="center">
     Build this project step by step with our detailed tutorial on <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a> YouTube. Join the JSM family!
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤸 [Quick Start](#quick-start)
2. 🕸️ [Snippets](#snippets)
<!-- 3. 🔗 [Links](#links) -->


## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

1. go to [tailwindcss](tailwindcss.com)
2. click get Started
3. go to quick Search and type vite
4. click on install tailwindcss with vite

### 1. Create a Project

```bash
npm create vite@latest ./ -- --template react
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

### 2. Create a Project

```bash
npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p
```
### 3. Configure your template paths

<summary><code>tailwind.config.js</code></summary>

```javascript
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html", 
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

### 4. Add the Tailwind directives to your CSS

Add this to your  <code>./src/index.css</code>


```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 5. Start your build process 

```base
npm run dev
```




## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>.vscode/settings.json</code></summary>

```json
{
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": "explicit",
        "source.addMissingImports": "explicit",
    },
    "prettier.tabWidth": 2,
    "prettier.useTabs": false,
    "prettier.semi": true,
    "prettier.singleQuote": false,
    "prettier.jsxSingleQuote": false,
    "prettier.trailingComma": "es5",
    "prettier.arrowParens": "always",
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[css]": {
        "editor.defaultFormatter": "vscode.css-language-features"
    },
    "[svg]": {
        "editor.defaultFormatter": "jock.svg"
    }
}
```

</details>

from video description take code for this file
`tailwind.config.js` and paste code to this file

**timeline `4:07:00`**

from video description take code for this file
`index.css` and paste code to this file

**timeline `4:07:50`**

add 
```css
:root { color-scheme:dark; }
```

**create a new terminal and paste this**
```bash
npm install react-router-dom
```

**use router in main.jsx**
```jsx
import { BrowserRouter as Router } from "react-router-dom";
<Router>
    <App />
</Router>
```

**Package for Disable page Scrolling**
while hamburger is open in smaller devices

```bash
npm install scroll-lock
```

**Diffrernt Purpose**
```bash
npm install react-just-parallax
```