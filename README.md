# RENTapi
Reune información sobre casas o departamentos en renta.<br>
provee metodos para acceder a los datos de las casas o departamentos y de los arrendatarios que publican las ofertas.<br>
<br>
Manejo mediante URIs previamente definidas.<br>
El formato de la información es JSON.<br>
Pasos para hacer uso de RENTapi<br>
-git clone<br>
-npm install<br>
Conexion a MongoDB<br>
-mongod.exe<br>
-mongo.exe<br>
#Ejecución de la aplicación <br>
npm start

#PETICIONES<br>
GET<br>
localhost:3000/casas  <br>
localhost:3000/arrendadores <br>
localhost:3000/casas?param1=value&param2=value<br>
localhost:3000/arrendadores/:id/casas <br><br>
POST<br>
localhost:3000/casas   <br>
localhost:3000/arrendadores<br><br>
PUT<br>
localhost:3000/casas/:id <br>
localhost:3000/arrendadores/:nombre<br><br>
DELETE<br>
localhost:3000/casas/:id  delete<br>
localhost:3000/arrendadores/:id 
