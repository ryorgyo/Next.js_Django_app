# nodeの最新バージョンを取得する
FROM node
# 開発フォルダとしてfrontフォルダを作成する
RUN mkdir /front
WORKDIR /front
# npmを最新化し、nextをインストールする
RUN npm install -g npm@latest && npm install create-next-app