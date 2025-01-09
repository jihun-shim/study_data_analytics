| NO | Variable | Definition | Key | 분석가 의견 |
|----|----------|------------|-----|------------|
| 1 | TransactionID | 트랜잭션ID | number |  각 트랜잭션의 고유 식별자로, 추적성을 보장합니다. | 
| 2 | TransactionDate | 거래 날짜 | number | 거래가 발생한 날짜와 시간으로, 시간별 분석이 가능합니다.
| 3 | Amount | 금액 | number | 거래의 금전적 가치로, 사기를 나타낼 수 있는 비정상적으로 큰 거래를 식별하는 데 도움이 될 수 있습니다.
| 4 | MerchantID | 판매자ID | number | 거래에 관련된 판매자의 식별자로, 판매자 관련 사기 패턴을 평가하는 데 유용합니다.
| 5 | TransactionType | 거래유형 | string(refund, purchase) | 거래가 구매인지 환불인지를 나타내며 활동에 대한 컨텍스트를 제공합니다.
| 6 | Location | 위치 | string | 거래의 지리적 위치로, 지역별 사기 동향을 쉽게 분석할 수 있습니다.
| 7 | IsFraud | IsFraud | number ( 0 or 1 ) | 거래가 사기(1) 또는 정상(0)인지를 나타내는 이진 대상 변수로, 지도 학습 모델에 필수적입니다.