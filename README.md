# Calculating-Probability-of-a-student-passing-the-exam
Calculating Probability of a student passing the exam by Monte Carlo Method



You have a friend who is applying for a public job. The way the exam works is as follows:
- There are 69 topics.
- On the day of the exam, 5 topics are chosen at random in front of the students.
- Each student chooses a single topic from these 5 randomly selected topics.
- If your friend knows the topic she has chosen and passes the exam, she gets the job.

Examples. There are 69 topics: T1, T2, ..., T69. On the day of the exam, the topics T2, T8, T29, T50, T51 are randomly selected.
- Student A has prepared topics T1, T2, and T3. Student A will decide to take T2.
- Student B has prepared T50, T51. He will choose either of the two topics to take the exam.
- Student C has prepared T1, T3, T4, T5. Unfortunately, he has not prepared any of the randomly selected topics. Student C will fail.

A. Your friend wants to know how likely she is to pass if she studies 20 of the 69 topics perfectly. Help her to calculate mathematically the probability of passing if she focuses only on studying 20 topics; assuming that she will pass if at least one of the topics she has studied is selected.

B. Make a small script using Monte Carlo methods to prove that the theoretical probability you have calculated in the previous section (Exercise 1, part A) is empirically correct. Using your script, what’s the probability of passing the exam if she prepares 15 topics?
