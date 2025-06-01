### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1
```template
//
```
### @explicitHints true
### @flyoutOnly 0
# 활동 2 – 패턴, 패턴, 패턴...
## 단계 1
이제 몇 마리의 다른 오셀롯들로부터 다양한 털 패턴을 가진 대량의 사진 데이터를 수집했으므로, 데이터셋을 코딩할 수 있습니다.
 
## 단계 2 
`||Datasets: make dataset(데이터셋 만들기)||` 코딩 블록을 사용하여 시작하고, `||Datasets: historical(과거 데이터셋)||`로 설정합니다. 그 안에 방금 수집한 모든 `||Input: trap camera data(트랩 카메라 데이터)||`를 배치합니다.

## 단계 3 
마지막 단계로 사진 데이터에서 오셀롯 털의 패턴을 추출해야 합니다. `||Datasets: extract patterns(패턴 추출)||` 코딩 블록을 사용합니다.
이제 코드를 실행하면 오셀롯 패턴의 미리보기가 컴파일됩니다.
```ghost
Input.trap1_PR()
Input.trap2_PR()
Input.trap3_PR()
Datasets.extractPatterns_PR()
Datasets.setOfData_PR(datasetType.historical, function() {})
```
```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```