---
layout: post
title: 6 steps to make web service
---

“개발자가 되고 싶으세요?” 라는 책을 읽으며 정리한 자료이다.

1.	프로젝트 결정
2.	설계
3.	기술 세트 선정
4.	환경 구축
5.	서비스 개발 및 테스트
6.	서비스 배포 및 시작

1.	프로젝트 결정
현업에선 복잡한 일이지만 개인 프로젝트이니 적당히 넘어갑시다.

2.	설계
프로젝트에 적용할 개발 방법론에 따라 설계 단계의 치밀함은 조정 가능
‘애자일’을 사용하는 것으로 가정

3.	기술세트 선정
부동산 서비스의 경우, 지역 정보를 이용해 많은 데이터를 주고 받는다.
실제 금융 거래가 오고 갈 수 있는 보안이 중요.
	JSP로 라이브러리를 적용시키자.

기술을 정했으니 팀을 가르자.  HTML 웹 페이지를 개발할 사람과 자바 개발자를 구분.

서버는 아파치와 톰캣    DBMS는 MySQL <- 개발자가 익숙한 기술이기에 선택.

현업에서는 유지보수의 관점도 고려해야 하기에 익숙한 기술을 선택하는 것이 중요하다.
	속도가 빨라야 하는 것도 잊지 말 것

4.	환경 구축
환경은 개발할 환경과 서비스가 배포될 환경을 모두 의미한다.  
개발환경 : git
실제 환경 테스트를 위해 약간 성능이 떨어지는 pc를 준비해서 완성된 서비스를 돌린다.
혹은 클라우드 서비스를 이용하는 것도 방법이다.

5.	서비스 개발 및 테스트
서비스에 필요한 기능을 JSP 팀이 만들고, HTML팀은 어떻게 적용할 지 정한다.
개발기간을 정하고 접근. 정확히 산정하는 것은 어렵다.

6.	서비스 배포 및 시작