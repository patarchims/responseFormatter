# responseFormatter
#ResponseFormatter


Use :
Make new folder "Helpers" in app/
and paste file ResponseFormatter.php


<?php

use App\Helpers\ResponseFormatter;


API Success :
 return ResponseFormatter::success(
       $data, 'Data berhasil diambil'
  );
  
API ERROR :
 return ReposnseFormatter::error(
    null, 'Data  tidak ada', 404
);
