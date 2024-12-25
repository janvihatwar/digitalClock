# Digital Clock

A simple Digital Clock application built with React to display the current time in real-time.

## Features
- Displays the current time in HH:MM:SS format.
- Updates in real-time every second.
- Responsive design for both desktop and mobile.

## Live Demo
[Demo Link](https://janvihatwar.github.io/digitalClock)

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/digital-clock.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the app:
   ```bash
   npm start
   ```

## Deployment to GitHub Pages
1. Install `gh-pages`:
   ```bash
   npm install gh-pages --save-dev
   ```
2. Add this to `package.json`:
   ```json
   "homepage": "https://<your-username>.github.io/digital-clock",
   "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d build"
   }
   ```
3. Deploy:
   ```bash
   npm run deploy
   ```


## What I Learned
- **React Hooks:** Learned how to use the `useState` and `useEffect` hooks for managing state and side effects in a React application.
- **Date API:** Utilized JavaScript's `Date` object to fetch and format the current time.
- **Real-time Updates:** Understood how to set up intervals in React for real-time updates and how to clean them up to prevent memory leaks.



### Thank you for checking out the Digital Clock!
### Happy coding!
