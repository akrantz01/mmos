HTML
====
The HTML behind the example

index.html
----------
Main website

.. code-block:: html

    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <title>MMO Server</title>
            <link rel="stylesheet" type="text/css" href="main.css"/>
            <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.6.1/p5.min.js"></script>
            <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.6.1/addons/p5.dom.min.js"></script>
            <script src="https://cdnjs.cloudflare.com/ajax/libs/jscolor/2.0.4/jscolor.min.js"></script>
        </head>
        <body>
            <script src="mmoc.js"></script>
            <script src="main.js"></script>

            <div id="modal">
                <div id="modal-content">
                    <div id="modal-head">
                        <h2>Select Type</h2>
                    </div>
                    <button id="observer">Observer</button>
                    <button id="player">Player</button>
                    <br>
                    <label for="color">Ball Color: </label><input id="color" class="jscolor" onchange="update(this.jscolor)" value="ffffff">
                </div>
            </div>
        </body>
    </html>
