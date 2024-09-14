# troubleShooting
작업을 진행하며, 문제가 생겨서 정리해놓은 트러블 슈팅을 모아놓는 공간  
> 99/0 99%의 완벽한 물에 1%의 불순물을 섞으면, 물이 더러워진다.
<br/>
![혼돈의주문서](https://github.com/user-attachments/assets/ea64eca0-817e-4f52-a30c-908d3a08a446)

## 작성시 참고
[마크업 언어 사용법 정리](https://github.com/chaSunil/markUpLanguage/blob/main/README.md)

[트러블 슈팅 양식](https://github.com/chaSunil/troubleShooting/issues/3)
<br/><br/>

## troubleShooting
[Trouble Shooting (0) 동시성 주문](https://github.com/chaSunil/troubleShooting/issues/1)
<br/><br/>

## 오류해결
[(1) Error Resolution (ERROR:ORA-01034: ORACLE not availableORA-27101: shared memory realm does not exist)](https://chainterior.tistory.com/237)

[(2) Error Resolution (Pulling 1 repository Checkout conflict with files)](https://chainterior.tistory.com/277)

[(3) Error Resolution (Mybatis mapper 오류)](https://www.notion.so/Spring-42682aa5b10e466a9b732564b4ed0e4a?pvs=4#64c94b3d1bea4641828ba0d758c49ce1)

> mapped statements collection does not contain value for orders.insertorders
servlet.service() for servlet [dispatcherservlet] in context with path [] threw exception [request processing failed: org.mybatis.spring.mybatissystemexception] with root cause
.bindingexception: invalid bound statement (not found): com.githrd.figurium.order.dao.ordermapper.insertorders] with root cause

[(4) Error Resolution (Gradle 매개변수 충돌)](https://www.notion.so/Spring-42682aa5b10e466a9b732564b4ed0e4a?pvs=4#24c43b5f465f40f6a8f95cc8de345dfb)

> : Servlet.service() for servlet [dispatcherServlet] in context with path [] threw exception [Request processing failed: java.lang.IllegalArgumentException: Name for argument of type [int] not specified, and parameter name information not available via reflection. Ensure that the compiler uses the '-parameters' flag.] with root cause
java.lang.IllegalArgumentException: Name for argument of type [java.lang.String] not specified, and parameter name information not found in class file either.
No qualifying bean of type 'com.example.demo.MemberRepository' available: expected single matching bean but found 2: memoryMemberRepository,memberRepository
