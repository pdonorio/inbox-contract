
# app

## setup

In Sublime install package `Ethereum` to see the highlights.

## docker to the rescue

```bash
docker-compose up -d && docker-compose exec js ash

# only the first time
apk update && apk add git
yarn install

# all the times
yarn start
```

## compile

Solidity compiler to get ABI + Bytecode and deploy it in the real network.
