# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 윤지영
- 리뷰어 : 옥창우

|평가문항|상세기준|
|:---|:---|
|1. SentencePiece를 이용하여 모델을 만들기까지의 과정이 정상적으로 진행되었는가?|	코퍼스 분석, 전처리, SentencePiece 적용, 토크나이저 구현 및 동작이 빠짐없이 진행되었는가?|
|2. SentencePiece를 통해 만든 Tokenizer가 자연어처리 모델과 결합하여 동작하는가?|	SentencePiece 토크나이저가 적용된 Text Classifier 모델이 정상적으로 수렴하여 80% 이상의 test accuracy가 확인되었다.|
|3. SentencePiece의 성능을 다각도로 비교분석하였는가?|	SentencePiece 토크나이저를 활용했을 때의 성능을 다른 토크나이저 혹은 SentencePiece의 다른 옵션의 경우와 비교하여 분석을 체계적으로 진행하였다.|

# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 코드를 캡쳐해 근거로 첨부


### 루브릭1. SentencePiece를 이용하여 모델을 만들기까지의 과정이 정상적으로 진행되었는가?
- 코퍼스 분석, 전처리, SentencePiece 적용, 토크나이저 구현 및 동작이 빠짐없이 진행되었는가?     
    - 코퍼스 분석:
    
      <img width="353" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/ccc99e61-77a3-4143-bce5-a94e2ef3abf8">
    - 전처리:
    
      <img width="467" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/915c35cf-ae14-4778-b796-ca2f2d383f02">
    - SentencePiece 적용:
    
      <img width="795" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/26ec28a8-97b7-475d-979c-197763f045bd">
    - 토크나이저 구현 및 동작:
    
      <img width="616" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/10983ca8-43e0-4699-a851-02cc1ca27eee">

### 루브릭2. SentencePiece를 통해 만든 Tokenizer가 자연어처리 모델과 결합하여 동작하는가?	
- SentencePiece 토크나이저가 적용된 Text Classifier 모델이 정상적으로 수렴하여 80% 이상의 test accuracy가 확인되었다.
    - SentencePiece를 통해 만든 Tokenizer가 자연어처리 모델과 결합하여 동작:

      <img width="732" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/f6dbc416-d305-4cf2-b81a-3fcab7d247a5">
      <img width="729" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/d662b20f-34dd-4943-92ef-1c040b669247">
    - 80% 이상 acc:

      <img width="734" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/be82a47a-8e21-45a3-b805-5a8e35b2f4a6">

  
### 루브릭3. SentencePiece의 성능을 다각도로 비교분석하였는가?
- SentencePiece 토크나이저를 활용했을 때의 성능을 다른 토크나이저 혹은 SentencePiece의 다른 옵션의 경우와 비교하여 분석을 체계적으로 진행하였다.
    - <img width="549" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/5fcf2eb5-4062-4bf9-b591-a286066d96fc">
      <img width="599" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/078facee-6ba3-4407-b4de-ea125b5dbdb4">


- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
    
    <img width="805" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/605ad11d-7393-43cb-9586-a02aee123be6">

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
    
    <img width="578" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/e7a7d5a2-b7e2-4ba3-aeaa-a73917c8d4bc">
    <img width="646" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/d4220833-298b-4854-89a6-bc2a5828e2e5">


- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
    
    <img width="437" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/7c9c618c-125d-4074-84c6-e5f0c87bbd48">
    <img width="650" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/fdb78289-5fe2-437a-8f17-3fb5875974a2">


- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
    
    <img width="599" alt="image" src="https://github.com/wldud01/Aiffel_online_Quest/assets/124979889/b39ddbae-ba6f-4aa5-9fac-e60db3c73e96">




# 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
