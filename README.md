# Data_Preprocessing
안드로이드 수집 데이터를 Pandas를 이용해 가시성이 높은 데이터프레임 및 엑셀로 추출

- letter+timetaken+totalMetric.ipynb
  1. 사용자의 Typing Pattern을 분석하기 위해 사용자별, 앱 별 Typing Entry 추출 작업 수행
  2. 추출된 Typing Entry를 통해 Typing Metric(Character per second/minute, Word per second/minute, Keystroke per second, Keystroke per Character, Intra-InterCharacter Time) 추출
 
- Parsing_toExcel.ipynb
  1. 데이터 마이닝 거쳐 JSON으로 추출된 주요 사용 패턴의 Typing Metric을 추출하여 DataFrame으로 변환
  2. 변환된 DataFrame을 엑셀로 추출하여 원활한 인순인계
