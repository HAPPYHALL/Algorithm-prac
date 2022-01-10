# 작은 수 제거하기

def solution(arr):
    if len(arr) > 1:
        arr.remove(min(arr)
        return arr
    else:
        return [-1]





def solution(arr):

    if len(arr) == 1:
        arr = []
        arr.append(-1)
    else:
        arr.remove(min(arr))

    return arr
    
    
    

def solution(arr):
	answer = [] 

	minVal = min(arr) 
	arr.remove(minVal) 

	if not arr: 
		arr.insert(0,-1) 
    
	return arr
     
    
    
 def rm_small(mylist): 
 return [i for i in mylist if i > min(mylist)]
  
  
  def solution(arr):
    arr.remove(min(arr))

    if len(arr)!=0: 
       answer = arr
    else: 
       answer = [-1]
    return answer
  
  
