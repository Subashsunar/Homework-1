# 01 HTML, CSS, and Git: code Refactor

## Introduction

**Refactored** existing code (without changing the feature). The original code missed the the accessibility standards. There were some repetation, missing alt attributes, and lack of concise and descriptive title in the HTML and CSS file.

The code now follows all the accessibiliity standards, semantic HTML elements logical structure independent of styling and positioning, links, accessibile alt attributes, and concise, descriptive title.

## Image/Screenshot

The following image shows the web applications appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](assets\images\Horiseon-screen-shot.PNG)

### Changes in HTML file:

1. Added section in parent div tag.

2. Added concise, descriptive title.

```HTML
<title>Horiseon Social Solution Services</title>
```

3. Added consistant feature in the **Navigation bar**.

```HTML
<div id="search-engine-optimization" class="content-section">
```

4. Added descriptive alt attribute in for an images.

```HTML
<!-- Added accessible alt attribute with clear description for all three image tags.  -->
<img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="Young business men and women are deciding a plan for a business." />

<img src="./assets/images/online-reputation-management.jpg" class="float-right" alt="Laptop with magnifying glass on it. Some hightlighter and colors on the pencil jar. Notes on a note book with hot coffee on the left side." />

<img src="./assets/images/social-media-marketing.jpg" class="float-left" alt="Looking company's reputation at the bar and pie chart on a macbook at the same time looking the smart phone." />

```

### Changes in CSS file:

```CSS
/* Wiped out the repetative code to make it clean. */
.section-benefits {
  margin-bottom: 32px;
  color: #ffffff;
}

.section-benefits h3 {
  margin-bottom: 10px;
  text-align: center;
}

.section-benefits img {
  display: block;
  margin: 10px auto;
  max-width: 150px;
}

```

Here is the completed work with [repository](https://github.com/Subashsunar/Homework-1) and [deployed application](https://subashsunar.github.io/Homework-1/).

