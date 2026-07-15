Web Basics — My Learning Project

This is my personal repo for learning web development from scratch: HTML, CSS,
and responsive design. I'm working through a course, building small pages as I go,
and committing my progress with Git.

I'm an architect / computational designer, so my long-term goal is a portfolio
website and web skills that complement my AEC work.


Learning resource

Following this Udemy course:


Build Responsive Real-World Websites with HTML and CSS
"Learn modern HTML5, CSS3 and web design by building a stunning website for your
portfolio! Includes flexbox and CSS Grid."
— by Jonas Schmedtmann (jonas.io)



All credit for the teaching material goes to the course author. This repo is just my
own practice work while following along.


What I'm learning


 HTML fundamentals — structure, tags, semantic elements
 CSS fundamentals — selectors, the box model, colors, fonts
 Layout with Flexbox
 Layout with CSS Grid
 Responsive design (making pages work on phones and desktops)
 Building a full page from scratch


(I tick these off as I finish each section.)


Folder structure

I'll grow this as I go. Right now it looks roughly like:

web-basics/
├── README.md          <- this file
├── index.html         <- main page
├── css/
│   └── style.css      <- my styles
└── images/            <- pictures used in the pages


Note: as the course moves through different mini-projects, I may add a folder per
exercise (e.g. 01-flexbox-practice/, 02-grid-practice/) so each stays self-contained.




How to view it locally

No build tools or installs needed — it's just HTML and CSS.

Option 1 — open directly:
Double-click index.html, or drag it into a browser window.

Option 2 — Live Server (auto-refreshes when I save):
In VS Code, install the Live Server extension, then right-click index.html
→ "Open with Live Server." The page reloads automatically on every save.


My Git workflow

Basic loop I use while learning:

bashgit add .                       # stage my changes
git commit -m "message here"    # save a snapshot with a note
git push                        # (if using a remote like GitHub) upload it

I try to commit after finishing each small piece, with a short message like
"add hero section" or "fix flexbox alignment" — so my history reads like a diary
of what I learned.

Learning in public, one commit at a time.