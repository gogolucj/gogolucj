# Hi, I’m Jisoo 👋

I'm a **Data Scientist** focused on building systems that understand people —  
through recommendations, language, temporal patterns, and graphs.

-----

## 🔍 Interests

`Recommender Systems` `Information Retrieval` `NLP` `Large Language Models` `Time-Series Forecasting`

-----

## 🛠 Projects

### 🎬 [Graph-Explainable Movie Recommendation](https://github.com/gogolucj/graph-explainable-movie-recommendation)

> Knowledge Graph 기반 추천 시스템 + GPT 설명 생성

- 협업 필터링의 블랙박스 문제를 해결하기 위해 지식 그래프로 추천 근거를 구조화
- 유저 → 시청 영화 → 장르/감독/배우 → 추천 후보의 **2-hop 탐색** 구현
- ChatGPT가 그래프 경로를 자연어 설명으로 변환 (Streamlit 데모)
- `NetworkX` `OpenAI GPT-4o-mini` `Streamlit` `MovieLens`

-----

### 🍽️ [Agentic Restaurant Finder](https://github.com/gogolucj/agentic-restaurant-finder)
> LangGraph Agentic AI 기반 한국 음식점 추천 서비스
- 사용자 질문을 coordinator → planner → search_agent → evaluator 파이프라인으로 처리하는 **ReAct 멀티 에이전트** 구현
- Elasticsearch BM25 + Dense KNN + **RRF 하이브리드 검색**으로 음식점 후보 추출
- 네이버 블로그 리뷰 실시간 크롤링, 예산 적합도 판정, Haversine 거리 계산 **4종 도구 자율 조합**
- `LangGraph` `Elasticsearch` `baai/bge-m3`  `FastAPI` `Streamlit`

----

### 📰 [Elasticsearch Korean News Search](https://github.com/gogolucj/elasticsearch-korean-news-search)

> Elasticsearch 기반 한국어 뉴스 검색 파이프라인 + 검색 품질 정량 평가

- 연합뉴스 RSS 피드 크롤링 후 Elasticsearch 인덱싱, Nori 분석기로 검색 품질 향상
- Precision@K · MAP · MRR · nDCG@K 4가지 지표 구현
- MRR **1.0000** · nDCG@5 평균 **0.9958** (쿼리 4개 · top-5 수동 레이블링)
- `Elasticsearch` `Nori` `Python` `Docker` `Jupyter`

-----
### 🔧 [Qwen3-14B LoRA Fine-tuning](https://github.com/gogolucj/qwen3-lora-finetuning)
> OpenMathReasoning + KoAlpaca 혼합 데이터로 Qwen3-14B LoRA 파인튜닝

- Catastrophic Forgetting 방지를 위해 reasoning(25%) + 한국어 instruction(75%) 데이터 설계
- 파인튜닝 후 한국어 비율 Thinking OFF 시 59.3% → 82.9%, Thinking ON 시 30.2% → 83.6% 으로 향상
- `Qwen3-14B` `LoRA` `KoAlpaca` `RunPod H100`

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
