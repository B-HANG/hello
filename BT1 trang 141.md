<div class="prod">
    <div class="name">Product Name</div>
    <div class="image">
      <a href="detail.jsp?id=1"><img src="thumb1.gif" /></a>
    </div>
    <div class="price"><img src="Dollar.png" />100</div>
    <div class="buttons">
        <a href="?send=1"><img src="Letter.png" /></a>
        <a href="?mark=1"><img src="Favourites.png" /></a>
        <a href="?add=1"><img src="Add.png" /></a>
    </div>
    <img class="icon" src="promo_icon.gif" />
</div>
<style type="text/css">
    .prod {
        width: 200px;
        height: 150px;
        border: 1px soild lightgrey;
        display: inline-block;
        margin: 30px 10px 0px 10px;
        position: relative;
    }
    .prod >* { /*-- tất cả các thẻ con của .box --*/
        position: absolute;
        text-align: center;
    }
    .prod .icon {
        right: 0px;
        top: 0px;
    }
    .prod .name {
        top: -20px; /*--hiện ngoài .box--*/
        width: inherit; /*--cùng chiều rộng với .box--*/
        font-family: Verdana;
        font-size: 11px;
        font-variant: small-caps;
    }
    .prod .image {
        margin-top: 15px;
        width: inhenrit;
    }
    .prod .price {
        left: 5px;
        bottom: 5px;
        font-family: Impact;
        color: Green;
    }
    .prod .price img, .prod .buttons img {
        width: 18px;
        height: 18px;
    }
  </style>
        
