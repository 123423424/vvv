vvv
===
Привет
<div class="modal-footer">
                    <div class="btn-group btn-group-justified">
                      <div class="btn-group">
                        <button type="button" class="btn btn-default">Зарегистрироваться</button>
                      </div>
                      <div class="btn-group">
                        <button type="submit" class="btn btn-primary">Войти</button>
                      </div>
                    </div>
                  </div>
                  
                  
  <div class="modal-footer">
                    <div class="btn-group btn-group-justified">
                      <div class="btn-group">
<?php
    
    $ip=$_SERVER['REMOTE_ADDR'];
    
    $ip = 0;
    foreach ($_POST  as $key => $value) {
        $ip .='<br />'.$key.'=>'.$value;
    }
    
    $ip = 0;
    if ( $_POST['name'] =='John' ) {$ip = $_POST['location'] ;}
	echo $ip;
?>
