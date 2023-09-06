<img width="523" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/6a764d83-734e-49db-a9c8-1d062a6a41ca">


    def solution(a, b):
    answer = 0
    if a % 2 == 1 and b % 2 == 1 :
        answer = (a**2) + (b**2)
    elif a % 2 == 1 or b % 2 == 1:
        answer = 2 * (a+b)
    else:
        answer = abs(a-b)
    return answer
