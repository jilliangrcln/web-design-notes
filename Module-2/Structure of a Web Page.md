# Week 2: Structure of a Web Page

## Document Object Model (writing clean mode)
- Basis of HTML5 is "New features should be based on HTML, CSS, the DOM, and JavaScript"
- DOM provides common tree-like structure that all pages should follow
- Computer Scientists loves trees (the mathematical kind) because you can test them

# HTML is built on the DOM
![alt text](image.png)

# Three parts of a well-formed document
1. Doctype
    - Version of HTML that you will be using
    - HTML5
      -  ``` <!DOCTYPE html> ``` 
2. Head
    - Additional information used by the browser
      - Meta data : language, title
      - Supporting files - Javascript, Styling, Add-ons
    - Other than title, meta-data is not displayed
3. Body
    - Displayable content
    - Bulk of your page
    - Important to write well-formatted (tree-like) code.
    - Most of the content is displayed by the browser, but there may be some meta data too.

**Example**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First Page</title>
</head>
<body>
    This should be displayed by the browser
</body>
</html>
```


