# springboot-admin-server
Springboot admin server example

[참고 사이트](https://jaehyun8719.github.io/2019/06/20/springboot/admin/)

## 사용방법

### 빌드
```shell script
$ ./gradlew build
```

### Run (with spring boot plugin)
```shell script
$ ./gradlew bootRun
```

### Run (with JAR)
```shell script
$ java -jar ./build/libs/*.jar
```

## 접속 정보 설정
[application.properties](./src/main/resources/application.properties) 파일을 수정 필요

아이디 / 패스워드를 적절히 바꿔서 사용해야 함

```properties
# 포트 설정
server.port = 18080

# Admin 아이디 / 비밀번호 세팅
spring.security.user.name=omnipede
spring.security.user.password=password
```