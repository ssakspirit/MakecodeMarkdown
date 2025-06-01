### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# 활동 3 – 여기저기 오염 물질.

## 1단계
이제 오염원을 찾을 AI를 코딩해야 합니다. 이를 위해서는 지난 활동에서 
코딩한 **현재** 데이터셋을 **분석**하고 오염 물질의 농도가 가장 높은 위치를 찾아야 합니다.

## 2단계
먼저 `||AI: supervised machine learning(지도 기계학습)||` 코딩 블록을 사용하고 그 안에 **현재**로 설정된 `||Datasets: input datasets(데이터셋 입력)||` 코딩 블록을 배치하세요.

## 3단계
그런 다음 `||AI: analyze water data(물 데이터 분석)||` 코딩 블록을 배치하세요. 이어서 `||Output: locate pollution sources(오염원 위치 찾기)||` 코딩 블록을 배치하세요.
이제 코드를 실행하면 AI가 오염의 발생원 위치를 찾을 것입니다.


```ghost
Datasets.input_WQ()
AI.ml_WQ(function(){})
AI.analyze_WQ()
Output.locatePollution_WQ()
```

```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```