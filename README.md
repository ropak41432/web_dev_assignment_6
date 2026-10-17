# Module 6 Assignment: Personal Profile Webpage Using HTML

A complete, semantic, and responsive personal profile webpage built in HTML5 to satisfy the requirements for **Module 6 Assignment** in the Ostad Full-Stack Web Development Course.

---

## Assignment Overview & Requirement Checklist

This project demonstrates the proper use of HTML structural tags, text formatting, form controls, tables, multimedia elements, semantic layout tags, and interactive elements.

| Task # | Category | Required Elements | Implementation Status in `index.html` |
| :---: | :--- | :--- | :---: |
| **1** | **Structural Tags** | `<html>`, `<head>`, `<title>`, `<body>`, heading (`<h1>`, `<h2>`), paragraph (`<p>`) | **Completed** |
| **2** | **Text Formatting** | Bold (`<b>` / `<strong>`), Italic (`<i>` / `<em>`), Underline (`<u>`), Highlighted (`<mark>`) | **Completed** |
| **3** | **Form** | Name, Email, Password, Gender (Radio buttons), Hobbies (Checkboxes), Submit button | **Completed** |
| **4** | **Table** | Academic information with at least 3 rows and 3 columns | **Completed** (4 rows, 4 columns) |
| **5** | **Multimedia** | At least one image, plus audio or video element | **Completed** (Image, `<audio>`, and `<video>`) |
| **6** | **Semantic Elements** | `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>` | **Completed** |
| **7** | **Interactive Elements** | `<details>` and `<summary>` for additional info, clickable button (`<button>`) | **Completed** |

---

## Directory Structure

```text
web_dev_assaignment_6/
├── index.html                   # Main personal profile webpage
├── README.md                    # Project documentation and checklist
├── .gitignore                   # Standard git ignore file
├── assets/
│   ├── images/
│   │   └── profile.jpg          # Profile photo
│   └── media/
│       └── sample-audio.wav     # Audio demonstration file
└── Questions and Materials/     # Course question PDF and lecture source code
    ├── Module_6_Assignment_Question.pdf
    ├── Session 1/
    └── Session 2/
```

---

## Detailed Section Breakdown

### 1. Header & Navigation (`<header>`, `<nav>`)
- Contains main heading `<h1>` with profile owner name.
- Provides internal anchor links (`#about`, `#academics`, `#multimedia`, `#contact`, `#more-info`) for smooth in-page navigation.

### 2. About Myself (`<section id="about">`)
- Introduces the profile owner using semantic paragraph tags.
- Implements all required text formatting:
  - **Bold**: `<b>Md. Rupok Chowdhury</b>`
  - *Italic*: `<i>modern full-stack engineering</i>`
  - <u>Underline</u>: `<u>Ostad Python with Django Full-Stack Web Development Course</u>`
  - <mark>Highlight</mark>: `<mark>robust, scalable, and responsive web applications</mark>`

### 3. Academic Information (`<section id="academics">`)
- Displays completed degrees and credentials in a responsive `<table>` layout:
  - Columns: *Degree / Certificate*, *Institution / Board*, *Year of Completion*, *Result / Division*.
  - Rows: Master of Science (M.Sc.), Bachelor of Science (B.Sc. Hons), HSC, and SSC.

### 4. Multimedia Gallery (`<section id="multimedia">`)
- **Image**: High-resolution profile avatar inside circular frame.
- **Audio**: HTML5 `<audio controls>` player referencing local `assets/media/sample-audio.wav`.
- **Video**: HTML5 `<video controls>` element with fallback player support.

### 5. Contact Form (`<section id="contact">`)
- Comprehensive interactive HTML `<form>` including:
  - **Text input**: `name="full_name"`
  - **Email input**: `type="email"`
  - **Password input**: `type="password"`
  - **Radio buttons**: Gender selection (Male, Female, Other)
  - **Checkboxes**: Multiple hobbies and technical interests
  - **Submit button**: `<button type="submit">`

### 6. Interactive Features (`<section id="more-info">`)
- Two `<details>` & `<summary>` accordions revealing career goals and technical proficiencies.
- Clickable `<button type="button">` triggering an interactive welcome message alert.

### 7. Footer (`<footer>`)
- Closes the document with copyright information and assignment metadata.

---

## How to View and Run the Webpage

1. **Directly in Browser**:
   - Double-click `index.html` or right-click and select **Open with** -> **Google Chrome** (or Edge/Firefox).
2. **Using VS Code Live Server**:
   - Open the `web_dev_assaignment_6` folder in VS Code.
   - Right-click `index.html` and click **Open with Live Server**.
