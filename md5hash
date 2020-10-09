<form method="POST">
            <input type="text" name="text" placeholder="Masukkan text">
            <input name="submit" type="submit" value="hash">
    </form>
<?php
	if(isset($_POST['submit'])){
      $plaintext = $_POST['text'];
    if($plaintext){
		echo"<b>text awal: </b>".$plaintext;
		echo"</br>";
		echo "<b>hasil: </b>".md5($plaintext);
    }
    }
?>
