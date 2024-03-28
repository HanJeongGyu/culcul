# culcul

# 과목 점수를 저장할 빈 리스트 생성
scores = []

# 사용자로부터 5개의 과목 점수를 입력받음
for i in range(1, 6):
    score = float(input(f"{i}번째 과목의 점수를 입력하세요: "))
    scores.append(score)

# 총합과 평균 계산
total = sum(scores)
average = total / len(scores)

# 결과 출력
print(f"총합: {total}, 평균: {average:.2f}")
