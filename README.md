<div id='one' style='visibility: hidden; text-align: center; height: 100%; max-width: 100%; border: none; overflow: hidden;'><iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdS0Gpw_9nkEc9yWdAIcoUwUNLXLgsUX6GwvwUeMwoPWnxRhQ/viewform?embedded=true" width="640" height="6345" frameborder="0" marginheight="0" marginwidth="0"></iframe></div>

<div id='two' style='visibility: hidden; text-align: center; height: 100%; max-width: 100%; border: none; overflow: hidden;'><iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeomz5EeqWG1KVQnHwlsthJLIx1WgDV56DrY_73h4iAnffPuQ/viewform?embedded=true" width="640" height="6345" frameborder="0" marginheight="0" marginwidth="0"></iframe></div> 

<div id='three' style='visibility: hidden; text-align: center; height: 100%; max-width: 100%; border: none; overflow: hidden;'><iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfyytOlTOcWWivEw4TsSjwYywesjR3Qse-ye5WukRbfLm1zzw/viewform?embedded=true" width="640" height="6345" frameborder="0" marginheight="0" marginwidth="0"></iframe></div> 

<div id='four' style='visibility: hidden; text-align: center; height: 100%; max-width: 100%; border: none; overflow: hidden;'><iframe src="https://docs.google.com/forms/d/e/1FAIpQLSe0KnBNT2ZWqbqb3bRFr4ELWxt8FQ18sy6Kjksdh-lIAUDdaw/viewform?embedded=true" width="640" height="6345" frameborder="0" marginheight="0" marginwidth="0">로드 중…</iframe></div>

 
<script type="text/javascript">
var xxx = Math.floor(Math.random() * 4) + 1;
one = document.getElementById('one');
two = document.getElementById('two');
three = document.getElementById('three');
four = document.getElementById('four');


if (xxx === 2) {	
	two.style.visibility = "visible";	
	one.style.height = 0;	
	three.style.height = 0;	
	four.style.height = 0
}

else if (xxx === 3){	
	three.style.visibility = "visible";	
	one.style.height = 0;	
	two.style.height = 0;	
	four.style.height = 0;
}

else if (xxx === 4){
	four.style.visibility = "visible";	
	one.style.height = 0;	
	two.style.height = 0;	
	three.style.height = 0;
}

else {	
	one.style.visibility = "visible";	
	two.style.height = 0;	
	three.style.height = 0;		
	four.style.height = 0;
}
</script>
