# Hi, I’m Jisoo 👋

**Data Scientist** focused on building systems that understand people —  
through recommendations, language, and graphs.

-----

## 🔍 Interests

`Recommender Systems` `Information Retrieval` `NLP` `Large Language Models`

-----

## 🛠 Projects

### 🎬 [Graph-Explainable Movie Recommendation](https://github.com/gogolucj/graph-explainable-movie-recommendation)

> Knowledge Graph 기반 추천 시스템 + GPT 설명 생성

- 협업 필터링의 블랙박스 문제를 해결하기 위해 지식 그래프로 추천 근거를 구조화
- 유저 → 시청 영화 → 장르/감독/배우 → 추천 후보의 **2-hop 탐색** 구현
- ChatGPT가 그래프 경로를 자연어 설명으로 변환 (Streamlit 데모)
- `NetworkX` `OpenAI GPT-4o-mini` `Streamlit` `MovieLens`

-----

### 📰 [elasticsearch-korean-news-search](https://github.com/gogolucj/elasticsearch-korean-news-search)

> RSS 피드 기반 한국어 뉴스 검색 파이프라인 + 검색 품질 정량 평가

- 연합뉴스 RSS 피드 크롤링 후 Elasticsearch 인덱싱, Nori 분석기로 검색 품질 향상
- Precision@K · MAP · MRR · nDCG@K 4가지 지표 구현
- MRR **1.0000** · nDCG@5 평균 **0.9958** (쿼리 4개 · top-5 수동 레이블링)
- `Elasticsearch` `Nori` `Python` `Docker` `Jupyter`

-----

### 🇰🇷 [Korean Tokenizer Benchmark](https://github.com/gogolucj/korean-tokenizer-benchmark)

> Subword vs. 형태소 분석기 정량 벤치마크

- 네이버 뉴스 코퍼스(17,327문장)로 BPE·WordPiece·Mecab·Okt·Kkma 비교
- Fertility, UNK Rate, 처리 속도(ms) 3가지 지표로 정량 평가
- 데이터 규모(10%→100%)에 따른 어휘 커버리지 변화 분석
- `HuggingFace Tokenizers` `KoNLPy` `Mecab` `Naver News API`

-----

## 🧰 Tech Stack

**Language**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**ML / DL**  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

**Recommender Systems**  
`A/B Testing`

**NLP / LLM**  
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

**Agent**  
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/langgraph-%231C3C3C.svg?style=flat&logo=langgraph&logoColor=white)

**Data Engineering**  
![Apache Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat&logo=apachehadoop&logoColor=black)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)

**Cloud & Infra**  
![AWS](https://img.shields.io/badge/AWS_SageMaker-232F3E?style=flat&logo=amazonaws&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=flat&logo=amazonaws&logoColor=white)

**Visualization & BI**  
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Power BI](https://custom-icon-badges.demolab.com/badge/Power_BI-F1C912?style=flat&logo=power-bi&logoColor=fff)
