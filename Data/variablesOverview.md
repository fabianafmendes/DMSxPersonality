# Variables Overview

### Personal Information Variables
#### Gender (GENDER)
* **Scale:** nominal
* **Possible values:** 1 = male; 2 = female; 3 = not declared 
* **Summary statistics:** 

GENDER    | #       | %
------    | ---     | ---------
male	     | 72	     | 70.6%	
female    |	30      | 29.4%	
**Number of valid cases** | **102** | - 

#### Role (ROLE)
* **Scale:** nominal
* **Possible values:** 1 = business; 2 = management, 3 = technical; 4 = mixed 
* **Summary statistics:** 

Role       | #       | %
---------- | ---     | ---------
business	  | 6	      | 5.9%	
management |	18      | 17.6%	
technical  | 51      | 50.0%
mixed      | 27      | 26.5%
**Number of valid cases** | **102** | -

#### Age (AGE)
* **Scale:** Ordinal
* **Possible values:** 1 = less than 25 years-old; 2 = 26-35 years-old; 3 = 36-45 years-old; 4 = 45-55 years-old; 5 = more than 55 years-old 
* **Summary statistics:** 

Age            | #       | %
---------------| ---     | ---------
less than 25   | 16      | 15.7%	
26-35          |	59      | 57.8%	
36-45          | 14      | 13.7%
45-55          | 9       | 8.8%
more than 55   | 4       | 3.9%
**Number of valid cases** | **102** | -

#### Educational Level (EDL)
* **Scale:** Ordinal
* **Possible values:** 1 = high school; 2 = bachelor; 3 = master; 4 = doctor; 5 = other
* **Summary statistics:** 

EDL         | #       | %
----------- | ---     | ---------
high school | 5       | 4.9%	
bachelor    | 64      | 62.7%	
master      | 24      | 23.5%
doctor      | 9       | 8.8%
other       | 0       | 0%
**Number of valid cases** | **102** | -

#### Experience (EXP)
* **Scale:** Ordinal
* **Possible values:** 1 = internship, 2 = less than 2 years, 3 = 2-5 years; 4 = 6-10 years; 5 = 11-15 years; 6 = more than 15 years
* **Summary statistics:** 

EXP         | #       | %
----------- | ---     | ---------
internship  | 4       | 3.9%	
less than 2 | 7       | 6.9%	
2-5         | 36      | 35.3%
6-10        | 20      | 19.6%
11-15       | 20      | 19.6%
more than 15| 15      | 14.7%
**Number of valid cases** | **102** | -

### Decision-Making Frequency Variables
#### Frequency of participation in a decision-making (DMF-P)
* **Scale:** ordinal
* **Possible values:**  1 = never; 2 = rarely; 2 = sometimes; 4 = very often; 5 = always
* **Summary statistics:**

DMF_P      | #       | %
---------- | ------- | ------
never      | 0       | 0%
rarely	    | 1       | 1.0%	
sometimes	 | 24	     | 23.5%	
very often	| 57	     | 55.9%	
always	    | 20	     | 19.6%	
**Number of valid cases** | **102** | -


#### Frequency of leading a decision-making (DMF-L)
* **Scale:** ordinal
* **Possible values:**  1 = never; 2 = rarely; 2 = sometimes; 4 = very often; 5 = always
* **Summary statistics:** 

DMF_L      | #       | %
---------- | ------- | ------
never      | 2       | 2.0 %
rarely	    | 13      | 12.7%	
sometimes	 | 32	     | 31.4%	
very often	| 42	     | 41.2%	
always	    | 13	     | 12.7%	
**Number of valid cases** | **102** | -

#### Frequency of volunteering to lead a  decision-making (DMF-V)
* **Scale: ordinal**
* **Possible values:**  1 = never; 2 = rarely; 2 = sometimes; 4 = very often; 5 = always
* **Summary statistics:** 

