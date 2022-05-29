<h1>I.4. Project Develop</h1>
<h2>Universidad Tenológica de Chihuahua BIS</h2>
<h5><i>Student:Kevin Parra - Group:TIDBIS51M - IoT Applications - 28/05/2022</i></h5>

<h4>Description</h4>
<p>This is is an application developed with Python with the framework called Flask, is a like a<b>client-server connection, showing our results using the postman to receive the GET and POST.</p>

<h4>Server</h4>
<ul>
  <li>Establishes GET endpoint for devices, to receive the results using POSTMAN.</li>
  <li>Establishes POST endpoint for devices and users, as the previous part.</li>
</ul>

<h4>iiot_server</h4>
<p>Is just a function that works as a sensor with random numbers, it gets numbers from 0 to 50</p>

<h4>Client</h4>
<ul>
  <li>Declares a dictionary called data that will recieve the random numbers while(while loop) the server is opened.</li>
  <li>Transforms data or the request into a json.</li>
  <li>Uses jsoned data to work as a POST endpoint called devices.</li>
  <li>Check the respective sensor's numbers and tell us if the number is or not less than 15.</li>
  <li>Uses time library to send repeat the while loop each .5.</li>
</ul>

<h4>Results</h4>

<h5>Device POST</h5>
<img src="https://github.com/JoshuaAv07/Client-Server/blob/develop/images/postdevice.PNG?raw=true"/>

<h5>Device GET</h5>
<img src="https://github.com/JoshuaAv07/Client-Server/blob/develop/images/getdevice.PNG?raw=true"/>

<h5>User POST</h5>
<img src="https://github.com/JoshuaAv07/Client-Server/blob/develop/images/postuser.PNG?raw=true"/>

<h5>Client Results</h5>
<img src="https://github.com/JoshuaAv07/Client-Server/blob/develop/images/client.PNG?raw=true"/>

<h5>Server Results</h5>
<img src="https://github.com/JoshuaAv07/Client-Server/blob/develop/images/server.PNG?raw=true"/>
