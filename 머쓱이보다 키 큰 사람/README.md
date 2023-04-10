![image](https://user-images.githubusercontent.com/115756142/230811997-a200ff5e-0081-468f-bac6-e71297d450b9.png)

> Code
    
    def solution(array, height):
    answer = 0
    for i in array:
        if i > height :
            answer += 1
        else :
            answer = 0
    return answer
