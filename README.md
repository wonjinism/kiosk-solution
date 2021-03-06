# kiosk-solution
KFC 키오스크를 벤치마킹해서 웹 솔루션으로 구현해 보는 프로젝트
- 스프링 연습용 프로젝트입니다.
- 코딩 연습을 위한 것이라서 분석은 가설입니다 ^^;

# 프로젝트 계획
## 1. 프로젝트 배경
   1) 이슈 분석
      - 최저임금의 상승으로 인한 인건비 증가로 프랜차이즈의 무인화 도입이 증가
      - 관련 기사 : [무인화 쓰나미] "가맹점주들 최저임금 걱정 줄이자"...프랜차이즈 직접 무인화기계 개발
      - 최저임금은 점진적으로 증가하여 1만원을 목표로 하고 있음
      - 이를 해결하기 위한 방안으로 무인화 키오스크를 도입하는 프랜차이즈가 늘고 있음

   2) 시장 분석
      - 규모가 있는 프랜차이즈의 경우에는 독자적인 디스플레이와 솔루션을 가진 키오스크 도입하는 실정
      - 가맹점주 모집 단계에서 인건비 절감을 위한 무인 발권기(키오스크)를 홍보하는 경우도 있음
      - 프랜차이즈 규모가 작거나 개인 사업자인 경우 키오스크 도입은 어려운 실정
      - 키오스크는 사실상 세로형 디스플레이에 불과하며, 나머지는 결제와 연결된 솔루션임
      - 다양한 프랜차이즈 사업 형태와 기기에 유연하게 대응할 수 있는 솔루션을 개발하여, 무인화 시장 규모를 키우면서 성장할 수 있음.

   3) 사용자 분석
      - 사업자
         - 규모가 작거나 개인 사업자는 사실상 최저임금 상승에 대한 비용 증가를 그대로 부담하고 견뎌내야 함
         - 단, 사업자가 기존에 보유하고 있는 디스플레이, 포스 등을 활용하더라도 무인화 서비스하는 것에는 기술적 파트너가 필요함
      - 소비자
         - 유명 프랜차이즈를 통해 키오스크 사용에 익숙해져 가고 있는 상황
         - 기술의 발전과 인건비 상승으로 인한 무인화에 대해서 납득하고 있는 상황

## 2. 서비스 특징
   - 사업자의 사정에 맞는 다양한 디스플레이에 대응할 수 있는 무인 주문 웹 솔루션 개발
   - 사업 형태에 따라 매장, 포장, 딜리버리 등 다양한 주문 포맷을 사전 고려하여 선택 가능하도록 개발

## 3. 벤치마킹
   - 햄버거 프랜차이즈 : KFC, 롯데리아 등 키오스크를 빠르게 도입한 패스트푸드 프랜차이즈
   - 그 외 : 미스사이공, 모범 떡볶이
