# **Bedtime Stories**

## <a id="introduction-aa"></a>**Introduction**

The [Bedtime Stories](https://github.com/DaSHdotHub/BedtimeStories) website is a page for parents and children alike.
As long as someone can read, he or she should be encouraged to visit to check for new or classic short stories.

One of the key concepts of this website is to showcase cherished short stories from our childhood, creating an immersive experience beyond plain black text on a white background.

### <a id="motivation-aa"></a>**Motivation**

One of the things I do most regularly is read a goodnight story to my son. As marvelous as books are, there are times when it's not possible to bring them along on a trip. A website like [Bedtime Stories, deployed on GitHub pages](https://dashdothub.github.io/BedtimeStories/) 
charms readers with its simplicity and old-fashioned retro styling.

![Am I Responsive](assets/img/doc/am-i-responsive.webp)


## **Table of Contents**

## [**Introduction**](#introduction-aa)

- [**Motivation**](#motivation-aa)

## [**Features**](#features)

- [**Preview mobile**](#preview-mobile)

- [**Preview desktop**](#preview-desktop)

- [**Responsive Desgin Elements**](#responsive-design)

- [**Future Features**](#future-features)

## [**Design Principles**](#design-principles)

- [**Fonts**](#fonts)

- [**Coloring**](#coloring)

## [**Technologies, Libraries & Sources**](#technologies-libraries--sources)

- [**Technologies**](#technologies)
  
- [**Libraries & Sources**](#libraries--sources)
  
- [**IDE**](#ide)

### [**Testing & Quality Control**](#quality-control-aa)

- [**W3C Validator - HTML**](#w3c-html-validator)

- [**W3C Validator - CSS**](#w3c-csee-validator)

- [**Lighthouse report - mobile**](#lighthouse---mobile)

- [**Lighthouse report - desktop**](#lighthouse---desktop)

### [**Deployment and local development**](#deployment-and-local-development-aa)

- [GitHub Pages](#github-pages)
- [Forking the GitHub Repository](#forking-the-github-repository)

### [**Credits**](#credits-aa)

- [Content](#content)
- [Media](#media)

## Features

### **Responsive Design**
This project was developed in a *mobile first* approach, later on designs were changed to deliver a complete user experience for mobile as well as for larger devices, like tablets and desktop computers.

#### **Preview mobile**

  To enlarge the 'preview for mobile' either *pinch to zoom* on mobile devices or use the zoom feature from your browser, e.g. [CTRL+Scroll on most windows machines].

  | Index.html                                                | Library.html                                                  | Overlay in Library.html                                                          | Feedback.html                                                   |
  | --------------------------------------------------------- | ------------------------------------------------------------- | -------------------------------------------------------------------------------- | --------------------------------------------------------------- |
  | ![Index.html on mobile](assets/img/doc/mobile_index.webp) | ![Library.html on mobile](assets/img/doc/mobile_library.webp) | ![Library overlay element on mobile](assets/img/doc/mobile_library_overlay.webp) | ![Feedback.html on mobile](assets/img/doc/mobile_feedback.webp) |

#### **Preview desktop**

In the following the desktop presentation is shown of each page, clicking on one or all of the pane elements will display the content behind it.

<details>
<summary>Index.html</summary>
<img src="assets/img/doc/desktop_index.webp" alt="Index.html as introduction page">
</details>
<details>
<summary>Libraray.html</summary>
<img src="assets/img/doc/desktop_library.webp" alt="library.html showing the covers of the short stories">
</details>
<details>
<summary>Overlay in Libraray.html</summary>
<img src="assets/img/doc/desktop_library_overlay.webp" alt="showing a short story of a clicked cover">
</details>
<details>
<summary>Feedback.html</summary>
<img src="assets/img/doc/desktop_feedback.webp" alt="feedback.html as information gathering page">
</details>

### **Responsive Design Elements**

#### **Header**

- On smaller devices, the header shows the logo and three symbols for navigation. This changes on larger screens, where labels are also shown for convenience.<br>
  ![Header on small devices](assets/img/doc/Header_iPhone_XR.webp)
  ![Header on tablet devices and bigger](assets/img/doc/Header_iPad.webp)
- The active page is circled on the intended navigation symbol.
- Design Language - Intuitive icons represent the expected interaction: 
  - 'Home' for the *main* page
  - 'Openend book' for the *library*
  - 'Pen on note' for *feedback*

#### **Footer**

- On smaller devices the footer is very consistent with the whole design of the complete webpage.
- This changes for bigger screens as the footer gets framed to attract more attention. <br>
![Header on small devices](assets/img/doc/Footer_iPhone.webp)
![Header on tablet devices and bigger](assets/img/doc/Footer_iPad.webp)
- On desktop devices where you would hover with a mouse over the *Social Network* icons, they will enlarge to attract even more attention.

#### **Index.html**

  As can be seen above in the preview section from mobile and desktop the *index.html* does slightly differ depending on the screensize maintaining a good visibility and readability without the need to scroll horizontal.
  
  The *interruption element* also changes it's size and placement on the background depending on the screen size, though always maintaining the element does not attend to much attention and visually blocking the background image.

#### **Library.html**

  The difference can be seen quite clearly in the preview section. Where on mobile the user will experience a seamless sequence of images, desktop devices or rather *bigger* screens will show a two column gallery approach where each image reminds the user unintentionally of an *app*-like structure.

#### **Overlay in Library.html**

  Almost identical between mobile and desktop, with the exception of the alignment of the content. On mobile it is left alligend for better readability where on desktop size the allignment is centered for better use of the visual space.

#### **Feedback.html**
  
  The sole difference between mobile and desktop is the size of the input fields and the text-alignment to make the most use of the given space.


### **Future Features (not currently planned)**

- Add more short stories to the library.
- Add "reading out" feature
- Gather Feedback and actually send it to an address where it gets processed

## Design principles

- Creating immersion through background colouring
- Gamification through using special fonts like Pixelify and underlining it with corresponding *pixeled* background images.

### **Fonts**

* Ysabeau Infant <br>

      A serif font which was used in this project for displaying text's and paragraph elemnts. Also used for the short stories. You would find a serif font rather often in printed out fairy-tales.

* Pixelify Sans <br>

      This 'special' is used for the enhancement of the *gamification* feeling, headings, header and footer do contain this font. Also this font was used for the headings seen on the covers on the library page.


### **Coloring**

| Theme coloring                                                  | Font colorining                                               | Interruption El.                              | Button coloring                                                                     |
| --------------------------------------------------------------- | ------------------------------------------------------------- | --------------------------------------------- | ----------------------------------------------------------------------------------- |
| ![Magenta blue as background](assets/img/doc/colors/2a0746.svg) | ![White as main font color](assets/img/doc/colors/ffffff.svg) | ![Wine red](assets/img/doc/colors/8e2748.svg) | ![A medium dark shade of brown used for button's](assets/img/doc/colors/a15b00.svg) |


## Technologies, Libraries & Sources
In this section, we detail the technologies, libraries, and sources used in the project.

### **Technologies**

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

### **Libraries & Sources**

- [Git](https://git-scm.com/) - For version control.
- [GitHub](https://github.com/) - Deployment of the website and storing the files online.
- [Google Fonts](https://fonts.google.com/) - Imported main fonts for the website.
- [Am I Responsive](https://ui.dev/amiresponsive) - Mockup responsive image for the README file.
- [Python3 template from CI](https://github.com/Code-Institute-Org/ci-full-template) - Python3 based template from 'Code Institute' for easier deployment.


### **IDE**

- [Codeanywhere](https://codeanywhere.com/signin) - Cloud IDE, was abandoned due to performance reasons in favour to
- [VS-code for Mac](https://code.visualstudio.com/download) - Local IDE

## <a id="quality-control-aa"></a>**Quality Control**

W3C HTML Validator, W3C CSS Validator, and Dev-Tools Lighthouse were used for quality control.

### **W3C HTML Validator**

<details>
<summary>Results - W3C HTML Validator</summary>

No Errors found. <strong>Index.html</strong>

<img src="assets/img/doc/reports/Validation_index.webp" alt="W3C HTML Validator results for index.html">

No Errors found. <strong>Library.html</strong>

<img src="assets/img/doc/reports/Validation_library.webp" alt="W3C HTML Validator results for library.html">

No Errors found. <strong>Feedback.html</strong>

<img src="assets/img/doc/reports/Validation_feedback.webp" alt="W3C HTML Validator results for feedback.html">
</details>

### **W3C CSS Validator**

<details>
<summary>Results - W3C CSS Validaor</summary>

No Errors found

<img src="assets/img/doc/reports/Validation_css.webp" alt="W3C CSS Validator results">

</details>

### **Lighthouse - mobile**


<details>
<summary>Results - Dev-Tools Lighthouse - mobile</summary>

<strong>Overall good results can for mobile be seen</strong>

<strong>For Index.html</strong>

<img src="assets/img/doc/reports/Lighthouse_mobile_index.webp" alt="lighthouse report from chrome dev-tools for index.html and mobile">

<strong>For Library.html</strong>

<img src="assets/img/doc/reports/Lighthouse_mobile_library.webp" alt="lighthouse report from chrome dev-tools for library.html and mobile">

<strong>For Library.html</strong> after low resolution covers were added for mobile devices with a screen width smaller than 480px.

<img src="assets/img/doc/reports/Lighthouse_mobile_library2.webp" alt="lighthouse report from chrome dev-tools for library.html and mobile after a low resolution fix">

<strong>For Feedback.html</strong>

<img src="assets/img/doc/reports/Lighthouse_mobile_feedback.webp" alt="lighthouse report from chrome dev-tools for feedback.html and mobile">

</details>


### **Lighthouse - desktop**


<details>
<summary>Results - Dev-Tools Lighthouse - desktop</summary>

<strong>Overall good results can for mobile be seen</strong>

<strong>For Index.html</strong>

<img src="assets/img/doc/reports/Lighthouse_desktop_index.webp" alt="lighthouse report from chrome dev-tools for index.html and desktop">

<strong>For Library.html</strong>

<img src="assets/img/doc/reports/Lighthouse_desktop_library.webp" alt="lighthouse report from chrome dev-tools for library.html and desktop">

<strong>For Feedback.html</strong>

<img src="assets/img/doc/reports/Lighthouse_desktop_feedback.webp" alt="lighthouse report from chrome dev-tools for feedback.html and desktop">

</details>


## <a id="deployment-and-local-development-aa"></a>**Deployment and local development**

### **GitHub Pages**

To deploy the project on GitHub Pages...

1. Log in to GitHub and locate [GitHub Repository Bedtime Stories](https://github.com/DaSHdotHub/BedtimeStories)
2. At the navigation bar of the repository tab find "Settings", click.
3. At the left side under the "Code and automation" section, click on "Pages".
4. Next locate the "Source" and set it to "Deploy from a branch", branch should be "main", folder set to "root" and then click on the "Save" button.
5. Head back to the [Project Repository](https://github.com/DaSHdotHub/BedtimeStories) and on the right side click on [Deployments](https://github.com/DaSHdotHub/BedtimeStories/deployments) and under the "Active deployments" section is the freshly deployed project: [Bedtime Stories](https://github.com/DaSHdotHub/BedtimeStories)

### **Forking the GitHub Repository**

By forking the GitHub Repository we can make a copy of the original repository to view or make changes without changing the original repository.

For forking the GitHub Repository...

1. Log in to GitHub and locate [GitHub Repository Bedtime Stories](https://github.com/DaSHdotHub/BedtimeStories)
2. At the top, in the line with the project's name, on the right side find "Fork", click.
3. Now you have a copy of the original repository in your GitHub account.

### **Local run**

To run the project locally...

- Make sure python3 is installed.<br>
- Inside or outside an IDE run following command from the root directory of the project:<br>
  <code>python3 -m http.server</code>

## <a id="credits-aa"></a>**Credits**

Special thanks to my wife and child for their unwavering support. :-)

### **Content**

- Some design patterns were inspired by [Love Running](https://github.com/DaSHdotHub/Love-Runnin-on-CI-Template) project.
- Short stories were artificially generated with the help of ChatGPT v4, see following example
<details>
<summary>Rhyme for *Snow White*, extract from the chat with ChatGPT</summary>
<img src="aassets/img/doc/chat_openAI_snow_white.webp" alt="chat with ChatGPT for creating a rhyme for the fairy-tale Snow-White">
</details>

### **Media**

- Images used as cover pictures were artificially generated from from: [StableDiffusion](https://stablediffusion.com/).
- Images used for background styling were artificially generated from: [NightCafe](https://nightcafe.com/).
- Resizing and converting images: [Simple Image Resizer](https://www.simpleimageresizer.com)
- All Icons except the favicon were taken from [FontAwesome](https://fontawesome.com/.)
- The FavIcon was chosen from [FlatIcon](https://www.flaticon.com/free-icons/storytelling)
- Creating Responsive Mock [UI.dev](https://ui.dev/amiresponsive)
- Color panes for this documentation [Encycolorpedia](https://encycolorpedia.com/)