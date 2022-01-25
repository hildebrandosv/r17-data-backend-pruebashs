+ Instalar Json Server: npm install json-server
+ Agregar el script START: "start": "node server.js"
+ Ejecutar START en una ventana de comandos.
+ Sin cerrar la ventana anteriuor (server corriendo), abrir otra ventana de comandos
   - Instalar el CLI de heroku: npm install -g heroku
   - heroku login
   - git init
   - heroku git:remote -a pruebashs
   - git add .
   - git commit -am "make it better"
   - git push heroku main
+ Al terminar el PUSH saca la dirección de acceso (END-POINT) para consumir los datos con base en la APP creada en Heroku. Por ejemplo: "pruebashs".
   https://"PONER AQUÍ LA APP CREADA EN HEROKU (SIN LAS COMILLAS)".herokuapp.com/
   para este repositorio es: https://pruebashs.herokuapp.com/ 
   Para acceder a una tabla en particular, se pone al final "/" y el nombre de la tabla, como por ejemplo: "tbProducts". Entonces quedaría así:
   https://pruebashs.herokuapp.com/tbProducts




