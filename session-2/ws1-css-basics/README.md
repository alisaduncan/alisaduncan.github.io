# CSS Basics {#top}
CSS decorates your website with visual appeal and invites the user to connect with your website's personality. We'll use basic CSS to bring a website to life.

This section will help guide you through the following steps:
---- 
 * Create the HTML file
 * Link the stylesheet
 * Resize images
 * Change title color
 * Cascade styles
 
----

** CHROMEBOOKS!! **

----
## Create the HTML file {#html-file} <span class="navigate-top"><a href="#top" title="Take me to the top of page"><i class="fa fa-chevron-circle-up" aria-hidden="true"></i></a></span>
{% include "./1html-file.md" %}

## Download images and link the stylesheet {#link-stylesheet} <span class="navigate-top"><a href="#top" title="Take me to the top of page"><i class="fa fa-chevron-circle-up" aria-hidden="true"></i></a></span>
{% include "./2download-images.md" %}

## Resize images using relative and absolute sizes {#resize} <span class="navigate-top"><a href="#top" title="Take me to the top of page"><i class="fa fa-chevron-circle-up" aria-hidden="true"></i></a></span>
Images are a big part of any website and what most people see first because your eyes are drawn to visuals. Let’s learn about absolute and relative sizing and apply it to the images in the menu.
{% include "./3resize-images.md" %}

## Change the color of the title {#resize} <span class="navigate-top"><a href="#top" title="Take me to the top of page"><i class="fa fa-chevron-circle-up" aria-hidden="true"></i></a></span>
Color helps differentiate sections within a website and helps convey importance. In this section we'll change the color of the "LadyDev Bar & Grill" title.
{% include "./4title-color.md" %}

## Cascade background color changes {#cascade} <span class="navigate-top"><a href="#top" title="Take me to the top of page"><i class="fa fa-chevron-circle-up" aria-hidden="true"></i></a></span>
The ability to cascade styles makes CSS powerful. In this section we will apply background colors to demonstrate how to cascade styles.
{% include "./5background-color.md" %}


## Checkpoint
Your _styles.css_ file should look like this

PICTURE HERE OF PAGE AND REPLACE CODE WITH IMAGE

```css
body {
  background-color: #fefaec;
}

nav {
  background-color: #cb6f10;
}

.hero h1 {
  color: #cb6f10;
}

.hero h2 {
  color: #cb6f10;
}

.hero p {
  color: #cb6f10;
}

.drinks img {
  width: 120px;
  height: 120px;
}

.sidebar {
  background-color: #d9e9ce;
}

footer {
  background-color: #cb6f10;
}

```


### References and helpful links
[Mozilla Developer Network CSS reference documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)