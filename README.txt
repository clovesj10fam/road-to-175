ROAD TO 175 — putting it on the web
===================================

The file index.html is the whole site. No server, no database, no build step.

USE IT WITHOUT HOSTING
  Open index.html in any browser. It works. Your entries save in that browser.
  On iPhone: open it in Safari, tap Share, "Add to Home Screen" — it then opens
  full screen like an app.

PUT IT ON A REAL URL (free, about two minutes)
  Netlify Drop — go to app.netlify.com/drop and drag the road-to-175 FOLDER onto
  the page. You get a live https link immediately. No account needed to start.

  GitHub Pages — make a repo, upload index.html, then Settings > Pages > deploy
  from main branch. Your URL is username.github.io/reponame.

  Cloudflare Pages, Vercel, Surge — all work the same way with a static folder.

IMPORTANT ABOUT YOUR DATA
  Entries live in the browser you enter them in. They are not synced between
  your phone and your laptop, and clearing site data erases them.
  Use BACK UP (under THE LOG) now and then to save a .json file, and RESTORE to
  merge it back in on another device.

CHANGING THE NUMBERS
  Near the top of the <script> block:
    GOAL        the target weight (175)
    GATE        the line you don't want to cross back over (200)
    START_W     starting weight (207)
    GHOST_RATE  pounds per week the ghost loses (2.0)
