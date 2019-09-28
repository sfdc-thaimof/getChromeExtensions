# getChromeExtensions 
  Get all of currently installed chrome extensions from all users and profiles.
  </br>
  Available for MacOS, Linux and Win10!
  </br>
  -->  On Linux it will also extract all of the domains and IPs which are inside the js/json/txt/html files of the extensions


## On MacOS/Linux, open terminal and run:
   
  	chmod u+x getChromeExtensions.py
  	./getChromeExtensions.py
   
    
In order to get information from all users, it should run with "sudo":</br>
  
  	sudo ./getChromeExtensions.py
   
    
## Please note that "requests" library is required
 
## On Win10, open powershell and run:</b>
    
    ./getChromeExtensions.ps1
    
In case you get an error regarding "Execution Policy", just run:
    
    powershell.exe -executionpolicy bypass -file FULLFILEPATHHERE
    
For example:
    
    powershell.exe -executionpolicy bypass -file "c:\cyberiko\getChromeExtensions.ps1"
    
In order to get information from all users, it should run with admin privileges (Run As Administrator) 
  


## By Tomer Haimof
