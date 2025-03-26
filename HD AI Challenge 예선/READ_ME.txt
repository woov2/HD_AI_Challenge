파일 실행 순서.

1. file_woo.zip을 통해 final_sub_woo.csv submission 생성

2. 이 후 해당 csv(final_sub_woo.csv)를 본 폴더 submission 폴더에 옮긴후 진행.

3. notebook 폴더 속 LGBM_SEED_ENSEMBLE.ipynb 파일에서 lgbm 모델링 및 추론을 통해 lgbm_seed_ensem.csv submission을 submission 폴더 안에 생성.

4. notebook 폴더 속 Machine_Choi_After_processing_Final.ipynb 파일에서 submission 폴더 속 final_sub_woo.csv 와 lgbm_seed_ensem.csv 두개의 submission을 불러와 3대 7으로 앙상블 후 후처리 진행.

5. 후처리 후 최종 제출용 submission 파일 FINAL_7_3_afterprocessing.csv을 submission 폴더 속에 생성.

6. 최종 제출 submission 파일 : FINAL_7_3_afterprocessing.csv
