GitHub Pages Deployment Notes

1) Create a new public repo on GitHub (e.g., romysurprise).
2) Upload the following to the repository root:
   - index.html
   - .nojekyll
   - /assets/ (this folder with all files inside)
3) In GitHub → Settings → Pages:
   - Build and deployment: Source = Deploy from a branch
   - Branch = main (or master) / root (/) folder
   - Save. Wait 1–2 minutes until GitHub shows a green "Your site is live" banner.
4) Your site will be available at: https://<your-username>.github.io/<your-repo>/

Notes:
- iOS/Safari may require a first tap to allow audio: the page shows a small toast and starts music after tap.
- If the MP3 is over 100 MB, GitHub will reject the push. In that case compress or trim the file to ≤100 MB.
- Keep the 'assets' folder name the same. If you rename files, update paths in index.html accordingly.