DMF_V      | #       | %
---------- | ------- | ------
never      | 2       | 2.0%
rarely	    | 3       | 2.9%	
sometimes	 | 27	     | 26.5%	
very often	| 42	     | 41.2.9%	
always	    | 0	      | 0%	
**Number of valid cases** | **102** | -

### Decision-Making Self-Efficacy Variables
#### Affect Control Efficacy (ACE)
* **Scale:** interval, bounded
* **Possible values:** for each item in the questionnaire, the respodent can choose one a number from 0 to 100.
* **Formula to compute the ACE Score:** 
  * ACE_gross.score = sum of the value chosen for each ACE item in the questionnaire
  * ACE = ACE_gross.score/9
* **Score Range:** 0-100
* **Questionnaire items related to this variable:** 1, 2, 6, 7, 8, 9, 15, 16, 17.
* **Summary statistics:**
  * Minimum: 41.11
  * Maximum: 96.67
  * Mean: 71.72
  * Std. Deviation: 12.07
  * Number of valid cases: 102


#### Analytical and Inferential Efficacy (AIE)
* **Scale:** interval, bounded
* **Possible values:** for each item in the questionnaire, the respodent can choose one a number from 0 to 100.
* **Formula to compute the AIE Score:**
  * AIE_gross.score = sum of the value chosen for each AIE item in the questionnaire
  * AIE = AIE_gross.score/11
* **Score Range:** 0-100
* **Questionnaire items related to this variable:** 10, 11, 12, 13, 18, 19, 20, 22, 21, 23, 27

* **Summary statistics:** 
  * Minimum: 	36.36
  * Maximum:	100.00
  * Mean:	73.74
  * Std. Deviation:	11.63
  * Number of valid cases:	102

#### Social Influence Efficacy (SIE)
* **Scale:** interval, bounded
* **Possible values:** for each item in the questionnaire, the respodent can choose one a number from 0 to 100.
* **Formula to compute the SIE Score:**
  * SIE_gross.score = sum of the value chosen for each SIE item in the questionnaire
  * SIE = SIE_gross.score/5
* **Score Range:** 0-100
* **Questionnaire items related to this variable:** 24, 25, 26, 28, 29
* **Summary statistics:**
  * Minimum:12.00
  * Maximum:	94.00
  * Mean:	55.16
  * Std. Deviation:	17.81
  * Number of valid cases:	102 

#### Thought Control Efficacy (TCE)
* **Scale:** interval, bounded
* **Possible values:** for each item in the questionnaire, the respodent can choose one a number from 0 to 100.
* **Formula to compute the TCE Score:**
  * TCE_gross.score = sum of the value chosen for each TCE item in the questionnaire
  * TCE = TCE_gross.score/5
* **Score Range:** 0-100
* **Questionnaire items related to this variable:** 3, 4, 5, 14, 30
* **Summary statistics:**
  * Minimum:	16.00
  * Maximum:	80.00
  * Mean:	47.88
  * Std. Deviation:	14.99
  * Number of valid cases:	102
 

### Decision-Making Style (DMS)
* **Scale:** interval, bounded
* **Possible values:** for each case in the questionnaire, the respodent can choose one of the following alternatives: 

Alternative | Value showed in the data file | Value added in the final score
----------- |------------------------------ |-------------------------------
AI  | 1 | 0
AII | 2 | 1
CI  | 3 | 5
CII | 4 | 8
GII | 5 | 10

* **Formula to compute the DMS Score:** DMS = sum of the chosen alternative score of each case
* **Score Range:** 0-300
* **Summary statistics:**
  * Minimum:	77.00
  * Maximum:	266.00
  * Mean:	173.59
  * Std. Deviation:	41.11
  * Number of valid cases:	63
 

