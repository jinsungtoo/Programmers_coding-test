<img width="536" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/1d83b34e-018e-47ea-823f-c154fc06708c">


    def solution(n, arr1, arr2):
    answer = []
    for i, j in zip(arr1, arr2):
        answer.append(bin(i|j)[2:].zfill(n).replace("1", "#").replace("0", " "))
    return answer
