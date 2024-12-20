<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SONU BISOI DEVELOPER</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(3, 3, 52);
            color: white;
            font-family: 'poppins', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(10, 10, 80);



        }

        nav ul {
            display: flex;
            justify-content: center;

        }

        nav ul li a {
            text-decoration: none;
            color: white;
            margin: 0 23px;
        }

        nav ul li a:hover {
            color: rgb(128, 128, 174);
            font-size: 1.01rem;

        }

        .left {
            font-size: 1.5rem;
        }

        .firstsection {
            display: flex;
            justify-content: space-around;
            margin: 80px;
            align-items: center;
        }

        .firstsection>div {
            width: 30%;
        }

        .leftsection {
            font-size: 1.5rem;
            margin: 30px 0;
        }

        .rightsection {
            width: 50;
        }

        .purple {
            color: rgb(107, 107, 240)
        }

        #element {
            color: rgb(107, 107, 240)
        }

        .secondsection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;

        }

        main hr {
            border: 0;
            background: rgb(124, 124, 155);
            height: 1.2px;
            margin: 100px 84px;

        }

        secondsection h1 {
            font-size: 1.9rem;
        }

        .text-gray {
            color: grey;
        }

        .secondsection .box {
            background: white;
            width: 74vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondsection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 140px;
        }

        .vertical-title {
            margin-left: 10px;


        }

        .vertical-desc {
            position: relative;
            top: 50px;
            color: grey;
            width: 150px;
            font-size: 5px;

        }

        .img-top {
            width: 23px;
            position: relative;
            top: -24px;
            margin-left: -11px;
        }
    </style>
</head>

<body>

    <header>
        <nav>
            <div class="left">Sonu's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">HOME</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">
                Hi, My name is <span class="purple">sonu bisoi</span>
                <div>And i'm a Passionate</div>
                <div>Front End Developer</div>
                <span id="element"></span>

            </div>
            <div class="rightsection">
                <img src="bg.png" alt="">
            </div>


        </section>
        <hr>
        <section class="secondsection">
            <span class="text-gray">WHAT I'M DONE SO FAR</span>
            <h1>LANGUAGE</h1>
            <div class="box">
                <div class="vertical">
                    <img class="img-top" src="html img.jpg" alt="">
                    <div class="vertical-title">HTML</div>
                    <div class="vertical-desc">HTML (Hypertext Markup Language) is the standard language for creating
                        webpages. It structures content using tags and attributes. Tags define elements such as
                        headings, paragraphs, and links, while attributes provide additional information about those
                        elements.

                        HTML documents have a head section for metadata and a body section for visible content. It uses
                        semantic tags to improve the meaning of the content and enhance accessibility. HTML also
                        supports forms for user input and embeds media like images, audio, and video.

                        Together with CSS for styling and JavaScript for interactivity, HTML is essential for building
                        functional and visually appealing websites.</div>
                </div>
                <div class="vertical">
                    <img class="img-top" src="css.jpg" alt="">
                    <div class="vertical-title">CSS</div>
                    <div class="vertical-desc">CSS (Cascading Style Sheets) is a stylesheet language used to describe
                        the presentation (layout, colors, fonts, etc.) of a document written in HTML or XML. It defines
                        how elements on a web page should be displayed.</div>
                </div>
                <div class="vertical">
                    <img class="img-top" src="js.jpg" alt="">
                    <div class="vertical-title">JS</div>
                    <div class="vertical-desc">JavaScript is a high-level, interpreted programming language that is
                        commonly used to create dynamic and interactive web pages. It enables client-side scripting,
                        meaning it runs in the user's browser to update HTML and CSS content without reloading the page.
                    </div>
                </div>
                <div class="vertical">
                    <img class="img-top" src="wd.jpg" alt="">
                    <div class="vertical-title">WEB DESIGN</div>
                    <div class="vertical-desc">Web design refers to the process of planning, conceptualizing, and
                        creating the layout, structure, and appearance of websites. It includes aspects such as web page
                        layout, content arrangement, colors, fonts, images, and overall user interface design to ensure
                        a good user experience.</div>
                </div>

            </div>
        </section>
    </main>

    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['WEB DEVLOPER', 'FRONT END', 'WEB DESIGNER'],
            typeSpeed: 50,
        });
    </script>
</body>
</body>

</html>
