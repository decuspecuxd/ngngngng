<!DOCTYPE HTML>
<html lang="pl">
<head>
	<meta charset="utf-8" />
    <title>JS innerHTML</title>
<script>
    function z1()
    {
        document.getElementById("z1").innerHTML="Żadnego. To Noe płynął arką";
    }
    function z2()
    {
        document.getElementById("z1").innerHTML="Tu znajdziesz odpowiedź";
    }   

    
	function z3()
    {
        document.getElementById("z3").innerHTML="Mył okna na pierwszym piętrze i stamtąd spadł";
    }
    function z4()
    {
        document.getElementById("z3").innerHTML="Tu znajdziesz odpowiedź";
    } 
		
	
	function z5()
    {
        document.getElementById("z5").innerHTML="Trumną";
    }
    function z6()
    {
        document.getElementById("z5").innerHTML="Tu znajdziesz odpowiedź";
    } 
	
	
	function z7()
    {
        document.getElementById("z7").innerHTML="Po prostu podszedł, bo łańcuch nie był do niczego przymocowany";
    }
    function z8()
    {
        document.getElementById("z7").innerHTML="Tu znajdziesz odpowiedź";
    } 
	
	
	function z9()
    {
        document.getElementById("z9").innerHTML="Prezydent";
    }
    function z10()
    {
        document.getElementById("z9").innerHTML="Tu znajdziesz odpowiedź";
    } 
	
</script>
</head>
<body>

<h1>Zagadki logiczne</h1>
<h2>ZAGADKA 1</h2>
   <p>
    Ile zwierząt Mojżesz zabrał do arki?
    </p>
    <input type="button" value="zobacz odpowiedź" onclick="z1()">
</br></br>
<div id="z1">Tu znajdziesz odpowiedź</div>
</br>
</br>
<input type="button" value="ukryj odpowiedź" onclick="z2()">

</br></br>
</br></br>
<h2>ZAGADKA 2</h2>
<p>
    Człowiek mył okna w 20-piętrowym budynku. W pewnym momencie stracił równowagę i spadł, ale nie został ranny. Jak to możliwe?
    </p>
    <input type="button" value="zobacz odpowiedź" onclick="z3()">
</br></br>
<div id="z3">Tu znajdziesz odpowiedź</div>
</br>
</br>
<input type="button" value="ukryj odpowiedź" onclick="z4()">

</br></br>
</br></br>
<h2>ZAGADKA 3</h2>
<p>
   Ten, kto mnie tworzy, nie potrzebuje mnie, kiedy to robi. Ten, który mnie kupuje nie potrzebuje mnie dla siebie. Ten, kto mnie użyje, nie będzie o tym wiedział. Czym jestem?
    </p>
    <input type="button" value="zobacz odpowiedź" onclick="z5()">
</br></br>
<div id="z5">Tu znajdziesz odpowiedź</div>
</br>
</br>
<input type="button" value="ukryj odpowiedź" onclick="z6()">

</br></br>
</br></br>
<h2>ZAGADKA 4</h2>
<p>
    Koń jest na łańcuchu o długości 20 metrów i udało mu się sięgnąć jabłko, które było w odległości 30 metrów od niego. Jak to zrobił?
    </p>
    <input type="button" value="zobacz odpowiedź" onclick="z7()">
</br></br>
<div id="z7">Tu znajdziesz odpowiedź</div>
</br>
</br>
<input type="button" value="ukryj odpowiedź" onclick="z8()">

</br></br>
</br></br>
<h2>ZAGADKA 5</h2>
<p>
   Pan Blue mieszka w niebieskim domu, Pani Pink mieszka w różowym domu, a Pan Brown w domu brązowym. Kto mieszka w Białym Domu?
    </p>
    <input type="button" value="zobacz odpowiedź" onclick="z9()">
</br></br>
<div id="z9">Tu znajdziesz odpowiedź</div>
</br>
</br>
<input type="button" value="ukryj odpowiedź" onclick="z10()">


</body>
