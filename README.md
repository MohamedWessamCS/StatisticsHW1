# StatisticsHW1

1. 250 C 2 = 31125
2. 5! / (3! * 2!) = 10
3. 2 ^ 3 = 8
4. 30 C 3 = 4060
5. 6 C 3 = 20
6. Let A = Sum up to 7, A1 = P(A) for first dice.
P(A1) = 6 / 36, It would be easier to calculate the complement probability instead, instead of figuring out when it has to equal 7 each throw, we can instead calculate the probability of never getting a 7 in all throws, which would be: P(!A1) = 1 - 6/36 = 30/36, so the probability of never getting a 7 in all three throws will be equal to: (30/36) ^ 3, then we get the complement of that and we get our answer of P(A) = 1 - (30/36)^3 = 1 - 0.5787 = 0.4213.

7. 25 students: 2 Ahmed, 2 Sally, 2 Mariam, 2 Yousef, 2 Ibrahim, the remainder 15 students all have distinct names
a) How many different 14 student study groups s.t:
Only 1 Ahmed, Only 1 Sally, Only 1 Mariam, Only 1 Yousef, Only 1, Ibrahim.
14 student study groups:
9 Non conditional
5 Conditional
The probability for each of these student names will be 2, there are 2 of the same name so we can either chose one or the other.
So the possible ways of choosing 5 with these names is 2 ^ 5 = 32
We are left with 9 students to chose from 15, so the possble ways of choosing 9 from 15 = 15 c 9 = 5005
So the total ways to choose 5 students with these names AND 9 other students, is 32 * 5005 = 160160.
a) 160160

b) 14 student study groups s.t: there will be all students with the given names (Mariam, Ahmed, Sally, Yousef, Ibrahim) = 1 ^ 5 = 1
So we are left with 4 students who don't have a condition, so we can choose 4 students from 15 which = 15 c 4 = 1365
we multiply both and we get: 1365 * 1 = 1365.

