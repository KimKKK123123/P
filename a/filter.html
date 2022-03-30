<?php
$U_ID = $_POST["U_ID"];
$U_pwd = $_POST["U_pwd"];
if ($U_ID=="admin" && $U_pwd=='admin')
        {
            echo("<script>location.replace('admin.php');</script>"); 
            exit();
        }

//echo $userID, "<BR><BR>";
$con=mysqli_connect("localhost", "root", "1234", "stopbusdb");
if(mysqli_connect_error($con))
{
    echo "접속실패", mysqli_connect_error();
    exit();
}
//echo "접속성공<BR>";
//echo $userID, "<BR>";
//echo gettype($userID), "<BR>";

$sql ="select * from user WHERE user.U_ID='$U_ID'";
$ret = mysqli_query($con, $sql);
 
if($ret) 
{   
    //pk로 회원 조회해야할듯 무조건무조건
    mysqli_close($con);
    $row=mysqli_fetch_array($ret);
    
    if(mysqli_num_rows($ret)!=0)
    {
        //echo gettype($row[0]), "<BR>";
        //echo $row[0], "<BR>";
        //echo mysqli_num_rows($ret), "건이 조회됨.<br><br>"; 
        if ($row[0]=="admin")
        {
            echo("<script>location.replace('admin.php');</script>"); 
            exit();
        }
        else
        {
            // 전 페이지로 부터 받아온 정보를 다음 페이지로 넘겨주는 부분
            echo "<form id='gopage' method='post' action='user.php'> \n";
            echo "  <input type=\"hidden\" name=\"U_ID\" value=\"$U_ID\" /> \n";
            echo "</form> \n";
            echo "<script> \n";
            echo " document.getElementById('gopage').submit(); \n";
            echo "</script>\n";
            
            exit();
        }
    }
    else
    {
        echo "등록되지 않은 사용자 입니다!";
        exit();
    }
   
}
else 
{
    echo "쿼리 실패!!!"."<br>";
    echo "실패 원인 : ".mysqli_error($con);
    echo "<br>";
    mysqli_close($con);
	exit();
}
   

?>