# monit

Log to /var/log/messages

# Add an existing user to a group

```
sudo usermod -G GroupeName UserName
```

Then reload the shell or ssh again to see the changes.

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
	
	
