<?php
//Creating a connection
$con = mysqli_connect("localhost", "root", "", "mydb");
//Executing the multi query
$query = "SELECT * FROM Student";
//Retrieving the records
$res = mysqli_query($con, $query, MYSQLI_USE_RESULT);
if ($res) {
while ($row = mysqli_fetch_row($res)) {
print("ID: ".$row[0]."<br>");
print("NAme: ".$row[1]."<br>");
}
}
//Closing the connection
mysqli_close($con);?>
