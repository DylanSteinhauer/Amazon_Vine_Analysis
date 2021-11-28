# Amazon_Vine_Analysis
## Purpose
The purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members. To do this, I 
used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.
## Results
![deliverable2_part1](https://user-images.githubusercontent.com/87148177/143724633-b081865e-f654-4341-96e7-61908a33813d.png)\
![deliverable2_part2](https://user-images.githubusercontent.com/87148177/143724635-6d41a90f-9be4-4960-9247-7e14f9de1ad5.png)
## Summary
This analysis does not find any positivity bias for reviews in the Vine program. 
Out of the 40,565 total reviews, only 94 of them were from paid vine reviews. While there were a greater percentage 
of 5 star reviews for paid (51.06%) than unpaid (38.70%), this is a relatively small differential and the sample size of 
paid reviews is too small to conclude that there is positivity bias.
One additional analysis we could do to get a better idea of potential bias would be to look at 1 star reviews as well. 
Determining if there are significantly more 1 star reviews in the unpaid category could give a better idea 
as to whether there is bias.
