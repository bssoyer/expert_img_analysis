This rule-based expert system is written in Arity/Prolog32 interpreter. Some preparations must be made before running this program on a Windows box. The following steps may be followed to set up the environment and run the expert system.

1. Download and install the Arity/Prolog32 zipped file.
2. Run the expert system application inside the Prolog interpreter.

##
**1.1 Download and install the Arity/Prolog32 zipped distribution file

To download and install the Arity/Prolog32 interpreter, please visit Peter L. Gabel's website at http://petergabel.info/ArityProlog32/InstallingArityProlog32/. After downloading, set the following system environment variables.

+ C:\ArityProlog32\BIN to your PATH variable
+ C:\ArityProlog32\LIB to your LIB variable
+ C:\ArityProlog32\INCLUDE to your INCLUDE variable

After installing the software, you can run the Arity/Prolog32 interpreter by typing the following command in the command prompt: C:\api32

##
**1.2 Run the expert system application inside the Prolog interpreter

To run the expert system application, imgexp.ari Prolog file, download it from the section on GitHub. Go to the directory where you put the imgexp.ari file after downloading and run the api32.exe interpreter, see Figure 1.

In the interpreter, type in Alt-F and select File > Consult File … In the dialog box that pops up, type in the filename imgexp.ari, see Figure 2.

Now, you can interact with the expert system, trying out various tool combinations using the thresholding method for edge enhancement, See Figufre 3.

                  Figure 1 The Arity/Prolog32 Interpreter
![image](https://github.com/user-attachments/assets/91902556-257e-46c1-8428-44bb589d6661)

                  Figure 2 Consulting a Prolog file to run
![Figure_2_rsz](https://github.com/user-attachments/assets/a16a0ec4-a5f6-4564-89d3-6d05a9e20caa)

                  Figure 3 The Expert System for Edge Detection
![Figure_3_rsz](https://github.com/user-attachments/assets/439df082-fad1-49e3-af15-c5207e27a73a)




