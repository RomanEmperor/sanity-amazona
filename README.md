#Sanity Amazona

## Lessons

1. Introduction
   1. What we will be learning
   1. What we will be building
   1. What packages we will be using
2. Required Tools to be installed

   1. VS Code
   1. Chrome
   1. Git
   1. Node js

3. Starting Development

   1. npx create-next-app@latest
   2. add @mui library : `npm install --save --legacy-peer-deps @mui/material @mui/styles @mui/icons-material @emotion/styled @emotion/server @emotion/react`

4. Publish to github

   1. sign in to github account
   2. push to github from vs code

5. Create website layout

   1. Add header
   2. Add Main Section
   3. Add footer

6. Connect to Sanity.io

   1. Install Sanity
      `npm install -g @sanity/cli`
      `sanity init --coupon codingwithbasir`
   2. initialize Sanity
   3. create product model
   4. insert sample data to the product model

7. List Products
   1. Add localhost:3000 to the CORS origins in sanity
   2. Added package to connect to sanity from next applicaiton
      2.1 client : `npm install @sanity/client`
      2.2 Add package image `npm install @sanity/image-url`
   3. Created components
      3.1 Created client.js: to make it easy to connect to the sanity server
      3.2 Created config.js: to access from sigle source file
      3.3 Product item: to render product thumbnail in the home screen index.js
   4. Added Utility
      4.1 Created utility file: image.js :: to get imageUrl from sanity
