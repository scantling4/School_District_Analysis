# School_District_Analysis

## Overview of the School  District Analysis

### Purpose

The purpose of this analysis was to help, Maria, who is the chief data scientist for a city school  district, to analyze information from a variety of sources and formats. She was tasked with preparing all standardized test data for analysis and to provide insights and patterns. These can be used to inform decisions regarding school budgets and priorities. FERPA had to be kept in mind while completing this analysis because it protects the privacy of student records and we handled such data in this analysis. Some of the data (Thomas High School’s ninth graders grades) was altered. In order to uphold state-testing standards, we helped Maria remove the data from the corrupted data and we re-ran the initial school district analysis. 

### Results 
-The district summary was not affected by the changes.
-The school summary changed as a result of removing the 9th grade scores from Thomas High School. 
-Replacing the ninth graders’ scores improves Thomas High School’s performance drastically in comparison to other schools. They are ranked second amongst the highest scoring schools. 
-Replacing the ninth-grade scores did not affect the math and reading scores by grade because a NaN value stood in place of the altered score. 
- The % passing for math, reading, and overall all increased in the bin containing the spending ranges $630-$644 (per student). This is a result of the spending per student staying the same despite removing the 9th grades reading and math scores, yet the % passing rates increased.
-Because Thomas High School is a medium sized high school (1000-2000 students) as defined by the analysis metrics, the % passing math, reading and overall all increased for the medium sized bin because of the removal of the ninth grade grades. 
-Because Thomas High School is a charter school, the % passing math, reading and overall passing rates for charter schools increased. 

### Summary
There were a few big changes as a result of replacing reading and math score for ninth grade at Thomas High School. One major change is the % passing reading went up significantly: from 69.7% to 97.0%. Another major change is the % passing math went up significantly as well. It went from 66.9% to 93.2%. Thus, a third change was that the percent overall passing  went up from 65.1% to 90.63%. As a result of this, Thomas High School’s performance drastically in comparison to other schools and they were ranked second amongst the highest scoring schools. The % passing for math, reading, and overall all increased in the bin containing the spending ranges $630-$644 (per student). This is a result of the spending per student staying the same despite removing the 9th grades reading and math scores, yet the % passing rates increased. Because Thomas High School is a charter school, the % passing math, reading and overall passing rates for charter schools increased. The removal of the ninth grades math and reading scores affected the analysis- specifically the passing percentages. 
