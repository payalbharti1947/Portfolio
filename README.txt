PAYAL BHARTI PORTFOLIO - VERCEL STATIC DEPLOYMENT

FILES
- index.html: the complete single-file portfolio (HTML, CSS and JavaScript embedded)
- vercel.json: tells Vercel to treat this as a static/Other project and serve the root folder

DEPLOY WITH GITHUB
1. Create a new GitHub repository, e.g. payal-bharti-portfolio.
2. Upload index.html and vercel.json directly into the repository root (not inside another nested folder).
3. Open Vercel and choose Add New -> Project.
4. Import the repository.
5. In Configure Project, set Framework Preset to Other.
6. Leave Build Command empty. Set Output Directory to . (dot), if Vercel asks for it.
7. Make sure Root Directory is ./ (repository root).
8. Click Deploy.

IF THE PROJECT ALREADY EXISTS IN VERCEL
1. Open Project -> Settings -> Build and Deployment.
2. Framework Preset: Other.
3. Root Directory: ./ (repository root, or the folder containing index.html if intentionally nested).
4. Build Command: blank / disabled.
5. Output Directory: . (dot), unless using a public folder.
6. Save, then go to Deployments and redeploy the latest commit.

IMPORTANT
- The homepage file must be named exactly index.html (lowercase) and be in the configured project root/output directory.
- Do not upload only Payal_Bharti_Portfolio_Single_File.html and expect / to open automatically.
- This is a static website; no Node.js build or package.json is required.
