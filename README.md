# Portfolio of Joseph Andrew P. Sacil

**AI Tools Acknowledgment**

ChatGPT was my primary AI tool for coding assistance, debugging, and improving the structure of my website. Other AI tools, such as Google Gemini, Claude, and GitHub Copilot, may also be used to support coding ideas, problem-solving, and code improvements. All generated code was reviewed and customized to fit the requirements of my portfolio.**.

## Folder structure

```
Portfolio/
├── index.html      homepage (your text, projects and links)
├── style.css       design (colors, fonts, layout, background)
├── script.js       interactions (menu, typing text, filters, search, form)
├── images/         profile picture, favicon, and project screenshots
│   ├── profile.jpg
│   └── favicon.svg
└── .vscode/        Visual Studio Code settings (optional)
```

## Languages used

| Language | File | What it does |
| --- | --- | --- |
| HTML | `index.html` | The content and structure of the page |
| CSS | `style.css` | The design, colors, fonts and animations |
| JavaScript | `script.js` | The interactive features |

## Open it in Visual Studio Code

1. Open VS Code, then choose **File > Open Folder** and select the `Portfolio` folder.
2. When VS Code asks to install the recommended extensions, click **Install**. This gives you **Live Server** and **Prettier**.
3. Right-click `index.html` and choose **Open with Live Server**. Your portfolio opens in the browser and refreshes every time you save.

No Live Server? You can also double-click `index.html` to open it in any browser.

## Where to edit things

- **Text, projects, links:** `index.html` (look for the `<!-- ========== ... ========== -->` comments)
- **Colors and fonts:** `style.css`, section 1 (`:root`)
- **Typing words and features:** `script.js`
- **Profile picture:** replace `images/profile.jpg` with a new picture of the same name (a 4:5 portrait works best)
- **Project screenshots:** put them in `images/`, then add `<img src="images/your-picture.jpg" alt="Describe the picture">` inside the project in `index.html`

## Publish it free with GitHub Pages

1. Create a **public** repository on github.com named `portfolio`.
2. Upload the **contents** of this folder (`index.html`, `style.css`, `script.js` and the `images` folder), not the zip file.
3. Go to **Settings > Pages**, set Source to **Deploy from a branch**, choose **main** and **/(root)**, then **Save**.
4. After a few minutes your site is live at `https://YOUR-USERNAME.github.io/portfolio/`.

## Troubleshooting: the photo shows text instead of a picture

This means GitHub cannot find `images/profile.jpg`. In your repository, check that there is an **images** folder containing **profile.jpg** (the name must match exactly, including lowercase letters). If it's missing, choose **Add file > Upload files** and drag the whole **images** folder in, then **Commit changes**. (`script.js` also has a built-in backup copy of your photo, so the page still shows your picture while you fix this.)
