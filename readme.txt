Some of the progrmas have external resource access using d3.csv call
To load csv file run the host '..\d3\data-set' directory as server in user local machine.

In data-set directory server.py file is there, 
it hosts the current directory as server.
python 3 is required to host the directory as server

cmd:	
	python server.py 	<<port-number>>

example 
	python server.py 	4200
	
after this programs with d3.csv loads files from external resource 
change the existing IP to your system IP
To know your system IP
cmd:
	ipconfig [enter]
	

change this above IP in program and above used port number.
Before running make sure that server is running.