### Personality Factors Variables
* **Scale:** interval, bounded
* [Instructions about how to compute the score](https://ipip.ori.org/newScoringInstructions.htm)
* **Range:** 24-124
* **Key:**
  * Agreeableness (A)
  * Conscientiousness (C)
  * Extraversion (E)
  * Neuroticism (N)
  * Openness (O)
* **Summary statistics:** 

Measure   | A 	   | C 	   | E 	   | N
--------- | --    | --    | --    | -- 
Minimum   | 48.00 | 59.00 | 45.00 | 36.00
Maximum   | 114.00| 112.00| 99.00 | 99.00
Mea       | 91.33 | 91.08 | 76.95 | 65.89
Std. Dev. | 11.48 | 11.47 | 11.74 | 13.15
Number of valid cases | 102    | 102  | 102   | 102


### Personality Facets Variables
* **Scale:** interval, bounded
* [Instructions about how to compute the score](https://ipip.ori.org/newScoringInstructions.htm)
* **Range:** 4-20
* **Key:**
  * Agreeableness Facets 
    * Trust (A1)
    * Morality (A2)
    * Altruism (A3)
    * Cooperation (A4)
    * Modesty (A5)
    * Sympathy (A6)
  * Conscientiousness Facets
    * Self-Efficacy (C1)
    * Orderliness (C2)
    * Dutifulness (C3)
    * Achievement-Striving (C4)
    * Self-Discipline (C5)
    * Cautiousness (C6)
  * Extraversion Facets
    * Friendliness (E1)
    * Gregariousness (E2)
    * Assertiveness (E3)
    * Activity Level (E4)
    * Excitement-Seeking (E5)
    * Cheerfulness (E6)
  * Neuroticism Facets
    * Anxiety (N1)
    * Anger (N2)
    * Depression (N3)
    * Self-Consciousness (N4)
    * Immoderation (N5)
    * Vulnerability (N6)
  * Openness Facets
    * Imagination (O1)
    * Artistic Interests (O2)
    * Emotionality (O3)
    * Adventurousness (O4)
    * Intellect (O5)
    * Liberalism (O6)
* **Summary statistics:**

Personality Facet | Minimum | Maximum | Mean | Std. Dev. | Number of Valid Cases
----------------- | ------- | ------- | ---- | --------- | --
A1 | 5 | 20 | 13.71 | 3.32 | 102
A2 | 10 | 20 | 17.95 | 2.05 | 102
A3 | 7 | 20 | 16.07 | 2.78 | 102
A4 | 7 | 20 | 17.13 | 2.90 | 102
A5 | 4 | 19 | 11.50 | 3.23 | 102
A6 | 4 | 20 | 14.98 | 3.11 | 102
C1 | 8 | 20 | 15.19 | 2.46 | 102
C2 | 5 | 20 | 14.57 | 4.01 | 102
C3 | 10 | 20 | 16.58 | 2.23 | 102
C4 | 11 | 20 | 16.44 | 2.21 | 102
C5 | 4 | 20 | 13.93 | 2.87 | 102
C6 | 4 | 20 | 14.37 | 3.69 | 102
E1 | 6 | 20 | 14.33 | 3.33 | 102
E2 | 4 | 19 | 10.84 | 3.63 | 102
E3 | 6 | 20 | 14.63 | 3.04 | 102
E4 | 7 | 19 | 13.11 | 2.59 | 102
E5 | 4 | 17 | 8.89 | 3.00 | 102
E6 | 8 | 20 | 15.15 | 2.48 | 102
N1 | 6 | 19 | 12.69 | 3.22 | 102
N2 | 4 | 19 | 9.95 | 3.99 | 102
N3 | 4 | 20 | 8.25 | 3.37 | 102
N4 | 7 | 20 | 12.91 | 2.76 | 102
N5 | 6 | 18 | 10.95 | 2.67 | 102
N6 | 5 | 19 | 11.14 | 2.88 | 102
O1 | 8 | 20 | 14.75 | 2.81 | 102
O2 | 4 | 20 | 14.03 | 3.41 | 102
O3 | 6 | 20 | 14.41 | 3.10 | 102
O4 | 5 | 19 | 12.39 | 3.08 | 102
O5 | 6 | 20 | 14.32 | 3.08 | 102
O6 | 4 | 19 | 12.50 | 2.65 | 102
