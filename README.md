# Tools to convert website image to frontend code

## Method 1: Use GPT Store (GPTs) third party tool
If you have GPT-4 access, it is very likely you can access GPT Store (GPTs). Here are the major steps:

1. Click "Explore GPTs" 
2. Search the third party app "Screenshot To Code GPT"
3. Click "Start Chat"
4. Upload a screenshot
5. Wait for the application to finish generating results
6. Copy code to a static HTML file
7. Open the HTML file in browser to preview the website

A video for using "Screenshot To Code GPT" is used below:

![Video recording for Screenshot To Code GPT](https://github.com/lilyyy01/screenshot_to_code_tutorial/tree/main/movie/GPTs_screen2code.mp4)


## Method 2: Use Vercel V0 to build React/NextJS frontend
Vercel, the creator of NestJS, also provides an AI tool for you to convert website screenshot to frontend code in React.

Here are the major steps:
1. Go to the website: https://v0.dev/
2. Upload the image
3. (Optional) Choose either  "Speed" or "Quality" mode
4. Click submit to let the AI run
5. After AI stops running, click "Code" button on top right to see the corresponding code
6. A link is provided to install the created code using npx package manager locally (e.g., npx v0 wq23fn4sef)
7. In your NextJS project, cd into your app folder, and install the v0 package by running "npx v0@latest init"
8. Then, copy the command from the website (e.g., npx v0 wq23fn4sef)
9. Choose the name corresponds to the AI generated component
10. In your webpage, load the component.
11. Use "npm run dev" to run the app locally, go to the page to see the generated component

A video for using "Vercel V0" is used below:

![Video recording for Vercel v0](https://github.com/lilyyy01/screenshot_to_code_tutorial/tree/main/movie/vercel_v0.mp4)

