<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="http://localhost/tugas/proses1.php" method="GET">
        
     bilangan 1<input type="text" name="bilangan1"><br>
     
    bilangan 2<input type="text" name="bilangan2"><br>
     
   Operasi <select name="operasi"><br>
         <option value="+">+</option>
         <option value="-">-</option>
         <option value="/">/</option>
         <option value="*">*</option>
    
     <input type="submit" value="kirim">
     
     
    </form>
</body>
</html>
  
  
  <?php       
$bilangan1=$_GET['bilangan1'];
$bilangan2=$_GET['bilangan2'];
$operasi=$_GET['operasi'];

if($operasi == '+'){
     $hasil = $bilangan1 + $bilangan2;
}else if($operasi =='-'){
     $hasil = $bilangan1 - $bilangan2;
}else if($operasi =='/'){
     $hasil = $bilangan1 / $bilangan2;
}else if($operasi =='*'){
     $hasil = $bilangan1 * $bilangan2;
}
else{
    echo "tidak ditemukan";
}
echo "bilangan 1 adalah $bilangan1 <br>";
echo "bilangan 2 adalah $bilangan2 <br>";
echo "hasil dari $bilangan1 $operasi $bilangan2 adalah $hasil"



?>
