# Expectation Decider – Summary Report

## Project Overview

The objective of this project was to analyze a dataset of 200 students and identify probability patterns associated with success in a competitive mathematics examination. The dataset included study hours, attendance percentage, participation in group discussions, previous test scores, and final examination results. Probability and statistical techniques were applied to understand the factors influencing student performance.

---

## Probability Fundamentals

Probability is a numerical measure of the likelihood that an event will occur. It ranges from 0 to 1, where 0 represents an impossible event and 1 represents a certain event.

Examples of events from the dataset include:

* A student studies more than 10 hours per week.
* A student has attendance greater than 80%.
* A student passes the final examination.

---

## Empirical and Theoretical Probability

The empirical probability was calculated using the actual dataset.

* Total Students = 200
* Students Passed = 109

[
P(Pass)=\frac{109}{200}=0.545
]

Therefore, the empirical probability of passing is **54.5%**.

The theoretical probability was calculated assuming two equally likely outcomes (Pass or Fail).

[
P(Pass)=\frac{1}{2}=0.5
]

Therefore, the theoretical probability of passing is **50%**.

The empirical probability is slightly higher than the theoretical probability, indicating that students in the dataset passed more frequently than expected under a simple equal-likelihood assumption.

---

## Random Variable and Probability Distribution

Let:

[
X = \text{Number of students passing among 3 randomly selected students}
]

Possible values of X are:

[
X = {0,1,2,3}
]

Using the probability of passing:

[
p = 0.545
]

the probability distribution obtained was:

| X | P(X)   |
| - | ------ |
| 0 | 0.0942 |
| 1 | 0.3385 |
| 2 | 0.4054 |
| 3 | 0.1619 |

Mean:

[
\mu = np = 3(0.545)=1.635
]

Variance:

[
\sigma^2=np(1-p)=3(0.545)(0.455)=0.7441
]

This indicates that, on average, approximately 1.64 students pass among every three randomly selected students.

---

## Venn Diagram Analysis

Two sets were considered:

* Set A: Students studying more than 10 hours per week.
* Set B: Students with attendance greater than 80%.

The overlap between the two sets represents students who satisfy both conditions. The Venn diagram helped visualize the relationship between study habits and attendance patterns.

---

## Contingency Table and Probability Analysis

The contingency table comparing participation in group discussions and examination results was:

| Group Discussion | Fail | Pass |
| ---------------- | ---- | ---- |
| No               | 63   | 46   |
| Yes              | 28   | 63   |

From the table:

* Joint Probability (Discussion and Pass)

[
P(Discussion \cap Pass)=\frac{63}{200}=0.315
]

* Marginal Probability of Passing

[
P(Pass)=\frac{109}{200}=0.545
]

* Conditional Probability of Passing Given Discussion

[
P(Pass|Discussion)=0.6923
]

This indicates that students participating in group discussions had a higher probability of passing compared to the overall student population.

---

## Relationship Between Events

The conditional probability of passing given participation in group discussions was:

[
P(Pass|Discussion)=0.6923
]

The overall probability of passing was:

[
P(Pass)=0.545
]

Since these probabilities are not equal, participation in group discussions influences the likelihood of passing.

Therefore:

* The events are **Dependent**.
* The events are **Not Mutually Exclusive**, because students can both participate in group discussions and pass the examination.

---

## Bayes Theorem Application

Given:

[
P(H|Pass)=0.70
]

[
P(H|Fail)=0.40
]

[
P(H)=0.60
]

where H represents high attendance (>80%).

Using Bayes Theorem:

[
P(Pass|H)=\frac{P(H|Pass)P(Pass)}{P(H)}
]

The result obtained was:

[
P(Pass|H)=0.7778
]

or

[
77.78%
]

This means that a student with high attendance has approximately a 77.78% probability of passing the examination.

---

## Final Conclusion

The analysis indicates that attendance, study habits, group discussion participation, and previous academic performance all contribute to examination success. Students who actively participate in group discussions and maintain high attendance rates demonstrate a significantly higher probability of passing the final examination.

The Bayes Theorem analysis further confirms the importance of attendance, showing that students with high attendance have nearly a 78% chance of passing. Overall, attendance and participation emerged as the strongest indicators of examination success within the dataset.
