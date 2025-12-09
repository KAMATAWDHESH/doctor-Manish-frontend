# Dr. Manish Ranjan Orthopedic Website

## Deploying to Netlify

1. **Manual Deploy:**
   - Go to [Netlify Drop](https://app.netlify.com/drop).
   - Drag and drop your entire project folder (all HTML, CSS, JS, images, etc.).

2. **GitHub Deploy:**
   - Push this folder to a GitHub repository.
   - In Netlify, click "Add new site" > "Import an existing project".
   - Connect your repo and follow the prompts.
   - Set the publish directory to `.` (the root).

3. **Custom Domain:**
   - After deploy, go to Site Settings > Domain Management to add your custom domain.

---

- No build command is needed (static site).
- The included `netlify.toml` is for best practices and SPA support (uncomment if needed).
