
# Daily report

@(14/6/2017)
##Form
- Using input information about login or register form:
	- Textfile
	- Input
	- Radio: choose a time
	- Textarea
	- Checkbox: switch staged after a click
	- Button
	ex:
``` html
<!DOCTYPE html>
<html>
<head>
	<title>form</title>
</head>
<body>
	<form action="registerPage" method="post">
		<div>
			<label for="name"> User name</label>
			<input type="text" name="name">
		</div>
		<div>
			<label for="Password">Password</label>
			<input type="Password" name="Password">
		</div>
		<div>
			<label for="gender">Gender</label>
			<input type="radio" name="gender" value="male">
			<input type="radio" name="gender" value="female">
		</div>
		<div>
			<label for="content">Content</label>
			<textarea name="content"></textarea>
		</div>
		<div>
			<button>Submit</button>
		</div>
	</form>
</html>
```
- Template engines: use make shorter code than
	- Template: functional HTML modules
	- Data sources: 
		 - Object: list product about: name, img, decs
	- Template engines:
- Coding conventions: code follow the rule

