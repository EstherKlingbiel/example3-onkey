# example3-onkey
<!DOCTYPE HTML>
<html>
<head>
<title>Javascript: onkeydown, onkeyup</title>

<style type="text/css">
	
	body 
	{
		background-color: rgb(102, 255, 255);
	}

</style>
</head>

<body>

		<input type="password" id="demo">


		<script type="text/javascript">
			console.log('javascript is working')

		function down() 
		{

			document.getElementById("demo").style.width= "500px"
			document.getElementById("demo").style.height="1px"
		}

		document.getElementById("demo").onkeydown = function()
		{
			down();
		}

		function up()
		{
			document.getElementById("demo").style.height="30px"
			document.getElementById("demo").style.width="300px"
		}

		document.getElementById("demo").onkeyup = function()
		{
			up();
		}

		</script>


</body>
