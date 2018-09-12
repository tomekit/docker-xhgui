# Back-end XHGui + MongoDB + PHP 7.2

Build:

`` 
docker build -t "docker-xhgui" .
``

Run :

``
docker run --name docker-xhgui -p 27017:27017 -p 8080:80 docker-xhgui
``