<img width="539" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/10864280-d253-41b8-9941-3f535ffc8709">


    def solution(name, yearning, photo):
    answer = []
    for i in photo:
        cnt = 0
        for j, k in enumerate(name):
            if k in i:
                cnt += yearning[j]
        answer.append(cnt)
    return answer
