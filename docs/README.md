
# getChromeExtensions 
  Get all of currently installed chrome extensions from all users and profiles.
  </br>
  Available for MacOS, Linux and Win10!
  </br>
  --> On Linux it will also extract all of the domains and IPs which are inside the js/json/txt/html files of the extensions

  <a href="https://github.com/cyberiko/getChromeExtensions">Go to github repo!</a>

  <b>On MacOS/Linux, open terminal and run:
  </b>
</br>
   
  	chmod u+x getChromeExtensions.py
  	./getChromeExtensions.py
   
    
  In order to get information from all users, it should run with "sudo":</br>
  
   
  	sudo ./getChromeExtensions.py
   
    
   <b>Please note that "requests" library is required</b>
</br>
 
</br>
   <b>On Win10, open powershell and run:</b>
</br>
    
    ./getChromeExtensions.ps1
    
   In case you get an error regarding "Execution Policy", just run:
</br>
    
    powershell.exe -executionpolicy bypass -file FULLFILEPATHHERE
    
   For example:
</br>
    
    powershell.exe -executionpolicy bypass -file "c:\cyberiko\getChromeExtensions.ps1"
    
   In order to get information from all users, it should run with admin privileges (Run As Administrator) 
  


# By Tomer Haimof
