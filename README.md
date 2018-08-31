![CF](https://i.imgur.com/7v5ASc8.png)  Lab 01: Mobile First
=======
[Code of Conduct](https://github.com/codefellows/code-of-conduct)

## Lab 01

Welcome to your intro lab assignment for Code 301!!

This morning, we'll be kicking off our blog app by applying our knowledge of CSS to implement a mobile-first design using responsive web design techniques.

You and your partner will be able to incorporate the CSS you each write this morning as you continue working on this blog tomorrow morning.

*Please take the time to read carefully through each of the READMEs for lab assignments as they have detailed information regarding your assignment, such as: submission instructions, resources, configuration, user stories with feature tasks, and documentation.*

## Resources  
<!-- a list of links if any are necessary for the assignment-->
- [Video: Mobile Testing Tip for Your Phone](https://www.youtube.com/watch?v=2t4E_tc8TKM)

---

## Configuration
_Your repository must include:_

- `.gitignore` - with standard NodeJS configurations
- `.eslintrc.json` - with Code 301 course standards for the linter

```
01-mobile-first
└── starter-code
└── driver-navigator
	├── .eslintrc.json
	├── .gitignore
	├── LICENSE
	├── index.html
	├── styles
	│   ├── base.css
	│   ├── layout.css
	│   └── modules.css
	└── vendor
	    └── styles
		   ├── fonts
		   │   ├── icomoon.eot
		   │   ├── icomoon.svg
		   │   ├── icomoon.ttf
		   │   └── icomoon.woff
		   ├── icons.css
	  	   └── normalize.css
	└── PULL_REQUEST_TEMPLATE.md
	└── README.md
```

---

## User Stories and Feature Tasks

**Note: This intro lab only includes HTML and CSS, no JavaScript or jQuery yet!**

Follow along with the TODOs in the `index.html` file of the starter code.

*As a user, I want to have an application that looks good, is easy to use, and is updated often, so that I want to come back and use it frequently.*

- Working from the provided comp images, write CSS such that the browser rendering matches the images as closely as possible.
- Utilize the icon fonts located in `styles/icons.css` for navigation features as shown in the comp images.

*As a developer, I want to use standard industry practices for setting up and organizing the code that handles the styling of my application so that my code is easy to edit and maintain.*

- Utilize a [`normalize.css`](https://github.com/necolas/normalize.css/blob/master/normalize.css) file, which should be placed in a `vendor/styles/` directory, to override default browser settings that affect the way documents render.
- Utilize SMACSS practices to organize CSS into separate files and appropriately order the loading of those files in the `<head>` of the HTML document.

*As a user, I want a familiar experience of the application so that I know how to use it on my smartphone and occasionally my laptop.*

 - Initially design the application to render per the comp images on mobile devices.
 - Set up the viewport and fluid media rules so content renders per the comp images in both mobile and desktop views. Use a breakpoint of 640 pixels.
 - Add a "Hamburger" menu button that reveals the nav links when hovered over.
- Ensure that images are responsive and do not exceed the size of the viewport.

## Submission
This assignment is just getting you set up for success tomorrow, so you have nothing to turn in today! You can use this CSS tomorrow morning in your lab.
