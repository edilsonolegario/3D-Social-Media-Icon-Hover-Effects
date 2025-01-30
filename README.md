# 3D Social Media Icon Hover Effects

This project demonstrates 3D hover effects for social media icons, showcasing a creative and interactive way to add hover animations to your website's social media links.

## Features

- 3D hover effects for social media icons using CSS animations.
- Smooth transition and interactive feel.
- Easy to implement and customize.
- Supports multiple social media platforms (Facebook, Twitter, Instagram, etc.).

## Demo

You can see the live demo of this project [here](https://edilsonolegario.github.io/3D-Social-Media-Icon-Hover-Effects/).

## Installation

To use the hover effects in your own projects, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/edilsonolegario/3D-Social-Media-Icon-Hover-Effects
    ```

2. Open the `index.html` file in your browser to see the effect in action.

3. Customize the icons and hover effects by editing the `style.css` file.

## Usage

You can easily implement these 3D hover effects into your project by including the provided HTML and CSS. Here's an example of how to use the icons in your website:

### Example Usage:

```
HTML
<div class="social-icons">
  <a href="https://www.facebook.com" class="social-icon facebook" target="_blank"></a>
  <a href="https://www.twitter.com" class="social-icon twitter" target="_blank"></a>
  <a href="https://www.instagram.com" class="social-icon instagram" target="_blank"></a>
</div>

CSS
.social-icon {
  display: inline-block;
  width: 50px;
  height: 50px;
  background-color: #333;
  border-radius: 50%;
  transition: transform 0.3s ease;
}

.social-icon:hover {
  transform: scale(1.1) rotate(15deg);
}
