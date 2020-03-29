<html>
	<head>
		<title> Title! </title>
	</head>
	<script> src="require.js" </script>
	<body>
		<p> hellooo </p>
		<div id="cntr"> 
            The number of visitors is : 
            <span>0</span>
        </div>
       	<script> 

			function counter(){
				console.log("hello?");
				var fs = require("fs");
				var text = fs.readFileSync("./counter.txt");
				console.log(text);
			};  
			window.onload = counter;
		</script>	
		<p> bruh is this shit updating? </p>
	</body>
</html>
