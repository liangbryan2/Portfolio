# Portfolio
[View my portfolio here](https://liangbryan2.github.io/Portfolio/)


Here we have my portfolio which contains all of the projects I have created during my time at the UC Berkeley Extension Coding Bootcamp. I decided to pick up [UI Kit](https://getuikit.com/) for this portfolio as I have seen what it can do during project I. I am still getting used to everything UI Kit can do, and I also still prefer Bootstrap's grid, but I like the overall feel of UI Kit's prebuilt components as opposed to Bootstrap's prebuild components.

## Learning Points
I really wanted to create a site that had smooth scrolling and some sort of parallax animation styling to it. I think I achieved my goal here with this portfolio. UI Kit made it really easy to create those effects and they were all there in their documentation. I did not use any JavaScript, but I am sure there is javascript involed for the slideshow on UI Kit's end. 

## Code Snippets
This portfolio is 90% in the HTML with the 10% being me not liking UI Kit's default styling.
Here we have the navbar. As you can see, each div has many classes. Each class comes from UI Kit and alters the div accordingly. I probably should not have used so many UI Kit classes, but I was learning this new framework and challenged myself to mostly use their classes. The @s you see is their syntax for all things media query related. In this case, I hide the main navbar when the site is viewed on a mobile device and show a toggle icon for navigation instead.
``` html
<nav class="uk-navbar-container uk-background-secondary" uk-sticky="animation: uk-animation-slide-top; top: 100">
  <div class="uk-navbar-left uk-background-default uk-visible@s">
    <a href="#" class="uk-navbar-nav uk-logo uk-padding-small" uk-scroll>Bryan Liang</a>
    <ul class='uk-navbar-nav' uk-scrollspy-nav="closest: li; scroll: true; offset: 100">
        <li>
          <a href="#aboutMe">About Me</a>
        </li>
        <li>
          <a href="#portfolio">Portfolio</a>
        </li>
        <li>
          <a href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  <a href="#offcanvas-nav" class='uk-padding uk-hidden@s' uk-navbar-toggle-icon uk-toggle></a>
  <a href="#" class="uk-navbar-brand uk-logo uk-padding-small uk-hidden@s" uk-scroll>Bryan Liang</a>
</nav>
```
## Built With
* HTML
* CSS
* [UI Kit](https://getuikit.com/)

## Author

**Bryan Liang** - [My Github](https://github.com/liangbryan2)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
