Naive bayes Theorem:
It is a classification technique based on Bayes' Theorem with an assumption of independence among predictors. 
In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.


P(A|B)=(P(B|A)*P(A))/P(B) 

eg:
Mach1: 30 wrenches/hr
Mach1: 20 wrenches/hr
Out of all produced parts: we can see that 1% are defective. 
Out of all defective parts: we can see that 50% came from Machine 1 and 50% came from Machine 2.
Probability that a part produced by Mach2 is defective:
P(Mach2) = 20/50 = 0.4
P(Defect) = 1%
P(Mach2|Defect) = 50%
P(Defect|Mach2) = (0.5 * 0.001)/0.4 = 0.0125

