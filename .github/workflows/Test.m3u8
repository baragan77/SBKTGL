<?php
 
/*Special thanks to: 
@GitRhs * @Rukman39 * @ottoprie * @ariyosaputra *  @faster all UnderGround IPTV Team 
*/ 
 
header('Content-type: Application/x-mpegURL');  
error_reporting(0); 
$eroz = fopen('error_log', 'w'); 
fwrite($eroz,'Mau Ngapain...?');  
//contoh ambil single channel warner
$intip = "https://raw.githubusercontent.com/apistech/IPTV/master/hbohits.m3u8"; 
$chn = curl_init($intip); 
curl_setopt($chn, CURLOPT_RETURNTRANSFER, true); 
$kops = 'User-Agent: Mozilla/5.0 (Linux; Android 11; vivo 1904) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.115 Mobile Safari/537.36'; 
curl_setopt($chn, CURLOPT_HTTPHEADER, $kops); 
$get = curl_exec($chn);
echo $get;

?>
