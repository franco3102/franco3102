<!DOCTYPE html>
<html>
<body>

	<h1>Hai Cantik aku Prisca Prisilia</h1>
	<img src="WhatsApp Image 2021-06-09 at 14.11.21.jpeg">
	<h1>Mau tetap bareng aku gak?</h1>
	<button id='btn_mau' onClick='alert("I <3 U")'>mau</
	button>&nbsp;
	<button id='btn_gamau' onClick='gamau(this)'
	style='position:absolute'>Gamau</button>		
</body>
<script>
	function gamau(id){
		var mau = document.getElementById('btn_mau'):
		var i = Math.floor(Math.random()*300)+1;
		var j = Math.floor(Math.random()*100)+mau.offsetTop;
		id.style.left = i+'px';
		id.style.top = j+'px';
	}
</script>
</html> 
