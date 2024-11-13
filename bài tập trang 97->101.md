<html>
<head>
  <title>HTML, CSS & JQuery</title>
  <style type="text/css">
     /*--võ bọc bên ngoài rộng 900px, canh giữa, nền thằng--*/
     .container {
       width: 900px;
       margin: 0px auto;
       background-color: White;
    }
    /*--đầu trang cao 100px--*/
    .top {
      height: 100px;
      background-color: Red;
    {
    /*menu trang cao 22px, canh giữa--*/
    .menu {
      height: 22px;
      background-color: Yellow;
      text-align: center
    }
    /*--giữa trang cao tối thiểu 400px--*/
    .middle {
      min-height: 400px;
    }
    /*-- giữa-trái cao như middle, rộng 250px, gâm trái--*/
    .middle_left {
      float: left;
      width: 250px;
      min-heigth: inherit;
      background-color: Aqua;
    } 
    /*--giữa-phải cao như middle, rộng 650px, gâm phải--*/
    .middle_right {
      float: right;
      width: 645px; 
      min-heigth: inherit;
      background-color: White;
    /*--chân trang  không gâm, cao 22px--*/
    .bottom {
      clear: both;
      height: 22px;
      background-color: Yellow;
    }
    /*--fieldset trong. middle_left cao tối thiểu 150--*/
    .middle_left fieldset {
      min-height: 150px;
    }
    /*-- li trong .middle_left không dùng dấu, kẽ chân--*/
    .middle_left li { 
      list-style-type: none;
      border-bottom: 1px dotted red;
   }
   /*--liên kết trong .menu cách nhau 20px--*/
   .menu a {
     padding: 0px 10px 0px 10px;
  }
  /*--liên kết trong .middle_left chữ HOA nhỏ--*/
    .middle_left a {
      font-variant: small-caps;
  }
  /*--liên kết có chuột trong .middle_left in đậm--*/
  .middle_left a:hover {
    font-weight: bold;
  }
  /*--liên kết chung cho toàn trang--*/
  a { text-decoration: none; }
    a:hover {
      color: Red;
  }
body {
    background-color: Gray;
  }
 </style>
</head>
<body>
  <div class="container">
    <div class="top"></div>
    <div class="menu">
      <a href ="#1" >Home</a>
      <a href ="#2" >About Us</a>
      <a href ="#3" >Contact Us</a>
      <a href ="#4" >Feedback</a>
      <a href ="#5" >FAQs</a>
     </div>
     <div class ="middle">
      <div class="middle_left">
       <fieldset>
        <legend>Member Infor</legend>
       </fieldset>
       <fieldset>
        <legend>Products</legend>
        <li><a href="#1">Nokia</a></li>
        <li><a href="#2">Samsung</a></li>
        <li><a href="#3">Sony Ericsson</a></li>
        <li><a href="#4">Motorla</a></li>
        <li><a href="#5">Apple</a></li>
        <li><a href="#5">Seamen</a></li>
       </fieldset>
       <fieldset>
         <legend>Online Support</legend>
       </fieldset>
      </div>
      <div class="middle_right"></div>
    </div>
    <div class="bottom"></div>
  </div>
</body>
</html>
