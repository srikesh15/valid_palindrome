# valid_palindrome
#class Solution:
def isPalindrome(s):
        new_str = ""

        for i in s:
            if i.isalnum():
                new_str = new_str + i.lower()
        return new_str == new_str[::-1]
    
s = input()
print(isPalindrome(s))
