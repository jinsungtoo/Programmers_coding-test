<img width="488" alt="image" src="https://user-images.githubusercontent.com/115756142/229050208-97bc3cff-5bc5-417c-a67b-784cb5633c1c.png">


> code
    
    def solution(x):
        sum_x = sum(map(int, str(int(x)))) # 각 자릿수의 합
        if x % sum_x == 0:
            return True
        else:
            return False
