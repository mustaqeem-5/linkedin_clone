## How to setup Tailwind CSS

Step 1: Run the followinf commands

```
npm install -D tailwindcss 
npx tailwindcss init
```

Step 2: Update tailwind.conf.js file to include this line:
```
content: ["./*.html"],
```
Step 3: create src/input.css to include:
```
@import "tailwindcss";
```
Step 4: Include the src/output.css file to your html

Step 5: run the following command:
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

