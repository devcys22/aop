# aop

![image](https://github.com/devcys22/aop/assets/78769412/653ea5ee-906f-4aba-8324-271e7dc26d3d)
<h3>AOP 구현1 - 기본</h3>
<img src="https://github.com/devcys22/aop/assets/78769412/d1772376-dbce-4037-b966-8604c24bdbbf">

<h3>AOP 구현2 - 포인트 컷 분리</h3>
<img src="https://github.com/devcys22/aop/assets/78769412/b6f6686c-99de-4eaf-8ba7-adbe69754f0e">

<h3>AOP 구현3 - 어드바이스 추가</h3>
<img src="https://github.com/devcys22/aop/assets/78769412/9b78b6ac-f868-4489-a372-922b5cd007f9">
<img src="https://github.com/devcys22/aop/assets/78769412/5c12c77d-f1fe-406a-a401-3b1fcd9c8b8b">

<h3>AOP 구현6 - 어드바이스 종류</h3>
<img src="https://github.com/devcys22/aop/assets/78769412/4dd2d22f-bdd1-415d-a156-d9752869f6e2">
<a href="https://dev22.tistory.com/232">제약의 중요성</a>

<h3>AOP 포인트컷</h3>
execution(접근제어자? 반환타입 선언타입?메서드이름(파라미터) 예외?)

<h3>AOP 실무주의사항</h3>
<img src="https://github.com/devcys22/aop/assets/78769412/558f0d13-2aba-4001-a994-68fa8cfb979d">
프록시 방식의 AOP 한계 - 프록시 방식의 AOP는 메서드 내부 호출에 프록시를 적용할 수 없다. 

<h4>대안1 자기 자신 주입</h4>
<img src="https://github.com/devcys22/aop/assets/78769412/d90c6069-cb55-47bd-8e96-2fdc6bdd1b20">
김영한 스프링 핵심원리 - 고급편
<img src="https://github.com/devcys22/aop/assets/78769412/fe05a8d5-a3f3-4f50-aa97-0f8eded23755">

<h4>대안2 지연 조회</h4>
<img src="https://github.com/devcys22/aop/assets/78769412/21ffee95-51dd-4b9d-9d27-3c8fd117ad91">

<h4>대안3 구조 변경</h4>
<img src="https://github.com/devcys22/aop/assets/78769412/d9cb77c8-8340-421d-bc63-4134646823b1">

![image](https://github.com/devcys22/aop/assets/78769412/17818d1c-39ad-45eb-8f80-2c4df4232401)

<h3>스프링의 해결책</h3>
#CGLIB 프록시 기본 사용
