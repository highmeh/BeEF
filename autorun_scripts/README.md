## README:
This directory contains autorun scripts for the [Browser Exploitation Framework](https://github.com/beefproject/beef).  
  
  
The .json files should be placed in your BeEF directory, under /beef/arerules/enabled/. Note that they'll be parsed and loaded the next time you run ./beef  
  
  
Should you notice any issues, or come up with rules of your own, feel free to submit a pull request.  


## QUICKREFERENCE:  
* Valid Values for Browser Field:  
  * "FF" = Firefox  
  * "IE" = Internet Explorer  
  * "S" = Safari  
  * "O" = Opera  
  * "ALL"  
  *(Need more information on specific browser types? Want to define your own? Check /beef/core/main/client/browser.js)*  

* Valid Values for OS Field:  
  * "Linux"  
  * "Windows"  
  * "OSX"  
  * "Android"  
  * "iOS"  
  * "BlackBerry"  
  * "ALL"  
* Valid Values and Operators for Version field:  
  * "<" Less than version X. Ex: < 7 is below version 7  
  * "<="  Equal to or lesser than version X. Ex: <= is version 7 or lower  
  * "==" Equal to the exact version listed. Ex: == 7 is only version 7  
  * ">=" Greater than or equal to version X. Ex: >= 7 is version 7 or higher  
  * ">" Greater than version X. Ex: > 7 is above version 7  
  * "Digits" Any digit in the version number. Example: 7 could apply to Windows 7, 10 to Windows 10, etc.  
  * "XP" Windows XP  
  * "Vista" Windows Vista  
  * "ALL" Any operating system  
  *(Need more information on specific versions? Want to define your own? Check /beef/core/main/client/os.js)*  

