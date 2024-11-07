# readme### 2-2. SQL(구도질의 언어)
 - DBMS에게 명령을 내리기 위한 언어
 - 예) SELECT * FROM tbl_user;

### 2-3. 설치 방법
   1. 로컬 설치(설치파일 다운로드 직접 설치)
   2. 로컬 도커
   3. 클라우드

## 3. 도커
 - 컨테이너 가상화 기술을 사용할 수 있는 프로그램
 - 컨테이너를 사용하기 위해서는 → 도커엔진 + 도커이미지
 - 도커이미지 → 도커 컨테이너의 설계 도면
 - 도커엔진 → 도커이미지대로 컨테이너를 만들어서 실행

### 3-1. 도커 명령어
  - docker ps                             # 현재  실행중인 컨테이너 목록 확인
  - docker images                         # 도커 이미지 목록 확인
  - docker logs [컨테이너 이름]            # 도커 컨테이너 로그 확인
  - docker run                            # 도커 컨테이너 실행

docker run --name mariadb -d -p 3306:3306 -e MARIADB_ROOT_PASSWORD=mariadb mariadb
