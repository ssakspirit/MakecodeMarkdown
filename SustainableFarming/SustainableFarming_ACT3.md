### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1
```template
//
```
### @explicitHints true
### @flyoutOnly 0
# 활동 3 – 예측 분석.
## 1단계
이제 최적의 농업 위치를 찾을 AI를 코딩해야 합니다. 
지난 활동에서 작성한 **현재** 데이터셋을 사용하고 
위성 관측소에서 이미 보유하고 있는 **과거** 데이터셋과 **비교**해야 합니다.

## 2단계
먼저 `||AI: semi-supervised machine learning(준지도 기계학습)||` 코딩 블록을 사용하고 그 안에 `||Datasets: input datasets(데이터셋 입력)||` 코딩 블록을 배치하세요.
그 다음에 `||Datasets: compare datasets(데이터셋 비교)||` 코딩 블록을 배치하세요. **현재** 데이터셋과 **과거** 데이터셋으로 설정하세요.

## 3단계
그런 다음 `||AI: run predictive analysis(예측 분석 실행)||` 코딩 블록을 배치하고, `||Output: find best farming locations(최적 농업 위치 찾기)||` 코딩 블록을 이어서 배치하세요. 
이제 코드를 실행하면 AI가 최적의 농업 위치를 찾고 밝게 표시합니다.

```ghost
Datasets.compare_SF()
Datasets.input_SF()
AI.ml_SF(function(){})
AI.analyze_SF()
Output.locateFarm_SF()
```
```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```