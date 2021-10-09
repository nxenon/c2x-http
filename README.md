# C2X-HTTP

[![Tool Category](https://badgen.net/badge/Tool/Post%20Exploitation/black)](https://github.com/nxenon/c2x-http)
[![APP Version](https://badgen.net/badge/Version/Beta/red)](https://github.com/nxenon/c2x-http)
[![Python Version](https://badgen.net/badge/Python/3.x/blue)](https://www.python.org/download/releases/3.0/)
[![License](https://badgen.net/badge/License/GPLv2/purple)](https://github.com/nxenon/c2x-http/blob/master/LICENSE)

C2X-HTTP is a C2/Post-Exploitation Framework [working on HTTP(S)] for Red Teaming and Ethical Hacking.

Screenshots
----
![Screenshot](https://user-images.githubusercontent.com/61124903/130267743-f7b989e2-d377-4b0c-934e-984153444b21.png)

![Screenshot_terminal](https://user-images.githubusercontent.com/61124903/130267844-ba3a76e2-21d1-45e2-ba16-3ace1fe23282.png)

![Screenshot_terminal2](https://user-images.githubusercontent.com/61124903/130267852-49f66a65-3e25-4f8e-be49-ae634f652523.png)


Installation
----
    git clone https://github.com/nxenon/c2x.git
    cd c2x
    pip3 install -r requirements.txt
    
Usage
----
    python3 c2x.py --web
    --use-https argument enables HTTPS for C2X web interface
    then open http(s)://127.0.0.1:8585/ in your browser

Web Interface
----

[Web README and Screenshots](https://github.com/nxenon/c2x-http/blob/main/web_interface/README.md)

Use HTTPS
----

[HTTPS Usage README](https://github.com/nxenon/c2x-http/blob/main/web_interface/README.md#https-usage)

Client Side
----
You need some instructions for running client side codes after creating your scripts:

[Client Side README](https://github.com/nxenon/c2x-http/blob/main/modules/clientside/README.md)


Help
----
      .oooooo.     .oooo.   oonoooo  ooooo
     d8P'  `Y8b  .dP""Y88b   `8x88    d8'     HTTP(S) Version
    888                ]8P'    Ye88..8P
    888              .d8P'      `8n88'
    888            .dP'        .8PYo88.       {version : Beta}
    `88b    ooo  .oP     .o   d8'  `n88b      https://github.com/nxenon/c2x-http
     `-nxenon-'  8888888888 o888o  o88888o
    
    *** You have to run C2X-HTTP with root privileges for using C2 listening port from 1-1023 ***
    usage: python3 c2x-http.py [--web]
    
    optional arguments:
      -h, --help   show this help message and exit
      --web        Start Web Interface
      --use-https  Enable HTTPS for Web Interface


Configuration
----
All of project configuration params are in main/core/config.json file which you can change them.

[config.json](https://github.com/nxenon/c2x-http/blob/main/main/core/config.json)
