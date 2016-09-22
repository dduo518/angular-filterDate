# angular-filterDate
自定义计算日期过滤器
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>时间过滤指令</title>
	<script type="text/javascript" src='angular.js'></script>
	<script type="text/javascript" src='angular-dir.js'></script>
	<style>
		td{border:1px solid #CCC;width:300px;text-align: center;}
	</style>
</head>
<body ng-app='app' ng-controller='filterDate'>
	<table>
		<thead>
			<tr>
				<td>正常</td>
				<td>outoDate</td>
				<td>outoDate :'countDay'</td>
				<td>outoDate :'detail'</td>
			</tr>
		</thead>
		<tr>
			<td>{{time}}</td>
			<td>{{time | outoDate}}</td>
			<td>{{time | outoDate :'countDay'}}</td>
			<td>{{time | outoDate :'detail'}}</td>
		</tr>
		<tr>
			<td>{{time1}}</td>
			<td>{{time1 | outoDate}}</td>
			<td>{{time1 | outoDate :'countDay'}}</td>
			<td>{{time1 | outoDate :'detail'}}</td>
		</tr>
		<tr>
			<td>{{time2}}</td>
			<td>{{time2 | outoDate}}</td>
			<td>{{time2 | outoDate :'countDay'}}</td>
			<td>{{time2 | outoDate :'detail'}}</td>
		</tr>
		<tr>
			<td>{{time3}}</td>
			<td>{{time3 | outoDate}}</td>
			<td>{{time3 | outoDate :'countDay'}}</td>
			<td>{{time3 | outoDate :'detail'}}</td>
		</tr>
	</table>
</body>
</html>
