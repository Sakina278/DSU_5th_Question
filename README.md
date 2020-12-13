# DSU_5th_Question
Please submit your answer here.
Q1: Write a Python Program to check whether a number is palindrome or not.
Q2: What is your name?
# palindrome or not 
def isPalindrome(str):
 
    # Run loop from 0 to len/2 
    for i in range(0, int(len(str)/2)): 
        if str[i] != str[len(str)-i-1]:
            return False
    return True
 
# main function
s = "malayalam"
ans = isPalindrome(s)
 
if (ans):
    print("Yes")
else:
    print("No")
