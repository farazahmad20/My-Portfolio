# 🌐 Free Portfolio Website Template

> A beautiful, ready-to-use personal portfolio website — **no coding experience required!**

![Portfolio Preview](https://img.shields.io/badge/Status-Ready%20to%20Use-brightgreen?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-Only-orange?style=for-the-badge&logo=html5)
![No Framework](https://img.shields.io/badge/No%20Framework-Needed-blue?style=for-the-badge)
![Free](https://img.shields.io/badge/100%25-Free-success?style=for-the-badge)

---

## 🙋 Who Is This For?

This template is made for **everyone** — not just developers or tech people.

Whether you are a:
- 🎓 **Student** who wants to showcase academic projects
- 🎨 **Designer** who wants to display their creative work
- 💼 **Job seeker** who wants a professional online presence
- 🧑‍💻 **Developer** who wants a quick, polished portfolio
- 📸 **Photographer, writer, or freelancer** who needs a personal website
- 👤 **Anyone** who wants their own space on the internet

**→ This template is for you.** You don't need to write any code. Just follow the steps below.

---

## ✨ What Does This Template Include?

| Section | What It Shows |
|---|---|
| 🏠 **Hero / Home** | Your name, title, and a short introduction |
| 👤 **About Me** | Your photo, bio, and key stats (experience, projects, clients) |
| 🛠️ **Skills** | Cards showing your skills or tools |
| 🗂️ **Projects** | Featured work with links to live sites and GitHub |
| 📬 **Contact** | A working contact form (powered by EmailJS) |
| 🔗 **Social Links** | GitHub, LinkedIn, Twitter, and Email icons |

### 🎨 Design Features
- ✅ **Dark mode** design — modern and professional
- ✅ **Smooth animations** — elements fade in as you scroll
- ✅ **Mobile friendly** — looks great on phones, tablets, and desktops
- ✅ **Single HTML file** — everything in one place, easy to edit
- ✅ **No installation required** — just open in a browser

---

## 📁 Project Structure

```
portfolio/
│
├── portfolio.html        ← Main file (edit this to customize)
│
└── assets/
    ├── github.svg        ← GitHub icon
    ├── linkedin.svg      ← LinkedIn icon
    ├── twitter.svg       ← Twitter icon
    └── email.svg         ← Email icon
```

---

## 🚀 How to Use This Template

### Step 1 — Download the Project

**Option A: Download as ZIP (Easiest)**
1. Go to this GitHub repository
2. Click the green **`< > Code`** button
3. Click **"Download ZIP"**
4. Extract (unzip) the folder anywhere on your computer

**Option B: Using Git (If you know Git)**
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
```

---

### Step 2 — Open the File

1. Open the extracted folder
2. Find the file called **`portfolio.html`**
3. Right-click on it → **"Open with"** → choose any web browser (Chrome, Firefox, Edge)

You should see the portfolio website open in your browser! 🎉

---

### Step 3 — Edit Your Information

Open `portfolio.html` in a **text editor**. You can use:
- **Notepad** (Windows) — already on your computer
- **TextEdit** (Mac) — already on your computer
- **VS Code** (recommended, free) — [download here](https://code.visualstudio.com/)
- **Notepad++** (free) — [download here](https://notepad-plus-plus.org/)

Then find and replace the following placeholder text with your own:

---

#### 🔤 Change Your Name & Title

Find this line (around line 630):
```html
<div class="logo">Alex<span>.dev</span></div>
```
Change `Alex` to your name or nickname.

Find this line (around line 649):
```html
<h1 class="animate delay-1">Hi, I'm <span>Alex Rivera</span></h1>
```
Change `Alex Rivera` to **your full name**.

Find this line (around line 650):
```html
<p class="animate delay-2">MERN Stack Developer crafting beautiful...</p>
```
Change this to **your own short introduction**. For example:
- `"Graphic Designer creating stunning visual experiences."`
- `"Computer Science student passionate about solving real problems."`
- `"Freelance photographer capturing life's best moments."`

---

#### 👤 Update the About Me Section

Find this part (around line 679):
```html
<h3>Passionate about building great products</h3>
<p>I'm a full-stack developer with 3+ years of experience...</p>
<p>When I'm not coding, you'll find me...</p>
```
Replace this with **your own bio** — who you are, what you do, and what you enjoy.

**Change your profile photo:**
Find this line:
```html
<img src="https://images.unsplash.com/photo-..." alt="Alex Rivera">
```
Replace the `src="..."` URL with a **link to your own photo**, or upload your photo to the `assets/` folder and write:
```html
<img src="assets/your-photo.jpg" alt="Your Name">
```

**Update your stats:**
```html
<div class="number">3+</div> <div class="label">Years Experience</div>
<div class="number">25+</div> <div class="label">Projects Completed</div>
<div class="number">15+</div> <div class="label">Happy Clients</div>
```
Change the numbers and labels to match your own experience.

---

#### 🛠️ Update Your Skills

Each skill looks like this:
```html
<div class="skill-card">
    <div class="skill-icon">⚛️</div>
    <h4>React.js</h4>
    <p>Building interactive UIs</p>
</div>
```

- Change the emoji icon to something that fits your skill
- Change the skill name (`React.js`) to **your skill** (e.g., `Photoshop`, `Excel`, `Drawing`, `Python`)
- Change the description to a short line about it

You can add as many skill cards as you want by copying and pasting the block above.

---

#### 🗂️ Update Your Projects

Each project card looks like this:
```html
<div class="project-card">
    <div class="project-image">🛒</div>
    <div class="project-content">
        <div class="project-tags">
            <span class="project-tag">React</span>
        </div>
        <h3>E-Commerce Platform</h3>
        <p>A full-featured online store...</p>
        <div class="project-links">
            <a href="#">View Live →</a>
            <a href="#">GitHub →</a>
        </div>
    </div>
</div>
```

- Change the emoji in `project-image` to match your project
- Update the **tags** (e.g., `Design`, `Video`, `Research`)
- Change the **project name** and **description**
- Replace `href="#"` with the actual links to your project or GitHub repo

> 💡 **Tip:** If you don't have live links yet, just remove the `<a href="#">View Live →</a>` line.

---

#### 🔗 Update Your Social Links

Find these lines (around line 658–661):
```html
<a href="#" title="GitHub"><img src="assets/github.svg" ...></a>
<a href="#" title="LinkedIn"><img src="assets/linkedin.svg" ...></a>
<a href="#" title="Twitter"><img src="assets/twitter.svg" ...></a>
<a href="#" title="Email"><img src="assets/email.svg" ...></a>
```

Replace each `href="#"` with your actual profile URL. For example:
```html
<a href="https://github.com/yourusername" title="GitHub">
<a href="https://linkedin.com/in/yourprofile" title="LinkedIn">
<a href="https://twitter.com/yourhandle" title="Twitter">
<a href="mailto:youremail@gmail.com" title="Email">
```

---

### Step 4 — Set Up the Contact Form (Optional)

The contact form uses **EmailJS** — a free service that lets visitors send you emails directly from your website without any server setup.

1. Go to [https://www.emailjs.com](https://www.emailjs.com) and create a **free account**
2. Follow their setup to get:
   - **Public Key**
   - **Service ID**
   - **Template ID**
3. In `portfolio.html`, find these lines (around line 879–886):
```javascript
emailjs.init('YOUR_PUBLIC_KEY');

emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', {
    ...
    to_email: 'your-email@example.com'
});
```
4. Replace `YOUR_PUBLIC_KEY`, `YOUR_SERVICE_ID`, `YOUR_TEMPLATE_ID`, and `your-email@example.com` with your actual values.

> 💡 **Skip this step?** If you don't set up EmailJS, the contact form just won't send emails — everything else on the site still works perfectly.

---

### Step 5 — Publish Your Website for Free

Once you're happy with your edits, you can put it online for the world to see — **completely free**!

#### Option A: GitHub Pages (Recommended — Free Forever)
1. Create a free account at [github.com](https://github.com)
2. Create a new repository (name it `your-username.github.io` for a personal site)
3. Upload your `portfolio.html` file and `assets/` folder
4. Go to **Settings → Pages** → set source to `main` branch
5. Your site will be live at `https://your-username.github.io` 🚀

#### Option B: Netlify (Drag & Drop — Super Easy)
1. Go to [netlify.com](https://netlify.com) and sign up for free
2. Drag and drop your whole project folder onto the Netlify dashboard
3. Your site is live instantly with a free URL!

#### Option C: Vercel
1. Go to [vercel.com](https://vercel.com) and sign up
2. Import your GitHub repository or drag-and-drop your files
3. Live in seconds!

---

## 🎨 Customizing Colors

The color theme can be easily changed. At the top of `portfolio.html`, find this section:

```css
:root {
    --primary: #6366f1;      /* Main purple/indigo color */
    --primary-dark: #4f46e5; /* Darker version on hover */
    --secondary: #10b981;    /* Green accent color */
    --dark: #0f172a;         /* Background (very dark) */
    --dark-light: #1e293b;   /* Card backgrounds */
    --gray: #64748b;         /* Subtitle text color */
    --light: #f8fafc;        /* Main text color */
    --white: #ffffff;        /* White */
}
```

Change the color values (the `#xxxxxx` hex codes) to whatever you like.
Use sites like [coolors.co](https://coolors.co) or [htmlcolorcodes.com](https://htmlcolorcodes.com) to pick colors.

---

## ❓ Frequently Asked Questions

**Q: Do I need to know how to code?**
No! You only need to find the right text and replace it with your own. It's like editing a Word document.

**Q: Is this really free?**
Yes, 100%. The template is free, GitHub Pages is free, Netlify is free. No hidden costs.

**Q: Can I use this for my business?**
Yes! You can use and modify this template for personal or business use.

**Q: Can I add more sections?**
Yes, if you're comfortable with basic HTML, you can copy and paste existing sections and modify them. Even if you're not, a small ChatGPT prompt can help you add sections.

**Q: What if I break something?**
Just re-download the original file from GitHub and start fresh. Your edits are only in your local copy until you publish.

**Q: Can I remove sections I don't need?**
Yes! If you don't have projects yet, just delete the entire `<section class="projects">...</section>` block.

---

## 🤝 Contributing

Found a bug or have an idea to make this better? Feel free to:
1. **Fork** this repository
2. Make your changes
3. Open a **Pull Request**

All contributions are welcome!

---

## 📄 License

This project is open source and free to use under the [MIT License](LICENSE).
You are free to use, copy, modify, and distribute this template — for personal or commercial use.

---

## 🙏 Credits

Built with:
- [EmailJS](https://www.emailjs.com/) — for the contact form
- [Google Fonts](https://fonts.google.com/) — Inter & Fira Code typefaces
- Pure HTML & CSS — no frameworks, no dependencies

---

<div align="center">

**Made with ❤️ to help everyone get their own space on the internet.**

*If this helped you, consider giving it a ⭐ on GitHub!*

</div>
