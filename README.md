# TimeArch

Static TimeArch daily tracker, ready for GitHub + Vercel.

## Deploy on Vercel

1. Create a new GitHub repository.
2. Upload everything inside this folder to the repository root.
3. Import that repository in Vercel.
4. Choose **Other** as the framework preset if Vercel asks.
5. Leave build command and output directory empty.

Vercel will serve `index.html` automatically.

## Single-file deploy

If you want to upload only one file, upload `index.html` to your GitHub repository root. The app will work as a normal static site, but install/offline PWA support needs `manifest.webmanifest`, `sw.js`, and `icon.svg` too.
