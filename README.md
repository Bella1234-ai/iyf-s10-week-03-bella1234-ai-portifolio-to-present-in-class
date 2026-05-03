# iyf-s10-week-03-bella1234-ai-portifolio-to-present-in-class
about using HTML  SEMANTIC,Flexbox, Grid &amp; Responsive Design, Git &amp; GitHub Workflow

# Week {Number}: {Project Title}

## Author
- **Name:** ISABELLAH SIMIYU
- **GitHub:** [@bella1234](https://github.com/bella1234-ai)
- **Date:** 02 05, 2026

## Project Description
My personal portfolio website built with HTML and CSS — showcasing my projects, skills and experience as a Frontend Developer and Business Lady. Built during my studies at IYF Academy, Nairobi Kenya.

## Technologies Used
- HTML5
- CSS3


## Features
1. HTML Structure

- Semantic sections — nav, section, header, footer
- Anchor links for smooth scrolling between sections
- External font import via Google Fonts

2. CSS Features

- CSS Variables (--color-primary, --font-base etc) for consistent theming
- Flexbox — for nav, hero buttons, about layout, footer
- CSS Grid — for projects, skills, contact cards
- clamp() — for responsive font sizes that scale automatically
- backdrop-filter: blur — frosted glass effect on the nav bar
- CSS Animations — fadeUp, drift, pulse keyframe animations
- Gradient text — using background-clip: text
- Hover transitions — cards lift, buttons glow, experience items slide
- object-fit: cover — for the profile photo circleposition: sticky — nav stays at top when scrolling
- Responsive breakpoints with @media queries for mobile, tablet and desktop
- CSS custom properties with rgba() for transparent overlays and borders
- aspect-ratio — for proportional cards

3. Design Features

- Dark theme
- Animated color blobs in the hero background
- Gradient branding — pink → yellow → teal used consistently
- Animated status dot (pulsing green dot in About section)
- Smooth scroll behavior
- Mobile-first responsive layout

4. JavaScript

- DOM manipulation — selecting and updating elements
- addEventListener — for form submit handling
- classList — showing and hiding elements
- setTimeout — auto-hiding the success message
  
## How to Run
1. Clone this repository
2. Open `index.html` in your browser
   OR
   Run `npm install` then `npm start`

## Lessons Learned
What did you learn while building this project?
1. File organisation matters from the start
I learned that keeping all files — index.html, style.css and bella.jpg — in the same folder is not optional. When I had files in different places, images and styles broke. A clean folder structure saves a lot of debugging time.
2. CSS Variables make your life easier
Before I used variables like --color-primary and --font-base, I was repeating the same colour codes everywhere. When I wanted to change one colour I had to hunt through the whole file. Variables let me change one line and update the whole design instantly.
3. Flexbox and Grid solve different problems
I used to try to use Flexbox for everything. Building this portfolio taught me that Flexbox is best for one-direction layouts like the nav bar and buttons, while Grid is better for two-dimensional layouts like the projects section and contact cards.
4. Mobile responsiveness is not an afterthought
I learned to write @media queries to handle mobile, tablet and desktop separately. Without them, my portfolio looked broken on a phone. Now I always think about how a layout will look on a small screen first.
5. Git is a safety net
Pushing my work to GitHub using git init, git add ., git commit and git push taught me that version control is not just for big teams. It saved my work when files got lost locally — which actually happened to me at the start of this project.
6. Naming conventions are professional habits
I learned the hard way that folder names with spaces and special characters like CSS Setup & Basic Styling break URLs on GitHub Pages. Clean names like portfolio with no spaces or symbols are the right way to work.
7. Small details make a big difference
Adding hover effects, smooth scrolling, animated blobs and a pulsing status dot seemed like small things but they made my portfolio feel professional and alive. I learned that CSS transitions and keyframe animations are not complicated — they just need practice.

## Challenges Faced
What problems did you encounter and how did you solve them?

1. My portfolio files got lost in my computer i didnt remember the name that i named it
The biggest problem I faced was losing my portfolio files. This taught me the importance of saving work locally and pushing to GitHub regularly.
2. Folder name with spaces broke my GitHub Pages URL
My portfolio folder was named CSS Setup & Basic Styling which contained spaces and an ampersand. This caused the GitHub Pages URL to become ugly and broken — encoding it as CSS%20Setup%20%26%20Basic%20Styling. I learned that folder and file names should always be lowercase with no spaces or special characters.
3. My photo was not showing up
When I first tried to add my photo, nothing appeared on the screen. The problem was that bella.jpg was not in the same folder as index.html. Once I moved the photo into the correct folder and matched the filename exactly in the src attribute, it worked. I learned that file paths are case sensitive and must match exactly.
4. style.css was named incorrectly
My stylesheet was named style.css when the task required styles.css. This seems like a tiny difference but it caused my styles to not load at all in some situations. I learned that filenames must match exactly what is referenced in the HTML link tag.
5. README had template placeholders left in
I submitted my README with template prompts still inside it — lines like "What did you learn while building this project?" were still there as headings without answers. I also accidentally left an AI chatbot follow-up question inside the file. I learned to always read through my README carefully before committing.
6. Git push asked for a password and I did not know what to use
When I ran git push for the first time, GitHub asked for a password. I tried my normal GitHub password and it was rejected. I learned that GitHub no longer accepts passwords in the terminal — you need to generate a Personal Access Token from GitHub Settings and use that instead.
7. Live Demo link in README was broken
My README had a broken Live Demo link with multiple nested brackets and the template placeholder your-deployed-url.com still inside it. Nobody could click it. I learned to always test every link in my README before submitting by clicking it myself.
8. Commits were not descriptive
Nine out of my eleven commits were just called Update README.md. I learned that commit messages should describe exactly what changed — for example Fix broken live demo link or Add bella.jpg profile photo — so that anyone reading the commit history can understand what happened at each stage.

## Screenshots (optional)
![Screenshot description](path/to/screenshot.png)

## Live Demo (if deployed)
[View Live Demo]([https://your-deployed-url.com](https://github.com/Bella1234-ai/iyf-s10-week-03-bella1234-ai-portifolio-to-present-in-class.git))
