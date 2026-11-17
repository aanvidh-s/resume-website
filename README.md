# Personal Resume Website — IIM Bangalore BBA DBE

> **Course:** Website Development (Mid-Term Project)  
> **Student:** Aanvidh S  
> **Degree Program:** Bachelor of Business Administration in Digital Business & Entrepreneurship (BBA DBE)  
> **Institution:** Indian Institute of Management Bangalore (IIM Bangalore)  
> **Project Code:** `WD_MTProject`

---

## 🌟 Overview

This project is an executive, modern, and responsive personal resume website developed for the **IIM Bangalore BBA DBE** mid-term website development assignment.

It highlights Aanvidh S's academic journey at IIM Bangalore, diploma in office administration from Pondicherry University, professional certifications (McKinsey Forward, NISM V-A, FMVA), technical and strategic skill sets, competitive extracurricular achievements (chess and karate), and career aspirations in finance, consulting, and real estate entrepreneurship.

The project demonstrates mastery of fundamental HTML5 and CSS3:
- **Semantic HTML5:** `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`, `<button>`
- **Actual Profile Image:** High-resolution portrait integrated with circular framing and hover elevation
- **Default Dark Mode & Light Switcher:** Obsidian Space dark mode set as default with instant toggle to porcelain executive light mode
- **Vivid Glowing Tap Ripple & Sound:** Neon cyan luminous ripple expansion with synthetic glassy tap audio (zero-dependency Web Audio API)
- **Built-in Ambient Music Player:** Soothing study chord progression with amplified volume and live dancing equalizer bars
- **App Icon Socials & Highlights Box:** Official vector SVGs for LinkedIn, GitHub, and Instagram (`_aanvi_dh`), plus an attractive 3-item contact highlights card (Location, Email, Phone)
- **Elevated Information Hierarchy:** Certifications and Skills placed prominently in the top section; Achievements (Chess & Karate) placed in the lower section
- **Executive Typography & Palette:** Google Fonts (`Plus Jakarta Sans` & `Space Grotesk`) with Academic Navy and Obsidian Dark tones
- **The Box Model:** Universal `box-sizing: border-box` reset and consistent margin/padding architecture
- **CSS Selectors:** Class, ID, Element, Descendant, and interactive Pseudo-classes (`:hover`, `:active`, `:focus`)
- **Layout Engines:** CSS Flexbox (Navigation, Hero, Buttons) and CSS Grid (Education, Certifications, Skills, Achievements)
- **Responsive Design:** Viewport adaptability via media queries for desktop, tablet, and mobile devices
- **Academic Submission Report:** Pre-formatted 2-page academic report (`submission_report.html`) ready to export as PDF.

---

## 📂 Project Structure

```text
resume-website/
│
├── index.html              # Semantic HTML5 structure with Light/Dark toggle & tap animations
├── style.css               # Comprehensive, well-commented CSS stylesheet (Light & Dark modes)
├── profile.jpg             # Profile photograph asset
├── submission_report.html  # Print-ready 2-page academic submission report
└── README.md               # Project documentation and deployment instructions
```

---

## 🚀 Step-by-Step GitHub & Hosting Guide

Follow these exact steps to publish your website live on GitHub Pages:

### Step 1: Create a New GitHub Repository
1. Log in to your GitHub account: [github.com](https://github.com) (signed in as `aanvidh-s`).
2. In the top-right corner, click the **`+`** icon and select **New repository**.
3. Name your repository (e.g., `resume-website` or `iimb-wd-project`).
4. Set the visibility to **Public**.
5. Leave "Add a README file", ".gitignore", and "license" **unchecked** (we already have our own files).
6. Click **Create repository**.

### Step 2: Upload Files to the Repository
1. On your new repository page, click the link that says **"uploading an existing file"**.
2. Select or drag-and-drop the following files from your local folder into GitHub:
   - `index.html`
   - `style.css`
   - `profile.jpg` *(Important: ensures your photo shows on the live site!)*
   - `README.md`
3. At the bottom under "Commit changes", type: `Add resume website files with light/dark mode and profile photo`.
4. Ensure **"Commit directly to the `main` branch"** is selected.
5. Click **Commit changes**.

### Step 3: Enable GitHub Pages (Get Your Live Link!)
1. In your GitHub repository, click the **Settings** tab at the top.
2. In the left-hand navigation menu, click **Pages** (under the "Code and automation" section).
3. Under **Build and deployment > Branch**:
   - Change the branch dropdown from **None** to **`main`**.
   - Keep the folder set to **`/(root)`**.
   - Click **Save**.
4. Wait approximately 1 to 2 minutes, then refresh the page.
5. You will see a banner displaying your live link:
   > *"Your site is live at `https://aanvidh-s.github.io/resume-website/`"*
6. Copy this link for your university assignment submission!

---

## 📄 Generating Your 2-Page Assignment PDF

IIM Bangalore requires a 1–2 page submission document referencing the lecture learnings and containing your live links.

### How to Print the Submission Report:
1. Open the file `submission_report.html` in your web browser (Google Chrome or Microsoft Edge).
2. Check the top metadata box in the file—ensure your **Roll Number / Student ID** and actual repository/live URLs are entered.
3. Click the blue **"Print / Save to PDF"** button at the top banner (or press `Ctrl + P` / `Cmd + P`).
4. In the Print dialog:
   - **Destination:** Set to **Save as PDF**.
   - **Pages:** Select **All** (it will strictly render as 2 pages).
   - **Margins:** Set to **Default** or **None**.
   - **Options:** Make sure **"Background graphics"** is **checked**.
5. Click **Save**.
6. Name your file in the required IIMB format: `YourRollNo_WD_MTProject.pdf` (e.g., `25120000_WD_MTProject.pdf`).
7. Submit the PDF through your university student portal.
