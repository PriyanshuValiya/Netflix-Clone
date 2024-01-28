# Netflix-Clone
This is a Clone Website Of Netflix built using Tailwind.


# How to Setup Tailwind CSS ?
Step 1: Run the Following Commands.

```
npm i -D tailwindcss
npx tailwindcss init
```

Step 2: Update tailwind.conf.js file to include thie line 
```
content: ["*.html],
```

Step 3: Create src/input.css to include
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Step 4: Include the src/output.css file to your HTML.

Step 5: Run the following Commands.
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```