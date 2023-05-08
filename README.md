# infra

# Docker Container
각각의 컨테이너 들은 서로 독립적이다. 
각각ㄱ의 프로세스, 서비스, 네트워크, 인터페이스, 마운트 들을 가지고 있다. 
각각의 os들은 os kernel과 software 로 구성되어있다. 
os kernel은 기반 하드웨어와 상호 작용하는 역할을 하며 소프트웨어는 ui, 드라이버 파일 관리자, 개발자 툴 등이 있다. 

Docker는 같은 커널을 가지고 있다면 어떤 운영체제든 실행 할 수 있다. 
 

 ## docker 명령어 정리
 `docker run -p 8080:80 [imageId]` : -p는 publish 옵션 이므로 8080포트로 들어온 여총을 dockerfile에 `EXPOSE 80 `로 명시해놓았다면 80 포트로 연동 해라

 ### Image 관련 명령어

- `-t` : 태그 
- docker images : 이미지 list show
- docker image inspect : 이미지 분석
- docker rmi, docker prune : 이미지 삭제 

### Container 관련 명령어
- `--name`: 선테이너 내임 설정
- see --help : 세부사항 보기 
- docker ps : 컨테이너 리스트
- docker rm : 컨테이너 삭제