```html
<body>
  <h1>The Brown Bear</h1>
  <div id="introduction">
    <h2>About Brown Bears</h2>
    <p>The brown bear (<em>Ursus arctos</em>) is native to parts of northern Eurasia and North America. Its conservation status is currently <strong>Least Concern</strong>.<br /><br /> There are many subspecies within the brown bear species, including the Atlas bear and the Himalayan brown bear.</p>
    <h3>Species</h3>
    <ul>
      <li>Arctos</li>
      <li>Collarus</li>
      <li>Horribilis</li>
      <li>Nelsoni (extinct)</li>
    </ul>
    <h3>Features</h3>
    <p>Brown bears are not always completely brown. Some can be reddish or yellowish. They have very large, curved claws and huge paws. Male brown bears are often 30% larger than female brown bears. They can range from 5 feet to 9 feet from head to toe.</p>
  </div>
  <div id="habitat">
    <h2>Habitat</h2>
    <h3>Countries with Large Brown Bear Populations</h3>
    <ol>
      <li>Russia</li>
      <li>United States</li>
      <li>Canada</li>
    </ol>
    <h3>Countries with Small Brown Bear Populations</h3>
    <p>Some countries with smaller brown bear populations include Armenia, Belarus, Bulgaria, China, Finland, France, Greece, India, Japan, Nepal, Poland, Romania, Slovenia, Turkmenistan, and Uzbekistan.</p>
  </div>
  <div id="media">
    <h2>Media</h2>
    <img src="https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg" alt="A Brown Bear"/>

    <video src = "https://content.codecademy.com/courses/freelance-1/unit-1/lesson-2/htmlcss1-vid_brown-bear.mp4" width="320" height="240" controls>Video not supported</video>
  </div>
</body>
```
# Output:

# The Brown Bear

## About Brown Bears
The brown bear (*Ursus arctos*) is native to parts of northern Eurasia and North America. Its conservation status is currently **Least Concern**.

There are many subspecies within the brown bear species, including the Atlas bear and the Himalayan brown bear.

### Species
- Arctos
- Collarus
- Horribilis
- Nelsoni (extinct)

### Features
Brown bears are not always completely brown. Some can be reddish or yellowish. They have very large, curved claws and huge paws. Male brown bears are often 30% larger than female brown bears. They can range from 5 feet to 9 feet from head to toe.

## Habitat

### Countries with Large Brown Bear Populations
1. Russia
2. United States
3. Canada

### Countries with Small Brown Bear Populations
Some countries with smaller brown bear populations include Armenia, Belarus, Bulgaria, China, Finland, France, Greece, India, Japan, Nepal, Poland, Romania, Slovenia, Turkmenistan, and Uzbekistan.

## Media
![A Brown Bear](https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg)

