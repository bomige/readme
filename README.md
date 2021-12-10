## 심전도(Electorcardiogram,ECG) 데이터 분류  - Team : 데이탑
데이탑 팀의 "심전도 데이터 분류"에 대한 실행 가이드를 위한 파일입니다.
### 실행 환경
+ Jupyter Lab 3.1.7
+ tensorflow 2.7.0
+ keras 2.7.0
+ librosa 0.8.1
+ xmltodict 0.12.0

### 실행 방법
#### Train 파일 폴더 구조
 학습에 적용한 train, validation 폴더 구조fj, 동일한 구조로 평가 부탁드립니다.  
 #### "ECG_TEST_MODEL.ipynb"를 실행하시고 "DATA_DIR" 만 변경해주시고 실행 하시면 됩니다.
```c
data
├──── train
│       ├── normal
│       └── arrhythmia
└──── validation
        ├── normal
        └── arrhythmia
```
참고: 지정 폴더에서 Normal, arrhythmia 폴더의 파일명과 경로를 가져와 dataframe에 저장  
      decoding시 문제되는 파일과 Waveform data 조합 시 길이가 달라 error가 발생되는 파일에 대해 제거  
      제거 후 최종 dataframe에서 train & test 데이터 생성 됨


### 필요한 라이브러리 설치
+ pip install librosa  
+ pip install xmltodict  
