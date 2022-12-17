<!-- ### Hi there 👋

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/></a>

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/></a>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/></a>
<img src="https://img.shields.io/badge/DJango-092E20?style=flat-square&logo=Django&logoColor=white"/></a> -->



# 한정우 / Jungwoo Han
### MLops / Vision / 3D Vision / Multi-Modal

## About Me
 - MLops
 - 24시간 코딩하는 개발자
 - [백준](https://www.acmicpc.net/user/hanjungwoo2)
 - CleanCode

### Study
 MLops
 - Kubeflow
 - 핵심만 콕 쿠버네티스
 - 쉽게 시작하는 캐글 데이터 분석
 - 머신러닝 탐구생활
 - Idea : CI/CD, Data Pipeline : 지속학습 가능한 데이터(ex) [by crawling], 금융데이터)
 - Kaggle
 
 Coding Test
 - backjoon
 - Programmers
 - 이것이 코딩테스트다
 - 파이썬 알고리즘 인터뷰
 - Clean Code

 Interview
 - [개념 정리](https://github.com/hanjungwoo1/CodingTest/tree/main/Interview)

## Skill Set
|구분|Skill|
|-----|----|
|Programming Languages|Python, Go, Java, C, Javascript, HTML5, CSS3, C#|
|Framework/Library|Pytorch, Tensorflow, Keras, jQeury|
|Server|MySQL, MongoDB, Docker Registry|
|Tooling/Devops|Docker, Github, Kubernetes, Kubeflow, Unity|
|Environment|GCP, Linux, Window|

<!-- Programming Languages : Python - 중, JAVA - 중, C - 중, C++ - 중, C# - 하, JavaScript - 하, Html5 - 하, Css - 하
Framework/Library : Pytorch - 중, Tensorflow - 중, Keras - 중, Pandas - 중, Numpy - 중
Server : MySQL - 하, MongoDB - 하, Docker Registry - 하
Tooling/Devops : Docker - 중, Github - 중, Kubernetes - 하, Kubeflow - 하, Unity - 하
Environment : Linux - 중, GCP - 하, Window - 하 -->


## Projects
### Line InternShip[7.04 ~ 8.26] : Ads ML Engineer 
 - 주요 업무 : Server, Client, Model Serving, Feature Engineering, Code Refactoring
 - 담당 역할 : End to End
 - FeedBack : 근거에 기반하여 의사결정, Data-Driven 결정, 안되면 돌아가지말고 해결하자, 더 높은 코드 수준, 체계적이고, 정리된 문서

<!-- 주요 업무 : 대용량 로그 데이터를 처리하여 Model 학습, Go언어로 Server를 구현하여 Model 직접 구현 및 서빙, Client를 구축하여 Server 성능 테스트, Feature Engineering을 통해 모델 성능 향상, 프로파일링 및 리팩토링을 통해 코드 수준 올리기
업무 내용 : Line Ads의 MLops를 경험하였으며, 직접 구현하여 이해도를 높였습니다. 서버와 클라이언트 모두 멀티 쓰레드 기반으로 만들었으며, 서버의 경우 모델 Inference RPS가 약18,000까지 구현하였습니다. Client는 Boss-worker 아키텍처를 적용하여 구현하였고, TDD기반으로 모든 개발을 진행하였습니다. Feature Engineering을 통해 데이터 기반 의사 결정을 배웠으며, 추가적인 Feature를 생성하여 성능을 높였습니다. 프로파일링을 통해 병목현상이 생기는 부분을 파악하였고 최적화를 진행하였습니다. 코드 리팩토링을 진행하여 Clean Code를 적용하고 Readability를 높여 협업 가능한 코드를 작성하였습니다. 
사용 언어 및 프로그램 : Python, Go, Centos7 -->


### Feature Based Sampling: A Fast and Robust Sampling Method for Tasks Using 3D Point Cloud (IEEE Access)
- 주요 업무 : Project Lead
- 담당 역할 : 팀장
- 기술 스택 : 
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/></a>
- 업무 기간 : 2021.02 ~ 2022.5
- 인원 : 4
- 상세 내용 : 3D vision task인 Point Cloud 데이터를 다뤄내는 Model(PointNet++)에서 병목현상이 발생하는 Sampling의 문제점을 제기하고, 문제를 해결할 수 있는 새로운 Feature-based Sampling을 제안하였습니다. 프로파일링을 통해 확인한 연산량을 많이 차지하는 Farthest Point Sampling 대신에 각 점의 적합도를 판단하여 Sampling을 진행하는 Feature-based Sampling을 사용하였습니다. 제안한 방식은 Sampling에서 Outliers를 제거하며, 3배 이상의 속도 향상을 가져오게 되고 정확도 상승의 결과를 나타내었습니다. 저의 Contribution은 새로운 Sampling을 제시함으로써 Sampling에 대한 bias를 줄이고 설명 가능한 형태, 학습 가능한 형태의 Feature-based Sampling을 제시하였습니다. 결과를 증명하기 위해 Outlier Removal, Sampling Ratio 등 새로운 실험을 진행하여 증명하였습니다.
- 업무 성과 : 
    - IEEE Access - Feature Based Sampling: A Fast and Robust Sampling Method for tasks using 3D point cloud
    - [논문](https://ieeexplore.ieee.org/document/9783109)

### OCT image CNN Retinal Disease Prediction with Triple GAN(AI healthCare project 3)
- 주요 업무 : 데이터 분석, 모델 설계, 실험 및 검증
- 담당 역할 : 개인
- 기술 스택 : 
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/></a>
- 업무 기간 : 2020.11 ~ 2020.12 
- 인원 : 1
- 상세 내용 : 3D OCT images Segmentation를 활용하여 Tissue-Segmentation map classfication을 진행하였습니다. 데이터의 Imbalance 문제를 해결하기 위해make auxiliary data를Triple GAN 으로 만들어 사용하였습니다. Data Imbalance 문제를 해결하여, 56%의 Accuracy에서 80%까지 Accuracy로 상승시켰습니다.
- [프로젝트 내용](https://github.com/hanjungwoo1/Projects/tree/master/Projects/Retinal%20Disease%20Prediction)


### Lateral Venticle(AI Healthcare Project 2)
- 주요 업무 : 데이터 분석, 모델 설계, 실험 및 검증
- 담당 역할 : 개인
- 기술 스택 : 
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/></a>
- 업무 기간 : 2020.10 ~ 2020.11
- 인원 : 1
- 상세 내용 : Brain CT Data를 활용하여 Lateral Ventricle 뇌구조 파악하는 Task를 진행하였습니다. 여러 개의 2D이미지가 하나의 뇌를 구성하는 3D데이터 구조를 가지고 있고 BackBone으로 U-Net 사용하며 데이터가 적은 관계로 cross validation - 6-fold validation를 사용하여 검증하였습니다. 후에 Outlier가 Segment 되는 문제를 Post-Processing을 사용하여 처리합니다.
- [프로젝트 내용](https://github.com/hanjungwoo1/Projects/tree/master/Projects/Lateral%20Ventricle)



### Survival Analysis(AI healthCare project 1)
- 주요 업무 : 데이터 분석, 모델 설계, 실험 및 검증
- 담당 역할 : 개인
- 기술 스택 : 
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/></a>
- 업무 기간 : 2020.09 ~ 2020.10 
- 인원 : 1
- 상세 내용 : 사람의 개인적인 ADNI 데이터 사용을 하여 Survival Analysis를 진행하였습니다. 결측치를 찾아 해결하는 방식을 Missing data imputation by GAIN[Missing Data Imputation using Generative Adversarial Nets.ICML]을 적용하여 해결하였고, 이후의 다양한 ML방식을 적용하여 Survival Analysis를 진행하였습니다. Survival Analysis에서 주로 사용하는 Kaplan-Meier Estimator과 결과를 비교합니다.
- [프로젝트 내용](https://github.com/hanjungwoo1/Projects/tree/master/Projects/Survival%20Analysis)


### Multi-modal Fault Detection / RIST
- 주요 업무 : 모델링 및 실험
- 담당 역할 : 팀원
- 기술 스택 : 
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Numpy-013243?style=flat-square&logo=Numpy&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=white"/></a>
- 업무 기간 : 2020.05 ~ 2020.08
- 인원 : 4
- 상세 내용 : Single Data보다 Multi-modal 형태가 40프로 더 좋은 결과를 나타냈습니다. 설비 진단을 위해서 설비의 잔여 수명 및 고장을 예측하고 진단할 수 있도록 하는 방법을 멀티 모달 딥 러닝 기술Multi-modal deep Learning을 이용해서 수행할 수 있는지 가능성을 제시하는 기술 구현하는 것을 목표로 진행하였습니다. 모터는 다양한 설비에 사용되며, 진동 전류 등의 다양한 정보를 모니터링 할 수 있고, 고장의 시점을 예측하는 것이 의미를 갖으므로 모터의 수명 예측 및 고장 진단을 수행하였습니다. 모터의 고장 시점의 진동 및 전류의 파형 정보를 전체 Lifetime Data에 맞출 수 있으며 고장 시점을 진단해 냈다고 볼 수 있습니다. 그러므로 특정한 구간의 진동 및 전류 데이터를 입력으로 사용하여, 이 구간이 전체 lifetime data에서 어떠한 구간인지를 맞히는 방법을 멀티 모달 딥 러닝 방법을 통해 학습시키는 것을 목표로 하였습니다. Backbone은 Resnet을 사용하였고, End to End의 실험 진행을 맡아서 하였습니다. 
- [프로젝트 내용](https://github.com/hanjungwoo1/Projects/tree/master/Projects/Multi%20modal)

### Smart Container
- 주요 업무 : 팀 리드, 설계 및 백엔드 전담
- 담당 역할 : 팀장
- 기술 스택 : 
<img src="https://img.shields.io/badge/DJango-092E20?style=flat-square&logo=Django&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/></a>
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/></a>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Raspberry Pi-A22846?style=flat-square&logo=Raspberry Pi&logoColor=white"/></a>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/></a>
<img src="https://img.shields.io/badge/RestAPI-006600?style=flat-square&logo=RestAPI&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitLab-FCA121?style=flat-square&logo=GitLab&logoColor=white"/></a>
- 업무 기간 : 2019.04 ~ 2019.11 (약 7개월 소요)
- 인원 : 5
- 상세 내용 : 팀 리딩, 백 엔드 설계 및 개발. Django를 통해 백엔드를 개발하고 다양한 Edge Device와 통신하여 기존의 컨테이너를 스마트화 시켜 항만에서 관리하고 사용할 수 있는 플랫폼을 개발하였습니다. Socket통신을 활용하여 각 서버간 통신을 상시 연결하고 이를 통해 라즈베리 파이를 제어하였습니다. 파이에 NodeMCU로 연결 되어있는 장치들은 온습도 조절장치, 문개폐 등이 있습니다. 문 개폐는 YoloV2를 사용하여 얼굴인식을 적용하였고 또한 항만에서 얻어지는 데이터를 LSTM 모델에 적용하여 컨테이너들의 물동량을 예측하는 기능을 구현하였습니다. 이를 통해 서버 구축에 전반적인 이해도를 가지고 있으며, 모델(딥러닝)의 기능을 포함한 서버를 개발한 경험이 있습니다.
- 시연 연상 : https://youtu.be/9Vx05kWheak
- 업무 성과 :
    - 2019 스마트 항만물류 창업지원 선정(22,000,000(원))
    - 2019 삼육대학교 프로젝트 경진대회 대상
    - 2019 노원그린캠퍼스사업단 사업단장상

### Smart AGV
- 주요 업무 : 팀 리드, 설계 및 백엔드 전담
- 담당 역할 : 팀장
- 기술 스택 :
<img src="https://img.shields.io/badge/DJango-092E20?style=flat-square&logo=Django&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/></a>
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/></a>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Raspberry Pi-A22846?style=flat-square&logo=Raspberry Pi&logoColor=white"/></a>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/></a>
<img src="https://img.shields.io/badge/RestAPI-006600?style=flat-square&logo=RestAPI&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitLab-FCA121?style=flat-square&logo=GitLab&logoColor=white"/></a>
- 업무 기간 : 2019.04 ~ 2019.11 (약 7개월 소요)
- 인원 : 5
- 상세 내용 : 팀 리딩, 백엔드 설계 개발. 라즈베리 파이를 통해 반자율주행 차량을 개발하였습니다. Pi Car를 제작하여 각각의 모터를 제어하여 차량을 제어할 수 있게 만들고, Django 백엔드 서버를 통하여 여러개의 차량을 제어하는 플랫폼을 개발하였습니다. 이 차량은 항만에서 컨테이너를 운반하는 AGV를 예시로 제작하였고, 차량 위에 RFID칩을 포함한 Smart Container가 적재되면 필요한 위치로 반자율주행하게 됩니다. 주행 중에 Camera에 Yolo를 적용하고 초음파 탐지를 통해 장애물을 식별하며 Line Tracking 기술을 사용하여 차선이탈 방지를 구현하였습니다. 또한 다익스트라 알고리즘을 통해 차량들이 서로 방해받지 않는 경로를 찾아 진행합니다. 서버 개발을 통해 플랫폼을 구축하여 차량을 제어를 해보니 신뢰성 높은 시스템 구축의 중요성을 알게 되었습니다. 
- 시연 연상 : https://youtu.be/56Nr-upcPYU
- 업무 성과 :
    - 2019 스마트해상물류 프로젝트 경진대회 동상
    - 2019 삼육대학교 프로젝트 경진대회 최우수상
    - 2019 노원그린캠퍼스사업단 사업단장상

### 나만의 뉴스 - My news
- 주요 업무 : 팀 리드, 설계 및 백엔드 전담
- 담당 역할 : 팀장
- 기술 스택 : 
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/></a>
<img src="https://img.shields.io/badge/JSP-FF6F00?style=flat-square&logo=JSP&logoColor=white"/></a>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/></a>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/></a>
- 업무 기간 : 2018.04 ~ 2018.11 (약 7개월 소요)
- 인원 : 5
- 상세 내용 : 이 프로젝트의 결과물은 ‘나만의 뉴스’로서 정보가 넘쳐나는 시대에 내가 원하는 정보만 편하게 모아주는 기능을 가진 어플로 모든 사람의 기호에 맞춘 아침에 일어나서, 저녁에 자기 전에, 수시로 찾아보고 필수적인 정보들을 한 화면에 모두 모아주는 Crawling과 API 기반의 솔루션.
    프로젝트를 진행하면서 팀을 리드하고 전반적인 설계 및 개발을 맡아서 진행하였습니다. 메인 서버와 API와 Crawling 기능을 만든 뒤에 Front 부분에서 개개인의 편의성을 위한 Grid 방식의 UI를 채택하여 설계를 하였고 이러한 과정에서 메인 서버와 API, Crawling 위주의 개발을 맡았습니다.  프로젝트를 진행하는 중에 일정관리의 중요성을 많이 배웠고, 여러번 검토 후에 정확한 설계가 성공적인 프로젝트를 만든다는 것을 배웠습니다. 또한 진행 중에 변수가 발생할 것을 생각하여 Buffer 시간을 채용하는 것의 중요성도 깨달았습니다. 
- 시연 연상 : https://youtu.be/GUlju_2Bbm0
- 업무 성과 : 
    - 2018 한이음 공모전 입선
    - 2018 삼육대학교 아이디어 경진대회 우수

## Education
2020.03 ~ 2022.02 고려대학교(안암) 대학원 석사 (서울) / 컴퓨터 공학 / 4.31(4.5) / 졸업

2014.03 ~ 2020.02 삼육대학교 / 소프트웨어 / 4.01(4.5), 전공 : 4.13 (82/136) / 졸업

2009.03 ~ 2012.02 대신고등학교 / 졸업


## Experience
### 교내 전산원
 - 교내활동 / 정보전산원 / 교내 PC, 강의실 점검 및 관리 / 2018.03 ~ 2019.08
 - 교내활동 / 투비씨앤씨 / 교내 PC, 강의실 점검 및 관리 / 2019.10 ~ 2020.02
### YAHAIT 동아리 운영
 - 교내활동 / YAHAIT / YAHAIT 코딩 동아리 개설 및 운영(회장) / 2018.03 ~ 2020.02
     - 각 언어별 Study 운영(약 100명)
     - Toy Project 진행(약 40명)
     - Project 팀업(9명)
### SmartContainer / SmartAGV 울산항만 창업
 - 수행과제 / 울산과학기술원 / 창업지원 선정(22,000,000원) / 2019.10 ~ 2020.04

 - [뉴스기사](https://search.naver.com/search.naver?where=news&sm=tab_jum&query=YAHAIT)
 
 ### 교내 총대의원회
  - 2018.03 ~ 2020.02
  - 운영위원회에서 부의한 안건의 처리 
  - 회칙 개정안에 대한 결의
  - 예산 및 결산에 관한 결의 및 감사
  - 기타 필요한 사항의 심의 및 결의

## 수상 내역
 - 2019 스마트 해상 물류 프로젝트 경진 대회 / 한국정보산업연합회 회장 / 동상 (2019/12/14)
 - 삼육대학교 프로젝트 경진대회 / 삼육대학교 미래융합대학장 / 대상 (2019/11/28)
 - 삼육대학교 프로젝트 경진대회 / 삼육대학교 미래융합대학장 / 최우수상 (2019/11/28)
 - 2018 한이음 공모전 / 한국정보산업연합회 회장 / 입선 (2018/11/30)
 - 삼육대학교 아이디어 경진대회 / 삼육대학교 컴퓨터학부장 / 우수상 (2018/11/21)
 - 2019 노원 캠퍼스타운 창업아이디어 경진대회 / 노원그린캠퍼스타운사업단장 / 사업단장상 (2019/11/19)


## License
- 토익 805 (21.08.22/29) / ETS
- 정보처리기사 (19.08.16) / 19202020829L / 한국산업인력공단 
- Mos Master (19.11.25) / uPKz-XLR7 / Microsoft


<!--
**hanjungwoo1/hanjungwoo1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
