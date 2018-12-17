# My First HTML Form

1. Start with form tag. action attribute is for where to send our form (the url). Method attribute is for which method (HTTP method) to send data that we collected.

```html
<form action="the-url-to-send-this-form" method="post"> <!-- POST or Get -->

</form>
```

2. Use div tag to make it our job easier when we style the form later using CSS. The for attribute in label tag correspond to id in input.

```html
<form action="the-url-to-send-this-form" method="post">
  
  <div>
    <label for="name">Name:</label>
    <input type="text" id="name" name="user_name">  
  </div>

  <div>
    <label for="mail">E-mail</label>
    <input type="email" id="mail" name="user_email">
  </div>

  <div>
    <label for="msg"></label>
    <textarea id="msg" name="user_message"></textarea>
  </div>

  <div class="button">
    <button type="submit">Send your message</button>
  </div>

</form>