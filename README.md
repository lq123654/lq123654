<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>作业</title>	
			
	</head>
	<body>
		209001002  林巧
		<script>
			document.write('<br><br>三角形<br><br>');
				for(var i=1;i<=5;i++)   
				{
					for(var j=1;j<=5-i;j++)  
					{
						document.write('&nbsp;');
					}
					for(var k=1;k<=i;k++)
					{
						document.write('*'+'&nbsp;');
					}
					document.write('<br>');
				}
			</script>

			<script>
				document.write('菱形<br><br>');
				for(var i=1;i<=3;i++)
				{
					for(var j=1;j<=3-i;j++)
					{
						document.write('&nbsp;'+'&nbsp;');
					}
					for(var k=1;k<=2*i-1;k++)
					{
						document.write('*&nbsp;');
					}
					document.write('&nbsp;');
					document.write('<br>');
				}
				for(var i=2;i>=1;i--)
				{
					for(var j=1;j<=3-i;j++)
					{
						document.write('&nbsp;'+'&nbsp;');
					}
					for(var k=1;k<=2*i-1;k++)
					{
						document.write('*&nbsp');
					}
					document.write('&nbsp;');
					document.write('<br>');
				}
			</script>
			<script>
				document.write('平行四边形<br><br>')
				for(var i=1;i<=5;i++)
				{
					for(var j=i;j<=5;j++)
					{
						document.write('&nbsp;');
					}
					for(var k=1;k<5;k++)
					{
						document.write('*&nbsp');
					}
					document.write('<br>');
				}
			</script>
	</body>
</html>

