Finally the git-shit is done

log in using the credentials.

now whatttt is this Uppercase shell

Okay basically whatever I type in, it becomes an uppercase.

Simple? So I tried looking out for some shell commands that are already in upper-case.

So I went [here](https://ss64.com/bash/) and checked, but what there's no command which is in uppercase. Frrrriccckk !!!!

Then I thought, what if there were no characters itself. Turns out there were no commands with special chars or numbers. 

So then what else could we do. NOTHING. Oh wait we could get out of this stupid shell.

Then I got an idea. What if we created a script to enter a normal shell. But we cant access anything here. So time to go back to the previous level

There in /home/bandit31 we can look at files

then I did an `ls -la`

And shit there was no need to do use upperscript shell. The root user was bandit33. So we can use it to access the password from bandit33.

So I did an `su bandit32` and entered the password

And then goto /etc thing and find the password 

And you are done

**OR**

Also you could use `$0` command it seems to escape from the uppershell. Then you could basically escape to the normal shell. 

And do the same thing as I did earlier and YEAH We are done with bandit
