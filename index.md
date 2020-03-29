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
       		const fs = require('fs') 
  
			fs.readFile('count.txt', (err, data) => { 
    			if (err) throw err; 
  
   				console.log(data.toString()); 
			}) 
			
			// window.onload = counter(){

			// };  
		</script>	
		<p> bruh is this shit updating? </p>
	</body>
</html>
