What is prototyping in the browser?

## HTML + CSS + JS <!-- .element: class="fragment" data-fragment-index="1" -->
## ⬇️ <!-- .element: class="fragment" data-fragment-index="1" -->
## WP templates <!-- .element: class="fragment" data-fragment-index="1" -->

Note: Prototyping in the browser is a process of creating markup and styles independent from WordPress so you can preview what your final site will look like. At Alley Interactive, we’ve found this process holds a number of advantages over a more traditional design process in which you create or receive static, high-fidelity mock-ups in Photoshop, Sketch or a similar design tool and move directly into WordPress from there.

---

## What is Huron?

![Huron](https://cl.ly/3L1V1g3M3a3c/download/www.npmjs.com-package-huron.png)

Note: At Alley Interactive, we built an open-source tool called Huron that uses node and the Knyle Style Sheets system to create component-based, in-browser style guides and prototypes. We’ll be showing you how you can use Huron in your own prototyping process.

---

# Why do prototyping in the browser?

Note: There are two sides to how this prototyping system works. First!

---

![Gif of styleguide](https://cl.ly/2s292S0z3J2q/download/Screen%20Recording%202017-05-27%20at%2011.51%20AM.gif)

1️⃣  It creates a style guide of all your components

Note: So you can see in an ordered way what each components looks like separate from the rest of your site.

---

![Gif of prototype html updating](https://cl.ly/0z2A0v1v3v3z/download/Screen%20Recording%202017-05-27%20at%2012.03%20PM.gif)

2️⃣ It allows you to arrange those same components together in a prototype.

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

@todo this slide can be expanded to talk more about modular workflow.

---

# ⚙️
## Workshop time

Note: ### Go over requirements

Quick overview of npm
Quick overview of webpack (and build config)
Create Huron-specific configuration file
Create entry point
Create prototype html file
Create scss file
Create JSON file with data
Create HBS file
Show ✨ magic - it all coming together when you run the server
Show how to build to get a link to share.
Show how the css files are enqueued in assets.php for the WordPress theme

@todos
Make slide for people to fork https://github.com/pattiereaves/huronforwp/tree/demo
Ask in slack channel if most people attending the workshop have a local dev environment for WP.


---

[http://bit.ly/wcpwm17-huron](http://bit.ly/wcpwm17-huron)
