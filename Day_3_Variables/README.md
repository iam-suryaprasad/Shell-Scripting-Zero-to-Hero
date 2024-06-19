Introduction to Variables

 -> What is a variable & How to declare and define it ?

     Variables plays an important role in any programming or scripting language
     Variables are used to store data/value
     Variable data/value can be a number / character / string / path/ command output
     Defining Variables:
     Examples:
     p=1
     q=2.5
     r=y
     s=bash
     name=‘bash shell scritping’
     myPath=‘/home/VRTech’
     myCmdOut=$(whoami)

 -> Assigning One Variable Value to Another Variable

     Let say a=4 then b=${a} means a value is assigned to b

 -> Displaying Variable Value
    
     We can use echo, cat

 -> Types of Variables

     Basically, there are three types:

     User-defined-Variables
        These are the variables defined by us while developing shell scripts
     System-defined-Variables
        System-defined-Variables are default variables
        System-defined-Variables can get using set command
        System-defined-Variables are defined in CAPITAL LETTERS
        Note: Its better to avoid user-defined-variables in terms of CAPITAL LETEERS
     Special Variables
        Special variables are like $?,$$,$@,$*….

 -> Rules to define variables 
     
     Variable Name should contain only a-z or A-Z, 0-9 and _ characters.
     Variable Name Should not start with number
     Variable Name length should be less than or equal to 20 characters.
     Variable Names are case sensitive. Means x and X are different.
     Don’t Provide space on either sides of equal symbol while defining variables
     Ex: x=4 is valid
     x =4 or x = 4 or x= 4 are invalid
     No need to declare variable type, Automatically it will take care while executing commands or scripts.
     Use quotes for the data if data consist of spaces
     We can store the output of a command into a variable as follows:
     anyVariable=$(command)
     anyVariable=`command`
     We can assign one variable value/data into another using:
     Name=“Shell Scripting”
     NewName=$Name
     NewName=${Name}
     Better to avoid CAPTIAL Letters For Variables as system variables are in CAPITALS, if you want to use check once
     before creating it
