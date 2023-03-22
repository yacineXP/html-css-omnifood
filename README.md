<p align="center">
  <img src="https://i.postimg.cc/Xqj7XP1X/omnifood-logo.png" height="80" alt="logo">
</p>

<h1 align="center">
  Omnifood Website [Learning]
  <br>
<p  align="center">
<a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="48" height="48" alt="HTML5" /></a><a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="48" height="48" alt="CSS3" /></a><a  href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"  target="_blank"  rel="noreferrer"> <img  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"  alt="javascript"  width="48"  height="48"/> </a>
</p>
</h1>

<p align="center">
  <a href="#project-description">Project Description</a> |
  <a href="#tech-stack-and-libraries">Tech Stack and Libraries</a> |
  <a href="#how-it-works">How it Works</a> |
  <a href="#code-examples">Code Examples</a> |
  <a href="#acknowledgements">Acknowledgements</a>
</p>

<br>

[![Thumbnail-6.png](https://i.postimg.cc/7652hppX/Thumbnail-6.png)](https://postimg.cc/sQRX00fZ)


<div id="project-description"></div>

## 🚀 Project Description
The "html-css-omnifood" repository is a website project that was created by following the "Build Responsive Real-World Websites with HTML and CSS" course on Udemy. The website is designed for a fictional food delivery service called "Omnifood" and showcases various aspects of modern web design and development, such as HTML fundamentals, CSS fundamentals, layouts (floats, flexbox, and CSS grid), web design rules and 

<div id="tech-stack-and-libraries"></div>

## 🛠️ Tech Stack and Libraries
- HTML
- CSS
- JavaScript

<div id="how-it-works"></div>

## ⚙️ How it Works
The website is designed and developed entirely using HTML5 and CSS3. The HTML files provide the structure and content of the website, while the CSS files handle the styling and layout. The website is responsive and adapts to different screen sizes and devices using media queries.

The HTML code is organized using semantic tags to provide meaning and structure to the content. The content is divided into sections, such as header, main, footer, and each section is contained within a div element.

CSS is used to style the HTML content and layout. The CSS code is organized into separate files based on the purpose of the styling. For example, the general.css file contains styles that apply to the entire website, such as font-family and color scheme, while the main.css file contains styles specific to each section of the website, such as the header and footer.

Some of the key CSS concepts used in the website include:

- Box model: used to control the dimensions and spacing of elements
- Flexbox: used to create flexible layouts that adapt to different screen sizes and devices
- Media queries: used to create a responsive design that adapts to different screen sizes and devices
- CSS selectors: used to target specific HTML elements for styling
- CSS transitions and animations: used to add interactivity and visual effects to the website

<div id="code-examples"></div>

## 💻 Code Examples
**1. An example of the meal card structure:**
```html
<div class="meal">
  <img src="img/meals/meal-2.jpg" class="meal-img" alt="Avocado Salad" />
  <div class="meal-content">
    <div class="meal-tags">
      <span class="tag tag--vegan">Vegan</span>
      <span class="tag tag--paleo">Paleo</span>
    </div>
    <p class="meal-title">Avocado Salad</p>
    <ul class="meal-attributes">
      <li class="meal-attribute">
        <ion-icon class="meal-icon" name="flame-outline"></ion-icon>
        <span><strong>400</strong> calories</span>
      </li>
      <li class="meal-attribute">
        <ion-icon class="meal-icon" name="restaurant-outline"></ion-icon>
        <span>NutriScore &reg; <strong>92</strong></span>
      </li>
      <li class="meal-attribute">
        <ion-icon class="meal-icon" name="star-outline"></ion-icon>
        <span><strong>4.8</strong> rating (441)</span>
      </li>
    </ul>
  </div>
</div>
```
The code example shows the HTML and CSS code for displaying a meal item on the website. The HTML code defines a ```div``` element with the class ```meal``` that contains an ```img``` element for the meal image and a div element with the class meal-content for the meal details. The meal details are displayed using various HTML elements such as p, span, and ul, along with some custom classes such as ```meal-title``` and ```meal-attribute```.

**2. An example of the meal card styling:**
```css
.meal-title {
  font-size: 2.4rem;
  color: #333;
  font-weight: 600;
  margin-bottom: 3.2rem;
}

.meal-attributes {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.meal-attribute {
  font-size: 1.8rem;
  display: flex;
  align-items: center;
  gap: 1.6rem;
}
```
The CSS code defines styles for the meal title and meal attributes. The ```meal-title``` class defines the ```font size```, ```color```, and ```weight``` for the meal title. The ```meal-attributes``` class defines the display properties for the list of meal attributes, including setting the list style to none, displaying the list items as a vertical column, and adding a gap between the list items. The meal-attribute class defines the font size, display properties, and gap between the meal attribute items. The display: flex property on the .meal-attribute class sets its child elements to display as a flexbox, allowing the ```ion-icon``` and span elements to be aligned in a ```row```. The gap property adds space between the ion-icon and span elements.

<div id="acknowledgements"></div>

## 📚 Acknowledgements 
This project was created with the help of the course **"Build Responsive Real-World Websites with HTML and CSS"** by **Jonas Schmedtmann**. Many of the concepts and techniques used in this project were learned from this valuable resource.
