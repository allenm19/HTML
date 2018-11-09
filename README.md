<html>

	<head>

		<title>Wrapper Practice</title>

		<style>

			body {
				background-color: blue;
				}

			/* page wrapper/container code */

			#wrapper /* a wrapper section is commonly used to be the overall page "container" that holds everything on the page */
				{
				background-color: red;
				border-color: blue;
				border-style: dotted;
				border-width: 10px;
				margin-top: 0px; /* distance from top of page */
				margin-right: auto; /* tells the browser to center the page and determine equal margins from the left & right */
				margin-bottom: 0px; /* distance from bottom of page */
				margin-left: auto; /* tells the browser to center the page and determine equal margins from the left & right */
				padding: 2px; /* to give some breathing room so content is not right up against edges */
				height: 100%; /* this is included so the wrapper will take up the entire page */
				width: 1200px; /* you can change this value; obviously your background image shouldn't be wider than this */
				}

			/* CSS for our image will be added below */

			img {
			margin-top:200px;
			margin-left:300px;
			border-color:blue;
			border-style:dashed;
			border-width:5px;
			padding:10px;

			

			}

				
		</style>

	</head>

	<body>

		<div id="wrapper"><!-- div tags are used to refer to sections of a webpage -->

		
			<!-- all of our page content will go in here -->

			<img src="https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwiZrvGo8sfeAhXBJt8KHYi9De0QjRx6BAgBEAU&url=https%3A%2F%2Fwww.inc.com%2Fchris-matyszczyk%2Fthe-sign-outside-gym-said-tired-of-being-fat-ugly-just-be-ugly-what-happened-next-was-surprising.html&psig=AOvVaw1Ml3rIHEv4uBkP6nraScHo&ust=1541872808534652" />


		</div>

	</body>

</html>
