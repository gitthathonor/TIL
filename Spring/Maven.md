# Maven

## Maven은 무엇인가?
Maven은 자바용 프로젝트 관리도구이며, Apache License로 배포되는 오픈 소스 소프트웨어이다.

Maven같은 관리도구를 사용하게 되면 지금까지 일일히 라이브러리 등을 압축파일로 주고 받았던 방식에서 벗어나서 여러명이서 협업을 할 때, pom.xml 파일에다가 사용하는 라이브러리를 양식에 맞게 적어놓은 다음에 프로젝트를 실행할 때마다 웹상에서 다운받아서 사용할 수 있도록 해준다.

## Maven의 장점
1. 라이브러리의 관리를 매우 편하게 해준다.
2. 프로젝트의 여러 라이프사이클에 포함되는 각 테스트들을 지원해준다.
3. war기반의 배포용으로도 자주 사용된다.

## Maven의 LifeCycle
https://miro.medium.com/v2/resize:fit:1100/format:webp/1*_-K1nhOZhHeCxW1nlZ9VBw.png
Build : 각각의 phase에 연계된 goal을 실행하는 과정
LifeCycle : 미리 정의된 빌드 순서

## 대표적인 LifeCycle의 종류
- Maven build : 빌드를 실행한다.
- Maven clean : target에 지정된 모든 소스 삭제
- Maven install : Local Repository에 패키지를 복사
