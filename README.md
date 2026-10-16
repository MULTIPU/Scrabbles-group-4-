# Scrabble as a Teaching & Learning Aid
LASU · Dept. of Computer Science · EDT 104 · Group 4 "The Scrabble Strategists"
Lead Designer & Developer: Oyedola Daniel Oladimeji · Powered by Multipuhub

## Publish on GitHub Pages
1. Create a repo, upload `index.html`, `img/` and this README (keep the folder structure).
2. Settings > Pages > Deploy from branch > `main` / root. Your site URL appears there.

## Enable "Sign in with Google"
1. Go to console.cloud.google.com (sign in with mdmasterdan@gmail.com), create a project.
2. APIs & Services > Credentials > Create OAuth client ID > Web application.
3. Add your GitHub Pages origin (e.g. https://USERNAME.github.io) under Authorized JavaScript origins.
4. Paste the Client ID into `GOOGLE_CLIENT_ID` near the top of the script in `index.html`.
Until then, "Continue as Guest" lets you test the game.
