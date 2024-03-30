# qosf_hpn
QOSF : Cohort - 9

30-03-2024: Added Screening Task 1 notebook for submission
Task 1: less than k

Given a positive integer “k” and a list of integer numbers, look for the numbers within the list, that are less than k. Consider an appropriate number of qubits and explain why your proposal is valid for all kinds of numbers in case 


def less_than_k (int:k, list[int] ,list_n):
     k : integer value that is the positive number to compare in list_n,
     list_n : integer list that has positive numbers.
     Return the numbers that are in list_n and are less than k 

Example:

A = less_than_k (7,[4,9,11,14,1,13,6,15])
print(A)

“4,1,6”

