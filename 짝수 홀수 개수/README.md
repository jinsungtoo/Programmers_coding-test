![image](https://user-images.githubusercontent.com/115756142/231033271-909ab218-19cd-46a5-9265-d4ae89aa56b9.png)

> Code

    def solution(num_list):
    answer = 0
    for i in num_list:
        if i % 2 == 0:
            answer += 1
        else :
            continue
    return [answer, len(num_list)-answer]
    
