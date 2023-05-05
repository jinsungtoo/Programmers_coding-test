<img width="519" alt="image" src="https://user-images.githubusercontent.com/115756142/236396935-50d55b3e-b196-4e6c-b800-657e6a568cd3.png">

> Code

    def solution(my_string):
    answer = ''
    for i in my_string:
        if i.isupper():
            i = i.lower()
            answer = answer + i
        else:
            i = i.upper()
            answer = answer + i
    return answer
