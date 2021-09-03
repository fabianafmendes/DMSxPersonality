# Variables Overview

### Personal Information Variables
#### Gender (GENDER)
* **Scale:** nominal
* **Possible values:** 1 = male; 2 = female; 3 = not declared 
* **Summary statistics:** 

GENDER    | N       | %
------    | ---     | ---------
male	     | 72	     | 70.6%	
female    |	30      | 29.4%	
**total** | **102** | **100%**

#### Role (ROLE)
* **Scale:** nominal
* **Possible values:** 1 = business; 2 = management, 3 = technical; 4 = mixed 
* **Summary statistics:** 

Role       | N       | %
---------- | ---     | ---------
business	  | 6	      | 5.9%	
management |	18      | 17.6%	
technical  | 51      | 50.0%
mixed      | 27      | 26.5%
**total**  | **102** | **100%**

#### Age (AGE)
* **Scale:** Ordinal
* **Possible values:** 1 = <25 years-old; 2 = 26-35 years-old; 3 = 36-45 years-old; 4 = 45-55 years-old; 5 = > 55 years-old 
* **Summary statistics:** 

Age            | N       | %
---------------| ---     | ---------
less than 25   | 16      | 15.7%	
26-35          |	59      | 57.8%	
36-45          | 14      | 13.7%
45-55          | 9       | 8.8%
more than 55   | 4       | 3.9%
**total**      | **102** | **100%**

#### Educational Level (EDL)
* **Scale:** Ordinal
* **Possible values:** 1 = high school; 2 = bachelor; 3 = master; 4 = doctor; 5 = other
* **Summary statistics:** 

EDL         | N       | %
----------- | ---     | ---------
high school | 5       | 4.9%	
bachelor    | 64      | 62.7%	
master      | 24      | 23.5%
doctor      | 9       | 8.8%
other       | 0       | 0%
**total**   | **102** | **100%**

#### Experience (EXP)
* **Scale:** Ordinal
* **Possible values:** 1 = internship, 2 = < 2 years, 3 = 2-5 years; 4 = 6-10 years; 5 = 11-15 years; 6 = > 15 years
* **Summary statistics:** 

EXP         | N       | %
----------- | ---     | ---------
internship  | 4       | 3.9%	
less than 2 | 7       | 6.9%	
2-5         | 36      | 35.3%
6-10        | 20      | 19.6%
11-15       | 20      | 19.6%
more than 15| 15      | 14.7%
**total**   | **102** | **100%**

### Decision-Making Frequency Variables
#### Frequency of participation in a decision-making (DMF-P)
* **Scale:** ordinal
* **Possible values:**  1 = never; 2 = rarely; 2 = sometimes; 4 = very often; 5 = always
* **Summary statistics:**

DMF_P      | N       | %
---------- | ------- | ------
never      | 0       | 0%
rarely	    | 1       | 1.0%	
sometimes	 | 24	     | 23.5%	
very often	| 57	     | 55.9%	
always	    | 20	     | 19.6%	
**total**  | **102** | **100%**


#### Frequency of leading a decision-making (DMF-L)
* **Scale:** ordinal
* **Possible values:**  1 = never; 2 = rarely; 2 = sometimes; 4 = very often; 5 = always
* **Summary statistics:** 

DMF_L      | N       | %
---------- | ------- | ------
never      | 2       | 2.0 %
rarely	    | 13      | 12.7%	
sometimes	 | 32	     | 31.4%	
very often	| 42	     | 41.2%	
always	    | 13	     | 12.7%	
**total**  | **102** | **100%**

#### Frequency of volunteering to lead a  decision-making (DMF-V)
* **Scale: ordinal**
* **Possible values:**  1 = never; 2 = rarely; 2 = sometimes; 4 = very often; 5 = always
* **Summary statistics:** 

DMF_V      | N       | %
---------- | ------- | ------
never      | 2       | 2.0%
rarely	    | 3       | 2.9%	
sometimes	 | 27	     | 26.5%	
very often	| 42	     | 41.2.9%	
always	    | 0	      | 0%	
**total**  | **74** | **100%**

### Decision-Making Self-Efficacy Variables
#### Affect Control Efficacy (ACE)
* **Scale:** interval, bounded
* **Possible values:** for each item in the questionnaire, the respodent can choose one a number from 0 to 100.
* **Formula to compute the ACE Score:** 
  * ACE_gross.score = sum of the value chosen for each ACE item in the questionnaire
  * ACE = ACE_gross.score/9
* **Score Range:** 0-100
* **Questionnaire items related to this variable:** (TO DO)
* **Summary statistics:** (TO DO)

#### Analytical and Inferential Efficacy (AIE)
* **Scale:** interval, bounded
* **Possible values:** for each item in the questionnaire, the respodent can choose one a number from 0 to 100.
* **Formula to compute the AIE Score:**
  * AIE_gross.score = sum of the value chosen for each AIE item in the questionnaire
  * AIE = AIE_gross.score/9
* **Score Range:** 0-100
* **Questionnaire items related to this variable:** (TO DO)
* **Summary statistics:** (TO DO)

#### Social Influence Efficacy (SIE)
* **Scale:** interval, bounded
* **Possible values:** for each item in the questionnaire, the respodent can choose one a number from 0 to 100.
* **Formula to compute the SIE Score:**
  * SIE_gross.score = sum of the value chosen for each SIE item in the questionnaire
  * SIE = SIE_gross.score/9
* **Score Range:** 0-100
* **Questionnaire items related to this variable:** (TO DO)
* **Summary statistics:** (TO DO)

#### Thought Control Efficacy (TCE)
* **Scale:** interval, bounded
* **Possible values:** for each item in the questionnaire, the respodent can choose one a number from 0 to 100.
* **Formula to compute the TCE Score:**
  * TCE_gross.score = sum of the value chosen for each TCE item in the questionnaire
  * TCE = TCE_gross.score/9
* **Score Range:** 0-100
* **Questionnaire items related to this variable:** (TO DO)
* **Summary statistics:** (TO DO)

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
* **Summary statistics:** (TO DO)

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
* **Summary statistics:** (TO DO)


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
* **Summary statistics:** (TO DO)
