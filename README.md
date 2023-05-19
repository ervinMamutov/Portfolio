# Portfolio

> A longer description

## Table of contents

- [Portfolio](#portfolio)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Screenshots](#screenshots)
  - [Technologies](#technologies)
  - [Setup](#setup)
  - [Code Examples](#code-examples)
  - [Status](#status)
  - [Inspiration](#inspiration)
  - [Contact](#contact)
  - [Instructions for use](#instructions-for-use)
  - [Code Quality Checks](#code-quality-checks)
  - [Continuous Integration (CI)](#continuous-integration-ci)
  - [Repo Setup](#repo-setup)

## General info

> A short description This project to create my portfolio

## Screenshots

![Example screenshot](./public/img/portfolio-screen.png)

## Technologies

- Node 18
- VSC code
- Html5
- CSS3
- VSC code
- npm

## Setup

- `clone the rep`
- `npm install`

## Code Examples

-HTML

```html
<main>
  <section class="photo-container">
    <a href="./pages/about.html" class="photo a-photo">
      <img src="./public/img/ervin.jpg" alt="my photo" class="photo-my" />
      <h1 class="name">Ervin Mamutov</h1>
      <div class="glow-wrap">
        <i class="glow"></i>
      </div>
    </a>
  </section>
</main>
```

-CSS

```css
.photo .photo-my {
  width: 20rem;
  height: 30rem;
  object-fit: cover;
  filter: grayscale(10%) contrast(120%);
  box-shadow: 10px 15px 25px 0 rgba(0, 0, 0, 0.2);
  display: block;
  margin-top: -1rem;
  border-radius: 10px;
}
```

## Status

Project is: _in progress_

## Inspiration

This is a portfolio development project.

## Contact

By [Ervin Mamutov](https://github.com/ervinMamutov)

## Instructions for use

<!-- a guide to using this repository -->

1. `git clone git@github.com:ervinMamutov/Portfolio.git`
2. `cd template-markdown`
3. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run lint:ls`: Checks to make sure all folder and file names match the
  repository conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository.
- `npm run lint:css`: Will lint all of the CSS files in this repository.
- `npm run validate:html`: Validates all HTML files in your project.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.
- `npm run accessibility -- ./path/to/file.html`: Runs an accessibility analysis
  on all HTML files in the given path and writes the report to
  `/accessibility_report`

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running the code quality scripts
locally.

## Repo Setup

- Give each member **_write_** access to the repo (if it's a group project)
- Turn on GitHub Pages and put a link to your website in the repo's description
- Turn on GitHub Actions
- In _General_ Section > check **Discussions**
- In the _Branches_ section of your repo's settings make sure the
  `master`/`main` branch must:
  - "_Require a pull request before merging_"
  - "_Require approvals_"
  - "_Dismiss stale pull request approvals when new commits are pushed_"
  - "_Require status checks to pass before merging_"
  - "_Require branches to be up to date before merging_"
  - "_Do not allow bypassing the above settings_"

</details>
