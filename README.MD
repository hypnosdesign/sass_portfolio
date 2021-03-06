#Instructions

In this project you will convert a CSS stylesheet to Sass. You'll refactor the stylesheet from the "Responsive Layout" project using SCSS partials, variables, extends, and mixins.
***
**NOTE:** To get an "Exceeds Expectations" grade for this project, you'll need to "exceed" on every requirement that has an "Exceeds Expectations" option.
***
**NOTE:** The Front End Web Development Techdegree is meant to train you in HTML, CSS and JavaScript, and let you practice and show your mastery of these fundamental building blocks of the web. Because of that, please avoid using frameworks like Bootstrap, Foundation, Skeleton, and so on for this project. Even though you may end up using frameworks like these professionally, you still need to know and be able to implement designs with your own knowledge of HTML, CSS and JavaScript.
***
In addition, please avoid submitting any projects that rely on a server-side technology like PHP or Ruby on Rails.

##Project Instructions

To complete this project, follow the instructions below. If you get stuck, ask a question in the community.

####**13 STEPS**

[x] 1) **Create a 'scss' folder in your "Responsive Layout" project.**

***
[x] 2) **Convert the CSS stylesheet to an SCSS stylesheet, then place it inside the 'scss' folder.**

***
[x] 3) **Run Sass from the console or with a tool like CodeKit, Workspaces, or any of these.**

***
[x] 4) **In the 'scss' folder, create subfolders to organize your CSS code into Sass partial files.**
  - For example for base styles, layout, components, and so on.
  - Create at least three folders.

***
[x] 5) **Group related sections of CSS into SCSS partials.**
  - For example, base styles for elements can go inside a \_base.scss partial inside the 'base' folder.
  - Create at least 3 Sass partial files.

***
[x] 6) **Import your partials into your project's main SCSS file.**
  - When using multiple @import’s make sure they are listed in the correct order for styling.

***
[x] 7) **Find repeating patterns in the stylesheet and extract them into placeholder selectors, then extend them wherever necessary.**
  - At a minimum create at least one placeholder selector, and use it with the \@extend keyword in at least 3 other selectors.

***
[x] 8) **Create variables for repeating values. At a minimum create variables for colors, font-sizes and font-family values.**

***
[x] 9) **Write mixins for media queries.**

***
[x] 10) **Create at least one example of a nested Sass rule.**
For example:
```css
nav {
    ul {
        margin: 0;
       padding: 0;
        list-style: none;
    }
li { display: inline-block; }
a {
   display: block;
    padding: 6px 12px;
    text-decoration: none;
   }
}
```

***
[x] 11) **No nested rules greater than 3 levels deep.**
For example:
```css
.weather {
    .cities {
        li {
             // no more!
        }
    }
}
```
***
[x] 12) **You don’t need to make any changes to your original design, but make sure the site is still responsive and works well on different screen sizes.**
***
[x] 13) **Make sure to check your code is valid by running it through an HTML and CSS validator.**
- Links to the validators can be found in the Project Resources. This will help you spot any errors that might be in your code.
- **There are a few exceptions that you don’t need to fix:**
  - Don’t worry about any warnings, we just need you to check any errors that might be there.
  - If CSS validator flags use of calc, or vendor prefixes these errors should be ignored.
  - If HTML validator flags use of pipe (‘|’) in Google font links/URLs this error can also be ignored.

##Extra Credit
To get an "exceeds" rating, you can expand on the project in the following ways:

####**8 STEPS**

[x] 1) **Create multiple subfolders (more than 3) for organizing styles.**

***
[x] 2) **Create multiple SCSS partial files (more than 3).**

***
[x] 3) **Multiple (more than 1)placeholder selectors**

***
[x] 4) **Multiple (more than 3) uses of @extends with placeholders**

***
[x] 5) **Multiple (more than 1) additional Sass variables (not just color, font-size, font-family).**

***
[x] 6) **Include at least 1 additional mixin for other code (not just for media queries)**

***
[x] 7) **Create more than 3 nested Sass rules where appropriate.**

***
[x] 8) **Using JavaScript or CSS/Sass, include an icon that, when clicked toggles the navigation on and off when on mobile screen sizes.**
