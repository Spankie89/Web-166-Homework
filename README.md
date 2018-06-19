# Web-166-Homework
<?php
echo 'Hi '. $_POST['fullname'];
?>
<form action="form.php" method="post">
    Enter your name: <input type="text"
                            name="fullname"><br>
    <input type="submit" name="submit"
           value="Send Name">
</form>
