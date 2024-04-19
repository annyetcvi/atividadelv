# atividadelv
<?php
include 'Fatura.php';

$Fatura1 = new Fatura();
$Fatura1->setNumero(1);
$Fatura1->setDescricao("Celular");
$Fatura1->setQtd(2);
$Fatura1->setPreco(3000.5);

$total = $Fatura1->getTotalFatura();

echo "$total";






?>
