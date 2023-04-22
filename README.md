# AddSubMovZX
coded in x86 assembly language <br>
This program implements addition and subtraction operations for different bit sizes only on the 32 bit register <br>

The following directions where given:
1) add three predefined numbers together and store in bSum
2) Subtract the first number from the sum of the second and third number. Store the results in bDiff.
3) add bSum and bDiff. Store the results in bResult. <br>
Repeat this process for similarly-named WORD and DWORD operands <br>
Use only the MOV, ADD, and SUB commands in ONLY the 32 bit register to manipulate data. <br>
Finally use the 32 bit register to add all results together. Store the results in dwTotal. <br>

In order to run this code you will need to modify and upload to vsCode or download the following zip files: <br>
<b> masm615.zip</b> <br>
<b> Irvine.zip</b> <br>
<b> Satterley_ASM.zip</b> <br>
and store them in the C drive of your device. <br> 

Then go to the search bar at the bottom of your screen and type the letters CMD to open your command prompt. <br>
Next type or copy and paste the following lines to create an executable file and execute the program. <br> 
<b> cd C:\Satterley_ASM </b> <br>
<b> make32 Meghan-Satterley_AddSubMovZX </b> <br> <br>
You should see the following files appear in your folder directory <br> 
![make32_AddSubMovZX](https://user-images.githubusercontent.com/114275745/233754744-c96de394-3172-40da-985e-b21a9ebe09d5.png)
<br> <br> Lastly type the following line to execute the program <br>
<b> Meghan-Satterley_AddSubMovZX </b> <br> <br>
The following will result if executed correctly <br>
![AddSubMovZX_Exe](https://user-images.githubusercontent.com/114275745/233754735-11051856-0194-44e8-a867-b93dfd9e52cd.png)
<br> <br> The complete assembly program has 19 variables (6 in each set of 3 different data sizes and one overall total), 
<br> three separate memory dumps of sum, diff, and result 
<br> plus one memory dump of the total (10 total memory dumps)
<br> the purpose of this program is to show an understanding of basic data and 32 bit register manipulation.
