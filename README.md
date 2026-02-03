# DSS-SCORE
The DSS score predicts risk of dengue shock syndrome in adults, based on the percentage increase in hematocrit (HIR), the percentage decrease in platelet count (PDR) between two consecutive days, and WHO 2009 warning signs. It enables triage into low-, intermediate-, and high-risk groups for monitoring and management.

**Usage**

Download `DSS_Score.xlsx` from this repository.

**Input: **

HCT today and HCT yesterday

PLT today and PLT yesterday 

Select one or more WHO 2009 warning signs: 
  
  Abdominal pain/tenderness
  
  Persistent vomiting
  
  Clinical fluid accumulation
  
  Mucosal bleeding
  
  Lethargy/restlessness
  
  Liver enlargement > 2 cm below the right costal margin

**Output: **

Hematocrit increase rate (HIR); 

Platelet decrease ratio (PDR); 

Number of warning signs; DSS score; 

Risk group classification (low, intermediate, high)

**Example:**
Patient A

HCT today = 48%, HCT yesterday = 44%

PLT today = 20 K/uL, PLT yesterday = 80 K/uL

Warning signs: Abdominal pain or tenderness; Mucosal bleeding

Result:

HIR = 6.7%

PDR = 66.7%

Number of warning signs = 2

DSS score = 13

Risk group = High

**Citation  **
If you use this calculator in your research, please cite as:

Vu Thi Thanh Mai¹², Bui Thi Bich Hanh¹², Ha Vinh¹², Ho Dang Trung Nghia¹²  
Quantifying the Kinetics of Hematocrit and Platelet Count During Febrile Phase to Develop a Scoring System for Predicting Dengue Shock Syndrome in Adults: A Matched Case-Control Study from a Hospital in Vietnam  
[Journal Name], [Year], DOI: [to be assigned]

**License **

This project is licensed under the MIT License – you are free to use, modify, and distribute the code, provided that the original copyright notice is included.
