# International Yoga Science Council (IYSC)

The global standard for IKS research, grassroots delivery, and biofeedback innovation. Validating ancient wisdom through empirical rigor.

## Features
- **Academic & Research Hub**: Journal submission portal and peer-reviewed research tracking.
- **Grassroots Delivery**: Multilingual media library for community health workers.
- **Technology & Analytics**: Real-time impact dashboard and biofeedback integration.
- **Global Network**: Strategic MoUs with leading institutions like IIT Delhi, NIMHANS, and NDMU.

## Tech Stack
- **React 19**
- **Vite**
- **Tailwind CSS 4**
- **Motion** (for state-of-the-art animations)
- **Recharts** (for real-time analytics)
- **Lucide Icons**

## How to Host on GitHub Pages

### 1. Prepare the Project
Ensure your project is in a GitHub repository.

### 2. Update `vite.config.ts`
Add the `base` property to your `defineConfig` in `vite.config.ts`:
```typescript
export default defineConfig({
  base: '/your-repo-name/', // Replace with your repository name
  // ... other config
})
```

### 3. Install the GitHub Pages Package
Run the following command in your terminal:
```bash
npm install gh-pages --save-dev
```

### 4. Add Deployment Scripts
In your `package.json`, add these scripts:
```json
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist",
  ...
}
```

### 5. Deploy
Run the deployment command:
```bash
npm run deploy
```

Your site will be live at `https://your-username.github.io/your-repo-name/`.

## Legal Info
Registered under Section 8 of the Companies Act, 2013.
Public Charitable Trust Registration: #IYSC-2024-DEL
