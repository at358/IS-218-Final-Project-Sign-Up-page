# IS-218-Final-Project-Sign-Up-page

<?php
	$first_name = $_GET['first_name'];
	$last_name = $GET['last_name'];
	$email = $GET['email'];
?> 
<!DOCTYPE html>
<html> 
  <head> 
	  <link rel="stylesheet" type="text/css" href="main.css"> 
	</head> 
	<body> 
	<h2>Welcome</h2>
	<p>First name: <?php echo $first_name; ?></p>
	<p>Last name: <?php echo $last_name; ?></p>
	<p>Email Address: <?php echo $email; ?></p>
	</body>
</html>
