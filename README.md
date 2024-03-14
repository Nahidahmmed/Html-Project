1st  

<"link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet">

2nd 

npm init -y

3rd

npm install tailwindcss postcss autoprefixer -D

4th

npx tailwindcss init -p

5th

@tailwind base;
@tailwind components;
@tailwind utilities;

6th

"scripts": {
  "build": "tailwindcss -i ./styles.css -o ./dist/output.css --watch"
}


7th

npm run build

8th

<"link href="./dist/output.css" rel="stylesheet">
