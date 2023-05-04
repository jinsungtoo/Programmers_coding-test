![image](https://user-images.githubusercontent.com/115756142/236095440-96811044-62f8-4cfe-9e6c-c07f0bb4f8ed.png)

> Code

    def solution(sides):
    new_list = sorted(sides)
    if new_list[2] < new_list[0] + new_list[1]:
        return 1
    else:
        return 2
