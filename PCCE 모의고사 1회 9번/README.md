![image](https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/682cb3a6-02ea-4196-8dc6-df7b493f7014)

    def solution(num_list):
    answer = []
    for N in num_list:
        is_sosu= True
        for i in range(2,N):
            if N % i ==0:
                is_sosu=False
                break
        answer.append(is_sosu)
    return answer
