# Web Interface
C2X has web interface which you can run C2 Server with it and use all of C2X features.

Run
----
    python c2x-http.py --web

- Arguments
    - --use-https [Enable HTTPS for Web Interface]


- Connection Configuration 
  - You can change connection listening IP & port in main/core/config.json file.

Usage
----

    python3 c2x.py --web
    Open your browser and go to:
    http(s)://127.0.0.1:8585
    Go to Server Page and Start the Server
    You can create your script in Create Script Nav
    You can see your zombies in Zombies Nav
    then:
    Go to Terminal page and execute !help
    

Server Page
----
![Server_sc](https://user-images.githubusercontent.com/61124903/130274579-9b3881f5-592e-4392-ab89-a01dfc57d215.png)

for starting C2 server with HTTPS you can use the default self-signed certificate or you can replace your own certificate with files in web_interface/key.pem and cert.pem . 

Create Script Page
----
![CreateScript_sc](https://user-images.githubusercontent.com/61124903/130274826-c88fd4d1-b835-44e7-aac6-874ebcbe88f7.png)

- [Client Side README](https://github.com/nxenon/c2x-http/blob/main/modules/clientside/README.md)

Zombies Page
----
![Zombies_sc](https://user-images.githubusercontent.com/61124903/130274844-03a6961d-ae89-484b-99fb-98ce303bda44.png)

Terminal Page
----

![Screenshot_terminal](https://user-images.githubusercontent.com/61124903/130267844-ba3a76e2-21d1-45e2-ba16-3ace1fe23282.png)

![Screenshot_terminal2](https://user-images.githubusercontent.com/61124903/130267852-49f66a65-3e25-4f8e-be49-ae634f652523.png)


## HTTPS Usage

You can change the connection protocol to HTTPS, **C2X-HTTP** uses self-signed certificates for HTTPS connection, but you can change them.

Change Certificates
----

Go to web_interface directory and replace the `cert.pem` & `key.pem` with your new certificates files.

- note: **GO** lang C2X client does not work with default self-signed certificate ! `You have to change that`.
