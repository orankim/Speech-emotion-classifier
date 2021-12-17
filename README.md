 Speech Emotion Classifier
 =============================================================
 
 ### 분석 배경 및 목적
 
1. 음성 분석 기술의 변화
- 음성인식 -> 텍스트 변환 예) Speech to Text
- 음성인식 ->의미 파악  대답 예) 인공지능 스피커
- 음성인식 -> 감정분석

2. 음성 감성 분석 기술의 적용 예시
- 엠파스(Empath)와 일본 컨택센터 TMJ
- 센트릭(CENTRIC)과 WOWOW 커뮤니케이션즈 

### 사용 데이터

1. RAVDESS(Ryerson Audio-Visual Database of Emotional Speech and Song)
2. CREMA-D(Crowd-sourced Emotional Multimodal Actors Dataset)
3. SAVEE(Surrey Audio-Visual Expressed Emotion)
4. TESS(Toronto Emotional Speech Set)

### 음성 데이터 특징 분석 도구
1. Librosa
2. MFCC

### 결과
1. Epoch가 증가할 수록 Train, Test 데이터 둘 다 loss가 감소함
2. Train 데이터의 정확도는 Epoch가 증가할수록 상승하나 Test 데이터는 300부터 변화가 거의 없음

### 예측 결과
1. 성별 별 감정 정확도는 42%로 계산됨. 가장 높은 수치는 여성의 놀란 감정이며, 가장 낮은 수치는 남성의 공포 감정임
2. 성별 정확도는 80%로 계산됨. 여성보다 남성 목소리의 예측이 더 어려운 경향이 있음
3. 감정 정확도는 49%로 계산됨. 가장 높은 수치는 놀란 감정이며, 가장 낮은 수치는 공포 감정임


