![image](https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/675b5ad6-3693-4b0d-8893-4fd751c14fc2)


    def solution(num):
    answer = 0
    while (num != 1 and num != 500):
        if num % 2 == 0:
            num = num/2
        else :
            num = num*3+1
        answer += 1
    return answer if answer <500 else -1
