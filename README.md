# Excelr
For excelr assignments

Activity	Data Type
Number of beatings from Wife	Discrete
Results of rolling a dice	Discrete
Weight of a person	Continuous
Weight of Gold	Continuous
Distance between two places	Continuous
Length of a leaf	Continuous
Dog's weight	Continuous
Blue Color	Discrete
Number of kids	Discrete
Number of tickets in Indian railways	Discrete
Number of times married	Discrete
Gender (Male or Female)	Discrete
Q1) Identify the Data type for the Following:

Q2) Identify the Data types, which were among the following
Nominal, Ordinal, Interval, Ratio.
Data	Data Type
Gender	Nominal
High School Class Ranking	Ordinal
Celsius Temperature	Interval
Weight	Ratio
Hair Color	Nominal
Socioeconomic Status	Nominal
Fahrenheit Temperature	Interval
Height	Ratio
Type of living accommodation	Nominal
Level of Agreement	Ordinal
IQ(Intelligence Scale)	Ratio
Sales Figures	Ratio
Blood Group	Nominal
Time Of Day	Interval
Time on a Clock with Hands	Interval
Number of Children	Nominal
Religious Preference	Nominal
Barometer Pressure	Interval
SAT Scores	Interval
Years of Education	Ratio


Q3) Three Coins are tossed, find the probability that two heads and one tail are obtained?
3 coins tossed
Total number of possible combinations – 2 **3 = 8
Combinations – {HHH,HHT,HTT,TTT,HHT,THH,HTH,THT}
Number of combinations to get 2 heads and 1 tail
{HHT,HTH,THH} = 3/8 = .375

Q4)  Two Dice are rolled, find the probability that sum is
a)	Equal to 1
b)	Less than or equal to 4
c)	Sum is divisible by 2 and  3

D1 = {1,2,3,4,5,6}
D2= {1,2,3,4,5,6}
Total number of possible combinations- 36

a)0 
b){(1,1)(1,2)(1,3),(2,1),(2,2),(3,1)}
6/36=1/6
b){(1,5),(5,1),(2,4),(4,2),(3,3),(6,6)} 
6/36=1/6

Q5)  A bag contains 2 red, 3 green and 2 blue balls. Two balls are drawn at random. What is the probability that none of the balls drawn is blue?

Total balls – 7
2 balls are blue ,so probability of first ball not become blue -5/7
Remaining 6 balls ,in that 2 are blue ,so probability of second ball not become blue – 4/6
So probability of 2 balls drawn are not blue is – (5/7)*(4/6)=20/42=10/21


Q6) Calculate the Expected number of candies for a randomly selected child 
Below are the probabilities of count of candies for children (ignoring the nature of the child-Generalized view)
CHILD	Candies count	Probability
A	1	0.015
B	4	0.20
C	3	0.65
D	5	0.005
E	6	0.01
F	2	0.120
Child A – probability of having 1 candy = 0.015.
Child B – probability of having 4 candies = 0.20
For  Expected number of candies for a randomly selected child – 
P(AUB)=P(A)+P(B)
=1*.015+4*.20+3*.65+5*.005+6*.01+2*.120 = 
=.015+.8+1.95+.025+.06+.24
=3.09
Q7) Calculate Mean, Median, Mode, Variance, Standard Deviation, Range &     comment about the values / draw inferences, for the given dataset
-	For Points,Score,Weigh>
Find Mean, Median, Mode, Variance, Standard Deviation, and Range and also Comment about the values/ Draw some inferences.
Use Q7.csv file 
Mean – Points -3.59 ,Score -3.22 ,Weigh – 17.85
Mean =( x1+x2+….xn)/n
Median - Points -3.69 ,Score -3.33 ,Weigh – 17.71
Mode - Points -3.07 ,Score -3.44 ,Weigh – 17.02
Variance  - Points -.28 ,Score -.95 ,Weigh – 3.19
SD -  Points -.53 ,Score -.97 ,Weigh – 1.78
Range - Points -1.34 ,Score -2.21 ,Weigh – 5.06


Q8) Calculate Expected Value for the problem below
a)	The weights (X) of patients at a clinic (in pounds), are
4
Assume one of the patients is chosen at random. What is the Expected Value of the Weight of that patient?
Total Number of patients - 9
Assume that a patient chosen at random = 1/9
Expected Value of the Weight of that patient – 1/9*108+1/9*110+1/9*123+1/9*134+1/9*135+1/9*145+1/9*167+1/9*187+1/9*199 = 145.33
Q9) Calculate Skewness, Kurtosis & draw inferences on the following data
      Cars speed and distance 
Use Q9_a.csv

SP and Weight(WT)
Use Q9_b.csv
 
 
 


Q10) Draw inferences about the following boxplot & histogram

 
Ans:  
•	Histogram for chickWeight&weight positively skewed

 
Ans:
•	Box plot positively skewed 
•	Box plot has outliers

Q11)  Suppose we want to estimate the average weight of an adult male in    Mexico. We draw a random sample of 2,000 men from a population of 3,000,000 men and weigh them. We find that the average person in our sample weighs 200 pounds, and the standard deviation of the sample is 30 pounds. Calculate 94%,98%,96% confidence interval?
Q12)  Below are the scores obtained by a student in tests 
34,36,36,38,38,39,39,40,40,41,41,41,41,42,42,45,49,56
1)	Find mean, median, variance, standard deviation.
 

2)	What can we say about the student marks? 


Q13) What is the nature of skewness when mean, median of data are equal?
Ans : Normal Distribution ,Symmetrical 
Q14) What is the nature of skewness when mean > median ?
Ans : Positively Skewed
Q15) What is the nature of skewness when median > mean?
Ans : Negatively Skewed
Q16) What does positive kurtosis value indicates for a data ?
Ans : more data located in tails instead of mean or center of the curve.
Q17) What does negative kurtosis value indicates for a data?
Ans : less data located in tails than center of the curve.
Q18) Answer the below questions using the below boxplot visualization.
 
What can we say about the distribution of the data?
Ans : Not a normal distribution. It has outliers on left side.
What is nature of skewness of the data?
Ans : Negatively skewed data
What will be the IQR of the data (approximately)? 
Ans : IQR = (Q3- Q1)/2
= (18 – 10)/2
=8/2
IQR =4

Q19) Comment on the below Boxplot visualizations? 
 
Draw an Inference from the distribution of data for Boxplot 1 with respect Boxplot 2.
Q 20) Calculate probability from the given dataset for the below cases

Data _set: Cars.csv
Calculate the probability of MPG  of Cars for the below cases.
       MPG <- Cars$MPG
a.	P(MPG>38)
b.	P(MPG<40)
c.    P (20<MPG<50)


Q 21) Check whether the data follows normal distribution
a)	Check whether the MPG of Cars follows Normal Distribution 
        Dataset: Cars.csv


b)	Check Whether the Adipose Tissue (AT) and Waist Circumference(Waist)  from wc-at data set  follows Normal Distribution 
       Dataset: wc-at.csv

Q 22) Calculate the Z scores of  90% confidence interval,94% confidence interval, 60% confidence interval 
            Q 23) Calculate the t scores of 95% confidence interval, 96% confidence interval, 99% confidence interval for sample size of 25
  Q 24)   A Government  company claims that an average light bulb lasts 270 days. A researcher randomly selects 18 bulbs for testing. The sampled bulbs last an average of 260 days, with a standard deviation of 90 days. If the CEO's claim were true, what is the probability that 18 randomly selected bulbs would have an average life of no more than 260 days
Hint:  
   rcode   pt(tscore,df)  
 df  degrees of freedom

         

