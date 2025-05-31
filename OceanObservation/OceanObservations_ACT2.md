### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1
```template
//
```
### @explicitHints true
### @flyoutOnly 0
# 활동 2 – 수중 데이터.
## 1단계
이제 센서들이 설치되었으므로 **네 개의** 센서에서 나오는 모든 데이터를 저장할 **하나의** 라이브 데이터셋을 만들어야 합니다.
이것이 완료되면 네 개의 모니터에서 수면 아래에서 무슨 일이 일어나고 있는지 보고 매핑할 수 있게 됩니다.
## 2단계 
먼저 `||loops: on start(시작하면)||` 코딩 블록 안에 `||Datasets: make dataset(데이터셋 만들기)||` 코딩 블록을 사용하세요.
해당 블록을 `||Datasets: live(실시간 데이터셋)||` 데이터셋으로 설정하세요.
## 3단계
그다음 데이터셋 안에 `||Input: sensor data(센서가 수집한한 데이터)||`를 배치하세요.
```ghost
Input.sensor1_OO()
Input.sensor2_OO()
Input.sensor3_OO()
Input.sensor4_OO()
Datasets.setOfData_OO(datasetType.historical, function() {})
```
```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```
