<img width="540" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/f8e2a4e7-f1a0-4b1b-97b4-bca933e05ada">

    def solution(participant, completion):
    answer = ''
    participant.sort()
    completion.sort()
    for i in range(len(participant)):
        if i == len(participant)-1 or participant[i] != completion[i]:
            answer = participant[i]
            break
    return answer
