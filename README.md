# ejercicio-web

Se crea la carpeta html:
- mkdir html
- cd html/

Creo el contenedor:
- $ docker run --name some-nginx -p 8080:80 -v /workspaces/ejercicio-web/html:/usr/share/nginx/html:ro -d nginx