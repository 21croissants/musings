# monit

Log to /var/log/messages

# Add an existing user to a group

```
sudo usermod -G GroupeName UserName
```

Then reload the shell or ssh again to see the changes.

# Which processes have a file opened? 

In linux if you remove a file, but another processes still has the file open the space won't be released until the processes is restarted. You can see this with the output of lsof | grep staging.log With this information you can get the PIDs of the processes and check to see what processes still have the file open with a command like ps faux | egrep '1032|7298|12001|17364'.

# screen

## Start a session with name "staging"

	screen -S staging 
    # to detach: CTRL + A D
    
## Go back

	screen -x staging

## Rename session to make it easier to navigate

	CTRL + a A

    
## Navigate btw screens

	CTRL + A "
    
## Terminate screen session

	CTRL + D
	
# What's causing all the disk activity on OS X?
	sudo iotop -C 5 12
	
	
