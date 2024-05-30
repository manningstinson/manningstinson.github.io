Sure! Here is the README in markdown format:

```markdown
# Smile School Website

This README provides an overview of the Smile School webpage structure and styling.

## Table of Contents

- [Overview](#overview)
- [HTML Structure](#html-structure)
- [CSS Styling](#css-styling)
- [Images](#images)
- [Fonts](#fonts)

## Overview

The Smile School webpage is designed to provide users with information about smile tutorials. The website includes a main header section, testimonials, popular tutorials, membership information, an FAQ section, and a footer with social media links.

## HTML Structure

### Header Section

The header section includes the logo, navigation links, a title, subtitles, a registration button, and information about the professionals.

```html
<div class="school-page-container">
  <div class="main-part-container">
    <div id="header" class="header">
      <div class="logo">
        <a href="#">
          <img src="img/smile-school-logo.png" alt="Logo" class="logo" />
        </a>
      </div>
      <div class="nav">
        <a href="login.html">LOGIN</a>
        <a href="pricing.html">PRICING</a>
        <a href="courses.html">COURSES</a>
      </div>
      <div class="title-sub-title-container">
        <div class="get-schooled-title">
          <h1>Get schooled</h1>
        </div>
        <div class="subtitles">
          <div class="smiles-sub-title"><p>SMILES</p></div>
          <div class="grin-sub-title"><p>GRIN</p></div>
          <div class="laugh-sub-title"><p>LAUGH</p></div>
        </div>
        <a href="#" class="header-button">Register For Free</a>
      </div>
      <div class="learn-from-the-pros-container">
        <h2>Learn from the pros</h2>
        <div class="learn-the-pros">
          <!-- Professionals info -->
        </div>
      </div>
    </div>
  </div>
</div>
```

### Testimonials Section

The testimonials section features user feedback.

```html
<div class="testimonials-container">
  <div class="testimonial">
    <div class="avatar"></div>
    <div class="testimonial-info">
      <div class="description">
        « Those tutorials are concise and go straight to the point. I can’t think of a better place to learn smiling. And it’s so fun!
      </div>
      <div class="name">Person Name</div>
      <div class="jobprofile">weather presenter</div>
    </div>
  </div>
</div>
```

### Most Popular Tutorials Section

This section showcases the most popular smile tutorials.

```html
<div class="most-popular-tutorials-container">
  <div class="most-popular-tutorials-container-tutorial-content">
    <div class="most-popular-tutorials-title">
      <h2>Most popular tutorials</h2>
    </div>
    <div class="most-popular-tutorials-container-video-grid">
      <!-- Tutorial items -->
    </div>
  </div>
</div>
```

### Membership Section

Information about free membership options is provided here.

```html
<div class="membership-container">
  <div class="membership-container-title">
    <h2>Free membership</h2>
  </div>
  <div class="membership-options-container">
    <!-- Membership options -->
  </div>
  <div class="membership-options-select-membership">
    <button class="membership-options-select-membership-button">Register for Free</button>
  </div>
</div>
```

### FAQ Section

Common questions are answered in the FAQ section.

```html
<div class="faq-container">
  <div class="faq-title">
    <h1>F.A.Q.</h1>
  </div>
  <div class="faq-row">
    <div class="faq-column">
      <h3>How does this work?</h3>
      <p>Lorem ipsum dolor sit amet...</p>
    </div>
    <!-- More FAQ columns -->
  </div>
</div>
```

### Footer Section

The footer includes the logo and social media links.

```html
<div class="footer-container">
  <div class="logo-div">
    <img src="img/smile-school-logo.png" alt="Logo">
  </div>
  <div class="social-icons">
    <a href="#"><img src="img/Facebook_White.png" alt="Facebook"></a>
    <a href="#"><img src="img/Twitter_White.png" alt="Twitter"></a>
    <a href="#"><img src="img/Instagram_White.png" alt="Instagram"></a>
  </div>
</div>
```

## CSS Styling

### General Styles

```css
body {
  margin: 0;
  font-family: "Source Sans Pro", sans-serif;
}

a {
  text-decoration: none;
  color: #ffffff;
  font-weight: 700;
  padding: 0 20px;
}

a:hover {
  text-decoration: underline;
}
```

### Header Styles

```css
.header {
  width: 1050px;
  margin: 0 auto;
  position: relative;
}

.logo {
  float: left;
}

.nav {
  margin-left: auto;
}

.title-sub-title-container {
  text-align: center;
}

.get-schooled-title {
  font-size: 3.6em;
  font-weight: 900;
  color: #fff;
}

.header-button {
  background-color: #c271ff;
  color: #fff;
  border: none;
  border-radius: 200px;
  padding: 10px 20px;
  cursor: pointer;
}
```

### Testimonials Styles

```css
.testimonials-container {
  background: #c271ff;
  display: flex;
  padding: 50px 200px;
}

.testimonial {
  display: flex;
  align-items: center;
}

.testimonial .avatar {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  background: url("img/avatar.png") center top no-repeat;
  background-size: cover;
}

.testimonial-info {
  margin-left: 20px;
  color: #fff;
}
```

### Popular Tutorials Styles

```css
.most-popular-tutorials-container {
  background: #fff;
  padding: 50px;
}

.most-popular-tutorials-title {
  text-align: center;
  margin-bottom: 20px;
}

.most-popular-tutorials-container-video-grid {
  display: flex;
  justify-content: space-around;
}
```

### Membership Styles

```css
.membership-container {
  background: #071629;
  color: #fff;
  text-align: center;
  padding: 50px;
}

.membership-options-container {
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
}

.membership-options-select-membership-button {
  background-color: #c271ff;
  color: #fff;
  border: none;
  border-radius: 200px;
  padding: 10px 20px;
  cursor: pointer;
}
```

### FAQ Styles

```css
.faq-container {
  background: #fff;
  padding: 50px;
  text-align: center;
}

.faq-title h1 {
  font-size: 3em;
  margin-bottom: 20px;
}

.faq-row {
  display: flex;
  justify-content: space-around;
}

.faq-column {
  max-width: 45%;
  text-align: left;
}
```

### Footer Styles

```css
.footer-container {
  background: #071629;
  color: #fff;
  display: flex;
  justify-content: space-between;
  padding: 20px;
}

.footer-container .logo-div img {
  height: auto;
  width: 100%;
}

.footer-container .social-icons a img {
  height: 30px;
}
```

## Images

Make sure to place the following images in the `img` directory:

- smile-school-logo.png
- header-background.jpg
- avatar.png
- play-button.png
- rating.png
- phillip-massey-pro.png
- nannie-lawrence-pro.png
- bruce-walters-pro.png
- henry-hughes-pro.png
- diaganol-smile-tutorial.png
- sad-smile-tutorial.png
- natural-smile-tutorial.png
- happy-smile-tutorial.png
- Facebook_White.png
- Twitter_White.png
- Instagram_White.png
- faq-icon-purple-smile.png

## Fonts

The font used for this project is "Source Sans Pro", available from Google Fonts. Include it in your HTML file as follows:

```html
<head>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Source+Sans+Pro&display=swap">
</head>
```
```
