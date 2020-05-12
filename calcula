<?php

if ($_POST) {
	$primeiraProva = $_POST['primeraProva'];
    $segundaProva = $_POST['segundaProva'];
    $terceiraProva = $_POST['terceiraProva'];
    $quartaProva = $_POST['quartaProva'];

    if (is_numeric($primeiraProva) && is_numeric($segundaProva) && is_numeric($terceiraProva) && is_numeric($quartaProva)) {

    	if ($primeiraProva > 0 && $segundaProva > 0 && $terceiraProva > 0 && $quartaProva > 0) {
    		$totalProva = 4;

            $calculoProva = ($primeiraProva + $segundaProva + $terceiraProva + $quartaProva) / $totalProva;
            $calculoProva = number_format($calculoProva, 2, ',', '.');

            echo "Sua Média na Matéria que Informou as Notas é ". $calculoProva;
    	} else {
    		echo "Qualque numero digitado deve ser maior que zero.";
    	}

    } else {
    	echo "Qualquer dado digitado deve ser um Numeral";
    }

} else {
	echo "...";
}