[Watch the Brown Bear Video](https://content.codecademy.com/courses/freelance-1/unit-1/lesson-2/htmlcss1-vid_brown-bear.mp4)




Sure! Let's break down the HTML code and explain it line by line. I'll explain each part so you can understand how it works.

### HTML Code:

```html
<body>
  <h1>The Brown Bear</h1>
```
- **`<body>`**: This tag represents the main content of the web page.
- **`<h1>`**: This is a top-level heading tag that is used to define the main title of the page. In this case, it says "The Brown Bear".

```html
  <div id="introduction">
    <h2>About Brown Bears</h2>
```
- **`<div id="introduction">`**: This creates a container or a "division" with an ID attribute of `"introduction"`. The `id` can be used for styling or JavaScript manipulation.
- **`<h2>`**: This is a second-level heading, usually used for subheadings. "About Brown Bears" is a subheading that introduces this section.

```html
    <p>The brown bear (<em>Ursus arctos</em>) is native to parts of northern Eurasia and North America. Its conservation status is currently <strong>Least Concern</strong>.<br /><br /> There are many subspecies within the brown bear species, including the Atlas bear and the Himalayan brown bear.</p>
```
- **`<p>`**: This is a paragraph tag that contains text about brown bears.
- **`<em>`**: This tag is used to emphasize the species name, which typically renders it in italics.
- **`<strong>`**: This tag makes the text bold, in this case, "Least Concern" is bolded to highlight the bear's conservation status.
- **`<br />`**: This is a line break, which forces the following text to be on a new line.

```html
    <h3>Species</h3>
    <ul>
      <li>Arctos</li>
      <li>Collarus</li>
      <li>Horribilis</li>
      <li>Nelsoni (extinct)</li>
    </ul>
```
- **`<h3>`**: This is a third-level heading, used for sub-subheadings. It introduces the species section.
- **`<ul>`**: This is an unordered list. It contains items related to species.
- **`<li>`**: These are list items. Each species of the brown bear is listed here: "Arctos", "Collarus", "Horribilis", and "Nelsoni (extinct)".

```html
    <h3>Features</h3>
    <p>Brown bears are not always completely brown. Some can be reddish or yellowish. They have very large, curved claws and huge paws. Male brown bears are often 30% larger than female brown bears. They can range from 5 feet to 9 feet from head to toe.</p>
  </div>
```
- **`<h3>`**: Another subheading to introduce the "Features" section of the brown bear.
- **`<p>`**: Another paragraph providing information about the features of brown bears.

```html
  <div id="habitat">
    <h2>Habitat</h2>
```
- **`<div id="habitat">`**: This defines another division or section with an `id` of `"habitat"`.
- **`<h2>`**: This is a second-level heading, used for the subheading "Habitat" in the next section.

```html
    <h3>Countries with Large Brown Bear Populations</h3>
    <ol>
      <li>Russia</li>
      <li>United States</li>
      <li>Canada</li>
    </ol>
```
- **`<h3>`**: A third-level heading for introducing the list of countries with large brown bear populations.
- **`<ol>`**: This is an ordered list (numbered list). Here, it lists countries with large populations of brown bears.
- **`<li>`**: List items, which are the countries Russia, United States, and Canada.

```html
    <h3>Countries with Small Brown Bear Populations</h3>
    <p>Some countries with smaller brown bear populations include Armenia, Belarus, Bulgaria, China, Finland, France, Greece, India, Japan, Nepal, Poland, Romania, Slovenia, Turkmenistan, and Uzbekistan.</p>
  </div>
```
- **`<h3>`**: Another third-level heading introducing the section about countries with small brown bear populations.
- **`<p>`**: A paragraph listing the countries with smaller populations of brown bears.

```html
  <div id="media">
    <h2>Media</h2>
```
- **`<div id="media">`**: Another division with an `id` of `"media"`, used to group together media elements (images and videos).
- **`<h2>`**: A second-level heading for the "Media" section.

```html
    <img src="https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg" alt="A Brown Bear"/>
```
- **`<img>`**: This is an image tag. It has two main attributes:
  - **`src`**: The source of the image (URL). This tells the browser where to find the image file.
  - **`alt`**: The alternative text that describes the image. If the image can't be displayed, this text will appear.

```html
    <video src="https://content.codecademy.com/courses/freelance-1/unit-1/lesson-2/htmlcss1-vid_brown-bear.mp4" width="320" height="240" controls>Video not supported</video>
```
- **`<video>`**: This is the video tag. It embeds a video file into the web page.
  - **`src`**: The source URL of the video file.
  - **`width` and `height`**: These attributes define the dimensions of the video player.
  - **`controls`**: This attribute adds play, pause, and volume controls to the video player.
  - **Fallback text** ("Video not supported") is displayed if the video cannot be played in the browser.

```html
  </div>
</body>
```
- **`</div>`**: Closes the division tags for the "media" and "habitat" sections.
- **`</body>`**: Closes the body of the HTML document.

### Summary of Key HTML Elements:
- **`<div>`**: A container used to group elements together. It doesn't have a visual appearance but is often used for styling or organization.
- **`<h1>`, `<h2>`, `<h3>`**: Heading tags used to define titles and subtitles. `<h1>` is the highest level, while `<h3>` is a subheading.
- **`<p>`**: Paragraph tag used for text content.
- **`<ul>` and `<ol>`**: Unordered (bulleted) and ordered (numbered) lists.
- **`<img>`**: Image tag used to embed images in a webpage.
- **`<video>`**: Video tag used to embed video content.
- **`<br />`**: Line break, forcing the next content to appear on a new line.
- **`<strong>` and `<em>`**: Text formatting tags used to make text bold or italic, respectively.

### Output:
When this HTML code is rendered in a browser, the following will happen:
- The page will display a large title ("The Brown Bear") at the top.
- Below, sections will display information about brown bears, their features, species, and habitat.
- The "Media" section will include an image and a video about brown bears.

