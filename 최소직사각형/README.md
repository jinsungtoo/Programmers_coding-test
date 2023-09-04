<img width="537" alt="image" src="https://github.com/jinsungtoo/Programmers_coding-test/assets/115756142/09689a02-b0be-4253-8179-19e431129a93">


    def solution(sizes):
    answer = 0
    big = 0
    small = 0
    for w,h in sizes:
        if h > w:
            big = max(big, h)
            small = max(small, w)
        else:
            big = max(big, w)
            small = max(small, h)
    return big * small
