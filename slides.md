What is prototyping in the browser?

## HTML + CSS + JS <!-- .element: class="fragment code" data-fragment-index="1" -->
## ⬇️ <!-- .element: class="fragment" data-fragment-index="2" -->
## WP templates <!-- .element: class="fragment code" data-fragment-index="3" -->

Note: Prototyping in the browser is a process of creating markup and styles independent from WordPress so you can preview what your final site will look like. At Alley Interactive, we’ve found this process holds a number of advantages over a more traditional design process in which you create or receive static, high-fidelity mockups in Photoshop, Sketch or a similar design tool and move directly into WordPress from there.

---

## What is Huron?

<img src="https://cl.ly/0l440j1I1W15/download/Image%202017-05-24%20at%2011.11.17%20AM.png" width=200 alt="Webpack"><!-- .element: class="fragment" data-fragment-index="1" -->

![KSS](https://cl.ly/2V2O0d3V0Q0y/download/Image%202017-05-24%20at%2011.02.58%20AM.png)<!-- .element: class="fragment" data-fragment-index="1" -->

Note: At Alley Interactive, we built an open-source tool called Huron that uses node and the Knyle Style Sheets system to create component-based, in-browser style guides and prototypes. We’ll be showing you how you can use Huron in your own prototyping process.

---

# 1️⃣

Note: There are two sides to how this prototyping system works. First!

---


## [Gif of styleguide goes here]

It creates a style guide of all your components

Note: So you can see in an ordered way what each components looks like separate from the rest of your site.

---

# 2️⃣

Note: And second!

---

## [Gif of prototype html updating]

It allows you to arrange those same components together in a prototype.

Note: With just HTML and an optional templating language, you can make a version of your theme that looks just like what your final site will look like.

---

## 🤔
## How do you decide to prototype a project?

Note: Any new redesign of a WordPress theme where you need to architect a new design from scratch.

It could also work on themes where you are building the design of a new component or area. You can commit to prototyping as much or as little of the theme as you like, depending on your project’s needs.

This process is best suited to building a specific website. If you are building a general theme for sale, this probably isn’t worth it.

---

## < 🎨 > <!-- .element: class="code" -->
## Why choose to prototype in the browser?

Note: Lets go over some reasons.

---

# 🔨
## It’s more maintainable.

Note: *Maintainable*: Because atomic design forces you to keep your components small and modular, you can make changes to one component without being afraid the change will cascading unintentionally to other parts of your site.

---

# 👯
## Design discrepancies become obvious.

Note: Obvious discrepancies: Using a prototype and a style guide will encourage component reuse. So it is easier to catch the small things that are different in static design comps and then ask the question — _should_ this be different?

---

# 🙋
## Design implementation issues can be addressed earlier.

Note: The design will be vetted much earlier in the process for in-browser feasibility. No more discovering you need to show and hide markup based on screen size and not being able to go back to design and fix it.

---

# 👩‍💻💯
## Clients “experience” their website sooner.

Note: You don’t have to wait for the back-end or data migration to be complete before you start building and delivering your front-end code.

Even if waiting for a data migration isn’t not a factor, you can use hot module reloading to edit and refine your markup faster than a livereload-type setup.

This means that you can get a working website in your clients’ hands sooner

---

# 👩‍💻👨‍💻
### Front-end and back-end can progress _independently_ and _simultaneously_.

Note: If you’re on a team, front- and back-end work can happen independently and in a rolling, modular fashion. All your work on dynamic interactions with javascript, css styles, and markup structures can proceed without related back-end work blocking it. You won’t have to wait for a template part to be finished before working on styles for it.

---

# 🔨 ✖️ 1️⃣
### When you’re done, you have a production front-end!

Note: All the front-end work you put into building in-browser prototypes will work seamlessly (or near seamlessly) with your PHP markup in the WordPress theme.

---

# 🤔
## When do you start prototyping?

Note: You can start prototyping in the browser after you’ve established the components that are going to be on a page.

Low-fidelity wireframes usually come first — wireframes that show the placement and location of modules on a page, but don’t get into “pixel perfection.”

---

# ⚙️
## How it works

Demo time 

Note: ### Go over requirements

Quick overview of npm
Quick overview of webpack (and build config)
Create Huron-specific configuration file
Create prototype html file
Create scss file
Create JSON file with data
Create HBS file
Show ✨ magic - it all coming together when you run the server
Show how to build to get a link to share.
Show how the css files are enqueued in assets.php for the WordPress theme
