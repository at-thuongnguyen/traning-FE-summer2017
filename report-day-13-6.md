
# Daily report

@(13/6/2017)
## Variables:
- Global Variables:
	- Begin	with	$
	- Thought program
	- Change value
- Instance Variables
	- Begin with @
	- Prosess in 1 object

- Class Variables
	- Begin with @@
	
	 ```ruby
	  Class Cus
			@@no_of_cus=0
			def initialize(id)
				@cus_id=id
				@@no_of_cus+=1
				end
			def dis
			end
			def total()
				puts "#@@no_of_cus"
			end
		end
		cust1=Cus.new("1")
		cust2=Cus.new("2")
		cust1.total()
		cust2.total()
		```
- Local Variables
	- In a function
		```r
		i=1
		loop do 
			puts"#{1}"
			i+=1
			break if i>50
			
		end
		```
- Ruby consistant
```ruby
		class Exam
			VAR1=100
			VAR2=200
			def show
				puts"#{VAR1}"
				VAR1=400
				puts"#{VAR2}"
			end
		end
		object =Exam.new()
		object.show
```
Loops
##	for loops
- For loops
```ruby
		for i in 1..50
			puts"#{i}" if i.odd?
		end
```
- While loops
```ruby
		i=1
		while i<=50
		 	puts i if i.even?
		 	i+=1
		end
```
- Until loops
- Loop loops
- .time inerator loop
```ruby
		 5.time do
		 puts "hello"
		 end
```
##Methods
```ruby
	def method_mane
	def what_up (greeting, *bros)
		bros.each{|bros|  puts "#{greeting}, #{bros}!"}
	end
	what_up("what up", "J","b","k")
```
