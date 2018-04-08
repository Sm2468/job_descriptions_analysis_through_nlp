# job_descriptions_analysis_through_nlp
Text analysis of job descriptions with NERC and regular expressions

Using Natural Language Processing two techniques, Regular Expressions and Named Entity Recognition were used in order to give an insight in the number of vacancies and most requested skills in the United States of America. The dataset from the kaggle competition “US jobs on Monster.com” has been used as input. The new insights obtained could help job seekers to find a job. It is visualized through a word cloud and bar chart. For more information, visit this link: https://goo.gl/jTwbH2 

Many Natural Language Processing tasks are performed in pipelines. The pipeline used in this research is depicted below.
![pipeline jpg](https://user-images.githubusercontent.com/38191121/38473209-57e130bc-3b8c-11e8-86c2-a365475d9b46.JPG)



For the extraction of skills, the code can be found under the file 'extracting_skills_regex'. Along with the dataset (link: https://goo.gl/qVJ2Dk) it is possible to decipher which skills are sought most by employers. The output eventually looks as follows:
(FOTO OUTPUT)


Once you have runned your code and gained output, it is possible to visualize these results by means of a wordcloud. 
The code for this visualisation can also be found on this Github platform.
![skills](https://user-images.githubusercontent.com/38191121/38473067-b1ebd6fa-3b89-11e8-965e-1127831c8092.png)



For the extraction of the locations, you need to use the textfile version of the dataset in order to be able to apply the Stanford NER tagger on the job offers. Once you have applied the code (extracting_locations_NER) on the data, you are able to see in which states most of the job offers are located. 
(FOTO OUTPUT LOCATIONS )


Ofcourse also this result can be visualized properly. By means of a bar chart it is possible to gain more information about the states and their job offers.
![vacancies](https://user-images.githubusercontent.com/38191121/38473057-8a337334-3b89-11e8-9cbc-1ca84367e9b2.jpg)

We hope you found this small tutorial helpful!
