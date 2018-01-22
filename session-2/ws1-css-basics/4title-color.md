1. Pick out a color palette that you like to use from [http://colorhunt.co](http://colorhunt.co). Make note of the hex color values displayed when you hover over each color in your chosen palette. 
    {% hint style='tip' %}
Ensure your colors are a11y friendly by using the [Color Contrast Checker](https://webaim.org/resources/contrastchecker/) from WebAIM. You can put in your foreground and background colors selected color and it will help find contrasting colors to improve legibility.

Google's [Color Tool](https://material.io/color/) makes this a little easier by pre-defining color palettes with accessible contrast.
    {% endhint %}

1. Find the `div` containing the title of the website in _index.html_. Note the `class` name is "hero-text" and you have `h1`, `h2`, and `p` tags to style.
1. In _styles.css_, create the css to style the `h1` tag and add your selected title color using the "color" property like this
    
    {% filename %}styles.css{% endfilename %}
    ```css
    .hero h1 {
        color: #cb6f10;
    }
    ```
1. Apply the color to the `h2` and `p` elements.
    {% hint style='working' %}
What happens if you don't specify class when style the `p` element? 

The color changes applies to all `p` elements on the page, not just the title. Try it yourself to see CSS specificity.
    {% endhint %}
