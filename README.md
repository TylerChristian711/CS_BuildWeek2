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


# day 3 challange
# Definition for singly-linked list.
# class ListNode:
#     def __init__(self, val=0, next=None):
#         self.val = val
#         self.next = next
class Solution:
    def mergeTwoLists(self, l1: ListNode, l2: ListNode) -> ListNode:
        for len(l1):
            l1.append(l2)
            if l1[x] > l2[x]:
                l1[x].append(l2[x])
            else:
                l2[x].append(l1[x])
                
