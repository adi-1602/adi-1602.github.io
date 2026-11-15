# DocScanner website (free on GitHub Pages)
1. Sign in at github.com (create a free account if needed).
2. Create a **public** repository named exactly `<your-github-username>.github.io`
   (this puts the site at the domain root, which AdMob needs for app-ads.txt).
3. "uploading an existing file" → drag ALL files from this folder (including .nojekyll) → Commit.
4. Repo → Settings → Pages → Source: Deploy from a branch → main / (root) → Save.
5. In 1–2 minutes your pages are live:
   - https://<username>.github.io/              (home)
   - https://<username>.github.io/privacy.html  (privacy policy)
   - https://<username>.github.io/terms.html    (terms)
   - https://<username>.github.io/help.html     (help)
   - https://<username>.github.io/app-ads.txt   (fill in your AdMob pub ID first)
6. Put these URLs into DocScanner/Config/AppConfig.swift and App Store Connect.
