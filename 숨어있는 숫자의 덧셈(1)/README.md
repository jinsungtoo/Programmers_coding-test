![image](https://user-images.githubusercontent.com/115756142/236720119-6963c8d7-82e3-41e4-9027-3cb0e7c8689a.png)

> Code

    def solution(my_string):
    answer = 0
    str = "1","2","3","4","5","6","7","8","9"
    for i in my_string:
        if i in str:
            answer += int(i)
    return answer
    
    # def solution(my_string):
    #     answer = 0
    #     for i in my_string:
    #         if i.isdigit():
    #             answer += int(i)
    #     return answer
