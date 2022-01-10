# 작은 수 제거하기

#1
def solution(arr):
    if len(arr) > 1:
        arr.remove(min(arr)
        return arr
    else:
        return [-1]
def rm_small(mylist):
    return [i for i in mylist if i > min(mylist)]






#2
def solution(arr):

    if len(arr) == 1:
        arr = []
        arr.append(-1)
    else:
        arr.remove(min(arr))

    return arr
    
    
    
#3
def solution(arr):
	answer = [] 

	minVal = min(arr) 
	arr.remove(minVal) 

	if not arr: 
		arr.insert(0,-1) 
    
	return arr
     
    
    
#4 
  def rm_small(mylist): 
	return [i for i in mylist if i > min(mylist)]
  
  
  
