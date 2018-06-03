# Resume Template

After some frustration with trying to write a resume with Microsoft Word templates or Google Docs, I decided to fully code a template in HTML and style it with CSS. Although the template is more geared for technical resumes (with a slight bias to bootcamp graduates), anyone can change a few CSS classes or the HTML structure to their liking.

# Modular CSS Classes

Multiple css classes can be assigned to HTML nodes to allow for customization without writing too much CSS. If you prefer your own style, feel free to change either file.

font colors: black, green
font sizes: small, medium, large
font decoration: bold, italic
special styles: subtitle, link
flexbox spacing: flex, column (for flex), center, spaced
text-alignment: center-text, top

``` CSS
.black {
  color: rgb(0, 0, 0);
}

.green {
  color: #145214;
}

.small {
  font-size: 12px;
}

.medium {
  font-size: 16px;
}

.large {
  font-size: 24px;
}

.italic {
  font-style: italic;
}

.bold {
  font-weight: 700;
}

.link {
  color: forestgreen;
  font-weight: 700;
}

.flex {
  display: flex;
}

.column {
  flex-flow: column nowrap;
}

.subtitle {
  color: #145214;
  font-size: 14px;
  font-weight: 700;
  margin-bottom: 5px;
}

.center {
  justify-content: center;
  align-items: center;
}

.spaced {
  justify-content: space-between;
}

.center-text {
  text-align: center;
  align-self: center;
}

.top {
  text-align: center;
}
```

# Using grid

The template leverages CSS grid to make for easy styling and updating. Adding a new section in your resume does not require changing the rest of the resume's structure, but leaves that possibility open (with a few lines of CSS!)

# Contributing
Feel free to leave suggestions or raise issues - I'm happy to take feedback over the format or styling. Also feel welcome to use/edit for your own personal purposes.
