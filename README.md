# Portfolio — deploy on Vercel

## 1. Edit
- `index.html`: change text, email, LinkedIn, GitHub, project links.
- Add to `assets/`: `profile.jpg`, `cv.pdf`, `project-1.jpg` … `project-3.jpg`.

## 2. Push to GitHub
```bash
git init
git add .
git commit -m "portfolio"
git branch -M main
git remote add origin https://github.com/<you>/portfolio.git
git push -u origin main
```

## 3. Deploy
1. Go to vercel.com → sign in with GitHub.
2. Add New → Project → import `portfolio`.
3. Framework: **Other**. No build command. Click **Deploy**.
4. URL: `https://<project-name>.vercel.app`

Each `git push` = auto redeploy.
