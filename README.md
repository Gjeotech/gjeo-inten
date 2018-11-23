# gjeo-inten
Web Developer

				<?php
if(isset ($_POST['send'])){
	$username = $_POST['un'];
	$pword    = $_POST['pw'];
   	   
if($username == 'joshua' && $pword === 'inten'){
	header('location:home.php');
	   
	}else{
		echo "<script> alert('Neither your email nor password is here')</script>";
	}
	
}

?>
