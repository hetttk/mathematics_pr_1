# Expectation Decider Project

## Objective
Analyze a dataset of 200 students and study probability patterns related to passing a competitive mathematics exam.

## Dataset Fields
- study_hours
- attendance
- group_discussion (Yes/No)
- previous_test_score
- final_exam_pass (Pass/Fail)

## Task Results

### Task 1
Probability basics, terminology, and event definitions completed.

### Task 2
- Empirical Probability: P(Pass) = 109/200 = 0.545
- Theoretical Probability: P(Pass) = 1/2 = 0.5

### Task 3
Random Variable:
X = Number of students passing among 3 randomly selected students.

Distribution:
- P(X=0) = 0.0942
- P(X=1) = 0.3385
- P(X=2) = 0.4054
- P(X=3) = 0.1619

Mean = 1.635
Variance = 0.7441

### Task 4
Venn Diagram:
- A = Students with study_hours > 10
- B = Students with attendance > 80%
- A ∩ B = Students satisfying both conditions

### Task 5
Contingency Table

| Group Discussion | Fail | Pass |
|-----------------|------|------|
| No | 63 | 46 |
| Yes | 28 | 63 |

P(Pass) = 0.545
P(Pass|Discussion) = 0.6923

### Task 6
Conclusion:
- Events are Dependent
- Events are Not Mutually Exclusive

### Task 7
Bayes Theorem

Given:
- P(H|Pass) = 0.70
- P(H|Fail) = 0.40
- P(H) = 0.60

Result:
P(Pass|H) = 0.7778

Therefore, a student with high attendance has a 77.78% chance of passing.

## Final Conclusion

Students with higher attendance and participation in group discussions tend to have a higher probability of passing the final examination. Previous test performance and study hours are also important indicators of success.
