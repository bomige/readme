## 심전도(Electorcardiogram,ECG) 데이터 분류  - Team : 데이탑
데이탑 팀의 "심전도 데이터 분류"에 대한 실행 가이드를 위한 파일입니다.
### 실행 환경
>+ Jupyter Lab
>+ tensorflow 2.7.0
>+ keras 2.7.0
>+ librosa 0.8.1
>+ xmltodict 0.12.0

### 실행 방법
#### Train 파일 폴더 구조
학습에 적용한 train, validation 폴더 구조입니다.   
동일한 구조로 사용 부탁드립니다.  
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
