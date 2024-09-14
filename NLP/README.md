# NLP (Natural Language Processing)

- 자연어 처리

## 1. One-Hot Encoding 방식의 전처리

- 컴퓨터는 수치 데이터만 인식 가능; 단어를 수치 데이터화 한다
- 순서
    1. 토큰화 (Tokenizing): OOV (out of vocabulary) 와 최빈값으로 인덱스 배정 (tokenizing)
    2. 패딩: 패딩을 통해 입력 크기 맞추기
    3. 원 핫 인코딩

## 2. Embedding Layer 방식의 전처리

- 대표적인 임베딩 방식: Word2Vec, GloVe, FastText ...
    - 해당 방식들은 원 핫 인코딩 + 단어 간 유사도를 반영하므로 기존 원 핫 인코딩보다 좋다