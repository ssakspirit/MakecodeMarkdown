### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# 활동 3 – 전문가 추적기

## 1단계
이제 오셀롯을 추적할 AI를 코딩해야 합니다.
사바나에서 들어오는 **현재** 데이터를 사용해야 하고,
지난 활동에서 편집한 **과거** 데이터셋과 **비교**해야 합니다.

## 2단계
먼저 `||AI: semi-supervised machine learning (인공지능: 준지도 기계학습)||` 코딩 블록을 사용하고 그 안에 `||Datasets: input datasets (입력 데이터셋)||` 코딩 블록을 배치하세요.
그 다음 `||Datasets: compare datasets(데이터셋 비교)||` 코딩 블록을 배치하세요. **현재** 데이터셋으로 설정한 다음 **과거** 데이터셋으로 설정하세요.

## 3단계
그런 다음 `||AI: analyze pattern data(패턴 데이터 분석)||` 코딩 블록을 배치하세요. 그 다음에 `||Output: locate ocelots(오셀롯 위치 찾기)||` 코딩 블록을 배치하세요.
이제 코드를 실행하면 오셀롯 위치의 지도가 나타날 것입니다.

```ghost
Datasets.compare_PR()
Datasets.input_PR()
AI.ml_PR(function(){})
AI.analyze_PR()
Output.locateOcelots_PR()
```

```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```