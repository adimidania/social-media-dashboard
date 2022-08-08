# Frontend Mentor - Social media dashboard with theme switcher

![Design preview for the Social media dashboard with theme switcher coding challenge](./design/desktop-preview.jpg)

## The challenge

The challenge is to build out this Social Media Dashboard and get it looking as close to the design as possible.

For this one, I've decided using SASS instead of CSS. So I'll drop some notes below:

## Notes

- Here's a quick [Summary](https://danialearns.notion.site/SASS-f860ee7ea4f0476ea9efefe5b42f9777) from the freecodecamp SASS course that I took right before starting the challenge.

- SCSS folder contains 3 sub-folders, this was done for the sake of organization, you can clearly see that we have a sub-folder for utilities (breakpoints and functions that we will be using), globals contains some stylings that will be using, and finally components contains the styling our components such as cards etc. This makes it easy to navigate!

- The `_index.scss` file is responsible for loading all the scss files within the given folder.

- [BEM](https://sparkbox.com/foundry/bem_by_example#:~:text=BEM%20(which%20stands%20for%20Block,read%2C%20understand%2C%20and%20scale) (Block-Element-Modifier) is a naming convention standard for CSS class names. It has fairly wide adoption and is immensely useful in writing CSS that is easier to read, understand, and scale.

## Installation

- We use gulp to compile scss to css. In order to install it globally you can run the following command `npm install gulp-cli -g` on your terminal.

- We also need to install these packages `npm @babel/core @babel/preset-env postcss autoprefixer`. These will work on prefixing (-webkit-, -moz- etc that we usually type ourselves), these will help doing it automatically.

- We also need to install browser-sync by running this command `npm install browser-sync` So we can keep an eye on the changes without having to reload the page.

- We also need to install cssnano which takes our formatted CSS and runs it through many focused optimisations, we can do so by running the follwoing command `npm install cssnano`.

- Another command (bare with me) that should be run is `npm install dart-sass`, this allow us to use @forward and @use.

- Just one more command `npm install gulp gulp-babel gulp-sass gulp-postcss gulp-terser`

- **Have fun building!** 🚀
