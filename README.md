# Razorpay_clone
Html and Taliwind (CSS framework), responsive
(set enviornment variables if necessary)
**how to run the file on windows**
1. install nodejs on machine by visiting nodejs.org
2. 
3. make folder and clone the repository
4. open terminal
5. type **npm init** in terminal
6. {
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
7. press yes
8. type **npm i vite** in terminal for vite installation 
9. type **npm install -D tailwindcss postcss autoprefixer** in terminal for dev dependency installation (node_modules)
10. type **npx tailwindcss init** in terminal, it will install file with name **tailwind.config.js**
11. open file taiwind.config.js in that replace content with **content: ["*"],** so that it will be applied to main folder
12. 
13. make file in main folder with name **postcss.config.js** and add below code
        module.exports = {
      plugins: {
        tailwindcss: {},
        autoprefixer: {},
      }
    }

14. make file in main folder with name **main.css** and add below code
      @tailwind base;
      @tailwind components;
      @tailwind utilities;

15. open **package.json** file in script add **"start": "vite"**
16. if cloned repository than run cmd on terminal as **npm start** and **ctr+click**  on localHost to run project
17. if not clone than link make html file link main.css to html and follow step no 14 to run after building own project.
