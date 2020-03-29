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
                var counter = $('#cntr span').text(); // geting value from span
                var count = 0;
                count = parseInt(counter.value);
                count = count+1;
            	counter.innerHTML = parseInt(count);
           	}
           	window.onload = counter_fn;  
      	</script>
	<p> is this shit updating? </p>
	</body>
</html>
