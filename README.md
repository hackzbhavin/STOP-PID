# STOP-PID-PORTS


Hello this is Bhavin here 

lets have a normal understanding why this file is helpfull. 

1. In MacOS unix some of the commands differ from linux commands and make confusing
2. I have created this file to stop port immediately as soon as you enter its pid

>
Requirement
- terminal access
- pid

------
Version 1
-----


>
1. Go to /usr/local/bin
- `cd /usr/local/bin`

2. Just pull the repo or download and paste in  `/usr/local/bin` directory

3. give the file permission to write ....(use terminal)
- `chmod 777 destroy `

4. now ready to run use `filename` `pid`
-  `destroy 557`


------
to check pid 
------

- `lsof -i -P`
- `lsof -i tcp`


