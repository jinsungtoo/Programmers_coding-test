<img width="536" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/432b6e64-7f95-4214-902e-8d6e37b3c216">


    def solution(s):
    answer = []
    s_dict = {}
    for i in range(len(s)):
        if s[i] not in s_dict:
            answer.append(-1)
        else:
            answer.append(i - s_dict[s[i]])
        s_dict[s[i]] = i
    return answer
