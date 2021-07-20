# School_District_Analysis
Utilizing Pandas and Jupyter Notebook for School District Analysis
## Overview of School District Analysis
  * The purpose of this analysis is to compare the overall scores in the school district with and without reading and math grades for Thomas High School ninth graders amidst evidence of academic dishonesty.
## Results
District stats before replacing reading and math grades for Thomas High School ninth graders with NaNs
![Screen Shot 2021-07-20 at 4 49 08 PM](https://user-images.githubusercontent.com/60943801/126400089-94835e47-8f23-4b43-bc1c-5bc5426aa9cd.png)

Stats after replacing reading and math grades for Thomas High School ninth graders with NaNs
![Screen Shot 2021-07-20 at 4 47 22 PM](https://user-images.githubusercontent.com/60943801/126400133-a5e5641e-b972-41c0-8d0b-d54d00b631ed.png)

  * Replacing reading and math grades for Thomas High School ninth graders with NaNs lowered the overall district passing percentage by approximately 0.32%.
  * At the school level (THS), this lowered the overall passing percentage from 90.9% in the PyCitySchools.ipynb analysis, to 65.08% in the PyCitySchools_Challenge.ipynb analysis.
  * Replacing the ninth graders’ math and reading scores with NaNs brings Thomas High School down from 4th to 8th place among the overall passing percentages of schools in the district.
  * Thomas High School before replacement of ninth graders’ math and reading scores with NaNs
  ![Screen Shot 2021-07-20 at 4 31 46 PM](https://user-images.githubusercontent.com/60943801/126398246-07b9a5cb-4067-420c-869b-3065b31dcb97.png)
  * Thomas High School after replacement of ninth graders’ math and reading scores with NaNs
   ![Screen Shot 2021-07-20 at 4 31 57 PM](https://user-images.githubusercontent.com/60943801/126398310-7ad08908-ce66-4348-b0ef-97b1b2a37843.png)
### Effect of replacing ninth grade scores on different variables:
  * Math and reading scores by grade:
    * Replacing ninth grade scores wouldn't affect the math and reading scores of other grades.
  * Scores by school spending
    * This does not affect school spending  
  * Scores by school size
    * This does not affect school size
  * Scores by school type      
    * This does not affect school size

## Changes in the updated school district analysis 
  * The biggest change in replacing the reading and math grades for Thomas High School ninth graders with NaNs occurs at the school level.
  * Replacing reading and math grades for Thomas High School ninth graders with NaNs does not have a large effect on the overall district stats.
  * Overall reading scores for the district lower by about 1.1% after replacing reading grades for Thomas High School ninth graders with NaNs
  * Overall math scores for the district lower by about 1.1% after replacing math grades for Thomas High School ninth graders with NaNs
