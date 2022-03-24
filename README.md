# code-refactor-challenge
## description

## USER STORY
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our site is optimized for search engines
## launched site
## table of contents
## requirements

-   WHEN I view the source code
    THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN I find that they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## how i met requirements (snipits)
    ### SEMANTIC ELEMENTS
        Added description to the title
        <title>About Horiseon</title>
    ### Added the following to give information to sections of the page
            header
            article
            section
            footer
    ### ASSURED HEADING TAGS FOLLOWED CORRECT ORDER
            <h1>Hori<span id="seo">seo</span>n</h1>
                    <h2>Search Engine Optimization</h2>
    <h3>Cost Management</h3>
       <h4>Made with ❤️️ by Horiseon</h4>
    ### IMPEMENTED DRY CODING
        .benefits p {
    margin-bottom: 32px;
    color: #ffffff;
} 

#content {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
} 

.benefits img {
    display: block;
    margin: 10px auto;
   
    ### ACCESSIBILITY
        Added alt tags to explain the images
    
## resources
For Semantic Elements
https://www.w3schools.com/html/html5_semantic_elements.asp