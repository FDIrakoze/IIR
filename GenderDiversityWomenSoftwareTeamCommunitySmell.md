# RESUME

> **Presence of women usually reduce the amount of community smells**

## Introduction

 Community smells have been also linked to code smells, indications of poor design, coding, and implementation choice  
 The composition of a software team affects the presence of community smells, and in particular, about the impact of gender diversity on them

More gender diverse teams have been showb to be more productive than less gender divers ones 

## Methodology 

The goal of the study is to assess to what extent gender diversity and participation of women in software communities inﬂuence the health of such communities
We expect the number of community smells to be reduced based on evidence on the role of gender balance 

Research questions : 

> RQ1 :  **How does the number of community smells differ in teams without women and in teams with women?**  
> RQ2 :  **To what extent does the presence of women within teams inﬂuence the number of community smells?**

The context of the study was represented by software communities and community smells.

Their are many projects used for this study : 
    -> Akretion 
    -> Moodle 
    -> Django 
    -> Symfony
    -> ...

20 projects with with only men teams were selected, and the same amount of project were selected with mixed teams 



**4 patterns for comunity smells were selected where they have characteristics for which the presence of women might consistently affect their emergence :**  
- Organizational Silo : cases where a community presents siloed areas that essentially do not communicate with each other
- Black Cloud :  excessive information overload due to the lack of structured communication
- Lone Wolf :  unsanctioned or deﬁant contributors who carry out their work irrespective or regardless of their peers
- Radio Silence :  "unique boundary spanner", one member interposes herself into every formal interaction across two or more sub-communities with little or no ﬂexibility to introduce other parallel channels

> Detecting community smell :  

    - RQ1 : 
    Computed statistical metrics such as minimum, maximum, mean, median, ﬁrst, and third quartile of the distribution of community smells in the two groups with the aim of investigating whether nongender-diverse teams present a higher number of community smells with respect to gender-diverse ones

    - RQ2 : 
    Definition of a statistical model relating the set of community metrics present in the dataset exploited [11] to the detected smells. 
    Definition of the modeling approach : 
        > Independent Variables : Number of women in a team
        > Response Variables : number of community smells as identiﬁed by CODEFACE4SMELLS
        > Control Variables :  Number of Committers, Number of Commits,  Team size, turnover, project age, ...
        > Statistical Models Contructions

    
## Results 

    - RQ1 : 
     Non-gender diverse teams have a statisticallyhighernumberofcommunitysmellswithrespect to gender-diverse teams. This indicates the presence of factors within gender-diverse teams that possibly inﬂuence the presence of community smells.

    - RQ2 : 
    Gender diversity and women participation are relevant factors for Black Cloud and Radio Silence, while we found only partial relations between the variables of interest and Organizational Silo and Lone Wolf

## Discussion 

The diversity of teams appears much more statistically signiﬁcant for the Black Cloud community smell, which is connected to information overload

Similarly, the more prominent role of women is beneﬁcial to reduce a somewhat opposite condition, i.e., the Radio Silence smell, connected to miscommunicating sub-communities.

## Conclusion

This article reports on empirical evidence to shed light over the connections between the presence of women and the manifestation of community smells.
Results indicate a considerable and consistent role as mediators for the presence of woman professionals with respect to the occurrence of community smells, however, such presence seems to mediate more strongly with respect to those smells which affect the quality of communication (e.g., Radio Silence effect) as opposed to how the organizational structure is arranged or the quantities involved (e.g., Organizational Silo effect). 

There is a positive effect of gender balance in software teams, but not equally for all organizational circumstances. 