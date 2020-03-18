In this problem, I used PHP programming language.
It cannot be opened without software like xampp.

The codes are -

<!DOCTYPE html>
<html>
    <head>
        <title>
            SampleCode
        </title>
    </head>
<body>
    
<?php
for($row = 5 ; $row > 0; $row--){
$col = $row;
while($col>0){
echo "*";
$col--;
};
echo "</br>";
};

?> 

</body>
</html>
