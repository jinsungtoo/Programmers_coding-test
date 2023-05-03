![image](https://user-images.githubusercontent.com/115756142/235867964-b8d69d71-015d-4008-8903-d92286ee9f0b.png)

> Code

    def solution(cipher, code):
    answer = ''
    for i in range(code-1, len(cipher), code):
        answer += cipher[i]
    return answer
