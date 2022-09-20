# nodejs-http

## Dockerコンテナの起動
docker-compose up -d  
※--build オプションは、Dockerfile を変更したときに必要なオプションです。  
docker-compose exec app bash  

### コンテナを終了、破棄
docker stop $(docker ps -aq)  
docker rm $(docker ps -aq)  

## Node.jsプロジェクトの初期化
yarn init  

## プログラムの実行
node index.js  

## git
git init  
git add .  
git commit -m "comment"  
git remote add origin https://github.com/ysk-hello/nodejs-http.git  
git push origin master  
※passwordとして、tokenを使う  

## yarn
* yarn install
* yarn add
