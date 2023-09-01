![image](https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/2fe5f69e-d1d1-4007-8cc7-3c693b08d4c2)


    def solution(n):
    answer = ''
    while n:
        answer += str(n%3)
        n = n//3
    return int(answer,3)

