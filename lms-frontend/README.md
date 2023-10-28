# lms frontend

### setup instruction

1 clone the project

...git clone git remote add origin https://github.com/nandankushwaha62/lms-project.git

2 move into the directory

...cd lms-frontend-hn

3 install dependencies
...npm i

4. run the surver
... npm run dev

1. npm install -D tailwindcss postcss autoprefixer

...npx tailwindcss init -p

2. Add file extenstion to tailwind config file in the contends properties
  ..."./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",

3. Add the tailwind directive at the top of the index.css
...@tailwind base;
...@tailwind components;
...@tailwind utilities;