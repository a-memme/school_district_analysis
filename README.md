# School District Analysis 
## Purpose 
Reanalyzing school district data with Python, Pandas and Jupyter Notebook. Assessing how the disclusion of a set of ninth grade test scores - those suspected of academic dishonesty that is - will affect the analysis of the particular school in question, as well as the overall analysis of the entire city school district as a whole.

## Results 
Several areas of the data were affected with the removal of ninth grade math and reading scores from Thomas High School, however, many of these changes were usually quite minor. The changes are as follows:

### District Summary Results
(for references see images below - the top image references data without ninth grade scores; bottom with ninth grade scores)
 - a decrease in Average Math Score in the district by 0.1 points (78.9 without grade nine scores; 79 with)
 - a decrease in % of students passing math in the district by 0.2% (74.8% without grade nine scores; 75% with)
 - a decrease in % of students passing reading in the district by 0.3% (85.7% without vs 86% with)
 - a decrease in % of students passing overall in the district by 0.1% (64.9% vs 65%)

<img width="962" alt="districtsummary_without" src="https://user-images.githubusercontent.com/79600550/112369598-bdb8bc00-8cb2-11eb-9098-9efedf93dac4.png">
    
<img width="990" alt="districtsummary_with" src="https://user-images.githubusercontent.com/79600550/112369683-d75a0380-8cb2-11eb-8b83-5c3518b87cc5.png">

### School Summary Results
(for references see images below - the top image references data without ninth grade scores; bottom with ninth grade scores)
  - a decrease in Average Math scores at Thomas High School by ~0.16 points (83.35 without vs 83.42 with)
  - an increase in Average Reading scores at Thomas High School by 0.05 points (83.90 without vs 83.85 without)
  - a decrease in % of students passing math at Thomas High School by ~ 0.08% (93.19% vs 93.27%)
  - a decrease in % of students passing reading at Thomas High School by ~ 0.3% (97.02% vs 97.31%)
  - a decrease in % of students passing overall at Thomas High School by 0.32% (90.63% vs 90.95%)

<img width="1033" alt="schoolsummary_without" src="https://user-images.githubusercontent.com/79600550/112371679-433d6b80-8cb5-11eb-86d0-6e75ae6b852b.png">

<img width="1046" alt="schoolsummary_with" src="https://user-images.githubusercontent.com/79600550/112371748-5bad8600-8cb5-11eb-990a-36593b3f6e9f.png">

### Relative performance:
 - Although there is a ~ 0.3% decrease in % of students passing overall, Thomas High School remains to be the second highest performing school in the city school district based on overall passing % (See below). 

<img width="1103" alt="topperforming_without" src="https://user-images.githubusercontent.com/79600550/112372371-176eb580-8cb6-11eb-89e1-c5a1129c8571.png">

<img width="1096" alt="topperforming_with" src="https://user-images.githubusercontent.com/79600550/112372443-2c4b4900-8cb6-11eb-829f-d1079fcf18b3.png">

### Math & Reading Scores by Grade 

- Math:
  - No changes - Ninth grade scores simply displayed as NaN with no changes to other grades (See below). 

<img width="441" alt="math_grade_without" src="https://user-images.githubusercontent.com/79600550/112373753-b0520080-8cb7-11eb-8238-8d8602d7442f.png">

<img width="494" alt="math_grade_with" src="https://user-images.githubusercontent.com/79600550/112373867-d081bf80-8cb7-11eb-873a-da0ec78188d1.png">

- Reading 
  - Same as above; no changes and ninth grade scores are displayed as NaN (See below). 

<img width="457" alt="reading_grade_without" src="https://user-images.githubusercontent.com/79600550/112374185-2d7d7580-8cb8-11eb-9924-f77fa950a114.png">

<img width="470" alt="reading_grade_with" src="https://user-images.githubusercontent.com/79600550/112374253-40904580-8cb8-11eb-9ca0-ef23bf62dd31.png">

### Scores by School Spending 
- Very minor changes to the $634-644 spending range category to which Thomas High School falls under. Changes are as follows (reference images below in usual order):
  - 0.01 point decrease in Average Math Score
  - 0.01 point increase in Average Reading Score 
  - 0.02% decrease in % of students passing math 
  - 0.08% decrease in % of students passing reading 
  - 0.08% decrease in % of students passing overall 

<img width="820" alt="spending_without_noformat" src="https://user-images.githubusercontent.com/79600550/112375165-5b16ee80-8cb9-11eb-9aa5-4b51e3c3633f.png">

<img width="821" alt="spending_with_noformat" src="https://user-images.githubusercontent.com/79600550/112375250-72ee7280-8cb9-11eb-8c50-95a1eb9b846f.png">

- These changes, however, become insignificant once tables are formatted appropriately (See below):

<img width="808" alt="spending_without_formatted" src="https://user-images.githubusercontent.com/79600550/112375517-c2cd3980-8cb9-11eb-8ca9-f0efcd9b3add.png">

<img width="812" alt="spending_with_formatted" src="https://user-images.githubusercontent.com/79600550/112375596-d8426380-8cb9-11eb-8a40-69449c4f81df.png">

### Scores by School Size 
- A similar set of extremely minor changes are seen in scores categorized by school size, similarly to those shown in school spending categories. With scores in the medium school-size category, changes are as follows (reference images below in usual order):
  - 0.01 point decrease in Average Math Score 
  - 0.01 point increase in Average Reading Score 
  - 0.01% decrease in % of students passing math 
  - 0.06% decrease in % of students passing reading 
  - 0.07% decrease in % of students passing overall 

<img width="792" alt="size_without_noformat" src="https://user-images.githubusercontent.com/79600550/112376415-d1682080-8cba-11eb-8e9f-10e9dc0aa3b1.png">

<img width="779" alt="size_with_noformat" src="https://user-images.githubusercontent.com/79600550/112376504-eb096800-8cba-11eb-970c-58c6fd614927.png">

- Once again, these changes become insignificant once tables are formatted appropriately (See below). 

<img width="795" alt="size_without_formatted" src="https://user-images.githubusercontent.com/79600550/112376932-7edb3400-8cbb-11eb-8777-af232695e4f7.png">

<img width="772" alt="size_with_formatted" src="https://user-images.githubusercontent.com/79600550/112377031-9e725c80-8cbb-11eb-9371-95b89205c614.png">

Using Python3, Pandas, and Jupyter Notebook
