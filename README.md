# LAB - HTML + CSS Static Full Page Site - MFAH

## Context
The Museum of Fine Arts Houston wants to create a static webpage that shows their architectural history and future projects.  

They have provided us with the copy as well as the images and logos. We will need to create a site that places that content on the page with the styles and layout that are shown in the mockups below.

---

## Objectives
Create a site that has a multi-column layout.

### Learning Objectives

After completing this assignment, you should be able to create a multi-column layout in HTML and CSS and a faithful representation of a design.

## Performance Objectives

You should:
- use flexbox for making the columns
- use fluid widths (%) on columns so that they dynamically adjust to screen width
- be mindful of margin and padding and when/where to use them
- be mindful of typography

## Deliverables
- an `index.html` file with the content
- a `style.css` file with the styles
- a Github repository

----

## Setup Instructions

1. In Terminal:
  ```sh
  #(1) create a directory for this lab called `html-css-static-fullpage-mfah` in `~/Documents/muktek/labs` and cd into it.
  mkdir ~/Documents/muktek/labs/html-css-static-fullpage-mfah
  cd ~/Documents/muktek/labs/html-css-static-fullpage-mfah

  #(2) Download + unzip the image files for the project
  curl https://raw.githubusercontent.com/muktek/lab--html-css-static-fullpage-mfah/master/image-files.zip > image-files.zip

  #(3) unzip the image files for the project
  unzip image-files.zip

  ```

2. Create your project files and folders
  ```
  - index.html
  |
  + css/
    |
    - style.css
  ```

3. Use the `<link>` tag to link your `style.css` to your `index.html` in the `<head>` of your `index.html` file

4. In your CSS, you will need to apply border-box sizing to all elements:
  ```css
  * { box-sizing: border-box }
  ```

---

## Normal Mode
Create a site based on the mockup as shown below.

### The full-screen layout
![full](https://github.com/t3patterson/TIY-2016-Q3/blob/master/assignments/layout-html-css-mfah/mfah-fullscreen.gif)

----

## Adventurer Mode
Use media-queries to create a responsive site. The site should be one column on mobile screens (i.e. screen widths < 768px), and it should maintain the original layout on screen widths > 768px.

Also note that the search box at the bottom right becomes hidden on < 768px.

![mobile](https://raw.githubusercontent.com/t3patterson/TIY-2016-Q3/master/assignments/layout-html-css-mfah/mfah-mobile-layout-mockup.png)

----

## Additional Information
#### Designer Specs
```
+ The font stack for the project is: Helvetica Neue, Helvetica, sans-serif

+ Blue fixed call-to-action component on bottom-right has background-color: #3A539B

+ Anchor tag color : #3E7FBB.

+ Red color is : #DB4B38
```

#### Copywriter's Text
The **copywriter's text** can be found [here](https://github.com/TIY-Charleston-Front-End-Engineering/Course-Guide/blob/master/assignments/layout-html-css-mfah/mfah-architecture-site-copy.txt).
