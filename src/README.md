# Train Model

 This code is developed based on CWE, it is avaiable at [CWE](https://github.com/Leonard-Xu/CWE)
 
##Usage
- use make to compile scwe.c
- run ./scwe -train corpus.txt -output-word word.txt -output-char char.txt
- run ./cwe for more parameter information

 ##Input
 
 Segmented chinese corpus encoded in UTF-8
 
 ##Output
 
 **word embeddings**

 > N M
 
 > word#1 [x1, x2, ... , xm]
 
 > ...
 
 > word#N [x1, x2, ... , xm]
   
  **character embeddings**
  
  For our model, the output format of character embeddings is
  
  > N M
  
  >characeter#1 num1 [c1, c2, ... , cm]
  
  >characeter#1 num2 [c1, c2, ... , cm]
  
  >...
  
  >characeter#P numi [c1, c2, ... , cm]
  
  >...
  ,
  
  where numi denote the *i*-th meanings' embedding of character. For code convinience, in our **SCWE+M** model, we allocate a    fix number of array space for each character, for **SCWE** , the fix value is 1.
 
 
