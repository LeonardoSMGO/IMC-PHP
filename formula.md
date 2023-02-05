$peso = $_POST['p']; 


$altura = $_POST['a'];


$calculo_imc = $peso/($altura**2); 


if ($calculo_imc < 18.5) { 

    echo "Magreza";
    
} elseif ($calculo_imc >= 18.5 and $calculo_imc <= 24.9) {

    echo "Normal";
    
} elseif ($calculo_imc >= 25 and $calculo_imc <= 29.9) {

    echo "Sobrepeso";
    
} elseif ($calculo_imc > 30) {

    echo "Obesidade";
}