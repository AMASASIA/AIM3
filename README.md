


# AIM3-ADM (v1.0) – All-in-One DAO & Messaging SuperApp

This repository contains the fully integrated AIM3-ADM super app, combining video chat, AI map visualization, Stripe payments, NFT/SBT minting, and DAO governance UI.

---

## ✅ Features

### 1. 🎥 Video Chat (LiveKit or WebRTC)
- Join and create rooms for video/audio chat
- LiveKit integration (preferred)
- Fallback to WebRTC if needed

### 2. 🧠 AiMap.vue – AI-Powered Visualization
- Visual thread/mindmap view of DAO discussions
- Tracks messages, proposals, and votes
- Syncs with AI Advocacy panel

### 3. 💳 Stripe Payments + NFT Minting
- Stripe Checkout integration for credit card payments
- Upon successful payment:
  - Mint NFT (ERC-721)
  - Issue Soul-Bound Token (ERC-5192)
  - Create ERC-6551 Token Bound Account
- Connected to AI Map for traceability

### 4. 🛠 Vercel & GitHub Integration
- Vite-based build system
- Preconfigured `vercel.json` for Vercel auto-deploy
- `.github/workflows/deploy.yml` for CI/CD (coming soon)

---

## 🧪 How to Run Locally

```bash
npm install
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173).

---

## 🚀 Vercel Deploy Instructions

**Framework Preset**: `Vite` or `Other`  
**Build Command**: `npm run build`  
**Output Directory**: `dist`

Make sure your `vercel.json` contains:

```json
{
  "buildCommand": "npm run build",
  "outputDirectory": "dist",
  "framework": "vite"
}
```

---

## 📁 Structure

```
src/
  components/
    VideoChat.vue
    AiMap.vue
  App.vue
  main.js
public/
vercel.json
vite.config.js
README.md
```

---

## 📌 Notes

- ERC contracts are mocked for demo – can be replaced with live smart contracts.
- LiveKit credentials need to be configured in `.env.local`.
- AI Map uses mocked messages, can be extended to backend or P2P layer.

---

## 📬 Contact

For more info or contribution requests, contact:info@amas.asia









# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
