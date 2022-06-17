# Horiseon Refactoring Project - Module 1

**Goal:** The goal of this project was to take an HTML and CSS file, and refactor them to include semantic elements.

* A majority of the lines of code used the <'div'> element to separate the different areas of the webpage: **header,** **main body,** **portion on the side (aside),** and the **footer.** Using the <'div'> element is unhelpful to define these sections becasue it is a **non-semantic element.** This means that it cannot be used to define the purpose of the line of code.
* Using semantic elements allows users to see what each section is supposed to represent in a line of code. For example, headers and footers of webpages can be easily labeled as <'header'> and <'footer'>, respetively.

## Altering CSS code to match

* After adding the semantic elements to the HTML file, the CSS file also needs to be cleaned up so all styling changes can be seen in the webpage. The original file separated every section into different classes, even though they were all being formatted the same. The CSS was condensed so one class was used across all different sections affected by this.

## Adding accessibility to images

* All images included in the file did not have an alternate message. Not including an alternate message can hurt a user's full experience of being on a webpage if: the image is not loading properly or if a user requires accessibility features when using the internet. Sentences describing all images used in the webpage were added to the html file. 
