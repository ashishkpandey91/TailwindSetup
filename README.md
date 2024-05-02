## Setting up tailwind css 
**To setup tailwind css run these commands**
- Step_1. This initializes the directory as a NodeJs project
```bash
       npm init -y
```
- Step_2. Installs required packages
```bash
       npm install -D tailwindcss postcss autoprefixer vite
```
```bash
       npx tailwindcss init
```
- Step_3. Create a css file **input.css** add it to your html and edit it with this content:
  
  ```bash
         @tailwind base;
         @tailwind components;
         @tailwind utilities;
  ```
 - Step_4. In your tailwind.config.js file replace **content: [], with content: ["*"],**
  
 - Step_5. Add **"start" : "vite"** to your scripts in package.json
   
 - Step_6. Run **npm run start** command to start a dev server 
