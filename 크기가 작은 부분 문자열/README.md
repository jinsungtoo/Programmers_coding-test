<img width="541" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/d0921af7-4f4e-4b73-be7b-4caf8a3f9c70">


    def solution(t, p):
    answer = 0
    size = len(p)
    for i in range(len(t)-len(p)+1):
        num = t[i:i+len(p)]
        if int(num) <= int(p):
            answer += 1
    return answer
