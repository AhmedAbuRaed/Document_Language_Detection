# Document_Language_Detection
For testing the Language detector you will find the classes on the following directory 
Document_Language_Detection\out\production\Document_Language_Detection
you will find there two classes trainer Class and Identifier Class. 

The Trainer Class

First you should call the Trainer Class to train your data-set and create the .dat file.
The command should be called as followed : First argument is the trained language name, then the training files for example i will train it using three text files here.
>Java Trainer "Portugues" "PortuguesTrainingFile1.txt" "PortuguesTrainingFile2.txt" "PortuguesTrainingFile3.txt" 
The previous command will create the "Portugues.dat" data-file which is considered the Portuguese data-set.
Note i already trained some languages as you can notice inside the folder.

Identifier Class 

you just have to call the command with the sample files that you want to detect their language. For example:
>java Identifier "sample1.txt" "sample2txt" "sample3.txt"
It will identify the documents languages. you can add more arguments only as file names who are on the same directory.
Sorry i wanted to make a user interface but i am a little busy.
In all cases please only add your sample files on the same folder since i set the working directory as 
Document_Language_Detection\out\production\Document_Language_Detection
Please don't hesitate to contact me for any information.

Ahmed AbuRa'ed

Refferences :
Schmitt, John C. "Trigram-based method of language identification." U.S. Patent No. 5,062,143. 29 Oct. 1991.

