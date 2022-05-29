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

<h5>Device GET</h5>
<img src="https://user-images.githubusercontent.com/81264746/170850089-232f22cc-fa70-42fb-8f9e-566ed7d3aa82.png"/>

<h5>Device POST</h5>
<img src="https://user-images.githubusercontent.com/81264746/170850106-83163a3b-87ae-46aa-9c8d-8492b5339f64.png"/>

<h5>User POST</h5>
<img src="https://user-images.githubusercontent.com/81264746/170850124-20f4951f-8c02-458c-9547-8c20cf2b61da.png"/>

<h5>Client.py Results</h5>
<img src="https://user-images.githubusercontent.com/81264746/170850138-08fa18fa-e401-4f9c-becd-a3f656055a47.png"/>

<h5>Server Results, running when we start the Client.py</h5>
<img src="https://user-images.githubusercontent.com/81264746/170850160-1428dc30-aae9-4e1f-a229-f302e824e997.png"/>
