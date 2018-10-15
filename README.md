# algorithms
in studying..

# JAVA JDK 설치
* JDK dmg 다운로드 및 설치. https://www.oracle.com/technetwork/java/javase/downloads/index.html
* "JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk-10.0.2.jdk/Contents/Home" >> ~/.bash_profile

# 코드 실행방법
* javac
-cp: 참조하려는 클래스패스
-d: 생성한 클래스의 출력위치

* java
-cp: 참조하려는 클래스패스

* 참조하려는 클래스패스가 없는 경우
javac Main.java: "-d ." 옵션이 디폴트이고, 클래스패스가 없음
java Main
