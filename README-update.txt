BGCFL website with public documents

This package contains:
- index.html
- README-update.txt
- css/styles.css
- js/app.js
- docs/

No assets folder.
No images folder.
No chatbot.
No role generator.

Only public templates and learning resources were added.
Private signature pages, attendance trackers, member trackers, and planning documents were not included.

How to update local Git repo:
1. Extract this ZIP.
2. Copy index.html, README-update.txt, css folder, js folder, and docs folder into:
   C:\Jeeva\Workspace\bgcfl
3. Replace existing files if Windows asks.
4. Test locally.
5. Push:
   git status
   git add index.html README-update.txt css/styles.css js/app.js docs
   git commit -m "add public BGCFL documents"
   git pull --rebase origin main
   git push
