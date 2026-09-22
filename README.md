# COMP 322 — Assignments 1 and 2 example

Use this existing student website as a reference when correcting your own work.
The biography, courses, and education are Brandon's original example content;
replace them with your own information and images. Assignment 3 code is not
included here.

## Files and requirements

```text
index.html            Biography, image, courses, links to both other pages
introduction.html     Skills/abilities/education/training table, images, home link
little_prince.html    Cover, passage, CSS classes, home link
styles.css            Little Prince layout, underline, orange highlight, bold red text
img/                  Images referenced by the HTML files
```

Assignment 1 creates `index.html` and `introduction.html` in an `a1` folder.
Assignment 2 publishes that work and adds `little_prince.html`. This repository
places the website files at its root so GitHub Pages can serve `index.html`.

## Paths that work after publishing

```html
<!-- These pages are in the same directory. -->
<a href="introduction.html">Introduction</a>
<a href="little_prince.html">The Little Prince</a>
<a href="index.html">Home</a>

<!-- This image is inside the img directory. -->
<img src="img/img1.jpg" alt="Describe your image">

<!-- This CSS file is beside little_prince.html. -->
<link rel="stylesheet" href="styles.css">
```

Use forward slashes and exact filenames, including capitalization. Paths such as
`C:\Users\...`, `/Users/...`, and `file:///...` refer to your computer and will not
work for visitors. This example retains the existing filename
`img/littile_prince.jpg`; if you rename it, update the HTML too.

## Check your pages

Open `index.html` in a browser. Follow both page links and each Home link.
Confirm the home page has a biography, an image, and a course list, and the
introduction has a four-column table and at least two images. Check that the
Little Prince cover and passage have matching widths, the specified passages
are underlined/highlighted, and the quotations are bold red. Its styles come
from CSS classes, with no inline `style` attributes on that page.

## Publish and verify

Commit and push the HTML, CSS, and images together. Configure GitHub Pages to
publish the branch and directory containing your `index.html`, then open the
published URL and repeat the checks above. A public repository alone does not
prove that Pages is deployed. Test in a signed-out or private browser window.

- Repository URL: `https://github.com/USERNAME/REPOSITORY`
- Project Pages URL: `https://USERNAME.github.io/REPOSITORY/`
- A repository named exactly `USERNAME.github.io` uses `https://USERNAME.github.io/`.

Assignment 2 asks for the home repository (`USERNAME.github.io`). This instructor
example uses a project repository; its expected Pages URL, once enabled, is
`https://bbyrd2021.github.io/comp322_assignment2/`.

For Assignment 2, the class announcement specifies one ZIP containing the
published URL in a text file, a screenshot of the published website, and a
screenshot of GitHub commits. A repository/code screenshot does not show the
rendered website. Follow the submission instructions for each assignment;
Assignment 3 has its own requirements.
