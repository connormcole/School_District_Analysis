# School_District_Analysis

## Overview
The following analysis gathered various summary statistics after adjusting Thomas High School's 9th graders' scores out due to suspected cheating.

## Results
### District Summary Changes
- Average Math Score went from 79.0 to 78.9.
- Average Reading Score remained the same at 81.9.
- % Passing Math went from 75% to 74.8%.
- % Passing Reading went from 86% to 85.7%.
- % Overall Passing went from 65% to 64.9%.

#### Original District Summary
![district_summary_original](https://user-images.githubusercontent.com/92554586/143796895-cf994237-70bb-44d8-892b-6cf1ab6c0ecb.png)

#### Updated District Summary
![district_summary_updated](https://user-images.githubusercontent.com/92554586/143796935-638c78b3-b775-4a4e-8697-23f7a0ef3c80.png)

### School Summary Changes
- The average math score, average reading score, % passing math, % passing reading, and % overall passing for Thomas High School had very slight changes.

#### Original School Summary
![school_summary_original](https://user-images.githubusercontent.com/92554586/143798196-4d52818a-78ac-42a2-8c3d-f9ada6eeba3c.png)

#### Updated School Summary
![school_summary_updated](https://user-images.githubusercontent.com/92554586/143798208-5b3daf66-5fde-4f92-acaa-0d4a91340a2e.png)

### Thomas High School Performance 
After changing the Thomas High School 9th graders' scores to "NaN", all of the categories were minimally affected. Thomas High School's performance relative to the other schools stayed almost the same even after the change. 

### Other Categories
- The only change in math and reading scores by grade was Thomas High School's 9th grade scores for both categories - they were changed to NaN.
- When rounded to one decimal place, the average scores and percentages grouped into spending range bins remained unchanged.
- When rounded to one decimal place, the average scores and percentages grouped into school size bins remained unchanged.
- When rounded to one decimal place, the average scores and percentages grouped into school type bins remained unchanged.

## Summary
Replacing Thomas High School's 9th graders' scores with NaN affected the following district categories:
- Average Math Score went from 79.0 to 78.9.
- % Passing Math went from 75% to 74.8%.
- % Passing Reading went from 86% to 85.7%.
- % Overall Passing went from 65% to 64.9%.

All other changes were minimal due to such a small portion of the population being changed.
