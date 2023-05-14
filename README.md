<div class="header" align="center">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZjYzODJmNDM5YTJjMjI1OTk3NDNiYjI4NWNjMWIzZWYzN2FkNWNmNCZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/hR6Q01jCXOr31wctJw/giphy.gif"
        width="200">
    <h2>Hi, my name is Aarón 🤓</h2>
    <h3>I am a software developer, and I am always looking to learn new
        technologies. I enjoy working on challenging projects and collaborating in teams to achieve effective solutions.
        I am currently in constant training to improve my skills and keep growing as a professional.</h3>
</div>
<div id="badges" align="center">
<a
    href="https://twitter.com/_daguirre00" target="_blank">
    <img src="https://img.shields.io/twitter/url?color=aqua&label=_daguirre00&logo=twitter&logoColor=aqua&style=for-the-badge&url=https%3A%2F%2Ftwitter.com%2F_daguirre00" alt="Twitter Badges">
</a>
    <a href="https://www.facebook.com/aaronel92.aguirre/" target="_blank">
        <img src="https://img.shields.io/twitter/url?color=aqua&label=Aaron%20Aguirre&logo=facebook&logoColor=aqua&style=for-the-badge&url=https%3A%2F%2Fwww.facebook.com%2Faaronel92.aguirre%2F"
            alt="" />
    </a>
 
</div>

------
## 🧑🏽‍💻 About Me :

- 💼 I am currently developing my portfolio 
- 💼 I am currently developing my portfolio 
- 💼 I am currently developing my portfolio 
- 💼 I am currently developing my portfolio 
- 💼 I am currently developing my portfolio 

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>My GitHub Profile</title>
	<style>
		body {
			background-color: black;
			color: white;
			font-family: monospace;
			font-size: 24px;
			overflow: hidden;
		}
	</style>
</head>
<body>
	<div id="intro"></div>

	<script>
		var text = "Hi, my name is Aarón";
		var intro = document.getElementById('intro');

		function typeWriter(text, i, fnCallback) {
			if (i < text.length) {
				intro.innerHTML += text.charAt(i);
				setTimeout(function() {
					typeWriter(text, i + 1, fnCallback)
				}, 100);
			}
			else if (typeof fnCallback == 'function') {
				setTimeout(fnCallback, 1000);
			}
		}

		function startTextAnimation() {
			if (typeof text === 'string') {
				typeWriter(text, 0, function(){
					// Agrega un salto de línea después de la animación del texto
					intro.innerHTML += '<br><br>';
				});
			}
		}

		startTextAnimation();
	</script>
</body>
</html>
