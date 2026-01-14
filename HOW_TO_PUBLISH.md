# Deploying Otag Digital Website

You have successfully created the website files!

## Steps to Deploy

1.  **Move the Folder**:
    - Cut the `esaxd.github.io` folder from `islambirader` and paste it on your Desktop (or wherever you keep your projects).

2.  **Publish to GitHub**:
    - Open that folder in your terminal / command prompt.
    - Run these commands:
      ```bash
      git init
      git add .
      git commit -m "Initial commit - Otag Digital website & app-ads.txt"
      git branch -M main
      git remote add origin https://github.com/esaxd/esaxd.github.io.git
      git push -u origin main
      ```

3.  **Verify**:
    - Go to `https://esaxd.github.io` to see your new site.
    - Go to `https://esaxd.github.io/app-ads.txt` to verify the ads file is live.

## Why this works
- **Private Game**: Your `islambirader` game code stays in its own folder, completely private.
- **Public Website**: Only this specific folder is public, acting as your business card and verification site.
