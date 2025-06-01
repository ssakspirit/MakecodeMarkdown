### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1
```template
//
```
### @explicitHints true
### @flyoutOnly 0
# 활동 2 – 우주 밖으로.
## 1단계
이제 모든 위성 비콘을 설치했으므로, 위성을 **제어**하고 전송되는 정보로부터 **현재** 데이터셋을 코딩해야 합니다.

## 2단계
먼저 `||loops: on start(시작하면)||` 코딩 블록 안에 `||Input: control satelite(위성 제어)||` 코딩 블록을 사용하세요. 그 안에 `||Datasets: make dataset(데이터셋 만들기)||` 코딩 블록을 배치하고, 해당 블록을 `||Datasets: current(현재)||` 데이터셋으로 설정하세요.

## 3단계
그런 다음 모든 `||Input: location satellite data(위치 위성 데이터)||`를 안에 배치하세요. 실행하면 위성 카메라가 현재 데이터셋을 위한 데이터를 수집하면서 마을 위를 패닝하는 것을 볼 수 있습니다.

```ghost
Input.beacon1_SF()
Input.beacon2_SF()
Input.beacon3_SF()
Input.beacon4_SF()
Input.beacon5_SF()
Input.runSatelite_SF(function() {})
Datasets.setOfData_SF(datasetType.historical, function() {})
```
```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```