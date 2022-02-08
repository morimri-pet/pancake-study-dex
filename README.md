# PancakeSwapの勉強用リポジトリ

## 環境構築
- pull from repository
- copy smample.env to .env
- cd /mnt/node
- git clone https://github.com/pancakeswap/pancake-frontend.git

- cd /projectroot
- docker-compose up -d
- docker-compose exec node bash


下記を修正

mnt\node\pancake-swap-sdk\src\constants.ts
```
export const FACTORY_ADDRESS = 'xxx'
export const INIT_CODE_HASH = 'xxx'
```

mnt\node\pancake-frontend\src\config\constants\index.ts
```
export const ROUTER_ADDRESS = 'xxx'
```


# local
docker-compose up -d
docker-compose exec node bash
cd pancake-frontend
yarn dev

