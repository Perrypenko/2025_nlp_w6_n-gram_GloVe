```markdown
# 수학으로 구현하는 언어 모델: n-gram과 GloVe

이 저장소는 2인 1조로 진행하는 실습 프로젝트입니다.  
n-gram 기반 통계 언어 모델부터 GloVe 임베딩까지,  
수학적 개념을 직접 구현하고 시각화하며 언어모델의 핵심 원리를 이해하는 것이 목표입니다.

---

## 🧠 학습 목표

- n-gram 모델의 확률 기반 구조 이해 및 구현
- GloVe 목적함수와 임베딩 학습의 수학적 원리 구현
- numpy, scipy, pandas, matplotlib, PyTorch 활용 능력 향상
- 직접 구현한 결과를 분석하고 시각화하는 능력 배양

---

## 📁 디렉토리 구조

```sh
.
├── 1_corpus_preprocessing.ipynb         # 말뭉치 정제 및 n-gram 생성
├── 2_ngram_model.ipynb                  # 확률 기반 n-gram 모델 구현
├── 3_glove_matrix.ipynb                 # 동시출현 행렬 생성
├── 4_glove_loss_implementation.ipynb    # GloVe 목적함수 구현 및 최적화
├── 5_visualization_analysis.ipynb       # 결과 분석 및 시각화
├── report_template.md                   # 보고서 작성 템플릿 (논문 구조 기반)
└── data/
    └── corpus.txt                       # 예시 말뭉치 파일
```

---

## ✅ 실습 진행 방식

- 2인 1조로 역할 분담
- 각 단계별 코드 구현 및 결과 해석
- 최종 보고서 제출: `report_template.md` 기반

---

## 🔧 필요 환경

- Python 3.8+
- numpy
- scipy
- pandas
- matplotlib
- PyTorch

```bash
python -m venv venv # 가상환경 생성

# 가상환경 활성화
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows

# 필수 패키지 설치
pip install -r requirements.txt

# Jupyter Notebook 실행
# (VSCode에서 Jupyter Notebook을 사용하려면 아래 명령어를 사용하세요)
jupyter notebook # use jupyter lab if you prefer
code . # open the project in VSCode with jupyter extension
```


---

references:

https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter

---

## 📌 참고 문헌

- [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/pubs/glove.pdf)
- [Speech and Language Processing (Jurafsky & Martin)](https://web.stanford.edu/~jurafsky/slp3/)

