<img width="536" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/0eab5227-dba7-40f8-bc49-865598788504">

    def solution(age):
    answer = ''
    word = ["a","b",'c','d','e','f','g','h','i','j']
    for i in str(age):
        answer += word[int(i)]
    return answer
