# Una Health · Supplier note helper

Turns supplier emails into OrderWise Contact Manager notes, following the
"Supplier Chasing (through Contact Manager)" work instruction.

## Set up (once)

1. Upload everything in this folder to the repository: `index.html`, `taskpane.html`,
   `README.md` and the `assets` folder.
2. Settings → Pages → Source: **Deploy from a branch** → Branch: **main** / **(root)** → Save.
3. After a minute or two, open the address GitHub shows (it ends in `github.io/...`).
4. On that page, click **Download the Outlook add-in file**.
5. In Outlook: **Get Add-ins → My add-ins → Custom add-ins → Add from file**, and choose the file.
   IT can instead deploy it to everyone from the Microsoft 365 admin centre (Integrated apps).

## Using it

Open a supplier email, then choose **Supplier note** from the Apps menu (or the "..." menu on the message).
The email loads automatically. Pin the pane to keep it open as you move between emails.

## Updating

Upload the new `taskpane.html` over the old one. Everyone gets the update the next time they open the add-in.
