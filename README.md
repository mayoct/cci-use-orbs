# CircleCI Orb を使ってみよう
[![CircleCI](https://circleci.com/gh/mayoct/cci-use-orbs/tree/step03.svg?style=svg)](https://circleci.com/gh/mayoct/cci-use-orbs/tree/step03)## Step 01
まずは Node.js + Express の組み合わせでサンプルアプリケーションを構築
(https://github.com/mayoct/cci-use-orbs/tree/step01)
### 使用Orb
なし (CircleCI 未適用)

## Step 02
次に サンプルアプリケーションを Dockerコンテナ化し、CircleCI でコンテナをビルド
(https://github.com/mayoct/cci-use-orbs/tree/step02)
### 使用Orb
なし

## Step 03 (ここ)
最後に CircleCI を使って、コンテナを Heroku 上にデプロイ
(https://github.com/mayoct/cci-use-orbs/tree/step03)
### 使用 Orb
- circleci/docker (https://circleci.com/developer/orbs/orb/circleci/docker)
- circleci/heroku (https://circleci.com/developer/ja/orbs/orb/circleci/heroku)