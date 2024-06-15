Introduction
 - What is a Shell ?
  - The Shell is the Linux Command Line Interpreter, Shell executes the commands/scripts
  - There are different types of shells(interpreters) to execute commands/scripts in Unix/ Linux
  - Environment
  - #cat /etc/shells
    /bin/sh
    /bin/bash
    /user/bin/bash
  - The most popular and advanced shell is “bash”
 - What is a Shell Script ?
  - Shell Script is a sequence of commands pasted in a text file.
  - Example: Versions info of java, git, Jenkins, nginx, Docker/Kubernets, Ansible etc…
             java -version
             docker --version
             ansible --version
             #cat getDevOpsToolsVersions.sh
             java -version
             docker --version
             ansible --version
 - Why we need to develop shell scripts ?
  - To Automate repetitive tasks in our Unix/Linux Environment.
- We do release/deployment/patching on DevOps Tools – Week Ends
- So, just want to verify the all-DevOps Tools Versions info on every Monday

- Examples:
 - Send some DevOps tools versions Report to compliance team @ Every Friday
 - Versions info of java, git, Jenkins, nginx, Docker/Kubernets, Ansible etc…
 - Find Log Files Between Two Dates
 - Monitoring Application(s) or Tool(s) or File System Usage
 - Monitor xyz Log Directory and if any logs are not generating in last 24hrs then trigger a mail
 - Monitor Micro- Services and Send Automatic Email Alerts When Application are Down
 - Monitor Jenkins and Send Automatic Email Alert When Application is Down
 - Monitoring File System Usage and Send Automatic Email Alert When Your File System Usage is more than threshold let say 90%
 - Shell Scripting is a great way to Automate repetitive tasks in our Unix/ Linux Environment.




            
