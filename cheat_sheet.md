##Cheat Sheet

---

##Command Line Basics & Git

The terminal (command prompt on Windows) is the developer way of navigating your computer. You are probably used to using the graphical interface provided (Finder on a mac and MyComputer on Windows).

Here is a quick reference for some of the most common commands you will use in this class. 
Remember when you see ```“$”``` or ```“C:\>”``` in these notes that is the prompt, don’t type it.

 		$  MAC
		C:\>  WINDOWS
		
---

####Navigation


How do I get into a folder?

  		$cd folder_name
		C:\> cd folder_name

Use quotation marks if your folder name has spaces.

How do I get to the parent folder?

		$cd ..
		C:\> cd ..

How do I see what is in the folder?

		$ls
		C:\> dir


How do I know what folder I am in?

		$pwd
		C:\> cd

How do I create a new folder?

		$mkdir folder_name
		C:\> mkdir folder_name

---

####Deleting - (Proceed With Caution)

How do I delete a folder?

		$rm -r folder_name
		c:\> rmdir folder-name

How do I delete a file?
		
		$rm -f file_name
		C:\> del file_name

How do I move a file?

		$mv file_name folder_name
		C:\> move file_name folder_name
The file is removed from the old location and moved to the new one.

You can rename a file the same way

		$mv old_name new_name
		C:\> move old_name new_names

---

##Tips, Tricks & Motivation

Here are some keyboard shortcuts in the command line to help you keep up (note: not all command line apps support these):

**Tab Completion**: Press Tab to complete folder and file names                                                       

**Control + a**: Go to the beginning of the line                                                                      

**Control + e**: Go the the end of the line                                                                      

**Option + b**: Move back one word

**Option + f**: Move forward one word

**Up/Down Arrow Keys**: Repeats previous commands                                                               

**Control + w**: Delete last word typed

**Control + u**: Delete last line typed

**Control + y**: Paste last deleted item

**Control + l**: Clear the screen        
 
---

##Git Diagrams and Pictures

Fork Button

![Fork Button](/assets/GitHub/fork_button.png)

Pull Request Buttons

![Pull Request](/assets/GitHub/pull_request_button.png)

---

##Still Feel Lost? 
###Catch Up With These Resources

-	[Command Line Crash Course](http://cli.learncodethehardway.org/book/)

-	[GitHub Cheat Sheet](https://na1.salesforce.com/help/doc/en/salesforce_git_developer_cheatsheet.pdf)

-	[Intro to Git Videos](http://git-scm.com/videos)

-	[Intro to Git Tutorial](http://www.codeschool.com/courses/try-git) from Code School.