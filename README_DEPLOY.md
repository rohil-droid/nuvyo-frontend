
# Nuvyo Frontend — Netlify Deployment

## 1) Connect to Netlify
- New Site from Git → select this repo
- Build command: *(leave blank for static)*
- Publish directory: `/` (or the folder containing `index.html`)

## 2) Link the Try Now button
Open `config.js` and set:
```
window.NUVYO_BACKEND_URL = "https://YOUR-BACKEND.onrender.com";
```

## 3) Optional
- Set a Netlify custom domain or subdomain
