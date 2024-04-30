# install vite and npm modules
# for installing npm in vite

# npm create vite@latest

# for creating node

# npm i


<!-- Installing tailwind  -->

# step first

# npm create vite@latest my-project -- --template react
# cd my-project

# step second 

# npm install -D tailwindcss postcss autoprefixer
# npx tailwindcss init -p

# step third

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

# step forth

@tailwind base;
@tailwind components;
@tailwind utilities;

# start your build process

npm run dev