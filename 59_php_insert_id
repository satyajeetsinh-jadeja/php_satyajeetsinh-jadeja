<?php
//Creating a connection
$con = mysqli_connect("localhost","root","password","mydb");
//Inserting a record into the employee table
$sql = "insert into Cricketers values(1, 'Shikhar', 'Dhawan', DATE('1981-12-05'), 'Delhi', 'India')";
mysqli_query($con, $sql);
//Insert ID
$id = mysqli_insert_id($con);
print("Insert ID: ".$id ."\n");
$sql = "insert into Cricketers values(2, 'Jonathan', 'Trott', DATE('1981-04-22'), 'CapeTown',
'SouthAfrica')";
mysqli_query($con, $sql);
$id = mysqli_insert_id($con);
print("Insert ID: ".$id);
//Closing the connection
mysqli_close($con);?>