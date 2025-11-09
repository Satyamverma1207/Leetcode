class Solution(object):
    def reverse(self, x):
        sign = -1 if x<0 else 1
        s = int(str(abs(x))[::-1])*sign
        return s if -2**31 <= s <= 2**31 - 1 else 0
