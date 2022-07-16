# Ass-1-15-7-22
Assignment-1
class Solution:
    def singleNumber(self, n):
        res=0
        for i in n:
            res=res^i
        return res
