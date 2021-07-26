# School_District_Analysis
## Overview
  We used multiple different data sets to analysis and hopefully better allocate funds to fifteen high schools based on their math and reading scores. Some data we looked at was their overall populations of students, the budget for each school and how much money was allocated per student. We farther analyized how many students passed their reading and/or math tests and how many of these students were in a large, medium or small school.
 
## Results
UNfortunaly, there was some cheating afoot and for the 9th graders at Thomas High School had to have their test scores nullified because of **academic dishonesty.**
Let see how this affected your hours of hard data crunching work.
* How is the district summary affected?
  * The district summary was affected by 0.1-0.2% in the average math scores, the passing math and passing reading respectivly, and overall passing rates dropped as shown by the data frames below, OG meaning original and THS after the Thomas High School 9th graders schores were nulled.
![District_Summary_OG](https://user-images.githubusercontent.com/84158312/126929382-75aebc52-aaa5-43e4-a60c-a38aaa18a700.png)
![District_Summary_THS](https://user-images.githubusercontent.com/84158312/126929408-6d9b6b41-5560-46b6-9523-acd2ab4bf5dd.png)

* How is the school summary affected?
  * While Thomas High Schools average math and reading scores werent really affected, their passing rate fell from over 90% in each category to under 70% in each passing category, as shown by the data frames below.
![Summary_OG](https://user-images.githubusercontent.com/84158312/126929912-11ce449e-3f36-48ec-ad8e-75f863786889.png)
![Summary_THS](https://user-images.githubusercontent.com/84158312/126929898-54f42e96-9afa-4d81-a506-0ad07d74dcf2.png)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * They had a much lower amount of passing reading scores compared to most other schools, whereas their passing math scores dipped below the relative performace of the other charter schools, but were similar to some of the much larger distict schools. See Summary data frames above for reference.

* How does replacing the ninth-grade scores affect the following:
    -Math and reading scores by grade
      Obviously, with the entire ninth-grade scores nullified, the results in the entire ninth grade section of Thomas High School as Nan for both their math and reading scores respectfully.
    ![Math_scores_OG](https://user-images.githubusercontent.com/84158312/126931282-6122874d-8381-403f-b1df-76c2bc16b506.png)
    ![Math_Scores_THS](https://user-images.githubusercontent.com/84158312/126931309-adc217bd-bb49-469e-85c5-c4970e5d666e.png)
    ![Reading_Scores_OG](https://user-images.githubusercontent.com/84158312/126930367-780de52d-ffd0-4a3c-b7da-5b2d486f0084.png)
    ![Reading_Scores_THS](https://user-images.githubusercontent.com/84158312/126930377-28c6806c-7c9f-4340-80cb-8621f0bc3256.png)

    -Scores by school spending
      Schools within the $630 - $645 range saw a drop in all passing rates as a result of the nullified scores of Thomas High School. See below:
      
     ![Spending_Per_Student_OG](https://user-images.githubusercontent.com/84158312/126931786-5905b87b-a85f-4160-ba62-488e8565e407.png)
     ![Spending_Per_Student_THS](https://user-images.githubusercontent.com/84158312/126931805-05738295-acde-4d93-96c2-3b276de3a329.png)

    -Scores by school size
      Since Thomas High School was a medium sized school, all the passing rates fell a few points as a result of the nullified test scores. See below:
      
    ![School_Size_Averages_OG](https://user-images.githubusercontent.com/84158312/126931858-2efeec82-7df9-47fe-8ede-e27e7979323a.png)
    ![School_Size_Averages_THS](https://user-images.githubusercontent.com/84158312/126931868-afbfe3e9-7247-4150-a0db-86fbc95a4eed.png)

    -Scores by school type
      Since Thomas High School was a charter school, the charter schools saw a few points fall from all the passing rates, however their passing rates were sill signifigantly higher than the district schools passing rates, especially for math. Please see below:
    
    ![School_Type_Averages_Original](https://user-images.githubusercontent.com/84158312/126932188-3efab410-d325-49a0-ad86-08db669b4f3c.png)
    ![School_Type_Averages_THS](https://user-images.githubusercontent.com/84158312/126932213-227297c1-12c2-439f-ba63-5a1e4882ade7.png)

## Summary
In summary, all the passing rates, math, reading and overall passing rates, dropped as a result of the nuffified scores from the ninth graders of Thomas High School. Since it was a medium sized schools, all medium sized schools passing rates were effected, and since it was within the budget bin of $630 - $645 range, all those rates fell too. What I find interesting, as even taking out a set of scores did not reduce the difference between the passing rates of charter schools and district schools. District schools had a much lower rate of passing, especially for math, in comparision to the charters, dispite the nullified grades.

