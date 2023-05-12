<img width="534" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/7cae1d90-81ef-4265-8024-f272ef544705">

> Code

    def solution(my_string, num1, num2):
    answer = ''
    for i in range(len(my_string)):
        if i == num1:
            answer += my_string[num2]
        elif i == num2:
            answer += my_string[num1]
        else:
            answer += my_string[i]
    return answer
