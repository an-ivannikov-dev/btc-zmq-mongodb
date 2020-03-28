# BTC->ZMQ->MongoDB

## Варианты работы

- [ ] BTC-(RAW Block&TX)->ZMQ->APP-(RAW Block&TX)->MongoDB
- [ ] BTC-(RAW Block&TX)->ZMQ->APP-(Decoded Block&TX)->MongoDB
- [ ] BTC-(HASH Block&TX)->ZMQ->APP-(GET Decoded Block&TX)->RPC->BTC-(Decoded Block&TX)->RPC->APP->MongoDB

## Установка

```bash
git clone https://github.com/an-ivannikov-dev/btc-zmq-mongodb.git
cd btc-zmq-mongodb
yarn install
yarn start
```
