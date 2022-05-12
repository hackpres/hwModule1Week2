# <personalPortfolio>

## Description
This challenge was to build a portfolio page from scratch. It was a very enjoyable project to take on, and definitely stretched me as a developer. I'm proud of what I've created, and I look forward to refactoring it and making improvements in the future.

The required acceptance criteria is as follows
```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

However, I used this project to really try to stretch myself creatively. So my project meets the acceptance criteria while also including additional features (listed below).

-I learned the importance of keeping your stylesheet organized. Paricularly as my page got larger and more complex it continuously became more of a challenge to find the styling I was looking for. Adding all caps "header" comments helped to keep things organized and tell me where to add the styling I needed.

-I dabbled just a bit in adding some simple boolean changer in JavaScript. It was a fun addition and I really like how it was able to completely alter the feel of my site for mobile screens.

## Git links
github repo url: 
https://github.com/hackpres/personalPortfolio

github deployed url:
https://hackpres.github.io/personalPortfolio

## Screenshots of deployed app
![mobileSize](/assets/images/mobileSize.png?raw=true "Mobile view")
![tabletSize](/assets/images/tabletSize.png?raw=true "Tablet view")
![desktopSize](/assets/images/desktopSize.png?raw=true "Desktop view")

## Usage & Features

Navigation of my portfolio is super easy, as I utilized id links for the nav bar, and overflow-x: hidden; on the body to avoid any horizontal scrolling!
![nameAvatarNav](/assets/images/nameAvatarNav.png?raw=true "Header section")

I chose to add my work before "about me" because it's a portfolio site, and as such most viewers will be interested in seeing my work first. At the point that they are accessing my portfolio, they likely already know that I'm in web development, so I think giving them the work first feels cleaner. Then I am able to follow the work up with a quick statement about myself which helps to connect the work to a person (Me!).
![work](/assets/images/work.png?raw=true "Work section")

I added a form so site users can send me information about themselves to make a connection that much easier. Although it lacks an action at the moment, so the info has nowhere to be sent.
![form](./assets/images/form.png?raw=true "Form section")

At the bottom of my site is a connect section with links to a few of my social media accounts. I used font-awesome icons (https://fontawesome.com/icons) for the links.
![connect](./assets/images/connect.png?raw=true "Connect section")






