---
layout: page
title: Contact Us
permalink: /contact/
---

<html lang="en">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=email], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

button {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
</head>

<body>
  <aside>
       <p>
           We would <em>love</em> to hear from you! </p>
           <p>Please use the <b><em>Contact Form</em></b>
           to send us a message.
       </p>
   </aside>

<!-- START HERE -->
<div class="container">
  <form lass="mt-5 form-contact slideanim" method="POST" target="iframe1" data-email="jhKim0254@gmail.com"
  action="https://script.google.com/macros/s/AKfycbxNVXsD-9rjvzVkurMVpdIUnsUBYvjFAnYsI40ee-exwon8vd7hvPWn-0T2x5wrLh1oUw/exec">
    <!-- change the form action to your script url -->

    <label for="name" class="blind">Name</label>
    <input type="text" id="name" name="name" placeholder="Your name..">

    <label for="email" class="blind">Email Address</label>
    <input type="email" id="email" name="email" placeholder="Your email address..">

    <label for="comment">Message</label>
    <textarea id="comment" name="message" placeholder="Write message.." style="height:200px"></textarea>

    <button type="submit" onclick="alert('Thanks for conatacting us!\nWe will get back to you soon!')">SEND</button>

  </form>

  <!-- Submit the Form to Google Using "AJAX" -->
  <script data-cfasync="false" src="form-submission-handler.js"></script>
  <iframe id="iframe1" name="iframe1" style="display:none"></iframe>
<!-- END -->
</div>
</body>
</html>