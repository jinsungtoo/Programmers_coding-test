<img width="537" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/3847d8d8-88aa-4f67-a8f1-2c2925701960">

    def solution(arr):
    answer = []
    for i in range(1, len(arr)):
        if arr[i-1] not in answer:
            answer.append(arr[i-1])
        if arr[i-1] != arr[i]:
            answer.append(arr[i])
    return answer
