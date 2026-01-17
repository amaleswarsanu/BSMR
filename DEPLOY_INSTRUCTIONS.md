# How to Host the BSMR Group Website

State-of-the-art websites like this one deserve high-performance hosting. Since this is a static site (HTML/CSS/JS), you have several excellent free and premium options.

## Option 1: Netlify Drop (Easiest & Fastest)
*Best for: Instant public link, no account required initially.*

1.  Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2.  Open your file explorer to the `BSMR` folder on your desktop.
3.  Drag and drop the **entire `BSMR` folder** into the "Drop your site folder here" area.
4.  **Netlify will instantly generate a live URL** (e.g., `https://relaxed-beaver-123456.netlify.app`).
5.  You can claim the site to customize the domain name later.

## Option 2: GitHub Pages (Professional & Free)
*Best for: Long-term hosting with version control.*

1.  Create a new repository on [GitHub.com](https://github.com).
2.  Upload all files (`index.html`, `styles.css`, `script.js`, images, etc.) to the repository.
3.  Go to **Settings > Pages**.
4.  Under "Branch", select `main` and click **Save**.
5.  Your site will be live at `https://yourusername.github.io/repo-name`.

## Option 3: Surge.sh (Command Line Node.js)
*Best for: Quick updates via CLI.*

If you install Node.js later:
1.  Open Terminal/PowerShell in this folder.
2.  Run: `npx surge ./`
3.  Follow the prompts to create an account and deploy.

## Option 4: Local Preview (Offline)
You can view the site anytime by simply double-clicking `index.html`.
*Note: Some browser security settings may block advanced canvas animations when viewing via `file://`. Using a local server (like Live Server for VS Code) is recommended for development.*
