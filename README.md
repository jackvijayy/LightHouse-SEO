
<h1 align="center">
  :black_circle:The Ultimate CheatSheet For SEO Optimization 🌸:black_circle:
</h1>
<h1 align="center"> Lighouse 🗼</h1>
<p align="center">
<img src="https://github.com/user-attachments/assets/912d7bfb-29de-410a-be51-a5d1eed3523a" width="850" height="400" border="10"/>
  
 
</p>



> [!IMPORTANT]
> if you are a developer Definitely you should Konw waht is lighthouse because its crucial part of the development.its very useful for the SEO webpage
> most of the company ensure the quality of the page using lighthouse tool

- [Introduction](#introduction)
- [How to use](#Howtouse)


- [performance](#Performance)
  - [First-Contentful-paint](#First-Contentful-Paint)
  - [Bold](#bold)
  

# introduction

Lighthouse is an open-source tool created by Google. As Google is a reputable company that’s trusted by many, it makes the result more reliable than other tools. Furthermore, as Google’s search engine is the leading search engine for the past decade, appearing higher on their search engine will most likely result in more traffic. So, getting a higher score on their performance audit tool can potentially raise the ranking of your website in their search results.

# HowtoUse
Using Lighthouse through Chrome is the easiest method to measure your website’s performance. First, open any web page that you’d like to measure
Next, open the devtools either by clicking shift + control + J or F12 on Windows/Linux, or option + command + J or fn + F12 on macOS.

<p align="center">
  <img src="https://github.com/user-attachments/assets/208ced73-253f-4cce-bc1d-cbad5dbf3a8d" height="200" width="400"/>
</p>

# Performance
Performance focuses on how to make your website load faster. We’ll go over the six important metrics for Performance, what they each entail and how to achieve a better score in each of them.
  # First-Contentful-Paint
   The first contentful paint (FCP) is measured from the moment the user navigates to the web page. It measures how long it takes for the first piece of DOM content to load. The DOM content can include images, 
  non-white canvas elements, and SVG elements.

![615b61f7e9ad0ff0f44da880_dZi0l2w9qlBAO0UWQrHG1HEFlw75i21jWi_R7M1ZYXv6_btQny9XIt9oKo6JrfQavNbAZjTv6aHPmYe5xStYwdNdSRBwrYPEdpovJ_d10CIlnKOWVvg8iEUOy7tWYJIq44gltk7p=s0](https://github.com/user-attachments/assets/0267226c-f50f-4b8a-982c-9eb82afedadf)

FCP is measured in seconds. In order for your web page to have a “Green” score — which means a fast FCP — the first piece of DOM content should take at most 1.8 seconds to load. Once it goes above that, it can go to either moderate or slow.

One factor that can affect your website’s FCP time is fonts. Fonts can take a long time to load, sometimes making the text invisible until it loads. A good way to solve this is by using the CSS property font-display: swap; when declaring your font using @font-face. For example:

```css
@font-face {
    font-family: 'MyFont';
    font-style: normal;
    font-weight: 400; 
    src: url(MyFont.woff);
    font-display: swap;
}
```
<h2>Best Practice</h2>

<details>
  <summary>Minify JavaScript</summary>

   Minify the JavaScript and CSS files being used on the page, reducing its size so that loading these assets doesn’t take as long. This depends on what framework or programming language you’re using, but almost 
  all of them have a way of doing that. You can check out simple tips on how to minify JavaScript when using various popular frameworks on the web.dev site.
</details>
<details>
  <summary>Remove Unused Css</summary>
</details>
<details>
  <summary>Reduce Server Response Time</summary>
</details>
<details>
  <summary>javaScript Load</summary>
        ```javascript
  <script src="myScript.js" defer></script>
  ```
  
</details>



 




