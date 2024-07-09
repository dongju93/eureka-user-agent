## Command line
```shell
# Spring 실행
mvn spring-boot:run -Dspring-boot.run.jvmArguments='-Dserver.port=9004'

# Build clean
mvn clean

# Build
mvn compile package
# ROOT_DOR/target/user-service-0.0.1-SNAPSHOT.jar 파일 생성

# 빌드 파일 활용 실행
java -jar -Dserver.port=9006 ./target/user-service-0.0.1-SNAPSHOT.jar 
```