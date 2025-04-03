# WHS3 Secure Coding 18 - Lee Seung won(0806)

## Tiny Second-hand Shoppiong Platform

[ 기능(요구 사항) ]
1. 사람들이 플랫폼에 가입할 수 있어야 함
2. 상품들을 올리고 볼 수 있어야 함
3. 플랫폼 사용자들끼리 소통이 가능해야함
4. 악성 유저나 상품을 차단 해야 함
5. 유저들 간의 송금이 가능해야함
6. 상품을 검색할 수 있어야 함
7. 관리자가 플랫폼의 모든 요소를 관리할 수 있어야 함

위 내용 중 5~7은 시스템 분석부터 진행할 것


## Settings
실행 환경 세팅은 아래와 같습니다. (유호곤 멘토님이 작성하신 https://github.com/ugonfor/secure-coding README.md 내용과 같음)

### requirements
---
if you don't have a miniconda(or anaconda), you can install it on this url. - https://docs.anaconda.com/free/miniconda/index.html

```bash
git clone https://github.com/ugonfor/secure-coding
conda env create -f enviroments.yaml
```

### usage
---
run the server process.


```bash
python app.py
```

if you want to test on external machine, you can utilize the ngrok to forwarding the url.

```bash
# optional
sudo snap install ngrok
ngrok http 5000
```