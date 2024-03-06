# 해커가 2명인지 3명인지 찾
- 진행인원 : 1명

- 목표 : 군집분석을 이용하여 기업을 해킹한 해커가 2명인지 3명인지 찾기 
- 분석 방법
  1. 해커들이 서버에 접속하는데에 사용한 각 세션의 메타데이터 사용(학원제공)
  2. 데이터 확인
  3. 데이터 전처리
  4. 군집이 2일때와 3일때의 실루엣계수 확인하여 예측
- 분석 결과
  1. 군집이 2일때의 실루엣 계수(평균값) : 0.602
  2. 군집이 3일때의 실루엣 계숙(평균값) : 0.539
  3. 실루엣 계수는 1에 가까울수록 정확하다고 보이므로 해커는 2명으로 예측
- 개발도구 : Jypyter Notebook
- 개발언어 및 프레임워크 : Python / pandas, sklearn, yellowbrick
- 코드 : 파일첨부(주석포함)
- 배운내용 : 군집분석, 실루엣계수 
