# gpt2 based one on one interactive novel creation

## 개요

### 1. AI hub에서 소설데이터를 추출한 뒤 Q&A 형식으로 파인튜닝을 시키기 위해 데이터 전처리를 진행했습니다.

![image](https://github.com/user-attachments/assets/e101e964-25ac-4517-8821-fc37122a07f7)

![image](https://github.com/user-attachments/assets/d01281f4-645c-4674-bea5-f54292c03dc9)

![image](https://github.com/user-attachments/assets/3279c19b-b1a2-48e9-8a27-f9f65d8ff67d)
서사구조단계 발단, 전개, 위기, 절정, 결말로 축소

### 2. 파인튜닝 시킨 데이터의 등장인물 형식에 맞게 문장을 생성하도록 등장인물 변환기를 만들었습니다.

![image](https://github.com/user-attachments/assets/642f1214-e427-443e-96bb-08008aa04fc5)

### 3. gradio를 통해 대화형 소설을 구현했습니다.

![image](https://github.com/user-attachments/assets/f0b235e0-4c15-43be-9f69-77cded0b7146)


### 보완할 점
1. 파인튜닝할 때 Q&A task 뿐만 아니라 여러 task를 동시에 수행할 수 있도록 손실함수를 구성해서 성능 향상 가능
2. 다중 task LLM 고려
