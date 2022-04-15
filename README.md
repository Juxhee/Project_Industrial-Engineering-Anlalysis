## 온라인 커뮤니티 데이터 기반 산업공학 분석
- 잡코리아, 유튜브, 디시인사이드, 네이버 카페(독취사, 스펙업), 네이버 블로그, 네이버 지식인 데이터 활용
- 학생 및 일반인의 산업공학에 대한 관심도, 주요 관심 분야 및 동향 파악을 통한 산업공학 교육 방향성 설정을 목표로 한 온라인 커뮤니티 분석

## 키워드 분석

- dataset

`cafe.csv, jk.csv, orbi.csv`

- 빈도 기반

`keyword_analysis.ipynb`

</br>

- text rank 기반

`text-rank_keyword_analysis.ipynb`


</br>
</br>


## 토픽 모델링
- LDA를 활용한 토픽모델링
- 2019, 2020, 2021 긍/부정 데이터에 대해 각각 진행
```python
# 2019 긍정 데이터 
final_pos_2019.csv

# 2019 부정 데이터 
final_neg_2019.csv
```
```python
# 2020 긍정 데이터 
final_pos_2020.csv

# 2020 부정 데이터 
final_neg_2020.csv
```
```python
# 2021 긍정 데이터
final_pos_2021.csv

# 2021 부정 데이터 
final_neg_2021.csv
```
- 산업공학 분야 중 크게 IT분야, 전통 산업공학 분야를 토픽으로 LDA 진행
- 네트워크 클러스터링 sub clustering 결과를 참고하여 topic 수 조정해가면서 실험 진행
- 토픽 별 주요 키워드 및 주요 문장을 추출하여 IT 분야, 전통 산업공학 분야에 해당하는 토픽을 선정

`cluster_lda_2019.ipynb`
`cluster_lda_2020.ipynb`
`cluster_lda_2021.ipynb`
