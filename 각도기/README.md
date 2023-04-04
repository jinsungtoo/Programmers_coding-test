![image](https://user-images.githubusercontent.com/115756142/229666340-8aad1659-9b6e-49ed-862a-6c0022347da0.png)

>Code

    def solution(angle):
    if 0 < angle < 90:
        return 1
    elif angle == 90:
        return 2
    elif 90 < angle < 180:
        return 3
    return 4
