# Day1 from text to vector

문서를 단어렬로 변환하는 방법에 대하여 실습합니다.

## day1_KoNLPy.ipynb

KoNLPy 를 이용하여 형태소 분석을 수행합니다. 미등록단어 (out of vocablary) 문제도 확인합니다.

## day1_load_dataset_with_soynlp.ipynb

실습에 이용할 데이터셋과 soynlp 를 이용하여 로딩하는 실습을 합니다.

## day1_sentencepiece.ipynb

Google 에서 제공하는 sentencepiece (word piece model) 를 실습합니다.

## day1_soynlp_word_noun_tokenizer.ipynb

soynlp 를 이용하여 단어 점수를 계산하고 명사를 추출하는 방법을 실습합니다. 단어 점수를 이용하는 토크나이저의 사용법도 알아봅니다.

## day1_from_text_to_sparse_matrix.ipynb

KoNLPy 의 Komoran 을 이용하여 list of str 형식의 문장들을 term frequency matrix 로 변환합니다. 이를 위하여 scikit-learn 의 CountVectorizer 를 이용하며, 우리가 만드는 임의의 토크나이저를 CountVectorizer 에 입력하는 연습도 합니다.
