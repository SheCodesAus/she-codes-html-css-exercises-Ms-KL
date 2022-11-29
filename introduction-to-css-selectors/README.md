This folder contains She Codes Plus course material, weekly exercises and challenges. 

Includes:
- updating index & styles using coursework
- add ids and classes to html
- style using the new ids and classes in css

Link to material:
https://shecodes.thinkific.com/courses/take/she-codes-plus-perth-22-23/pdfs/38847789-intro-to-html-css

__________________________________________________________

Notes taken from class work:

- website is style from css --> defines styles including design and layout
- use SELECTORS to access elements and define their properties
- SELECTORS: Type, Class, ID
- We use class if we want multiple elements to have the same styles applied.
- We use id if we want only one element to have styles applied.

__________________________________________________________

- TYPE:    typename {}

    The following will select and style all elements with the <div> tag:

> HTML:
        <div>
            <div>
                <h2>About Me</h2>
                <p>Here is some info about me.</p>
            </div>
            <div>
                <h2>Things I like</h2>
                <p>Some info about things I like</p>
            </div>
        </div>
        
__________

> CSS:
        div {
            background-color: peachpuff;
        }

__________________________________________________________


- CLASS:    .classname {}

    The following will select and style all elements with the <div class="classname"> tag, due to the class attribute:
    
> HTML:
        <div>
            <div class="box">
                <h2>About Me</h2>
                <p class="body-text">Here is some info about me.</p>
            </div>
            <div class="box">
                <h2>Things I like</h2>
                <p class="body-text">Some info about things I like</p>
            </div>
        </div>
__________

> CSS:
        .box {
            background-color: peachpuff;
        }
        .body-text {
            color: blue;
        }

__________________________________________________________


- ID:    #idname {}

    The following will select and style only ONE element with the <div id="idname"> tag, due to the id attribute:

> HTML:
        <div>
            <div class="box">
                <h2>About Me</h2>
                <p class="body-text">Here is some info about me.</p>
            </div>
            <div class="box">
                <h2>Things I like</h2>
                <p class="body-text">Some info about things I like</p>
            </div>
            <div>
            <p id="first-paragraph" class="body-text">Some text.</p>
            <p class="body-text">Here is some more text.</p>
            </div>
        </div>

__________
    
> CSS:

        .box {
            background-color: peachpuff;
        }

        .body-text {
            color: blue;
        }

        #first-paragraph {
            color: red;
        }
