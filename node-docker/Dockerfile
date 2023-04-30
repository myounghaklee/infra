FROM node

# workdir를 설정하면 그 아래의 모든 명령어는 /app 내에서 실행한다. 
WORKDIR /app
COPY . /app
RUN npm install

EXPOSE 80
# CMD 명령어는 이미지를 기반으로 컨테이너가 시작될때 설행된다. 
CMD ["node",  "server.js"]