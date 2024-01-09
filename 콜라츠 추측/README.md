![image](https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/675b5ad6-3693-4b0d-8893-4fd751c14fc2)


    def solution(num):
    answer = 0
    
    while num != 1:
        if num % 2 == 0:
            num //= 2
        else:
            num = num * 3 + 1
        
        answer += 1
        
        if answer >= 500:  # 500번 이상 반복해도 1이 되지 않을 경우
            return -1
    
    return answer
