# Note Everything - Web Production Build

This repository contains the production-ready build for the **Note Everything Web** application. 
The files here are generated from the main source code and optimized for fast performance and static deployment.

## 🚀 Deployment

Since this is a static build (compiled via Vite & React), you can easily host this directory on any static web hosting service, such as:

- **GitHub Pages**
- **Vercel**
- **Netlify**
- **Cloudflare Pages**
- **Firebase Hosting**

Simply point your hosting provider to serve the contents of this directory as the root folder.

## 🔄 Updating the Build

When new updates are available in the main source code repository:
1. Run `npm run build` in the main project root.
2. Copy the generated files from `dist/` into this `deploys/` directory.
3. Commit and push the changes:
   ```bash
   git add .
   git commit -m "Update production build"
   git push origin main
   ```
*(A helper script `push.sh` is included for quickly pushing updates).*

## 📱 Mobile App

Note Everything is designed for two-way synchronization via Google Drive AppData with our mobile apps:
- [Google Play Store](https://play.google.com/store/apps/details?id=com.wrap.apps.note)
- [Apple App Store](https://apps.apple.com/us/app/note-everything/id6479020525)
