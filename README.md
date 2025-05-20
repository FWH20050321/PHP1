mkdir lamp-project && cd lamp-project
mkdir -p conf/apache conf/php htdocs build
Vim htdocs/index.php
<?php
phpinfo();
echo "<h1>Hello from PHP Container!</h1>";
?>
Vim build/Dockerfile

