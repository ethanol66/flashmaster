MEMOKI REVIEW - GITHUB PAGES VERSION

This is a no-build app. You do not need npm, Vite, React build commands, or a terminal.

HOW TO PUT IT ON GITHUB PAGES

1. Unzip this file.
2. Create a new public GitHub repository. Example name: memoki
3. Upload every file from this folder to the top/root of the repository.
   index.html must be visible at the top level, not inside another folder.
4. Go to Settings -> Pages.
5. Source: Deploy from a branch.
6. Branch: main.
7. Folder: /(root).
8. Save.
9. Wait a few minutes, then open the GitHub Pages URL.

IPHONE APP ICON

1. Open the GitHub Pages link in Safari on your iPhone.
2. Tap Share.
3. Tap Add to Home Screen.
4. Name it Memoki.

IMPORTING CARDS

Open Memoki -> Settings -> Import Cards.

Best format:
front<TAB>back
front<TAB>back<TAB>deck<TAB>tags

CSV also works:
front,back,deck,tags

JSON card list also works if it is an array like:
[
  {"front":"Capital of Japan","back":"Tokyo","deck":"Geography","tags":"asia"}
]

BACKUPS

Settings -> Export Backup JSON saves all decks, cards, scheduling, and statistics.
Settings -> Restore full backup brings it back.

DATA WARNING

Cards are stored in the browser on that device. Export a backup before clearing Safari data or changing phones.
