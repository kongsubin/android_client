# SNS 앱을 만들면서 배우는 안드로이드 클라이언트 개발
- 부제 : 팀 프로젝트를 진행하며 만들어 보는 SNS 앱
  
한 권으로 끝내는 안드로이드 클라이언트 개발  
앱 개발도 배우면서 팀 프로젝트 경험까지!  
  
이 책은 기획자, 디자이너, 서버 개발자 그리고 클라이언트 개발자가 팀을 이뤘다는 가정 하에 SNS 앱을 만드는 프로젝트를 진행한다. 클라이언트 개발자의 입장에서 각 팀원이 만든 스토리보드, 디자인 리소스와 가이드, API 서버와 문서를 참고하여 앱을 구현한다. SNS 앱 개발에 필요한 기술을 익히는 동시에 팀 프로젝트도 경험할 수 있는 책으로, 안드로이드 개발자를 준비하는 사람들에게 가장 유익한 책이 될 것이다.
  
[네이버 카페] https://cafe.naver.com/androidclientdev  
저자가 직접 운영하는 네이버 카페입니다. 질문 및 오탈자 제보/확인을 할 수 있습니다.

# 목차
1장 팀 프로젝트를 맛보자  
2장 안드로이드 개발을 준비하자  
3장 서버와 함께 Hello, world!  
4장 Gson으로 JSON을 다뤄보자  
5장 REST API로 오늘의 질문을 가져오자  
6장 JWT로 사용자를 인증하자  
7장 Retrofit과 Coil로 이미지를 다뤄보자  
8장 타임라인을 나눠서 불러오자  
9장 캐시로 HTTP를 효율적으로 사용하자  
10장 Room으로 오프라인 액세스를 지원하자  
11장 FCM으로 실시간 알림을 받아보자  
12장 테마로 취향을 존중하자    
13장 그래들로 배포를 준비하자  
부록 A 파이어베이스로 앱 품질 높이기  
부록 B 개발자가 알아야 할 날짜와 시간  
부록 C 계속되는 공부를 위한 조언  


# Server 실행시키기
1. dev.sqlite 파일 삭제
~~~bash
rm -rf dev.sqlite
~~~

2. 가상환경 진입
~~~bash
source venv/bin/activate
~~~

3. 서버 실행
~~~bash
flask run
~~~
