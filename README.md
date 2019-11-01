# 라인 메신저 Notify 알림 보내기
- line notify? 라인의 메시지 수신 전용 API  
- 메시지 수신 기능만 제공하기 때문에, 대화형 챗봇/UX구성과 같은 복잡한 기능 활용은 라인 봇 활용   
- 계정별로 notify 토큰 받고 시작하자 : https://engineering.linecorp.com/ko/blog/line-notify-with-node-js-python-1-basic/  

---

### 테스트 과제 : 웹 크롤링 결과를 라인 notify로 보내기
- 타겟사이트 : 오늘의 유머 베오베 사이트  
- 링크를 예쁘게 보이기 위해 단축URL 활용 : 네이버API(하루 2.5만건 무료 제공)  
