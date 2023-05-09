![image](https://user-images.githubusercontent.com/115756142/236976263-096bf317-d66f-4ecf-a77c-45b6de305fb4.png)

> Code

    def solution(rsp):
    answer = ''
    for i in rsp:
        if i == '2':
            answer += '0'
        elif i == '0':
            answer += '5'
        else:
            answer += '2'
    return answer
    
