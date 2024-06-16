-> Gmail Setup On CentOS(7 or 9)

   Two Steps:
     Step1: Get Gmail Id and Gmail App Password
     Step2: Configure Gmail Setup on CentOS

-> Get Gmail Id and App Password

     Gmail ID: xyz from xyz@gmail.com
     Gmail App Password:
     Open: Gmail 
     Open: Mange Your Google Account
          Select Security -> Goto How you sign in to Google -> Enable 2-Step Verification
     Open: Mange Your Google Account
          Select Security -> Goto How you sign in to Google -> Select 2-Step Verification and Generate App Password

-> Configure Gmail Setup On CentOS

    Step1: Enable systemctl if you are using CentOS from WSL
    Step2: Small Difference between CentOS 7 and 9
    Step3: Follow the Steps from Document
   
-> Basic Steps To Develop/Write And Execute Bash Shell Script
    
    Step1: Get Requirement & its required commands
    Step2: Choose Shell Type ( in our case bash) and find the location of shell : which bash
    Step3: Open file using vi/vim editors (ex: vi firstScript.sh) on Your Linux/Unix/Mac OS
          Note: .sh extension is not mandatory 
    Step5: Write Shebang line ( #!/bin/bash) as a very first line in script
    Step6: Place List of Commands in Sequence and save the file
    Step7: Provide the execution permissions for the script using chmod (example: chmod u+x scriptName)
    Step8: Run the script as follows
          ./scriptName
          Or
          /completePathOfTheScript example: /home/devopsScripts/scriptName
     