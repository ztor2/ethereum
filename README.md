### 이더리움 블록체인 고래 지갑 데이터 분석

- Etherscan과 Infura API를 이용해 최근 50개 블록의 트랜잭션 데이터 수집.
- 이더 잔고가 100ETH 이상인 지갑이 참여한 트랜잭션 정보만을 수집 후 그래프 모델링.
- 지갑 잔고와 트랜잭션 수를 함께 분석하면 거래소 지갑을 추정할 수 있다.
- 그래프 데이터베이스를 활용하여 많은 트랜잭션 수를 가지는 지갑을 효율적으로 검색할 수 있다.
<br>

<p align="center"> <img src="https://i.esdrop.com/d/f/stu7PPILpD/0Lk5LpSaf1.png" width="40%" align="center"> </p>
<p align="center">  <b> 그림 1. </b> 블록체인 트랜잭션 데이터 그래프 모델링. </p>

<br>

<p align="center"> <img src="https://i.esdrop.com/d/f/stu7PPILpD/bkO94SNXSV.png" width="60%" align="center"> </p>
<p align="center">  <b> 그림 2. </b> 블록체인 트랜잭션 데이터 그래프 데이터베이스 적재 결과. </p>

<br>

<p align="center"> <img src="https://i.esdrop.com/d/f/stu7PPILpD/LTpmGq1oci.png" width="85%" align="center"> </p>
<p align="center">  <b> 그림 3. </b> 그래프 데이터베이스를 활용한 거래소 지갑 추정. </p>



