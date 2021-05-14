# A Case Of Sour Greps !?!

In your journey of command like domination GREP is definetly a tool that should be in your toolbox at all times. If you have not tried it yet let me introduce you to my friend GREP before you have a case of sour greps! 



While this article is not meant to guide you through all the options of grep, it aims to share the most important and frequently used ones. Enough to allow you to sift through effeciently and get what you need in a matter of seconds. Also while grep is indeed powerful it's power can be significantly increased when used with some other commands. Read along to find out more...




1. Common Frequently used options

- v Once you use this option grep will show you everthing other than the text followed by *v*. A simple example would be to run the two below commands 

		df -h

and 

		df -h | grep -v tmpfs

The second command with grep gives a better and much clearer ouput of what is required. Check it out. 


- i An important option which allowd grep to be insensitive to case size of strings. 


- E The most important option which allows us to use Regular Expression


