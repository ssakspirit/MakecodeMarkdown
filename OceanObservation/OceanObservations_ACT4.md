### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1
```template
//
```
### @explicitHints true
### @flyoutOnly 0
### @hideIteration true 
# 활동 3 – 테스트해보기
## 1단계
AI가 컴파일한 생성된 경로가 올바른지 확인해야 합니다. 이를 위해 `||loops:on start(시작할 때)||` 코딩 블록 안에 `||AI:autonomous navigation algorithm(자율 내비게이션 알고리즘)||` 코딩 블록을 사용하세요. 그 안에서 (`||Output: OUTPUT(출력)||` 탭의 코딩 블록을 사용하여) 에이전트가 도달해야 하는 센서를 지정하세요. 에이전트가 도달해야 하는 센서는 **2번**과 **4번**입니다.
```ghost
AI.ml_OO2(function(){})
Output.reach1_OO()
Output.reach2_OO()
Output.reach3_OO()
Output.reach4_OO()
```
```package
aicustomblocks=github:fountainstudios/AICustomBlocks
```