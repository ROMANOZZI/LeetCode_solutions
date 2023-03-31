class Solution(object):
    def longestConsecutive(self, nums):
       arr=nums
       if len(arr)<=1:
           return len(arr)
       else:
           res,temp=1,1
           arr=sorted(arr)
           
           for i in range(len(arr)):
               print(temp)
               if(arr[i]-arr[i-1]==1):
                   temp+=1
               elif(arr[i]-arr[i-1]>1):
                   res=max(res,temp)
                   temp=1
               res=max(res,temp)
           return res
