# Razorpay_clone
Html and Taliwind (CSS framework), responsive
(set enviornment variables if necessary)
**how to run the file on windows**
1. install nodejs on machine by visiting nodejs.org
2. make folder and clone the repository
3. open terminal
4. type **npm init** in terminal
5. {
  "name": "tailwind_demo",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
} 
6. press yes
7. type **npm i vite** in terminal for vite installation 
8. type **npm install -D tailwindcss postcss autoprefixer** in terminal for dev dependency installation (node_modules)
9. type **npx tailwindcss init** in terminal, it will install file with name **tailwind.config.js**
10. open file **taiwind.config.js** in that replace content with **content: ["*"],** so that it will be applied to main folder
11. open file **taiwind.config.js** in the extend section add below code
    fontFamily: {
        mullish: ["Mulish", "sans-serif"],
      },
      colors: {
        deepBlue: "#02042a",
        lightBlue: "#2b84ea",
        lightBlue300: "#4b94ed",
        lightBlue500: "#0b72e7",
        greenLight: "#61cea6",
        grayText: "#818597",
        lightGray: "#e2e2e2",
        grayBlue: "#344a6c",
        deepBlueHead: "#162f56",
        gray2: "#525a76",
      },
12. make file in main folder with name **postcss.config.js** and add below code
        module.exports = {
      plugins: {
        tailwindcss: {},
        autoprefixer: {},
      }
    }

13. make file in main folder with name **main.css** and add below code
      @tailwind base;
      @tailwind components;
      @tailwind utilities;

14. open **package.json** file in script add **"start": "vite"**
15. if cloned repository than run cmd on terminal as **npm start** and **ctr+click**  on localHost to run project
16. if not clone than link make html file link main.css to html and follow step no 14 to run after building own project.
