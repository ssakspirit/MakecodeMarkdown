# 활동 1 – 위대한 바다.
### @explicitHints true
### @hideIteration true 
### @flyoutOnly 0
```
player.say
```
## 1단계
우리는 산호초에 대한 기후 변화의 영향을 관찰하고 연구하기 위해 산호초 바로 옆 바다에 있습니다.
이를 위해 산호초 주변에 **네 개의** 센서를 설치해야 합니다.
배 갑판의 상자에서 센서를 가져오세요. 그다음 물속으로 잠수하여 **빨간 깃발**로 표시된 
해저의 **금색** 블록에 센서를 설치하세요.
네 개의 센서를 모두 설치하면 활동 1이 완료되며 배로 돌아갈 수 있습니다.
**이 활동에서는 코딩이 필요하지 않습니다**.

---

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
