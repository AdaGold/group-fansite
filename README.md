# Static Site: Code Journal & Portfolio
__Learning Goal:__ Practice creating semantic HTML and applying visual styles with CSS. The goal is to explore the relationship between HTML and CSS, and how visual styles add to the semantics and hierarchy established by the foundational HTML.

You will create a _static_ web site using HTML & CSS. This static site will serve as the foundation for later projects, and will contain information about your programming projects and efforts at Ada.

## Project Requirements
This is an individual project. It consists of a baseline and a single wave. You are only permitted to use static HTML and CSS for this project. Preprocessors (haml, erb, sass, less, etc.) and Javascript of any time are not allowed.

### Baseline
- Create an `index.html` that has the necessary meta information to link a stylesheet called `styles.css`.
- Add a `<header>`, `<footer>`, and `<nav>` to your `index.html`.
- Create a `portfolio.html` page that also includes `styles.css`.
- Include a link to both pages in the `<nav>` on both pages.

### Primary Requirements
- Add pages to your static site. The requirement is a minimum of four pages. These pages should be:
    - `index.html`
    - `portfolio.html`: information about the projects you've completed at Ada (or elsewhere) with links (to github repo), descriptions, images, etc.
    - `code-journal.html` or `hobby-blog.html`: article or blog style posts about either your journey/observations about programming or a hobby you enjoy.
    - `about.html`: some information about you, your interests, background or similar. Whatever you're comfortable sharing.
- The site should follow best practices including:
  - All markup should be semantic, with consideration of hierarchy and accessibility.
  - CSS should be concise and well formatted
  - Images and stylesheets should be kept in their own folders, called `images` and `stylesheets`, respectively.
  - Given that this is our first html/css project, full browser compatibility is not a requirement, but you should make a minimal effort for _acceptable visual consistence_ in two of the three primary browsers available on OS X (Safari, Chrome, and/or Firefox).

### Optional Enhancements
- Create a `blog/` or `code-journal/` directory. Within this directory...
  - create single `html` file for each entry in your blog/journal
  - update the nav on the rest of your site to reference each entry as a sublist/subnav.
  - update any tags with path references (`img`, `link`, `a` tags) to accomodate for the entries being in a different directory.
- Create any number of additional pages or directories.

### A Word of Caution
Lots of developers find their initial foray into CSS frustrating. Every browser implements the CSS standard a little (or a lot) differently. Learning to manipulate elements and understand the _box model_ takes time. Floats can be especially challenging to developers new to CSS. For this project, focus on understanding the mechanics and semantics of HTML and CSS, and how the two work together.
