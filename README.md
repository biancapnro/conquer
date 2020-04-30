# conquer
Telas para Escola Conquer
<!DOCTYPE html>
<head>
	<link rel="shortcut icon" href="images/logoblack.png">
	<title>Training Conquer</title>
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css"
		integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">
	<link href="http://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">
	<link href="css/global.css" type="text/css" rel="stylesheet">
	<link href='https://fonts.googleapis.com/css?family=DM Sans' rel='stylesheet'>
	<script type="text/javascript" src="js/login.js"></script>
</head>
<body>
	<section class="logo"></section>
	<section class="container-fluid header">
	<img src="images/bg.png">
	<section class="row">
			<div class="bgg"></div>
			<h1 class="titulo">
					<span class="p1">Welcome to the </span>
					<span class="p2"><span class="p3">Jungle </span></span>
					<span class="p4">Training</span>
			</h1>
			<h2 class="text1">
				<span class="p1">OU VAI OU VOA</span>
			</h2>
			<h3 class="text2">
				<span class="p1">Meus Cursos</span>
			</h3>
			<form class="form-container" id="form">
				<div class="input-container">
					<i class="fa fa-envelope icon"></i>
					<input type="email" class="fc1" id="email" placeholder="Email" required autofocus>
				</div>
				<div class="input-container">
					<i class="fa fa-lock icon"></i>
					<input type="password" class="fc2" id="password" placeholder="Senha" required autofocus>
				</div>
				<div class="fc3" id="error"></div>
				<button class="submit" id="submit" onclick="validaLogin();"></button>
			</form>
	</section>
</section>
</body>
</html>
