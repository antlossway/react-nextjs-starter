# react starter kit with tailwind

## command used

- `npm create vite@latest`

- `npm install -D tailwindcss postcss autoprefixer`

- `npx tailwindcss init -p`

-  modify tailwind.config.js
```/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

- add in index.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

