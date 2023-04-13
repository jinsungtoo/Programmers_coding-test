![image](https://user-images.githubusercontent.com/115756142/231685975-cea7b6ac-7044-4dad-b48b-9a0b9aeb593a.png)
<img width="528" alt="image" src="https://user-images.githubusercontent.com/115756142/231686198-866fc951-5648-4818-bbe0-67f05d29e247.png">

>Code

    def solution(dot):
    x,y = dot[0], dot[1]
    if x > 0 and y > 0 :
        return 1
    elif x < 0 and y > 0 :
        return 2
    elif x < 0 and y < 0 :
        return 3
    elif x > 0 and y < 0 :
        return 4
    else :
        return 5
