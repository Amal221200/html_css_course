# Cascading Style Sheet (CSS)


CSS, short for Cascading Style Sheets, is a style sheet language used for describing the presentation of a document written in a markup language like HTML. It provides a mechanism to add styles (such as fonts, colors, spacing, and layout) to web documents. Here's a more detailed definition:

* CSS is a style sheet language used to describe the presentation of a document written in HTML or XML. It controls how elements are displayed on a webpage by specifying the layout, formatting, colors, fonts, and other visual aspects of the document. CSS separates the content of a webpage from its presentation, allowing developers to create consistent styles across multiple pages.

* CSS is a crucial aspect of web development, enabling developers to create visually appealing and user-friendly websites. By mastering CSS, developers can control the entire look and feel of a website, ensuring consistency and enhancing the user experience.

There are three ways to write CSS:-
1. **Inline CSS**:- Write CSS inside the style attribute in HTML Element.

    ```
        <p style="font-style: 23px;">Inline CSS</p>
    ```

2. **Internal CSS**:- Write CSS inside the style tag in the HTML.

    ```
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <!-- Internal -->
            <style>
                h1 {
                    font-size: 35px;
                }
            </style>
            <title>Internal CSS</title>
        </head>
        <body>

            <!-- Internal CSS -->
            <h1>Internal CSS</h1>
        </body>
        </html>
    ```

3. **External CSS**:- Write CSS in a separate CSS file and link it to the HTML file.

    ```
        /* style.css file */
        h2 {
            font-size: 57px;
        }
    ```

    ```
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <!-- link -->
            <link rel="stylesheet" href="style.css">
            <title>External CSS</title>
        </head>
        <body>
            <!-- External CSS -->
            <h2>External CSS</h2>
        </body>
        </html>
    ```
