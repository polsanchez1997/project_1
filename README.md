# README: PROJECT 1

## OVERVIEW

https://www.canva.com/design/DADwK32mGI4/hYVzoVxlMFcD64fwkkutPA/edit

This project focuses on developing skills in data cleaning and initiating data visualization. The dataset used pertains to shark attacks, and the analysis revolves around three key questions.

## LIBRARIES

The following Python libraries were utilized for this project:

* Pandas
* Numpy 
* Matplotlib
* Seaborn 

## QUESTIONS

This project is based on these three questions: 

a) What causes more deaths: provoked or unprovoked attacks?
b) At what time of the day do sharks attack the most?
c) Which activity causes more attacks?

## PROCESS

1) Exploring the dataset.
2) Cleaning and transforming the dataset.
3) Visualization so we can answer the questions
4) Getting to conclusions

## DEVELOPMENT

### a) What causes more deaths: provoked or unprovoked attacks?

We have separately analized the data in absolute and relative terms:

!countplot_provoked_unprovoked.png

!death_when_attack_provoked.png
!death_when_attack_unprovoked.png

In summary, unprovoked attacks are more frequent and tend to result in higher fatalities.

### b) At what time of the day do sharks attack the most?

To do that, we have standarized the data creating three big groups: Morning, Afternoon and Night. After cleaning the data, we got to this plot:

!time_sex_plot.png

Most attacks occur in the afternoon, aligning with shark behavior and human activity patterns.

### c) Which activity causes more attacks?

We have grouped the information to create more generic categories and to better analyze the information.

!activity_plot.png

Most attacks are associated with fishing, surfing, and swimming activities.