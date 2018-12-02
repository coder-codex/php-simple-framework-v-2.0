PHP `simple` framework V 2.0

developer : Flavius Pogacian

facebook : https://www.facebook.com/flavius.pogacian

date : 2 Dec 2018

code developed for the `Coder Codex` Project

email : office@codercodex.ro

This repo contains the source code needed to develop the `simple` framework.

This is the 2.0 version of the `simple` framework.

Updates from  V 1.0 to V 2.0 :

<pre>

+ the `backend` alias has been developed

 The `backend` alias folder structure :
 
 backend
    controllers
    views
        custom
        default
    web

 The `custom` controller file : 

    - backend/controllers/CustomController.php
 
    We have two available actions : detail & index
 
        - backend/views/custom/detail.php
        - backend/views/custom/index.php
 
 The `default` controller file :
  
    - backend/controller/DefaultController.php
 
    We have two available actions : custom & index
 
        - backend/views/default/custom.php
        - backend/views/default/index.php
 
 The main entry file :
 
 - backend/web/index.php

</pre>

The application files & folders structure :

<pre>

backend
    controller
        CustomController.php
            action Index
            action Detail    
        DefaultController.php
            action Index
            action Custom
    views
        custom
            index.php
            detail.php
        default
            custom.php
            index.php
    web
        index.php

frontend
    controller
        CustomController.php
            action Index
            action Detail    
        DefaultController.php
            action Index
            action Custom
    views
        custom
            index.php
            detail.php    
        default
            custom.php
            index.php
    web
        index.php

vendor
    framework
        components
            route
                detect_controller.php
                detect_action.php
                route.php
        controllers
            Controller.php
        simple.php
        
index.php
</pre>

Clone the repo, study the source code, investigate the flow, learn the logic behind the code.

Enjoy :)