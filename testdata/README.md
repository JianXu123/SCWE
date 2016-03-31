# About Test Data
To evaluate our method, we manually build two datasets in our experiment

**transworddetectdata**
This data set include 161 tranliterated words, and 161 semantic compsitional words, in which transliterated words are tagged as 
type 0, semantic compositonal words are tagged as 1.

The transliterated words are collected from the Internet, semantic compositonal words are the top 161 semantic compostional 
words selected from the output word embedding file.

**chardisamdata**
This data set consist some highly ambiguous Chinese characters. We tagged the type of a word using [online Xinhua Dictionary](
http://xh.5156edu.com/) as our stardard. Cause some of the words are not clearly described in the dictionary. Therefore, if there
exist some words you find the type of them are not correct, feel free to correct us.
