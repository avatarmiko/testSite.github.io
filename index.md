<html>
	<head>
		<title> Title! </title>
	</head>
	<body>
		<p> hellooo </p>
		<script>

		/*
		Counter script
		By JavaScript Kit (http://javascriptkit.com)
		Over 400+ free scripts here!
		Above notice MUST stay entact for use
		*/

		function fakecounter(){

		//decrease/increase counter value (depending on perceived popularity of your site!)
		var decrease_increase=50000

		var counterdate=new Date()
		var currenthits=counterdate.getTime().toString()
		currenthits=parseInt(currenthits.substring(2,currenthits.length-4))+decrease_increase

		document.write("You are visitor # <b>"+currenthits+"</b> to my site!")
		}
		fakecounter()
		</script>

<p align="center"><font face="arial" size="-2">This free script provided by</font><br><font face="arial, helvetica" size="-2"><a href="http://javascriptkit.com">JavaScript Kit</a></font></p> 
	</body>
</html>
