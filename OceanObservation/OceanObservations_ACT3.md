### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1
```template
//
```
### @explicitHints true
### @flyoutOnly 0
# 활동 3 – 미래 대비하기
## 단계 1
이제 안정적인 데이터 스트림이 들어오고 있으므로, 이러한 산호초에 대한 기후 변화의 영향에 관한 연구를 시작할 수 있습니다. 그러나 센서가 고장날 경우를 대비해 AI를 사용하여 센서에 도달하고 자동으로 수리하려고 합니다. 
이것은 우리가 수집하고 있는 실시간 데이터를 활용한 **자율 항법**을 통해 가능합니다.
## 단계 2 
`||loops: on start(시작할 때)||` 코딩 블록 안에 `||AI: machine learning(머신러닝)||` 코딩 블록을 사용하세요.
이 블록 안에 `||datasets: live dataset(실시간 데이터셋)||`으로 설정된 `||Datasets: input dataset(입력 데이터셋)||` 코딩 블록을 배치하세요.
그 다음에 `||AI: analyze terrain data(지형 데이터 분석)||` 코딩 블록을 배치하세요. 
## 단계 3
그다음 `||AI: generate routes(경로 생성)||` 코딩 블록을 배치하세요. 
이제 실행하면 AI가 에이전트가 취할 경로를 생성하여 다양한 산호와 충돌하지 않게 됩니다. 
또한 지도상에서 해저 지형을 볼 수 있게 됩니다. 
```ghost
AI.analyze_OO()
AI.ml_OO(function() {})
Datasets.input_OO()
AI.genRoutes_OO()
```
```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```