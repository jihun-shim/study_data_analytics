|Colunmn | Data Type | 설명 | 분석가 의견|
--------|-----------|------|----------|
id  |   int64  |    고유 식별자 |  식별하기 위한 id
age | int64 |   나이    |   나이 분포에 따른 소득 파악 후 소득이 최상 상 중 중하 최하 로 5단계로 구분 가능
workclass   |   object  |   직업 계급 및 고용형태   | 직업의 계급(?) 고용형태 등에 따라 어디에 많이 분포하는지 분석가능 
fnlwgt  |  int64    |   가중치 값   |   가중치 정확한 의미는 모르나 
education   |   object  |  교육 수준    |   교육 수준에 따라 소득과 연관 분석 가능
education_num   |   int64   |   교육 연수   | 얼마기간 동안 교육을 받았는지 교육기간과 소득의 비례 반비례 분석가능
marital_status  |  object   |  결혼 상태    | 결혼 유무가 소득에 미치는 영향
occupation  |  object   |  직업  |  어떠한 직업이 큰소득에 유리하고 불리한지
relationship    |    object |  가족 관계    | 가족관계에 따른 소득의 축적
race    |    object |  인종  |  어떠한 인종이냐에 따라 소득이 높고 낮음 + 좋은 머리DNA 파악가능
sex |   object    |  성별  |    성별에 따른 소득 분포현황 분석가능
capital_gain    |    int64  |   자본 이득   |  ?
capital_loss    |    int64  |   자본 손실   |  ?
hours_per_week  |  int64    |   주당 근무 시간  | 같은 시간을 근무해도 잘버는 사람과 반대인 사람 확인가능
native_country  |  object   |  출신 국가    | 출신국가 확인 및 어느나라가 많은지 파악
income  |  object   |  소득 수준 (<=50K 또는 >50K)  | 환율(1468원 기준) 73,376,000 원 이상 또는 이하인 사람

