<!-- .slide: data-background="#003333" -->
# Document Basics 

Document accessibility depends on the specific tool you are using

But there are some common concerns in every tool

---
## Structure

- Use structure properly
   - Use header styles to correctly label things
   - Don't skip header levels
   - Headings should form an outline of the page content
   - Use unique slide titles (makes navigation easier)
   - Use lists to identify all content that can be described as a list of something
   - Use tables used for content (not layout) and label their headers properly
   
Note:
update styles to make them look good
use 1/n for slide titles

---
## Color Contrast

- WCAG Level AAA requires a contrast ratio of at least
  - 7:1 for normal text <!-- .element: class="contrast71"  -->
  - 4.5:1 for large text (14t pt bold or larger)  <!-- .element: class="contrast41"  -->
  - Avoid anything else! <!-- .element: class="badcontrast"  -->

- Other tools 
  - [Colorzilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?hl=en) is an excellent tool for extracting the color value from any page element; 
  - WebAIM has a [contrast checker](https://webaim.org/resources/contrastchecker/#:~:text=WCAG%20Level%20AAA%20requires%20a,value%20from%20any%20page%20element)

<!-- .element: class="col"  -->

Note:
Choose colors that provide enough contrast between content and the background so that anyone with low-vision impairments and color deficiencies can perceive the content.

---
## Also: Don't depend on color

Don't use color or other visual characteristics to convey meaning 

<i class="red fa fa-times-circle fa-1x"  aria-hidden="true"></i> Wrong: “required fields are in red” <!-- .element: class="red"  -->

<i class="red fa fa-times-circle fa-1x "  aria-hidden="true"></i> Wrong: “click the circle on the right” 

<i class="green fa fa-check fa-1x"  aria-hidden="true"></i> Correct: "required fields are labeled 'Required'<!-- .element: class="red"  --> and colored red"

---
## Fonts

- Sans serif fonts are better for visual display
- Serif fonts are better for print documents  <!-- .element: class="times"  -->

Note: 

Sans serif is considered easier on the eyes for screen presentations; 

Serif is easier for printed documents

---
## Reading order (slide and web issue)

- tab-order == reading order
- Powerpoint has a nice interface for adjusting this; Google slides does not

---
## Other Considerations
- Provide a document title that describes its topic or purpose
- Identify the language of the document (or individual parts of a multilingual document).
- Allow users to bypass blocks of content that are irrelevant or often repeated (e.g., bookmarks in a PDF)
- Links should be labeled appropriately, as described [here](https://www.washington.edu/accesstech/courses/canvas/links/). 
<!-- .element: class="fragment"  -->

Just kidding! as described on the [UW page explaining meaningful link text](https://www.washington.edu/accesstech/courses/canvas/links/)
<!-- .element: class="fragment"  -->

---
## Add ALT Text

- HTML ```img src=... alt="Girl in a jacket" width="500" height="600"'''
- "Content Creation Platforms" (e.g. WordPress, twitter)
- Google Slides & PowerPoint
- Word Documents

---
## Accessible Documents Competency 

This applies to presentations, word documents, and PDFs.  You’ll need to demonstrate this on all documents you submit, but this should include:
- At least one presentation 
- At least one assignment write up that is long and complex enough to have headers and structure

