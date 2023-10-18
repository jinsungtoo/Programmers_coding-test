<img width="540" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/b17b12b7-fde5-4c19-85a8-64d0f02e60f2">


    def solution(food):

    eat_food = '' # 먹을 음식을 저장할 문자열 변수

    # food 리스트의 두 번째 요소부터 순회
    for idx, i in enumerate(food[1:]):
        
        # 각 음식을 반으로 나누고, 그 결과를 문자열로 변환하여 eat_food에 추가
        # 이때, 음식의 인덱스는 1부터 시작하므로 idx에 1을 더해줍니다.
        eat_food += str(idx+1) * (i//2)
        
    # 왼쪽에서 먹을 음식과 오른쪽에서 먹을 음식 사이에 물(0)을 추가하여 결과 문자열을 생성
    result = eat_food + "0" + eat_food[::-1]
    
    # 결과 문자열을 반환
    return result
