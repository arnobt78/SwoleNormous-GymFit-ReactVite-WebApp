
![Screenshot 2024-09-08 at 01 19 47](https://github.com/user-attachments/assets/20bc47ba-6ccf-458b-bd37-6449cd0f1c1f) ![Screenshot 2024-09-08 at 01 20 28](https://github.com/user-attachments/assets/73df8bd0-2946-46d4-8b92-28a154173830) ![Screenshot 2024-09-08 at 01 21 18](https://github.com/user-attachments/assets/ffe45b85-5246-4b4e-9cc9-e1c77507519d) ![Screenshot 2024-09-08 at 01 22 12](https://github.com/user-attachments/assets/11391ac5-fbad-4754-bfa3-3d77d5a970c0)

## SwoleNormous-GymFit-ReactVite-WebApp

SwoleNormous is an ultimate gym training app built with React Vite and TailwindCSS and deployed on Netfily.

**Note: To check this web app live, click here:** https://swolenormous-arnob.netlify.app

## To Install Dependences

Before launching this web application, be sure to install all required dependencies, which are listed in the package.json file.

To install all dependencies, run this command from your project folder: `npm install`

## To Install NodeJS

Make sure you have NodeJS installed on your machine first, The installation instructions are here: https://nodejs.org/en/

## To Create TailwindCSS React Vite Project

Open up your terminal and bootstrap a new React Vite App by: `npm create vite@latest my-project -- --template react`

Then go to that project folder, and write this command via terminal from your project folder: `npm install -D tailwindcss postcss autoprefixer`

Then install tailwindcss and its peer dependencies, then generate your `tailwind.config.js` and `postcss.config.js` files: `npx tailwindcss init -p`

Then add the paths to all your template files in your tailwind.config.js file.

```
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
}
```

Then add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Run your project: `npm run dev`

Run on your browser Local: `http://localhost:5173/`

(For more details, visit: https://tailwindcss.com/docs/guides/vite )


## About swoldier.js and functions.js File

I didn't create the algorithm that links the gym training routines together. Instead, I copied the swoldier.js and functions.js files from GitHub and itegrated them into my project.
