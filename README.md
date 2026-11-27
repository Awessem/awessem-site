# awessem.com

The Awessem Gaming website, hosted free on GitHub Pages.

- `index.html` - the studio home page
- `turnless/index.html` - the Turnless page (awessem.com/turnless)
- `privacy.html` - the privacy policy (link this in Google Play and Steam)
- `404.html` - shown for pages that don't exist
- `press/index.html` - the press kit (awessem.com/press)
- `share.png` - the picture shown when a link to the site is posted (1200x630); swap in your own art any time, same name and size
- `turnless/shots/` - put screenshots here (see the comment in turnless/index.html)
- `.well-known/security.txt` - how to report a security problem (renew the Expires date once a year)
- `.nojekyll` - lets GitHub Pages publish the .well-known folder (don't delete it)
- `style.css` - the look of every page
- `CNAME` - tells GitHub Pages to use awessem.com (don't delete it)

To change text, edit the .html files in any text editor, commit and push in GitHub Desktop. The site updates in about a minute.

Security: every page carries a Content-Security-Policy line that only allows this site's own files (no outside scripts at all). If you ever embed something new (a video player other than YouTube, a form, a script), that line needs updating, or it will be blocked.
