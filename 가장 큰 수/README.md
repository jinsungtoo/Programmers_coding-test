<img width="540" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/5a3b7458-d69d-4d12-bab8-e5aa2ea9fd0d">

    def solution(numbers):
    answer = ''
    num = list(map(str, numbers))
    num.sort(reverse=True, key=lambda x:x*3)
    answer = int(''.join(num))
    return str(answer)
