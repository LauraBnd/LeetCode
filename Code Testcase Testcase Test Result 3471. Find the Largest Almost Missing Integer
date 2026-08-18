class Solution(object):
    def largestInteger(self, nums, k):
        """
        :type nums: List[int]
        :type k: int
        :rtype: int
        """
        n = len(nums)
        answer = -1

        for x in set(nums):
            appears = 0

            for i in range(n - k + 1):
                if x in nums[i:i+k]:
                    appears += 1

            if appears == 1:
                answer = max(answer, x)

        return answer

        
