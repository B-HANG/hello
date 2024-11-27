<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8"/>
    <title></title>
    <style type="text/css">
        li {
            display: inline-block;
            width: 100px;
        }
    </style>
    <script
src="../lib/jquery/dist/jquery.min.js"></script>
    <script type="text/javacript">
          /*sau khi trang web duoc tai thanh cong thi su kien ready se xay ra */
          $(document).ready(function(){
              /*dat do rong va ke duong vien cho:text, :password va textarea */
              $("div > span").css({ "width": "250px"});
              $(":text, :password, textarea").css({
                  {"width": "350px", "border": "1px dotted red"});
              $(":button, :reset, :submit").css({
                  "width": "80px", "height": "25px", "color": "red", "font-weight": "bold"
              });
          });
    </script>
</head>
<body>
    <form id="frmDangky" action="Dangky.do" method="post" enctype="multipart/form-data">
        <div>
            <span>Ho va ten:</span>
            <input id="txtHoten" name="txtHoten" type="text"/>
        </div>
        <div>
            <span>Mat khau:</span>
            <input id="txtMatkhau" name="txtMatkhau" type="password"/>
        </div>
        <div>
            <span>Giot tinh:</span>
            <input id="NA" name="rdoGioitinh" type="radio" value="1"/>Nam
            <input id="NU" name="rdoGioitinh" type="radio" value="0"/>Nu
        </div>
        <div>
            <span>So thich:</span>
            <input id="DS" name="chkSothich" type="checkbox"/>Doc sach
            <input id="DL" name="chkSothich" type="checkbox"/>Du lich
            <input id="TT" name="chkSothich" type="checkbox"/>The thao
            <input id="AN" name="chkSothich" type="checkbox"/>Am nhac
        </div>
        <div>
            <span>Quoc tich:</span>
            <select id="cboQuoctich" name="cboQuoctich">
                <option value="VN">Viet Nam</option>
            </select>
        </div>
        <div>
            <span>Hinh anh:</span>
            <input id="filHinh" name="filHinh" type="file"/>
        </div>
        <div>
            <span>Ghi chu:</span>
    <textarea id="txtGhichu" name="txtGhichu" rows="4"></textarea>
        </div>
        <div>
            <input id="btnButton" name="btnButton" type="button" value="Button"/>
            <input id="btnReset" name="btnReset" type="reset" value="Reset"/>
            <input id="btnSubmit" name="btnSubmit" type="submit" value="Submit"/>
        </div>
    </form>
</body>
</html>
          
