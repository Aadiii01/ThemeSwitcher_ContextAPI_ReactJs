
# Theme Switcher

In this Project i made the Theme Switcher using **Context API** through `useContext` and `createContext`

## Description :-

In this Project You switch the dark mode and light mode and i use Tailwind for this, with the help of this project you should know the real use of Context API.

### Screenshots :- 

![Screenshot (62)](https://github.com/Aadiii01/PasswordGenerator_ReactJs/assets/134622355/1e59d3c6-0e8e-44e6-80f8-b85f34b6a74b)

---

![Screenshot (63)](https://github.com/Aadiii01/PasswordGenerator_ReactJs/assets/134622355/45332254-432a-49a3-a44c-cda1dfea9ed5)


## Installation

**Install my-project with npm**

```bash
  npm create vite@latest
  cd project_name
  npm install

```

**To install Tailwind** 

```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p
```

#### Necessary Changes in `tailwind.config.js` file :-

```javascript
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  darkMode: "class",
  theme: {
    extend: {},
  },
  plugins: [],
}

```


**To Run**
```bash
   npm run dev
```