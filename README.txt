# Muhammad Noman — Portfolio

Do files, dono ek saath deploy karni hain:
- `index.html`  (website)
- `M_Noman_New__CV.pdf`  (CV — naam bilkul same rakhna, warna CV link kaam nahi karega)

---

## STEP 1 — Password set karo (zaroori)

`index.html` kholo kisi bhi text editor mein (Notepad, VS Code, ya GitHub pe hi edit).
Upar JavaScript mein yeh line dhoondo:

    const ADMIN_PASSWORD = "CHANGE_THIS_PASSWORD";

`CHANGE_THIS_PASSWORD` ki jagah apna strong password daalo, jaise:

    const ADMIN_PASSWORD = "Mn$Portfolio2026!x";

Save karo.

---

## STEP 2 — GitHub

1. GitHub pe naya repository banao (naam: `portfolio`)
2. Dono files upload karo: `index.html` + `M_Noman_New__CV.pdf`
   (dono ek hi repo mein, ek saath)

---

## STEP 3 — Vercel deploy

1. vercel.com pe jao, GitHub se login karo
2. "Add New Project" -> apna `portfolio` repo select karo
3. "Deploy" dabao
4. 30 second mein live -> `tumhara-naam.vercel.app`

---

## Edit mode kaise kholein (sirf tum)

Website kholne ke baad, edit mode 2 tarike se aata hai:
- URL ke aakhir mein `#admin` lagao  ->  jaise `tumhara-naam.vercel.app/#admin`
- YA apne naam "Muhammad Noman" pe 5 baar tezi se click karo

Phir password box aayega. Password daalo -> Add / Edit / Delete buttons unlock.
Normal log (jinko link bhejoge) ko yeh buttons kabhi nahi dikhenge — sirf clean portfolio.

---

## ZAROORI NOTE — abhi cloud connect nahi hua

Abhi tumhare add/edit/delete sirf tumhare browser mein temporary chalte hain.
Doosron ko ya doosri device pe woh changes nahi dikhenge, aur page refresh pe wapas
demo data aa jayega.

Yeh normal hai — asli cloud save (Supabase) abhi baaki hai. Woh add karne ke baad:
- Tumhare changes cloud pe save honge
- Sab log, sab device pe dekhenge
- Tab dobara deploy karna (ek baar)

Deploy pehle karke process seekh lo — Supabase baad mein aaram se add kar denge.
