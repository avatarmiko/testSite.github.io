<html>
	<head>
		<title> Title! </title>
	</head>
	<body>
		<p> hellooo </p>
		<div id="cntr"> 
            The number of visitors is : 
            <span>0</span>
        </div>
       	<script> 
			function counter_fn(){
				var counterElement = document.getElementById("cntr")
			    var counterNumber = parseInt(counterElement.innerHTML)
			    counterNumber = counterNumber + 1
			    counterElement.innerHTML = counterNumber
			}
			window.onload = counter_fn;  
		</script>	
		<p> bruh is this shit updating? </p>
	</body>
</html>
