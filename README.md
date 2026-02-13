# Valentine's Day Interactive Page

A fun, interactive Valentine's Day page where the "Yes" button grows bigger every time they click "No" — with falling hearts, cute GIFs, music, and playful toast messages. Built with pure HTML, CSS, and JavaScript.

**Live demo:** https://issa-db.github.io/v-day/


### Fork It and Make It Yours

Want your own version you can customize? Follow these steps:


#### 1. Enable GitHub Pages
- In your forked repo, go to **Settings** (the gear icon tab)
- In the left sidebar, click **Pages**
- Under **Source**, select **"Deploy from a branch"**
- Under **Branch**, select **`main`** and **`/ (root)`**
- Click **Save**

#### 2. Wait ~2 Minutes
- GitHub will build and deploy your site
- Your site will be live at:
  ```
  https://yourusername.github.io/v-day
  ```
  (Replace `yourusername` with your actual GitHub username)

#### 4. Personalize It
- Edit `index.html` to change the question, title, or GIF
- Edit `yes.html` to change the celebration page
- Edit `script.js` to tweak the toast messages, button behavior, or GIF changes
- Edit `style.css` to change colors, fonts, or animations
- Swap out the music file in the `music/` folder with your own song

> **Tip:** You can edit files directly on GitHub by clicking on a file and hitting the pencil (edit) icon. No need to clone anything locally if you just want quick changes.

---

### Vibe Code Your Own From Scratch

Want something completely unique? Use AI to build it.

#### 1. Open Antigravity
- Google **"anti gravity google"** or go to [antigravity.dev](https://www.antigravity.dev)
- It has **Sonnet 4.6** built right in — no need to go anywhere else

#### 2. Describe What You Want
- Tell it exactly what you're imagining. Some ideas:
  - Falling hearts animation with a love letter reveal
  - Interactive story where they choose their adventure
  - A countdown to Valentine's Day with daily messages
  - A quiz about your relationship
  - Whatever your heart desires — literally

#### 3. Get the Code
- Antigravity will generate the full HTML, CSS, and JavaScript for you
- Copy the code into files on your computer

#### 4. Deploy It
- Create a new GitHub repository
- Push your code to it
- Enable GitHub Pages the same way as **Option 2** (Settings → Pages → Deploy from branch → main → root → Save)
- Your custom creation goes live in ~2 minutes

---

## Project Structure

```
v-day/
├── index.html       # Main page — "Will you be my Valentine?"
├── yes.html         # Celebration page after they say Yes
├── script.js        # Main page logic (button growth, GIF swaps, toasts)
├── yes-script.js    # Celebration page animations
├── style.css        # All the styling and animations
└── music/           # Background music
```

---

## How to Run Locally

You can preview the site on your computer before deploying:

1. Open your terminal in the project folder.
2. Run this command:
   ```bash
   python3 -m http.server 8000
   ```
3. Open your browser and go to: `http://localhost:8000`
 

## License
@SahilGogna