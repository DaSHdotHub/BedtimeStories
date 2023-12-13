# **Bedtime Stories**

## <a id="introduction-aa"></a>**Introduction**

The [Bedtime Stories](https://github.com/DaSHdotHub/BedtimeStories) website is a page for parents and children alike.
As long as someone can read he or she should be encouraged to visit to check for new or
old, rather classic short stories.

One of the key concepts of this website should be to sample some of these short
stories we all so cherish and love from our childhood. Create an immersion which
goes beyond plain black text on white background.

### <a id="motivation-aa"></a>**Motivation**

One of the thing I do most on a regulary basis is reading a good night story to my son.
As marvelous as books are, sometimes there is no possibilty to bring them along on a
longer trip. A website like [Bedtime Stories - deplyed on GitHub pages -](https://dashdothub.github.io/BedtimeStories/) is
charming to the reader through sheer simplicity and old fashioned retro styling.

## **Table of Content**

### [**Introduction**](#introduction-aa)

#### [**Motivation**](#motivation-aa)

### [**Technologies**](#technologiy-aa)

### [**Responsive Design and Preview**](#responsive_design-aa)

- [Header](#header)
- [Preview](#preview)
- [IAmResponsive](#I-am-responsive)

### [**Quality Control**](#quality-control-aa)

### [**Testing**](#testing-aa)

### [**Deployment and local development**](#deployment-and-local-development-aa)

- [GitHub Pages](#github-pages)
- [Forking the GitHub Repository](#forking-the-github-repository)

### [**Credits**](#credits-aa)

- [Content](#content)
- [Media](#media)

## <a id="responsive_design-aa"></a>**Responsive Design**

### **Header**

- On smaller devices the header will show besides the Logo only three small symbols
  for navigation. This changes however when a bigger screen is present, the labels
  are than also shown for convinience.<br>
  ![Header on small devices](assets/img/docs/small_header.png)
  ![Header on tablet devices and bigger](assets/img/docs/big_header.png)
- Also the active page is circled on the connected symbol.
- Design-Language, inuitive approach. The icons as shown do represent the interaction the
  user can expect when clicking on them.

### **I am responsive\***

![Am I Responsive](assets/img/docs/am-i-responsive.png)

### **Preview**

- **Mobile Phone**
  <details>
  <summary>index.html
  </summary>

  ![Preview Index Page Mobile](/assets/img/docs/mobile_iPhoneXR_index.png)
  </details>

  <details>
  <summary>library.html
  </summary>

  ![Preview Library Page Mobile](/assets/img/docs/mobile_iPhoneXR_library.png)
  </details>

  <details>
  <summary>feedback.html
  </summary>

  ![Preview Feedback Page Mobile](/assets/img/docs/mobile_iPhoneXR_feedback.png)
  </details>

## <a id="quality-control-aa"></a>**Quality Control**

- W3C HTML Validator
- W3C CSS Validaor
- Dev-Tools Lighthouse

## <a id="technology-aa"></a>**Technology**

In this project following technologies and tools were used:

- GitHub as 'Code Repository' and for version control
- Git for packaging and comittinng the code
- HTML5
- CSS3
- Codeanywhere as IDE
- Python3 template from CI
- Am I Resonsive for creating some mockup images for this documentation

## <a id="deployment-and-local-development-aa"></a>**Deployment and local development**

### **GitHub Pages**

1. Log in to GitHub and locate [GitHub Repository Bedtime Stories](https://github.com/DaSHdotHub/BedtimeStories)
2. At the navigation bar of the repository tab find "Settings", click.
3. At the left side under the "Code and automation" section, click on "Pages".
4. Next locate the "Source" and set it to "Deploy from a branch", branch should be "main", folder set to "root" and then click on the "Save" button.
5. Head back to the [Project Repository](https://github.com/DaSHdotHub/BedtimeStories) and on the right side click on [Deployments](https://github.com/DaSHdotHub/BedtimeStories/deployments) and under the "Active deployments" section is the freshly deployed project: [Bedtime Stories](https://github.com/DaSHdotHub/BedtimeStories)

### **Forking the GitHub Repository**

By forking the GitHub Repository we can make a copy of the original repository to view or make changes without changing the original repository.

1. Log in to GitHub and locate [GitHub Repository Bedtime Stories](https://github.com/DaSHdotHub/BedtimeStories)
2. At the top, in the line with the project's name, on the right side find "Fork", click.
3. Now you have a copy of the original repository in your GitHub account.

### **Local run**

- Make sure python3 is installed.<br>
- Inside or outside an IDE run following command from the root directory of the project:<br>
  <code>python3 -m http.server</code>

## <a id="credits-aa"></a>**Credits**

- Big thanks to my wife and my child who are always supporting me at their best :-)

### **Content**

- Some design patterns were inspired by [Love Running](https://github.com/DaSHdotHub/Love-Runnin-on-CI-Template) project.
- 8bit retro theming is just a personal thing.

### **Media**

- Images used as cover pictures were artificially generated from from: [StableDiffusion](https://stablediffusion.com/).
- Images used for background styling were artificially generated from: [NightCafe](https://nightcafe.com/).
- All Icons except the favicon were taken from [FontAwesome](https://fontawesome.com/.)
- The FavIcon was chosen from [FlatIcon](https://www.flaticon.com/free-icons/storytelling)
