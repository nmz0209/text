<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>購物網站會員資料</title>
</head>
<body>
<?php


$DB_NAME = "test"; 
$DB_USER = "root"; 
$DB_PASS = "12345678"; 
$DB_HOST = "localhost"; 

// 連接 MySQL 資料庫伺服器
$con = mysqli_connect($DB_HOST, $DB_USER, $DB_PASS);
if (empty($con)) {
    print mysqli_error($con);
    die("資料庫連接失敗！");
    exit;
}

// 選取資料庫
if (!mysqli_select_db($con, $DB_NAME)) {
    die("選取資料庫失敗！");
} else {
    echo "連接 " . "會員資料" . " 成功！<br>";
}

// 設定連線編碼
mysqli_query($con, "SET NAMES 'UTF-8'");

// 取得資料
$sql = "SELECT * FROM t1";
$result = mysqli_query($con, $sql);

// 獲得資料筆數
if ($result) {
    $num = mysqli_num_rows($result);
    echo "會員資料有 " . $num . "名會員<br>";
}

// --- 顯示資料 --- //

echo "<br>顯示資料（會員姓名）：<br>";

$result = mysqli_query($con, $sql);
while ($row = mysqli_fetch_array($result, MYSQLI_ASSOC)) {
    printf("會員編號(%s)  : %s<br>", $row["mId"], $row["name"]);
}
echo "<br>顯示資料（會員生日）：<br>";

$result = mysqli_query($con, $sql);
while ($row = mysqli_fetch_array($result, MYSQLI_ASSOC)) {
    printf("會員編號(%s)  : %s<br>", $row["mId"], $row["birthday"]);
}
echo "<br>顯示資料（會員手機號碼）：<br>";

$result = mysqli_query($con, $sql);
while ($row = mysqli_fetch_array($result, MYSQLI_ASSOC)) {
    printf("會員編號(%s)  : %s<br>", $row["mId"], $row["phone"]);
}


// 釋放記憶體
mysqli_free_result($result);

// 關閉連線
mysqli_close($con);

?>
</body>
</html>