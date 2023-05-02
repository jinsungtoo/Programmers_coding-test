![image](https://user-images.githubusercontent.com/115756142/235566592-e7749641-1928-4ada-938b-0a130e0468fb.png)

> Code

    def solution(price):
    if price >= 500000:
        answer = price - (price * 0.2)
    elif price >= 300000:
        answer = price - (price * 0.1)
    elif price >= 100000:
        answer = price - (price * 0.05)
    else:
        0
    return answer
