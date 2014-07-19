![GeneralAssemb.ly](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/raw/master/images/ga.png "GeneralAssemb.ly")

#Rails Workshop
## with Brian Fountain


---

##Course Overview

At a high level, we will focus on developing expertise with the following:

* The command line (terminal)
* Git and GitHub (source control)
* Ruby (programming language)
* Rails (web application framework)


<b>Most importantly, we will strive to teach you how to learn.</b>

---

## About Me: Brian Fountain

![GeneralAssemb.ly](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/raw/master/images/ga.png "GeneralAssemb.ly")
##Lesson 1: Working Like a Developer
###Agenda

*	Setup
*	What is Web Development?
*	Command Line
*	Git & GitHub

---

##Setup
###Getting Your Dev Environment Ready


This class is using Ruby 2.0 (p195) and Rails 4.0 (RC1). 

If you haven't done so already, please take some time now to get your machine set up. 

View the installation guide here:

-	[tinyurl.com/bewd-install](http://tinyurl.com/bewd-install)

---


##Web Development
###The Web Application Stack

![WebStack](/assets/server-side.jpg)

---

##Web Development
###Back-end vs Front-end Development

Let's define a few terms:

* _Web Development_ -> apps built for the web
* _Front-End Development_ -> client / browser code (HTML, CSS, JS)
* _Back-End Development_ -> server-side code (Ruby, C#.NET)

---

##The Command Line
###What is it?

The command line is a terminal giving you direct access to your operating system. You can enter simple commands to perform a variety of functions.

Many of the tasks we need to carry out (such as committing our code) are best performed in the command line.

---

##The Command Line
###How do I start?

For Macs:

* Open the "Terminal" app
* For a better experience, download and install "iTerm 2", which is a replacement app that is slightly better.


For Windows:

* Open the "Command Prompt" application
* For a better experience, try "Console" (http://sourceforge.net/projects/console/)

---

##Git
###What Is GIT?

* GIT is a source control management tool.
* GIT allows you to store and update your code in a structured way.
* GIT includes history of changes you make, so you can create "checkpoints" and track your work better over time.
* GIT allows multiple contributors to work on the same project, and has intelligence to resolve conflicts between changes committed by different people at different times.
* GIT is smart, but can be tricky.

---

![GeneralAssemb.ly](/assets/ICL_icons/Code_along_icon_md.png)
##Git Basics (~30 min)

**_1. Adding git to a folder_**

-	Create a folder and change into it
-	Create 3 files config, log, runner.rb
-	Tell git to add this folder as a new repository
-	Tell git to track the 3 files in the repo


---

![GeneralAssemb.ly](/assets/ICL_icons/Code_along_icon_md.png)
##Git Basics


**_2. Commiting_**

-	Open runner.rb in sublime text
-	Type ‘print “Commited!”’
-	Check the status of the file
-	Look at the difference in the file
-	Tell git it’s ok to commit this file
-	Commit the file

---


##Git vs GitHub

*	<b>Git</b>: A tool used to manage <b>local</b> repositories
*	<b>GitHub</b>: A cloud-based platform used to manage <b>remote</b> repositories

![Using Git](/assets/GitHub/git_general_diagram.png)

---


##GitHub Forks
###Forks Explained
![ Git In Class Diagram](/assets/GitHub/fork_Diagram.png)

---


##Agenda

*	Intro to Ruby & irb
* 	Variables
	* 	Numbers
	*	Strings
	*	Booleans
* 	Method Basics
* 	Conditional Logic
* 	Lab Time

---

##Ruby & Rails
###Ruby

*	An open source programming language
*	Created by Yukihiro Matsumoto (aka Matz)
*	Natural to read and easy to write

###Ruby on Rails

*	Open source web application framework that runs on Ruby
*	Allows you to create web applications that query a database.


![Ruby Images ](/assets/ruby/ruby_img.png )

---


##Ruby & Rails
###Ruby first.

*	It will be easier to navigate a Rails project once we have a basic understanding of Ruby.

![ Karate Kid](/assets/ruby/karate_kid.jpg)

---


##Ruby & Rails
###Ruby Keywords

*	The vocabulary you will need to "_speak_" Ruby: 

ENCODING break case ensure false or redo undef unless FILE LINE class 
def loop for if rescue retry until when BEGIN END alias and begin
defined? do else elsif end in module next nil not return self super then true while yield

###That's It!

---

##Math in Ruby
###Ruby Arithmetic Operators

![Ruby Arithmetic](/assets/ruby/ruby_arithmetic.jpg)

---


##Computational Thinking
###What does it mean to program?

"Learning about “for” loops is not learning to program, any more than learning about pencils is learning to draw."

 –Bret Victor, Learnable Programming

---

![GeneralAssemb.ly](http://studio.generalassemb.ly/GA_Slide_Assets/Code_along_icon_md.png)

###1.	Robot Activity

<table>
  <tr>
    <th>Topic</th>
    <td>Pseudo code, computational thinking, thinking like a computer</td>
  </tr>
 <tr>
    <th>Description</th>
    <td>Write down step by step directions to program a robot to take an order for pizza</td>
  </tr>

     <tr>
    <th>Activity Type</th>
    <td>Group activity in groups of 2-3</td>
  </tr>


	<tr>
		<th>Task Instructions</th>
		<td>
			<ul>
				<li>Form groups of 2-3 people. Your task is to write down step by step instructions for a robot to take a pizza order.</li>

				<li>To accomplish this, write pseudo-code to handle the step-by-step process that a robot would go about to take an order of pizza.</li>
			</ul>
		</td>
	</tr>
</table>


---


##Robot Recap
###Its about changing how you think
*	Think in logical steps to solve a problem
*	Use Ruby keywords to help solve those problems
	*	Conditional Logic
	*	Iteration
	
---


##Programming Fundamentals

---


##Variables
###Store Values

		name = "Salman"
		=> name # "Salman"
		age = 2013 - 1983
		=> age # 30
---


##Data Types

		1.class 					#Fixnum
		1.99.class					#Float
		'Hi! String here!'.class 	#String
		"I'm a string tool".class	#String


---


![GeneralAssemb.ly](http://studio.generalassemb.ly/GA_Slide_Assets/Code_along_icon_md.png)
##Teddit - Strings

Teddit is a news aggregator we will build during this course.
[Answer](../code_alongs/coa_stdnt_teddit_strings.rb)

---


##Variables
### Getting Info From Users

		puts "Can you help me with these groceries?"
		response = gets
		=> program waits for you to type your response
		
---


![GeneralAssemb.ly](http://studio.generalassemb.ly/GA_Slide_Assets/Exercise_icon_md.png)
##Teddit Strings

__Hint:__ Get familiar with using Google to look up syntax.
If you're stuck on syntax write down the steps in English. Focus on thinking like a programmer.

---


##Data Types
###Booleans 

It's either TRUE or FALSE

---


##Boolean
###Logic Operators


![](/assets/ruby/logic_operators.png)


---

![GeneralAssemb.ly](http://studio.generalassemb.ly/GA_Slide_Assets/Code_along_icon_md.png)
##Booleans
[Answer](../code_alongs/coa_stdnt_boolean.rb)

---


##Variables & Data Types
###Recap 

Data Types

*	Number
*	Float
*	String
*	Booleans

Variables

*	Store values 
*	Values can change
*	Can be passed to methods.


---


![GeneralAssemb.ly](http://studio.generalassemb.ly/GA_Slide_Assets/Code_along_icon_md.png)
##Methods

---


##Methods
###Keep your code DRY

* 	Groups program logic together so you don't have to repeat yourself. 
* 	Can pass variables to methods

		
		def say_hello_to(name)
			puts "Hi #{name}"
		end
		
		say_hello_to "John" 
		
	>	outputs: Hi John

----

##Conditional Logic
###Decision Time 

It's either TRUE or FALSE (like booleans)

If you are greater than 18 
you are an adult

	if age > 18
		puts "You are an adult"
	end

---


##Conditional Logic
###Multiple Conditions


	guess = 7 
	if guess > 5
		puts "Too high!"
	elseif guess < 5
		puts "Too Low!"
	else
		puts "You've guessed my hidden digit!"
	end

---

##Conditional Logic
###Multiple Conditions

![truth_table](/assets/ruby/truth_table.png)

---

![GeneralAssemb.ly](http://studio.generalassemb.ly/GA_Slide_Assets/Exercise_icon_md.png)
##Lab Time
* 	Conditional Teddit

---


## Homework
###Secret Number

Let's see a demo of Secret Number

*	HW 1 - Secret Number
	*	Secret number is a game we will incrementally build for homework during the Ruby portion of the course. 
		Players must guess a secret number and your program will provide feedback. 
---


<div id="resources">
## Resources: Variables, Conditionals and Methods



###Cheat Sheet

__Variables__


```ruby
 real_name = "Bruce Wayne"
 secret_identity = "Batman"
```

*String interpolation aka Adding Variables to String*

```ruby
puts "We just spilled the beans #{real_name} is #{secret_identity}"
```

> We just spilled the beans Bruce Wayne is Batman

__Arithmetic Operators__

| Operator | Description | Example (a = 4 and b = 2) | Output |
| ------------- |:-------------| :-----|:-----|
| ```+```      | Addition (add left to right, give result) |  ```puts a + b```  | 6 |
| ```-```      |  Subtraction (subtract left from right, give result)    |  ```puts a - b```  | 2 |
| ```*``` | Multiplication (multiply left by right, give result)   | ```puts a * b```  | 8 |
| ```/``` | Division (divide left by right, give result)  | ```puts a / b``` | 2 |
| ```%``` | Modulus (divide left by right, give remainder) | ```puts a % b```  | 0 |
| ```**``` |Exponent (multiply left by left, right times, give result)  | ```puts a ** b``` | 16 |


__Conditionals Operators__

| Operator        | Description  | Example         (a = 4 and b = 2)  | Evaluated As |
| -------------   |:-------------| :-----|:-----|
| == | Equality |  a == b | false |
| != |  Not Equal | a != b | true  |
| >  | Greater than | a > b | true  |
| < | Less than |a < b | true  |
| >= |Greater than  or equal to | a <= b | false |
| <= |Less than or equal to | a <= b | false |
| <=> |Same value? return 0, less than? return -1, greater than? return 1 | a <=> b | 1 |
| .eql? | same value and same type?| 1.eql?(1.0)| false |


__If Syntax__

```ruby
if (condition)
  code to execute if the condition is true
end
```

```ruby
if var == 20
   puts "Variable is 20"
end
```

__If Else Syntax__

```ruby
if var == 20
   puts "Variable is 20"
else
   puts "Variable is another number"
end
```

__If Else If Syntax__

```ruby
if var == 20
   print "Variable is 20"
elsif var == 30
   print "Variable is 30"
else
   print "Variable is something else"
end
```

__Methods__

__Simple Methods__

```ruby
def method_name
end
```

__Method w/ Parameters__

```ruby
def say (something)
      puts "They said #{something}"
end

 say ("Hello")

=> They said Hello
```

__Running .rb from the terminal__

```
	ruby file_name.rb
```

###Tips, Tricks and Motivation

- What is Programming [video](http://www.youtube.com/watch?v=YCDTYlUWkQE)
- Using Sublime Text 2 [video tutorial](https://tutsplus.com/course/improve-workflow-in-sublime-text-2/)
- [Tricked Out Sublime Text](http://net.tutsplus.com/tutorials/tools-and-tips/sublime-text-2-tips-and-tricks/)
-	[Learning to Program](http://worrydream.com/LearnableProgramming/)


###Still Feel Lost? 
####Catch Up With These Resources

- Intro to Ruby [tutorial](http://www.codeschool.com/courses/try-ruby) from Code School for beginners to wrap your head around programming concepts.
- Beginner Ruby [Tutorial](- http://www.codecademy.com/courses/ruby-beginner-en-d1Ylq?curriculum_id=5059f8619189a5000201fbcb)
- Book [chapter](http://ruby.bastardsbook.com/chapters/ifelse/) on conditionals.
- [Article](http://ruby.about.com/od/control/a/Conditional-Statements.htm) from about.com about ruby conditional statements.
- [Article](http://strugglingwithruby.blogspot.com/2008/11/conditional-statements.html) - More about true and false.
- [Khan academy tutorial](https://www.khanacademy.org/math/geometry/logical-reasoning/e/conditional_statements_and_truth_value) about logical reasoning.
- More on Methods [Videos](https://vimeo.com/gatv/review/67752033/50fc5adfa7) by Steven Nuñez for GA.
	-	password => BEWD_GA 