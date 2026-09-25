READY TO PUBLISH — AUTOMATIC SYNC (Firebase already configured)

This copy is already connected to your Firebase project. Any Leader edit
(tasks, files, links, notes, lectures) is saved the instant you tap
Add/Save, and appears on every device that has the site link open — no
extra download or re-upload step.

PUBLISH IT
Netlify:
  1. Go to https://app.netlify.com/drop
  2. Drag this whole folder onto the page.
  3. Click "claim your site" so the link stays online.

GitHub Pages:
  1. Create a repository and upload every file in this folder
     (index.html must be at the top level of the repo, not inside
     another folder).
  2. Settings > Pages > choose the main branch > Save.

UPDATING THE SITE LATER (files, not data)
If you ever want to change the design or code itself (not the schedule
data), re-upload the whole folder again the same way. Everyday changes
made by the Leader (tasks, files, notes) need NO re-upload — they sync
automatically through Firebase.

LEADER CODE: 2344
Stored in Firebase under config/code, and checked near the top of the
script in index.html as CODE.

FIREBASE PROJECT: schedule-4e8bf
Settings are already filled in firebase-config.js. Don't delete that
file or the "Rules" you published in the Firebase console, or syncing
will stop working.
