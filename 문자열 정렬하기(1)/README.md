<img width="539" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/42e7d06c-2049-4d64-8073-1bfdd507ba0a">

def solution(my_string):
    answer = []
    for i in my_string:
        if i.isdigit():
            answer += i
            a = list(map(int,answer))
            a.sort()
    return a
