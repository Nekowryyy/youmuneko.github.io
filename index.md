<html>
<head>
    <meta charset="utf-8">
	<title>YoumuNeko</title>
    <link rel="stylesheet" href="/live2d/css/live2d.css" />
</head>
<body>
	<h1>未完工</h1>
	<a href="http://106.75.240.191/">博客已部署至服务器，点此访问</a>
    <div id="landlord">
    <div class="message" style="opacity:0"></div>
    <canvas id="live2d" width="280" height="250" class="live2d"></canvas>
    <div class="hide-button">隐藏</div>
</div>
<script type="text/javascript" src="https://cdn.bootcss.com/jquery/2.2.4/jquery.min.js"></script>
<script type="text/javascript">
    var message_Path = '/live2d/'
    var home_Path = 'https://youmuneko.github.io/'
</script>
<script type="text/javascript" src="/live2d/js/live2d.js"></script>
<script type="text/javascript" src="/live2d/js/message.js"></script>
<script type="text/javascript">
    loadlive2d("live2d", "/live2d/model/tia/model.json");
</script>
</body>
</html>
