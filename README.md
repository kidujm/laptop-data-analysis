# LG 노트북 마케팅 인사이트 프로젝트

## 프로젝트 소개
LG 노트북이 자사 및 노트북 시장을 사전 조사하여 마케팅 인사이트를 도출하는 프로젝트입니다.
커뮤니티, 다나와, 네이버 스토어 리뷰, 유튜브 데이터 등 다양한 채널에서 데이터를 수집하고 분석합니다.

## 팀원 및 역할
| 이름 | 역할 |
|---|---|
| | |
| | |
| | |
| | |

## 데이터 수집 채널
- 커뮤니티 (클리앙, 뽐뿌 등)
- 다나와
- 네이버 스토어 리뷰
- 유튜브

## 분석 내용
- [ ] 데이터 수집 및 크롤링
- [ ] 데이터 정제 및 전처리
- [ ] 리뷰 감성분석
- [ ] 군집화 분석
- [ ] 마케팅 인사이트 도출
- [ ] 시각화 및 대시보드

## 사용 기술
- Python
- Gemini API
- Pandas
- Jupyter Notebook

## 실행 방법
1. 패키지 설치
```
    pip install -r requirements.txt
```
2. `.env` 파일 생성 후 API 키 입력
```
    GEMINI_API_KEY=본인키입력
```
3. Jupyter Notebook 실행 후 순서대로 실행

## 프로젝트 구조
```
laptop-data-analysis/
├── 📁 crawling/              # 데이터 수집
│   ├── naver_crawler.ipynb
│   ├── youtube_crawler.ipynb
│   └── danawa_crawler.ipynb
├── 📁 preprocessing/         # 데이터 정제
│   └── data_cleaning.ipynb
├── 📁 analysis/              # 데이터 분석
│   ├── sentiment_analysis.ipynb
│   └── clustering.ipynb
├── 📁 visualization/         # 시각화
├── .env
├── .gitignore
└── requirements.txt
```

## 발표자료
- 추후 업로드 예정
