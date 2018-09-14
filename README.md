# Personal Portfolio Site

Use HTML & CSS to create a static site whose content is your portfolio. Your personal portfolio site should contain information about you and the coding work you've done.

This is an individual, [stage 2](https://github.com/Ada-Developers-Academy/pedagogy/blob/master/rule-of-three.md) project.

## Learning Goals:
- Practice creating semantic HTML
- Practice applying visual styles with CSS
- Use both HTML & CSS together to create a comprehensive design

## Project Requirements
This is an individual project. It consists of a baseline and a single wave. You are only permitted to use static HTML and CSS for this project. Preprocessors (haml, erb, sass, less, etc.) and Javascript of any kind are not allowed. All submitted HTML needs to pass as valid HTML through an HTML Validator.

### Baseline
- Create an `index.html` that has the necessary meta information to link a stylesheet called `styles.css`.
- Add a `<header>`, `<footer>`, and `<nav>` to your `index.html`.
- Create a `portfolio.html` page that also includes `styles.css`.
- Include a link to both pages in the `<nav>` on both pages.

### Primary Requirements
- Add pages to your static site. The requirement is a minimum of four pages. These pages should be:
    - `index.html`
    - `portfolio.html`: information about the projects you've completed at Ada (or elsewhere) with links (to GitHub repo), descriptions, images, etc.
    - `code-journal.html` or `hobby-blog.html`: article or blog style posts about either your journey/observations about programming or a hobby you enjoy
    - `about.html`: some information about you, your interests, background or similar. Only post what you're comfortable sharing!
- The site should follow best practices including:
  - All markup should be semantic, with consideration of hierarchy and accessibility
  - CSS should be concise and well formatted
  - Images and stylesheets should be kept in their own folders, called `images` and `stylesheets`, respectively
- Run your site through an [HTML Validator](https://validator.w3.org/#validate_by_upload) and fix all errors before submitting

### Optional Enhancements
- Create a `blog/` or `code-journal/` directory. Within this directory...
  - create single `html` file for each entry in your blog/journal
  - update the nav on the rest of your site to reference each entry as a sublist/subnav.
  - update any tags with path references (`img`, `link`, `a` tags) to accommodate for the entries being in a different directory.
- Create any number of additional pages or directories.

### A Word of Caution
A lot of developers find their initial foray into CSS frustrating. Every browser implements the CSS standard a little (or a lot) differently. Learning to manipulate elements and understand the _box model_ takes time. Layout can be especially challenging to developers new to CSS. For this project, focus on understanding the mechanics and semantics of HTML and CSS, and how the two work together.

### Inspiration
- [http://lizabinante.com/](http://lizabinante.com/)
- [http://where.coraline.codes/](http://where.coraline.codes/)
- [http://danisaurus.github.io/](http://danisaurus.github.io/)
- [http://www.fenslattery.com/](http://www.fenslattery.com/)
- [https://www.heyellieday.com/](https://www.heyellieday.com/)
- [http://car.oline.codes/](http://car.oline.codes/)

### Optional: Deploy with GitHub Pages
Want more? Make your site live on the internet! There are a lot of ways to go about hosting a live website, but GitHub provides a way to host static sites for free using your GitHub account. [Follow the steps listed here](https://pages.github.com/).

## What Instructors Are Looking For
Check out the [feedback template](feedback.md) which lists the items instructors will be looking for as they evaluate your project.
