# Sign Up Form

## React Hook form

```bash
npm install react-hook form
```

## Yup

```bash
npm install yup @hookform/resolvers
```

##

## Etc.

### NextJS

```bash
npx create-next-app --typescript --use-npm
```

### TailwindCSS

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
npm install -D tailwindcss/forms
```

### `tailwind.config.js`

```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./pages/**/*.{js,jsx,ts,tsx}",
    "./components/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  darkMode: "media",
  plugins: [require("@tailwindcss/forms")],
};
```

### styles/global.css

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
