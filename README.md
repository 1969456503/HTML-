# HTML-
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>作业</title>
	</head>
	<body>
		<table border="1">
			<tbody>
		<tr>
				<td colspan="2" align="center">信息统计表</td>
			</tr>
		<tr>
			<td> 姓名:</td>
			<td>
				<input type="text" name="userName">
			</td>
		</tr>
		<tr>
			<td>年龄:</td>
			<td>
				<input type="text" age="userAge">
			</td>
		</tr>
		<tr>
			<td>性别:</td>
			<td>
				<input type="radio" name="sex" value=1>男
				<input type="radio" name="sex" value=0>女
			</td>
		</tr>
		<tr>
			<td>爱好:</td>
			<td>
				<input type="checkbox" name="hobby" value="1">旅游
				<br />
				<input type="checkbox" name="hobby" value="2">登山
				<br />
				<input type="checkbox" name="hobby" value="3">健身
				<br />
				<input type="checkbox" name="hobby" value="4">上网
				<br />
				<input type="checkbox" name="hobby" value="5">游泳
			</td>
		</tr>
		<tr>
			<td>学历:</td>
			<td>
				<select name="degree">
					<option value="">--请选择--</option>
					<option value="1">--专科--</option>
					<option value="2">--本科--</option>
					<option value="3">--硕士--</option>
					<option value="4">--博士及以上--</option>
					</select>
			</td>
		</tr>
		<tr>
			<td>自我介绍:</td>
			<td>
				<textarea name="comment" rows="5" cols="30">自我介绍:</textarea>
			</td>
		</tr>
		<tr>
			<td>
				<input type="submit" value="提交">
				<input type="reset" value="重置">
			</td>
			<td>
				<input type="hidden" name="userId" value="1001">
			</td>
		</tr>
		</tbody>
		</table>
	</body>
</html>
