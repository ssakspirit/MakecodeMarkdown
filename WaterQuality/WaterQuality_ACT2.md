### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# 활동 2 – 수도꼭지에서 바로.

## 1단계
이제 주변 강에서 물 샘플을 수집했으므로, 각 위치의 물 데이터로 **현재** 데이터셋을 코딩하세요.

## 2단계 
`||Datasets: current(현재)||`로 설정된 `||Datasets: make dataset(데이터셋 만들기)||` 코딩 블록을 사용하여 시작하세요. 그 안에 각 위치의 모든 `||Input: water data(물 데이터)||`를 배치하세요.

```ghost
Input.waterData1_WQ()
Input.waterData2_WQ()
Input.waterData3_WQ()
Datasets.setOfData_WQ(datasetType.historical, function() {})
```

```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```