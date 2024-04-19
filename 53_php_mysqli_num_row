<?php
$con = mysqli_connect("localhost", "root", "password", "mydb");
mysqli_query($con, "CREATE TABLE myplayers(ID INT, First_Name VARCHAR(255), Last_Name
VARCHAR(255), Place_Of_Birth VARCHAR(255), Country VARCHAR(255))");
print("Table Created...... ".<br>);
mysqli_query($con, "INSERT INTO myplayers values(1, 'Sikhar', 'Dhawan', 'Delhi', 'India')");
mysqli_query($con, "INSERT INTO myplayers values(2, 'Jonathan', 'Trott', 'CapeTown',
'SouthAfrica')");
mysqli_query($con, "INSERT INTO myplayers values(3, 'Kumara', 'Sangakkara', 'Matale',
'Srilanka')");
print("Record Inserted ...... ".<br>);
//Retrieving the contents of the table
$result = mysqli_query($con, "SELECT * FROM myplayers");
//Number of rows
$count = mysqli_num_rows($result);
print("Number of rows in the result: ".$count);
//Closing the statement
mysqli_free_result($result);
//Closing the connection
mysqli_close($con);?>
