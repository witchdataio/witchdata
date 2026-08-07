# WitchData Portfolio

A minimal static portfolio landing page featuring the WitchData logo and a GitHub link.

## Preview locally

From this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a new GitHub repository, for example `witchdata`.
2. Upload/push everything in this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will show the live site URL after deployment finishes.

## Git commands

```bash
git init
git add .
git commit -m "Launch WitchData portfolio"
git branch -M main
git remote add origin https://github.com/nickitaliano/witchdata.git
git push -u origin main
```

If you use a different repository name, replace the remote URL accordingly.
# witchdata
