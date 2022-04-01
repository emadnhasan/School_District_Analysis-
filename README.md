# School_District_Analysis

# Overview
* An analysis of school metrics to determine what impact skewed grades may have had on the district wide results.
* We have been asked to analyze the data further due to a possible discrepancy. The school distirct feels there may be an issue with the 9th grade scores at Thomas High School. We have been asked to reanalyze the data and see what impact this may have on the overall scores over a variety of metrics.

# Results
## District Summary
 Original
![District Original](https://user-images.githubusercontent.com/100659114/161272022-1d6df9f5-90ac-43ed-8fc9-14c71d0436a2.png)
Revised

![District revised (2)](https://user-images.githubusercontent.com/100659114/161273736-07e9606e-c544-47eb-820e-72ff45f0f7a8.png)
* When looking at the average cores throughout the district before and after removing the Thomas High School scores, the difference can be seen as inconsequential. The overall passing percentage changed by less than 0.05%.

## School Summary

Original
![School Original](https://user-images.githubusercontent.com/100659114/161277816-3b683d47-8d3f-4e7b-90fc-43b426a38080.png)


Revised
![School Revised](https://user-images.githubusercontent.com/100659114/161277830-fa22038b-2bf0-48a7-b9f4-a567f555a4ab.png)
* Removing the Thomas High School scores shows to have had a minimal impact on the data for the school as a whole. The overall passing percentage changed by less than 0.5%.
* The change in passing percentage was not substantial enough to change Thomas high School's standing relative to other schools.

## Math And Reading Scores By Grade
Original

![Scores By Grade Original](https://user-images.githubusercontent.com/100659114/161282674-2d5b6bcc-8a29-412a-a946-8baa15384671.png)

Revised

![Scores By Grade Revised](https://user-images.githubusercontent.com/100659114/161281055-5c7a4767-affb-4ddf-a07f-2e1ceabd9bdc.png)
* The only change in this data was the removal of Thomas High School 9th grade numbers. This can be seen as the data is listed as "nan". No other data was impacted by this change.

## Scores By School Spending
Original




![Spending Range Original](https://user-images.githubusercontent.com/100659114/161289483-9a558775-c6e2-4f03-83ef-b4b493dc3286.png)




Revised




![Spending range Revised](https://user-images.githubusercontent.com/100659114/161289488-601d2b45-fb22-43b4-bf5c-807637fa615f.png)

* There was a slight change in the $630-$644 range, which is where Thomas High School is located. However, this change was very small, resulting in less than a 0.1% change. No other data sets were impacted.

## Scores By School Size
Original




![School Size Original](https://user-images.githubusercontent.com/100659114/161292171-e80fc9a8-d07b-46f2-a9aa-fe50f17bc741.png)



Revised




![School Size Revised](https://user-images.githubusercontent.com/100659114/161292177-09f4289b-7ccb-4120-9fcf-fd88fde35690.png)


* The scores for Medium schools saw a slight change. But this was a very small change, less than 0.01%. No other data sets were impacted.

## Scores By School Type
Original




![School Type Original](https://user-images.githubusercontent.com/100659114/161292200-d4dec4c4-bede-4837-b498-493ad551c005.png)


Revised




![School Type Revised](https://user-images.githubusercontent.com/100659114/161292204-50c76bcd-a072-482a-add3-fd1be85b0a56.png)


* Since Thomas High School is a charter school, that was the only grouping that was impacted. The chamge in scpres was again very small, less than 0.1%.


# Summary
Overall the impact of removing the 9th grade scores from Thomas High School did not impact the data greatly. When brokem down into various metrics, small changes can be seen but none represent a substantial shift in data
* District: change of less than 0.05%
* School: change of less than 0.5%
* Ranking: Ranking remained the same
* By Grade: Data was removed
* School Spending: change of less than 0.1% in the group containing Thomas High School
* School Type: change of less than 0.1% in the school type containing Thomas High School

Also to be taken into account is the size of the dataset that was removed. There are 461 9th grade students at Thomas High School. This makes up 28% of the school's students but only 1.2% of the entire district student body. As a result, the removal of this data set had almost no impact on the analysis. 
