# 1. 베이스 이미지 선택
FROM adoptopenjdk:11-jre-hotspot

# 2. 작업 디렉토리 생성 및 설정
WORKDIR /app

# 3. 빌드된 JAR 파일 복사
COPY target/demo.jar /app/demo.jar

# 4. 실행 명령어 설정
CMD ["java", "-jar", "your-application.jar"]