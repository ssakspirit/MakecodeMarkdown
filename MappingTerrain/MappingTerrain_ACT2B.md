### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# 활동 2 – 모든 것을 지도로 만들기.

## 1단계
이 활동에서는 촬영한 모든 사진을 **하나**의 큰 `||datasets: dataset(데이터셋)||`으로 결합해야 합니다. 이 모든 데이터는 컴파일되어
숲의 큰 지도로 표시됩니다. 먼저 `||loops: on start(시작하면)||` 코딩 블록 안에 `||datasets: make dataset(데이터셋 만들기)||` 코딩 블록을 사용하세요.

## 2단계
**세** 위치에서 가져온 **모든** 데이터를 `||datasets: make dataset(데이터셋 만들기)||` 코딩 블록 안에 배치하세요. `||Input: picture data(사진 데이터)||` 
코딩 블록들은 `||Input: INPUT(입력)||` 탭에 있습니다.

```ghost
Input.location1PictureData_MTB()
Input.location2PictureData_MTB()
Input.location3PictureData_MTB()
Datasets.setOfData_MTB(function() {})
```

```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```