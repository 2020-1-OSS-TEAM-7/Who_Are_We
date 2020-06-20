---
   title : "Wha Are 양동재?" 

   categories : 
       양동재
   
   description : "양동재는 누구인가?"

   toc : True

   toc_label : "목차"

   tags : 
       who_are_we?

   last_modified_at : 2020-06-16

---

# **_Who Are 양동재?_**
![](https://yangdongjae.github.io/assets/images/About/About-Profile-img2.png)
<br/>
student of AI Software Engineering <br/>
<br/>
<br/>
<br/>

### 철학

> 인생은 원하는 데로, 단 인생을 되돌아봤을 때 **누구보다 행복하게 웃을 것**

### 소개

* Github : [https://github.com/YangDongJae](https://github.com/YangDongjae)
* [Linkedin](https://www.linkedin.com/in/dongjae-yang-88918b175/)
* Mail : ydj9805@gmail.com
* blog : [양동재블로그](https://yangdongjae.github.io)

### California Housing Data Machine Learning

* Path설정을 통해 온라인으로 dataset 다운로드

```python
import os
import tarfile
from six.moves import urllib

DOWNLOAD_ROOT = "https://raw.githubusercontent.com/ageron/handson-ml/master/"
HOUSING_PATH = os.path.join("datasets","housing")
HOUSING_URL = DOWNLOAD_ROOT + "datasets/housing/housing.tgz"

def fetch_housing_data(housing_url=HOUSING_URL, housing_path = HOUSING_PATH):
    if not os.path.isdir(housing_path):
        os.makedirs(housing_path)
    tgz_path = os.path.join(housing_path, "housing.tgz")
    urllib.request.urlretrieve(housing_url, tgz_path)
    housing_tgz = tarfile.open(tgz_path)
    housing_tgz.extractall(path = housing_path)
    housing_tgz.close()
```


### 경력

|  | 기간  | 담당업무 |
| :---------:|:---------:|:---------:|
| ![](https://yangdongjae.github.io/assets/images/About/AECF.png)<br/> Asia Economic Community Forum | 2017.06.03 ~ 2017.12.31    | 2017 아시아 경제공동체 포럼 기획 <br/> Model Asia Union 국제 학술대회 기획 및 운영 <br/>협력업체 선정 및 국제 포럼 홍보 및 마케팅 수행  |
| ![](https://yangdongjae.github.io/assets/images/About/PRISM.png)<br/>PRISM    |  2017.06.02 ~ 2017.10.31   |  PRISM 주관 교육행사 및 네트워킹 파티 기획 보조 <br/>  |
| ![](https://yangdongjae.github.io/assets/images/About/Vib.png)<br/>Vib    | 2017.11.01 ~ 2018.04.30    |  Front-end 개발 <br/>Plant 325 중,고등생 교과서 E북 개발 프로젝트 참여  |

### 대외활동 

| &nbsp;&nbsp;대&nbsp;&nbsp;외&nbsp;&nbsp;활&nbsp;&nbsp;동&nbsp;&nbsp;명 | 기간  |내용 | 설명 |
| :---------:|:---------:|:-----------------------------:|:---------:|
|![](https://yangdongjae.github.io/assets/images/About/AYC.png)<br/>아시아 청년연합<br/>서포터즈|2020.1.11 ~ 2020.04.11| ○[이슬람 종교 차별에 대한 <br/>  사회적 영상 기획 및 제작](https://www.youtube.com/watch?v=3uM8zKF3gJE)<br/> ○'20대가 생각하는 취업과 창업'을 주제로 영상 기획 및 제작 <br/>○외국인 서포터즈 프로그램기획 |Asia Federation Youth 의 아시아 청년 연합 서포터즈에 참가하여, 창업, 문화교류, 취업 을 주제로 영상과 발표자료를 기획하고 제작하여 대중들 앞에서 발표.|
|![](https://yangdongjae.github.io/assets/images/About/cool_Lion.png)<br/>멋쟁이 사자처럼|2020.04.11 ~ |||








