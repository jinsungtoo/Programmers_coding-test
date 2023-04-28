<img width="534" alt="image" src="https://user-images.githubusercontent.com/115756142/235065347-5f561afd-cac2-4bae-82cf-163bd9c9f6e5.png">

> Code

   def solution(s1, s2):
    answer = 0
    for i in s1:
        if i in s2:
            answer += 1
    return answer
