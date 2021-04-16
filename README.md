# C-Programming
Here You can see how I learned C programming Language from beginner to advance level.
abcsds

//Comments are used for the Documentation Purpose.
// Two types of comments

// 1) Single line comment
// 2) Multiline comments



//write a program to display "Welcome OC03 Batch" on output


/* a
d
d
*/


//File inclusion area

#include<stdio.h>                     //<stdio.h>  Stadard Input-Ouptut header file.

                                      //Heder files install like compailor

                                      // Header files are nothing but the pre-define functionality of the language.
                                      // The language features are defined by the header file, thats why we include header files.

                                      /* When we use #include in the program we are  intimating to the compailor that I wish to use 
                                       <stdio.h> header file. */

  // printf();                          //Printf(); function is used to disply the data o output screen
  
  
  
 #Identifiers



  int main(void)                    // Void is written as argument have to pass.   
                                    //The main() function  is called as Entry point function.
  {                               
  printf( "Welcome to World ");     //The functionality of the printf(); function is allready defined
                                    // in the header file <stdio.h>
  return 0;                         //0: Exit_Success    
 
  }                                 //Scope of main.   
                                    //0 is number and it is integer  data type.           

                                    //Convert a high level language program into machine level
                                    // Convertor : Compiler acts as Convertor
                                    /* The process of converting a source code/ high level language code into the 
                                       machine undestable code i.e Machine code is called as compailation process.

                                       Here we can use GCC Comailer -Gnus Compailer colllection 
                                       GCC compailer is used to convert source code to machine code.


   1.Compile the program (gcc programname.c)
   2.Execute the program (./a.exe)  OR (.\a.exe) => Executable File. (OutPut given by compailor) 


*/

/*  The Program Execution Phase- (Compilation Flow). */

**Data Type is the Intimation Given to the Operating System that perticular type of data is going to be used.

-The data type whose size is already define know as Primetative data type.
-Primetative ->The size is Completly define bt the operating system.


             1 byte = 8 bits
             
             int = 4 bytes
             
             float/double => 4bytes/8bytes.
             
             char => 1byte
             
             
             
 
***Variables***
-The names given to memory locations are known as Variables.
-Variable is used to identify the perticular memory location with the Name/Value.


* Indentifiers in C programming .

-Variables are also called as Idenifiers.


*** Format Specifires **

-If the data is to be printed on output screen then the format specifiers is used.

-Some format Speifiers are->

   %d   -Used when the integer data type is used.
   
    %f   -Used when the float data type is used.
   
   
  


    


