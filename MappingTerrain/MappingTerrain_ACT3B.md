### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# 활동 3 – 이상 징후 탐지.

## 1단계
이 활동에서는 만든 데이터셋을 기계학습 알고리즘에 사용해야 합니다. 이 알고리즘은 데이터셋에서 이상 징후를 찾아
지도에 표시해야 합니다. 먼저 `||loops: on start(시작하면)||` 코딩 블록 안에 `||AI: machine learning(기계학습)||` 코딩 블록을 사용하세요.

## 2단계
그 안에 `||Datasets: input dataset(데이터셋 입력)||` 코딩 블록을 배치하세요. 그런 다음 `||AI: analyze data(데이터 분석)||` 코딩 블록을 배치하세요.

## 3단계
이제 데이터를 가져와서 분석했고, 알고리즘이 결과를 가지고 있어야 합니다. 하지만 지도에서 결과를 볼 수 있도록 
`||Output: show locations(위치 표시)||` 코딩 블록을 배치하세요.


```ghost
Datasets.input_MTB()
AI.analyze_MTB()
Output.showLocations_MTB()
AI.ml_MTB(function() {})
```

```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```