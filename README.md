<h1>RealTime Chat Application - LetsChat</h1>

<ul>
<li>It is an scalable Realtime Chatting Application that provides an interface for multiple user chatting at the same time.</li>
<li>FrontEnd Technologies- HTML, CSS</li>
<li>BackEnd Technologies- JavaScript, Node.js</li>
<li>Used Socket.io module for a two-way connection between client and server.</li>
<li>FrontEnd includes a navigation bar, Chat window and a form submit button for sending the messages.</li>
<li>HTML has been used for preparing the structure of application.</li>
<li>CSS has been used for styling the application.</li>
<li>Added Client sided JavaScript for the purpose of playing with DOM elements.</li>
<li>First of all stored all the DOM elements in a respectives JS variable.</li>
<li>Used Audio file (ting.mp3) which gives notification on receiving the messages.</li>
<li>Everytime a new user tries to join, first of all ask his/her name and let the server know.</li>
<li>If a new user joins, receive the event from the server using eventListner.</li>
<li>Receive message from server using receive function.</li>
<li>If a user leaves the chat, tell all the other users that this user has left the chat.</li>
<li>Server Side JavaScript will handle the Socket IO connections.</li>
<li>If a new user joins, let the other users connected with server know.</li>
<li>If someone sends the message, broadcast it to other people.</li>
<li>If someone leaves the chat, let others know.</li>
</ul>

# Process to run the app
<ol>
  <li> run <b>nodemon nodeserver/index.js</b>
  <li> navigate to index.html and open it to edit.
  <li> Right click anywhere in the file <b>index.html</b> and from the menu that appears select <b> Open with Live server </b>
  <li> A instance of the application will appear in the browser. 
  <li> Copy the url from the address bar and open another instance in another tab or in incognito or on another browser.
</ol>
User First
![SS-1](https://user-images.githubusercontent.com/46307002/204150413-8d2f436d-3d85-4887-9030-bc6b5f425295.png)

User Second
![ss-2](https://user-images.githubusercontent.com/46307002/204150320-ca96df52-c3dc-4428-a6b9-e00203d2b64e.png)

User Third
![ss-3](https://user-images.githubusercontent.com/46307002/204150363-0bf92c9a-f3a6-4dc2-afca-c27952df6d5a.png)
