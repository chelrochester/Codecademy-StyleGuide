# Codecademy-StyleGuide

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My Website Style Guide</title>
        
        <!-- Meta -->
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        
        <!-- CSS -->
        <link rel="stylesheet" type="text/css" href="./styles.css">
        
        <!-- Fonts -->
        <link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed&family=Roboto:wght@100;400&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;400&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap" rel="stylesheet">
    </head>
    <body>
        <!-- Site Wide Header-->
        <header>
            <h1>My Website Style Guide</h1>
            <nav>
                <ul>
                    <li><a href="#target-colors">Color Palette</a></li>
                    <li><a href="#target-fonts">Fonts</a></li>
                    <li><a href="#target-text-styles">Text Styles</a></li>
                </ul>
            </nav>
        </header>
        <!-- Site Main Content -->
        <a class="anchor" name="target-colors"></a>
        <section id="colors">
        <div class="flexbox-center">
            <h2 class="title">Color Palette</h2>
            <div class="colorbox">
                    <p class="color-label" id="eggplant1">Eggplant</p>
                    <p class="color-hex">#5d4954</p>
            </div>
            <div class="colorbox">
                    <p class="color-label" id="eggplant2">Eggplant</p>
                    <p class="color-hex">#754f5b</p>
            </div>
            <div class="colorbox">
                    <p class="color-label" id="deeptaupe">Deep Taupe</p>
                    <p class="color-hex">#7d6167</p>
            </div>
            <div class="colorbox">    
                    <p class="color-label" id="almond">Almond</p>
                    <p class="color-hex">#e6dbd0</p>
            </div>
            <div class="colorbox">
                    <p class="color-label" id="mistyrose">Misty Rose</p>
                    <p class="color-hex">#f9e0d9</p>
            </div>
        </div>
        </section>
        <a class="anchor" name="target-fonts"></a>
        <section class="section">
            <h2 class="title">Fonts</h2>
            <div class="fontbox">
                    <p class="font-label roboto">Roboto</p>
                    <p class="regular-roboto">The quick brown fox jumps over the lazy dog.</p>
                    <p class="light-roboto">The quick brown fox jumps over the lazy dog.</p>
                    <p class="condensed-roboto">The quick brown fox jumps over the lazy dog.</p>
              </div>
        </section>
        <a class="anchor" name="target-text-styles"></a>
        <section class="section">
            <div class="text-styles">
                <h2 class="title">Text Styles</h2>
                <div class="text-panel">
                    <h1 class="text">H1: Main Page heading</h1>
                        <ul>
                            <li>Font-weight: 700 (bold)</li>
                            <li>Font-size: 26px</li>
                            <li>Font-family:</li>
                        </ul>
                    <h2 class="text">H2: Subheading</h2>
                        <ul>
                            <li>Font-weight: 500</li>
                            <li>Font-size: 19px</li>
                            <li>Font-famiy:</li>
                        </ul>
                    <p class="text">p: Paragraph text</p>
                        <ul>
                            <li>Font-wight: 400 (regular)</li>
                            <li>Font-size: 14px</li>
                            <li>Font-family:</li>
                        </ul>
                </div>
            </div>
        </section>    
    </body>
</html>
