# css
A Code Repo for CSS
/****************************** ype of CSS ***********************************/
1. Inline CSS: Inline CSS is applied directly to an HTML element using the style attribute. For exam
 <p style="color: red; font-size: 16px;">This is a paragraph with inline CSS.</p>
   
2. Internal CSS: Internal CSS is defined within the <style> element in the <head> section of an HTML document. It applies styles to the entire document or specific sections. For example:
<head>
    <style>
        p {
            color: blue;
            font-size: 18px;
        }
    </style>
</head>
3. External CSS: External CSS is defined in a separate CSS file and linked to an HTML document using the <link> element. It allows styles to be shared across multiple HTML files. For example:
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>

/***************************** Selector *************************************/
1. Element Selector: Selects HTML elements based on their tag name. For example, p selects all <p> elements.

2. Class Selector: Selects elements with a specific class attribute value. It is denoted by a dot (.) followed by the class name. For example, .example selects all elements with class="example".

3. ID Selector: Selects a single element based on its unique ID attribute value. It is denoted by a hash (#) followed by the ID name. For example, #header selects the element with id="header".

