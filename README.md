# Ankur Portfolio

Personal portfolio site for [Ankur Samad](https://github.com/Ankur-Samad). Single-page static site with dark/light theme, animated hero, certifications gallery, and contact links.

**Repository:** [github.com/Ankur-Samad/ankur-portfolio](https://github.com/Ankur-Samad/ankur-portfolio)  
**Live site (after deployment):** [https://ankur-samad.github.io/ankur-portfolio/](https://ankur-samad.github.io/ankur-portfolio/)

## Project structure

```
├── index.html              # Main portfolio page
├── assets/
│   ├── profile.png         # Profile photo
│   └── certificates/       # Certificate images
├── .nojekyll               # Required for GitHub Pages
└── README.md
```

## Deploy to GitHub Pages

1. Create a public repository named **`ankur-portfolio`** on [GitHub](https://github.com/new) under the **Ankur-Samad** account.
2. Push this folder to the `main` branch:

   ```bash
   cd "/Users/rajba/Desktop/Ankur Portfolio"
   git init
   git add .
   git commit -m "Initial portfolio deploy"
   git branch -M main
   git remote add origin https://github.com/Ankur-Samad/ankur-portfolio.git
   git push -u origin main
   ```

3. In the repo, go to **Settings → Pages**.
4. Set **Source** to **Deploy from a branch**.
5. Choose branch **`main`** and folder **`/ (root)`**, then click **Save**.
6. Wait 1–2 minutes. Your site will be live at:

   **https://ankur-samad.github.io/ankur-portfolio/**

## Local preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Contact

- **Email:** ankursamad20@gmail.com
- **GitHub:** [Ankur-Samad](https://github.com/Ankur-Samad)
- **LinkedIn:** [ankur-samad-111a86336](https://www.linkedin.com/in/ankur-samad-111a86336)
