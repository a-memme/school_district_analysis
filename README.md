# School District Analysis 
## Purpose 
Reanalyzing school district data with Python, Pandas and Jupyter Notebook. Assessing how the disclusion of a set of ninth grade test scores - those suspected of academic dishonesty that is - will affect the analysis of the particular school in question, as well as the overall analysis of the entire city school district as a whole.

## Results 
Several areas of the data were affected with the removal of ninth grade math and reading score from Thomas High School, however, many of these changes were usually quite minor. The changes are as follows:

- district summary (for all references see image below):
  - a decrease in Average Math Score by 0.1 points (78.9 without grade nine scores; 79 with)
  - a decrease in % of students passing math by 0.2 (74.8 without grade nine scores; 75 with)
  - a decrease in % of students passing reading by 0.3 (85.7 without vs 86 with)
  - a decrease in % of students passing overall by 0.1 (64.9 vs 65)

<img width="962" alt="districtsummary_without" src="https://user-images.githubusercontent.com/79600550/112369598-bdb8bc00-8cb2-11eb-9098-9efedf93dac4.png">
    
<img width="990" alt="districtsummary_with" src="https://user-images.githubusercontent.com/79600550/112369683-d75a0380-8cb2-11eb-8b83-5c3518b87cc5.png">



Using Python3, Pandas, and Jupyter Notebook
