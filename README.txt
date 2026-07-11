# Muhammad Noman — Portfolio

Two files, deploy both together:
- `index.html`  (the website)
- `M_Noman_New__CV.pdf`  (CV — keep the filename EXACTLY the same, or the CV link will break)

---

## STEP 1 — Set your password (required)

Open `index.html` in any text editor (Notepad, VS Code, or edit directly on GitHub).
Near the top of the JavaScript, find this line:

    const ADMIN_PASSWORD = "CHANGE_THIS_PASSWORD";

Replace `CHANGE_THIS_PASSWORD` with your own strong password, for example:

    const ADMIN_PASSWORD = "Mn$Portfolio2026!x";

Save the file.

---

## STEP 2 — GitHub

1. Create a new repository on GitHub (name it `portfolio`)
2. Upload both files: `index.html` + `M_Noman_New__CV.pdf`
   (both in the same repo, together)

---

## STEP 3 — Deploy on Vercel

1. Go to vercel.com and log in with GitHub
2. Click "Add New..." -> "Project"
3. Select your `portfolio` repo -> Import
4. Click "Deploy"
5. In about 30 seconds it goes live -> `your-name.vercel.app`

---

## How to open edit mode (owner only)

After opening the website, edit mode can be triggered two ways:
- Add `#admin` to the end of the URL  ->  e.g. `your-name.vercel.app/#admin`
- OR click your name "Muhammad Noman" 5 times quickly

A password box will appear. Enter your password -> the Add / Edit / Delete buttons unlock.
Normal visitors (anyone you send the link to) will never see these buttons — they only
see the clean portfolio.

---

## IMPORTANT NOTE — cloud is not connected yet

Right now your add/edit/delete actions only work temporarily in your own browser.
Other people (and other devices) won't see those changes, and refreshing the page
brings back the demo data.

This is expected — the real cloud saving (Supabase) is still to be added. Once it's set up:
- Your changes will be saved to the cloud
- Everyone, on every device, will see them
- You'll deploy once more (one time)

Deploy now to learn the process — we can add Supabase later.
