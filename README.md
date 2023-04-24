# TrueFoundry Frontend Assignment

## Table of Contents

</li>
<li><a  href="#problem-statement">Problem Statement</a>
</li>
<li><a  href="#tech-stack">Tech Stack</a></li>
<li><a  href="#other-packages">Other Packages</a></li>
<li><a  href="#website-screenshot">Website Screenshot</a></li>
<li><a  href="#getting-started">Getting Started</a>
<li><a  href="#available-scripts">Available Scripts</a>

## Problem Statement

You have to create a React application that will allow users to paste a UI schema on the left side and preview the rendered form on the right-hand side. The application will have a single screen which will be divided into two equal sections next to each other. On the left section will be a JSON editor to paste the UI-Schema. On the right section, a form will be automatically rendered based on the pasted UI-Schema.

## Tech Stack

- [React](https://react.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)

## Other Packages

- [react-syntax-highlighter](https://www.npmjs.com/package/react-syntax-highlighter)
- [react-modal](https://www.npmjs.com/package/react-model)
- [react-select](https://www.npmjs.com/package/react-select)
- [react-switch](https://www.npmjs.com/package/react-switch)

## Website Screenshot

[UI Schema for Pizza](https://drive.google.com/file/d/1RUU_ueF9BbQRLReuX88w8PWe2jsz3Z3C/view)
![image](https://user-images.githubusercontent.com/91727830/233930504-ecbc1581-3050-4c36-90de-0f8f5037b80d.png)
![image](https://user-images.githubusercontent.com/91727830/233930585-d513c9c7-e1b7-430a-9cea-04e733b6af96.png)

<br />

[UI Schema for Pasta](https://drive.google.com/file/d/19_E6dSDUbiDR31wNSSvUARHxh1HeT6L4/view)
![image](https://user-images.githubusercontent.com/91727830/233930166-d2d2a9d9-b7f3-4d81-99a1-d4f6e1ed5119.png)
![image](https://user-images.githubusercontent.com/91727830/233930264-4fab36f4-67c8-41bf-851b-bd3e12aaf9e6.png)

## Getting Started

```bash
frontend
    |-- src
    |  |-- common
    |  |  |-- components
    |  |  |  |-- elements
    |  |  |  |   |-- Input.tsx
    |  |  |  |   |-- Radio.tsx
    |  |  |  |   |-- Select.tsx
    |  |  |  |   |-- Switch.tsx
    |  |  |  |   |-- Toggle.tsx
    |  |  |  |-- form
    |  |  |  |   |-- index.tsx
    |  |  |  |-- ElementRenderer.tsx
    |  |  |  |-- ToolTip.tsx
    |  |  |  |-- UiComponents.tsx
    |  |  |-- context
    |  |  |  |-- Provider.tsx
    |  |  |-- types
    |  |  |  |-- component.ts
    |  |  |  |-- form.ts
    |  |-- utils
    |  |  |-- parse-label.ts
    |  |-- App.css
    |  |-- App.tsx
    |  |-- index.tsx
    |-- .gitignore
    |-- package.json
    |-- README.md
    |-- tailwind.config.js
    |-- tsconfig.json
    |-- yarn-error.log
    |-- yarn.lock
```

<br />

This is a [React.js](https://react.dev/) project bootstrapped with [`create-react-app`](https://github.com/facebook/create-react-app).

<br />

Firstly, make sure you have [Nodejs](https://nodejs.org/en) installed.

<br />

**To Install all the required node modules**

```bash
npm install
# or
yarn install
```

<br />

**To run the development server:**

```bash
npm start
# or
yarn start
```

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**
