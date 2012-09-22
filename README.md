Getting-current-website-url-in-php
==================================

this will be generates the current website url


<?php
$url="http://".$_SERVER['HTTP_HOST'].$_SERVER['REQUEST_URI']; 
echo $url;
?>