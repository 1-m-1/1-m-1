## Semi-Supervised Learning을 이용한 로마의 LCZ 분류 성능 향상

### 1. 프로젝트 계획 이유
LCZ(Local Climate Zone)는 토지 피복 특성에 따라 도시를 분류하는 체계로써 지표의 현황 및 변화를 잘 반영하기 때문에 다양한 연구에서 활용된다.
그러나 LCZ 참조 데이터가 구축되어있지 않은 경우 직접 구축해야하므로 많은 시간과 비용이 발생한다.
Semi-supervised learning 적용을 통해 참조 데이터 구축 과정의 시간과 비용을 감소시키고 기존 모델 이상의 성능을 달성하기 위해 프로젝트를 계획하였다.

### 2. 프로젝트 목적
본 연구는 CNN을 사용해 로마 지역의 LCZ 분류를 수행한다.
이때 Semi-supervised learning 기법을 적용해 성능을 향상시킨다.

### 3. 사용방법
1. 파일 다운로드
2. 구글 드라이브에 파일 업로드
3. ML2_LCZ_Semi_final.ipynb 실행
4. 코드에서 파일 위치 수정
+ 코드 수정 부분(5번째 셀)

```
root_dir = 'Fill this'
work_dir = root_dir +'Fill this'
tr_dir = work_dir + '/train'
va_dir = work_dir + '/val'
te_dir = work_dir + '/test'
u_dir = root_dir + '/random sampling'
model_dir1 = root_dir+'/model_dir'
```
*fill this 부분에 구글 드라이브 파일 위치를 넣어주세요*

### 4. CITATION
```
@report{
  author = {Jeong youngmin,Kim yechan, Nam geonoh},
  month = {12},
  number = {1},
  pages = {1--5},
  title = {{Improvement of LCZ classification performance in Rome using Semi-superviced learning}},
  volume = {1},
  year = {2022}
}
```
