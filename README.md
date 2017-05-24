# Statula

***

### Simple terminal-based program for descriptive statistics
##### *Current version: 0.1.3*

Initially developed as a leeway from statistics exam, this small piece of software is supposed to allow quick data analysis of big datasets.
The main focus of this project is speed.

***
#### Usage

In order to perform analysis, just type:
./statula dataset_filename
into your terminal. Data should be contained in text file.
***
#### *TODO*

  * Mathematical statistics

  * Extend fuctionalities in descriptive statistics

  * Extend starting parameters in order to allow for multiple configurations

  * Get around limitations of current language system for help panel*

  * Allow user to specify format in which data should be printed

  * Move file input from goddamned fscanf to something less shitty.

*I think help panel should work even if Statula is unable to load strings from file, however I am not quite sure how can I avoid hard-coding
it into the program itself. 

Tests are written using [Criterion](https://github.com/Snaipe/Criterion) library. Thanks [Snaipe](https://github.com/Snaipe)!
***
#### Starting Parameters
>**--help** / **--h** *Prints simple help panel*  
**--o**  *Open specified file*  
**--s**  *Save result to specified file. Amount of targets must be equal to amount of files opened via --o*  
**--l**  *Print result using specified language (language file has to be present in the current directory.* 
*If there is just one string after "./statula" (not starting with "--"), then it shall be used as a default filename for the session.*
