![image](https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/e61b467d-ff9a-4d8b-b8d0-3750ce9f215a)

> Code

    def solution(order):
    answer = 0
    order = str(order)
    for i in order:
        if i == '3' or i == '6' or i == '9':
            answer += 1
    return answer
