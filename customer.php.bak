<?php
/*
This program write by Phakapol kosolkarn
http://www.bump.in.th
Free for Purpose use no commercial
*/
include_once ('setting.php');
include_once ('connect.php');
$c_name=$_POST['name'];
$c_fullname=$_POST['fullname'];
$c_address1=$_POST['address1'];
$c_address2=$_POST['address2'];
$c_phone=$_POST['phone'];
$c_fax=$_POST['fax'];
$c_cellphone=$_POST['cellphone'];
$c_delvname=$_POST['delv_name'];
$c_delvadd1=$_POST['delv_add1'];
$c_delvadd2=$_POST['delv_add2'];
$c_mailctact=$_POST['email_contact'];
$c_namectact=$_POST['name_contact'];


$sql="INSERT INTO print_customer set name='$c_name' , fullname='$c_fullname' , address1='$c_address1' , address2='$c_address2' , phone='$c_phone' , fax='$c_fax' , cellphone='$c_cellphone' , deli_name='$c_delvname' , deliaddress1='$c_delvadd1' , deliaddress2='$c_delvadd2' , mail_contact='$c_mailctact' , name_contact='$c_namectact' ";

mysql_query($sql);



?>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Pragma" content="no-cache">
<META HTTP-EQUIV="Expires" CONTENT="-1">
<META HTTP-EQUIV="EXPIRES" CONTENT="Mon, 22 Jul  2000 11:12:01 GMT">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta http-equiv="refresh" content="1;URL=system.php" />
<title></title>
</head>
<body>
<center>
<br><br><br><font color=red size=+2><b> Process Complete</b></font>
<br>Please wait....
</center>
</body>
</html>

