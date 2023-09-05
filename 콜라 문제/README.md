<img width="533" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/3db61358-e677-4f98-9a3f-4d61e54bc889">


    def solution(a, b, n):
    answer = 0
    while (n >= a):
        answer += (n // a)*b
        n = (n//a)*b + n%a
    return answer
