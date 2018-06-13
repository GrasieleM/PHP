/*Parašykite funkciją, kuri generuotų 2 atsitiktinius skaičius (rand) nuo 1 iki 6 ir spausdintų juos į ekraną tol, kol vienas iš skaičių bus 6.*/
<?php
$x=0;
$y=0;

    while ($x!=6 && $y!=6)
    {
        $x=rand(1,6);
        $y=rand(1,6);
        echo " $x <br>";
        echo "$y <br>";
    }
    
?>
