# Daily report 
`9/6/2017`
## Ruby Language

- **Declaring Variable Name**: 
	- Snake_case: variable name
	- SamelCase and CamelCase: class mane
- **Comments**:
	- Noted funtion
	- Two way: 
		- =begin.... =end: multiple line comment 
		- #: a single line comment 
- **Symbols**: create object 
	- Ex: `new (host: 'redis-push')`
- **Prints,	Puts,	Return,	&	Yield**
	- prints: in tren cung 1 dong
	- pust: in xuong dong
	- return:  lay dong cuoi cung tra ve 
	- yield: 	allows	for	methods to	accept	a block	of	code
- **Control Flow** 
	- if
		>Syntax 1:
			`if condition 
				end `
		syntax 2: 
			`run1 if (condition)`

	- if/else
		> Syntax1:
			`if condition
			else 
			end`
		Syntax 2:
			`(condition)?(run1):(run2)`
		ex:
		
			def kt(n)
			=begin
					if(n%2==0)
						puts "so chan"
					else
						puts "so le"
					end
			=end
					puts (n%2==0)? "so chan":"so le"
			end
			kt(7)
- elsif
- case: 
		> `case
		when condition 
			code
		when condition
		else
	end`

- unless= if not

