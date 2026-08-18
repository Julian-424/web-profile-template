# Web Profile Template

A bilingual personal profile page for students of **Técnico Profesional en Programación Web**
at Institución Universitaria de El Espinal (UniEspinal).

The page works in **Spanish and English**. Visitors change the language with one button.

---

## What you will build

A public web page with six sections:

| Section | What goes there |
|---|---|
| Home | Your name, your role, your links |
| About | Two or three sentences about you |
| Skills | Your technical and professional skills |
| Resume | Your education and your experience |
| Projects | The projects you have built |
| Contact | How people can reach you |

---

## Before you start

You need:

- A **GitHub account**.
- A **profile photo** (a square image works best).
- A **screenshot** of each project you want to show.
- A **professional email address**. Do not use a nickname like `gamer_2005@...`.

---

## Step 1 · Create your own copy

1. Open this repository on GitHub.
2. Click the green **Use this template** button.
3. Click **Create a new repository**.
4. Give it a name, for example `my-web-profile`.
5. Choose **Public**. The page will not work if the repository is private.
6. Click **Create repository**.

Now you have your own copy. Nothing you do will change the original template.

---

## Step 2 · Publish the page

1. In **your** repository, go to **Settings**.
2. In the left menu, click **Pages**.
3. Under *Source*, select **Deploy from a branch**.
4. Choose branch **main** and folder **/ (root)**. Click **Save**.
5. Wait one or two minutes and reload the page.

Your address appears at the top:

```
https://YOUR-USERNAME.github.io/my-web-profile/
```

Open it. You should see the template with placeholder text.

---

## Step 3 · Add your images

Put your files inside the `images` folder, with these exact names:

```
images/profile.jpg      your photo
images/project-1.png    first project
images/project-2.png    second project
images/project-3.png    third project
```

File names are **case sensitive** on GitHub. `Profile.jpg` and `profile.jpg` are
two different files. Do not use spaces in file names.

---

## Step 4 · Write your content

### 4.1 · In `index.html`

Replace everything inside `[square brackets]`:

- your name
- your email
- your links (GitHub, LinkedIn)
- your project links
- the `data-percent` value of each skill

Do **not** delete the `data-i18n` attributes. They connect the page to the
language switcher.

### 4.2 · In `script.js`

This is where the words live. There are two dictionaries:

```javascript
const ES = { ... }   // Spanish texts
const EN = { ... }   // English texts
```

Both have the same keys. Write your Spanish text in `ES` and your English text
in `EN`.

**Write the English version first.** It is harder, and if you write it second
you will only translate the Spanish, word by word. That is not what we want.

---

## Step 5 · Reflect

Open `NOTES.md` and answer the three questions there, **in English**.
This file is part of your assignment.

---

## Rules about personal data

This page is **public**. Anyone can find it, including automatic programs that
collect emails and phone numbers.

**Never publish:**

- your home address
- your phone number
- your ID number (cédula)
- your date of birth

**It is safe to publish:**

- your city and country
- a professional email address
- links to your public profiles

A Colombian *hoja de vida* asks for many personal details. A public web profile
does not. This is not the same document.

---

## Common problems

| Problem | Cause | Solution |
|---|---|---|
| The page shows 404 | The file is not called `index.html` | Rename it. Check the capital letters. |
| The page has no colours | The browser cannot find `style.css` | Check the file name and the folder. |
| The language button does nothing | There is an error in `script.js` | Open the browser console (F12) and read the message. |
| A text does not change language | The key is missing in one dictionary | The console shows `Missing translation key`. |
| An image does not appear | Wrong name or wrong folder | File names are case sensitive. |

---

## Technical notes

- No frameworks and no build tools. Only HTML, CSS and JavaScript.
- The colours are defined once, at the top of `style.css`, inside `:root`.
- Skill bars read their value from `data-percent`. You change the number in one
  place only.
- The page is responsive and works on a phone.
- The language choice is not saved between visits. Saving it is an optional
  extra exercise.

---

## Licence

Free to use and modify for academic purposes at UniEspinal.
