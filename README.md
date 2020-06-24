# CS_BuildWeek2

Problem day 2 build week
class Solution:
    def containsDuplicate(self, nums: List[int]) -> bool:
        List = [int]
        
        # set a for loop to check each item in our List
        for x in List:
            if x != List[x]:
                return False
            elif x == List[x]:
                print(List)
                return True
            # look and see if that number is appering in the list
