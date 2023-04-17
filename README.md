# calculo-de-consumo
Codigo para calculra un consumo
<meta charset="UTF-8">
<h3>Halcohol o gasolina</h3>

<script>
    
    var tanque = 40;
    
    var kmrg = 480;
    var eficienciag = kmrg/tanque;

    var kmra = 300;
    var eficienciaa = kmra/tanque;

        document.write("Teniendo en cuenta que tenemos dos carros, uno que su motor funciona a gasolina y otro con alcohol.")    
            document.write("<br>");
            document.write("<br>");
       
        document.write("      ¿Cuál es la eficiencia del carro usando gasolina? ")
            document.write("<br>");
            document.write("<br>");
        document.write ("Si el carro tiene una capacidad de 40 Litros, y recorre " +kmrg +"km con el tanque lleno de gasolina obtenemos que la eficiencia por litro es de: "  +eficienciag + "km/L.")
            document.write("<br>");
            document.write("<br>");
        document.write("      ¿Cuál es la eficiencia del carro usando alcohol? ")
            document.write("<br>");
            document.write("<br>");
        document.write ("Si el carro tiene una capacidad de 40 Litros, y recorre " +kmra +"km con el tanque lleno de alcohol obtenemos que la eficiencia por litro es de: "  +eficienciaa + "km/L.")

</script>
