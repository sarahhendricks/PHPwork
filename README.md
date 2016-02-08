<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<title>PhpFiddle Initial Code</title>

<script type="text/javascript">
	
</script>

<style type="text/css">
	
</style>

</head>

<body>

<h2>
	Quiz: Name the country
	</h2>

<p>
	Which nation is home to the largest Muslim population in the world?
	</p>	

<form action ="" method="post">
  <input type="radio" name="country1" value="Saudi Arabia" checked> Saudi Arabia<br>
  <input type="radio" name="country1" value="Indonesia"> Indonesia<br>
  <input type="radio" name="country1" value="Nigeria"> Nigeria <br>
  <input type="radio" name="country1" value="Morocco"> Morocco <br>
  <input type="submit" name="submit" value="Get Selected Values" />
</form>

<?php
 
if (isset($_POST['submit'])){
	$answer=isset($_POST['country1']);
		if ($answer=="Indonesia"){
		echo 'correct';
		
	}
}


?>

</body>
</html>
