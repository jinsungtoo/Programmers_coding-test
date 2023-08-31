<img width="534" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/09f761e1-741f-4f59-b82a-9f07a642b025">


    def solution(number):
    answer = 0
    for i in range(len(number)-2):
        for j in range(i+1,len(number)-1):
            for k in range(j+1,len(number)):
                
                if number[i] + number[j] + number[k] == 0:
                    answer +=1
    return answer
