# palindrome_-number_python

class Solution(object):
    def isPalindrome(self, x):
        if x < 0:
            return False
        
        original = x
        reversed_num = 0 
    while x > 0:
        last_digit = x% 10
        reverse_num = reverse_num * 10 + last_digit
        x = x //10
    

    return original == reversed_num
print(is_palindrome(1291)) 
