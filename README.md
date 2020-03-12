# PHP-delete-exists-file
A simple script for deleting exists file 


```
<?php
      $file = "/images/sky.jpg";
      
      if(file_exists ($file)){   
          unlink($file);  //unlink() form deleting file return type boolean
      }
      
      

?>
```
