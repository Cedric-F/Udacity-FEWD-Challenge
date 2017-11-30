# Special Edition: Christmas
## Preview
![](https://i.imgur.com/ce79Yzh.gif)

# Udacity-Discourse-Themes
Standalone Custom Stylesheets for Discourse

# How to use
Download or clone the themes, open the desired one and copy the CSS code.
Depending on your browser install one of the following extension:

## User CSS
Available on Chrome Extensions catalog

## User JavaScript and CSS
Same as User CSS. Adds a JavaScript add-ons functionnality

## Stylish
Available on Chrome and Firefox

## Styllus
Available on Firefox

Go to the Discourse Forum.
In the extension editor, paste the CSS code, save, and if needed reload the page to apply the new theme.

## Enjoy

# Change the Default Theme
The themes are using CSS variables functionnality and thus allow you to create your own styles from the very top of the code.

```
:root{

  /* Dominant colors */
  --primary-bg: #292d3e; /* var(--primary-bg) */
  --secondary-bg: #343741; /* var(--secondary-bg) */
  --ember: rgba(253, 151, 31, 0.7); /* var(--ember) */
  --text: white; /* var(--text) */

  /* Miscellaneous */

  --social-btn: magenta; /* var(--social-btn) | default color of like/share/etc buttons */
  --like: red; /* Customize the "heart" (like-button) color */
  --flag: red; /* The "redflag" button to report inapropriate posts */
  --unread: rgba(0,0,0,0.2); /* Define the background color of unread topics cells (in the user stream) */
  --highlight: #DFA700; /* var(--highlight) | hilighted search result */
  --biography: rgba(255,255,255,0.3); /* var(--biography) | unexpanded biography div background */
  --foot-links: #e6db74; /* var(--foot-links) | links color in the footer */
  --quote-ctrl: green; /* var(--quote-ctrl) | color of the "expend/collapse" and "go-to" buttons on a quoted message */

}
```
_Snippet from the Default dark theme_

### Bluenight Theme _by Asher_
```
:root {
 /* Dominant colors */
  --primary-bg: #141d26; /* var(--primary-bg) */
  --secondary-bg: #1b2836; /* var(--secondary-bg) */
  --ember: white; /* var(--ember) */
  --text: white; /* var(--text) */
 
  /* Miscellaneous */
 
  --social-btn: white; /* var(--social-btn) | default color of like/share/etc buttons */
  --like: red; /* Customize the "heart" (like-button) color */
  --flag: red; /* The "redflag" button to report inapropriate posts */
  --unread: rgba(0,0,0,0.2); /* Define the background color of unread topics cells (in the user stream) */
  --highlight: #DFA700; /* var(--highlight) | hilighted search result */
  --biography: rgba(255,255,255,0.3); /* var(--biography) | unexpanded biography div background */
  --foot-links: #e6db74; /* var(--foot-links) | links color in the footer */
  --quote-ctrl: green; /* var(--quote-ctrl) | color of the "expend/collapse" and "go-to" buttons on a quoted message */
}
  ```

# Credits:

* Cedric F
* Asher K
* Maeva NAP
* Sarah F
* Cansurmeli
* Puritanic

# License
Apache 2.0
