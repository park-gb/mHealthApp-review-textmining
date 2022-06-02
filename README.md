# 건강관리 앱 리뷰 텍스트마이닝을 활용한 디자인 전략 연구1
### LDA 토픽모델링과 동시 출현 단어 네트워크 분석을 중심으로
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white))
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## 1. 개요
본 프로젝트는 건강관리 앱 리뷰 텍스트마이닝을 통해 고객 니즈를 도출하고, 이를 바탕으로 건강관리 앱의 디자인 전략을 제안합니다. 국내 구글 플레이 스토어에서 고객 리뷰 54만 건을 수집하고, LDA 토픽 모델링과 동시출현 단어 네트워크 분석을 수행합니다.

## 2. 데이터셋
- 웹 크롤링을 통해 한국 구글 플레이 스토어 내 건강관리 앱에서 리뷰 54만 건 수집
- [구글 플레이 스토어 리뷰 수집 크롤러]()

## 3. 분석 방법론
### 1) LDA 토픽 모델링
### 개념
- 토픽 모델링(Topic Modeling)은 텍스트 기반의 문서 데이터에서 핵심 주제(Topic)를 찾는 데이터 분석 방법론입니다. 특히, 잠재 디리클레 할당(Latent Dirichlet Allocation, LDA)은 토픽 모델링의 가장 대표적인 알고리즘입니다. 구체적으로, LDA 토픽 모델링은 확률 기반의 모델링 기법을 통해 방대한 양의 문서 데이터를 분석함으로써 문서 내에 어떤 토픽이, 어떤 비율로 구성되어 있는지 분석합니다[1](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf?ref=https://githubhelp.com). 또한, 토픽별로 어떤 키워드가 구성되었는지 정보를 제공하기 때문에, 키워드 조합을 통해 인사이트를 도출하는 데 효과적인 장점이 있습니다. 최근에는 LDA 토픽 모델링을 통해 SNS에서 유사한 토픽을 자동으로 분류하거나[2](https://ieeexplore.ieee.org/abstract/document/6454769) 항공사 온라인 리뷰를 분석하여 고객 니즈를 도출하는[3](https://www.mdpi.com/2078-2489/12/2/78) 등 다양한 분야에서 연구가 활발히 진행되고 있습니다.
- LDA 토픽 모델링에 대한 더욱 자세한 내용은[개인 블로그](https://heytech.tistory.com/328)를 참고해 주세요.

## 📝 License
```
MIT License

Copyright (c) 2022 Gyeongbin Park

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```