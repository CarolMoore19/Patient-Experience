#### Overview
Patient Experience (PX) project in Health Informatics at George Mason University. 

#### Motivation
According the Beryl Institute, a center for thought leadership in patient experience, "PX encompasses “All touch-points of people processes, policies, communications, actions and environment.” I was inspired by the US Department of Veterans Affairs' Patient Journey map, which highlights the impact of both clinical and non-clinical factors on the patient's emotions and sense of ease.
https://www.blogs.va.gov/VAntage/wp-content/uploads/2019/03/VA-Patient-Experience-Journey-Map.pdf

#### Project scenario
A healthcare system wants to improve PX for ambulatory office visits following poor reviews on social media, and to continue to monitor PX across its diverse population.
<img width="828" alt="image" src="https://user-images.githubusercontent.com/77211862/118364211-89040b00-b565-11eb-8335-f4728df6f428.png">

#### Approach
Synthetic patient survey data for a hypothetical healthcare system collected over four notional time periods.  Assumes 1 survey per patient and a 100% response rate, with all respondents being adults answering on their own behalf.  Survey responses and patient characteristics are randomly generated through the uniform, triangle and normal distributions. 

#### Products 
- Python program to generate synthetic patient population
- Python program to generate survey responses
- Python analytic tool for charts and survey response counts
- HTML code for notional website, PXCenter.html

#### Results
This tool includes many of the features a health system would need to start monitoring and improving PX around office visits:  a survey, an analytics program, and a web design. Survey could be adapted to focus on telehealth, which poses increasingly important PX challenges.

#### Limitations
1. User cannot tailor views to look at interactively.
2. Analysis program generates over 60 charts, leading to long run time even for small N
3. More sophisticated graphics needed to appeal to professional audiences.
4. Randomly generated response parameters were somewhat arbitrary and could be very difficult to estimate if realism is important.
5. Additional business data and social media monitoring would also be needed to give a complete view of PX.