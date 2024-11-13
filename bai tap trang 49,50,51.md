<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Học web chuẩn</title>
<style>
  /* Reset */
  * {
    margin: 0;
    padding: 0;
  }
  ul {
    list-style: none;
  }
  body {
    color: #6e6e6e;
    font-family: Helvetica, sans-serif;
    font-size: 16px;
    line-height: 1.8;
  }

  /* Viết độc lập các thành phần form, để sử dụng lại */
  input[type="text"],
  input[type="email],
  textarea{
    border: 1px solid #ccc;
    border-radius: 3px;
    box-shadow: 0 1px 1px 0 #ddd inset;
    /* Cần cho full-width */
    box-sizing: border-box;
    color: #6e6e6e;
    padding-left: 20px;
  }
  input[type="text"],
  input[type="email"] {
    height: 40px;
  }
  texarea {
    padding-top: 10px;
  }
  button {
    background-color: #7dcefd;
    border: 1px solid #59a8d5;
    border-radius: 4px;
    color: #fff;
    cursor: pointer;
    min-width: 125px;
    padding: 11px 10px;
    text-align: center;
    transition: 0.3s background-color;
  }
  button:hover {
    background-color: #59a8d5;
  }
  /* Layout */
  .contact-form {
    margin: 30px auto;
    width: 770px;
  }
  .contact-form h2 {
    color: #383838;
    font-size: 18px;
    margin-bottom: 17px;
  }
  .contac-form p {
    margin-bottom: 10px;
  }
  .contact-form input[type="email"] {
    float: right;
  }
  .contact-form texarea {
    height: 225px;
  }
  .half-size {
    width: 370px;
  }
  .full-size {
    width: 100%;
  }
  .contact-form .submit {
    margin-top: -10px;
  }
  </style>
  </head>
  <body>
    <select class="contact-form">
      <h2>Get in touch with us by filling contact form below</h2>
      <form method=" " action=" ">
        <p><inputtype="text" name="name" pllaceholfer="*Enter your fullname" value="" class="half-size"> <input type="email" name="email" placeholder="*Enter your email address" value="" class="half-size"></p>
        <p>input type="text" name="subject" placeholder="*Enter your subject" value="" class="full-size"></p>
        <p>texarea name="messagae" placeholder="*Your message here" cols="50" rows="10" class="full-size"></texarea></p>
        <p class="submit"><button type="submit">Send message</button><span>* Please fill all require form field, thanks!</span></p>
      </form>
    </select>
  </body>
  </html>
      
  