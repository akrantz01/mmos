CSS
===
The CSS behind the example

main.css
--------
General styling

.. code-block:: css

    body {
        padding: 0;
        margin: 0;
    }

    canvas {
        position: fixed;
    }

    @-webkit-keyframes animatetop {
        from {
            top: -300px;
            opacity: 0;
        }
        to {
            top: 0;
            opacity: 1;
        }
    }

    @-moz-keyframes animatetop {
        from {
            top: -300px;
            opacity: 0;
        }
        to {
            top: 0;
            opacity: 1;
        }
    }

    @-o-keyframes animatetop {
        from {
            top: -300px;
            opacity: 0;
        }
        to {
            top: 0;
            opacity: 1;
        }
    }

    @keyframes animatetop {
        from {
            top: -300px;
            opacity: 0;
        }
        to {
            top: 0;
            opacity: 1;
        }
    }

    #modal {
        display: none;
        position: fixed;
        z-index: 1;
        padding-top: 100px;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        overflow: auto;
        background-color: rgb(0, 0, 0);
        background-color: rgba(0, 0, 0, 0.4);
    }

    #modal-content {
        position: relative;
        background-color: #fefefe;
        margin: auto;
        padding: 0;
        border: 1px solid #888;
        width: 80%;
        -webkit-box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
        -moz-box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
        -webkit-animation-name: animatetop;
        -moz-animation-name: animatetop;
        -o-animation-name: animatetop;
        animation-name: animatetop;
        -webkit-animation-duration: 0.4s;
        -moz-animation-duration: 0.4s;
        -o-animation-duration: 0.4s;
        animation-duration: 0.4s;
    }

    #modal-head {
        padding: 2px 16px;
        background-color: #5cb85c;
        color: white;
    }

    #modal-content {
        padding: 2px 16px;
    }

    #observer {
        background-color: white;
        border: 2px solid #0a17a8;
        -webkit-border-radius: 10px;
        -moz-border-radius: 10px;
        border-radius: 10px;
        color: black;
        padding: 16px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        -webkit-transition-duration: 0.4s;
        -moz-transition-duration: 0.4s;
        -o-transition-duration: 0.4s;
        transition-duration: 0.4s;
        cursor: pointer;
    }
    #observer:hover {
        background-color: #0a17a8;
        color: white;
    }

    #player {
        background-color: white;
        border: 2px solid #a80a12;
        -webkit-border-radius: 10px;
        -moz-border-radius: 10px;
        border-radius: 10px;
        color: black;
        padding: 16px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        -webkit-transition-duration: 0.4s;
        -moz-transition-duration: 0.4s;
        -o-transition-duration: 0.4s;
        transition-duration: 0.4s;
        cursor: pointer;
    }
    #player:hover {
        background-color: #a80a12;
        color: white;
    }
