<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML & HTML-Forms</title>
    <style>
        header {
            margin: 15px;
            background-color: #d3d1d1;
        }

        section {
            margin: 15px;
            background-color: #EEEEEE;
        }

        div {
            background-color: #DDFFDD;
            margin: 15px;
        }

        p {
            background-color: #DDFFDD;
            margin: 15px;
        }

        p span {
            font-size: 26px;
            font-weight: bolder;
        }

        footer {
            margin: 15px;
            background-color: #72807cab;
        }
    </style>
</head>

<body>
    <header>
        <h1>
            HEADER
        </h1>
        A header element is intended to usually contain the section's heading (an h1–h6 element or an hgroup element),
        but this is not required. The header element can also be used to wrap a section's table of contents, a search
        form, or any relevant logos. <br>
        <a href="https://html.spec.whatwg.org/multipage/sections.html#the-header-element" target="_blank">header</a>
    </header>

    <section>
        <h1>SECTION</h1>
        Examples of sections would be chapters, the various tabbed pages in a tabbed dialog box, or the numbered
        sections of a thesis. A Web site's home page could be split into sections for an introduction, news items, and
        contact information. <br>
        <a href="https://html.spec.whatwg.org/multipage/sections.html#the-section-element" target="_blank">section</a>
    </section>

    <div>
        <h1>DIV</h1>
        The div element has no special meaning at all. It represents its children. It can be used with the class, lang,
        and title attributes to mark up semantics common to a group of consecutive elements. It can also be used in a dl
        element, wrapping groups of dt and dd elements. <br>
        <a href="https://html.spec.whatwg.org/multipage/grouping-content.html#the-div-element" target="_blank">div</a>
    </div>

    <p>
        <span>Paragraph Tag</span><br>
        While paragraphs are usually represented in visual media by blocks of text that are physically separated from
        adjacent blocks through blank lines, a style sheet or user agent would be equally justified in presenting
        paragraph breaks in a different manner, for instance using inline pilcrows (¶) <br>
        <a href="https://html.spec.whatwg.org/multipage/grouping-content.html#the-p-element" target="_blank">P Tag</a>
    </p>
    <hr>
    <p>
    <h1>FORM</h1>
    A form is a component of a Web page that has form controls, such as text, buttons, checkboxes, range, or color
    picker controls. A user can interact with such a form, providing data that can then be sent to the server for
    further processing
    </p>
    <form autocomplete="off">
        <label for="text">Text</label>
        <input type="text" name="text" id="text" value="some text" placeholder="your text here" required
            minlength="3"><br><br>
        <label for="email">Email</label>
        <input type="email" name="email" id="email" placeholder="abc@mail.com" autofocus autocomplete="on"><br><br>
        <label for="number">number</label>
        <input type="number" name="number" id="number" value="some number" placeholder="your number here"
            disabled><br><br>
        <label for="password">your password</label>
        <input type="password" name="password" id="password" placeholder="your password here" maxlength="5"><br><br>
        <label for="file">select file</label>
        <input type="file" name="file" id="file" placeholder="your file here"><br><br>
        <label for="file">select multiple file</label>
        <input type="file" name="file" id="file" placeholder="your file here" multiple><br><br>
        <label for="male">male</label>
        <input type="radio" name="radio" id="male" value="Male">
        <label for="female">female</label>
        <input type="radio" name="radio" id="female" value="Female"><br><br>
        <label for="checkbox">checkbox</label>
        <input type="checkbox" name="checkbox" id="checkbox" value="check"><br><br>

        <input type="image" src="https://www.freelogodesign.org/Content/img/logo-samples/flooop.png" name="img" id="img"
            height="30" width="50">
        <input type="button" name="button" id="button" value="sample button">
        <input type="submit" name="submit" id="submit" value="some submit">
        <input type="reset" name="reset" id="reset" value="some reset"><br><br>

        <button type="submit">Submit</button>
        <button>button</button>
        <button type="reset">reset</button>
        <a href="http://particletree.com/features/rediscovering-the-button-element/" target="_blank">read about
            button</a>
    </form>
    <hr>
    <h1>UL & OL tags</h1>
    <ul>
        <li>JavaScript</li>
        <li>Python</li>
        <li>MySQL</li>
        <li>MongoDB</li>
    </ul>

    <ol type="1">
        <li>JavaScript</li>
        <li>Python</li>
        <li>MySQL</li>
        <li>MongoDB</li>
    </ol>

    <ol type="A">
        <li>JavaScript</li>
        <li>Python</li>
        <li>MySQL</li>
        <li>MongoDB</li>
    </ol>

    <ol type="I">
        <li>JavaScript</li>
        <li>Python</li>
        <li>MySQL</li>
        <li>MongoDB</li>
    </ol>



    <hr>
    <footer>
        <h1>
            FOOTER
        </h1>
        The footer element represents a footer for its nearest ancestor sectioning content or sectioning root element. A
        footer typically contains information about its section such as who wrote it, links to related documents,
        copyright data, and the like. <br>
        <a href="https://html.spec.whatwg.org/multipage/sections.html#the-footer-element" target="_blank">footer</a>
    </footer>

</body>

</html>
