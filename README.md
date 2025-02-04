[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=2000&color=0092F1&width=435&lines=Hello+World!;Welcome+to+the+Lee+Yeon+Ho's+Github)](https://git.io/typing-svg)



## Tech Stack 🔨🔨

<div style="display:flex; flex-direction:column;">
    <!-- Backend -->
    <p><strong>Backend</strong></p>
    <div>
        <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white">
        <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
        <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=spring boot&logoColor=white"> 
    </div>
    <!-- Frontend -->
    <p><strong>Frontend</strong></p>
    <div>
        <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
        <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
        <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
      <img src="https://img.shields.io/badge/react-20232a.svg?style=for-the-badge&logo=react&logoColor=61DAFB">
    </div><br>
</div>

## Profile
- 홍익대학교 컴퓨터공학과 <sub>(2022.03 ~ )</sub>
- 홍익대<a href="https://github.com/HIUMC"> UMC</a> - 5기 FE(Web) <sub>(2023.09 ~ 2024.02)</sub>
- 홍익대<a href="https://github.com/HIUMC"> UMC</a> - 6기 BE <sub>(2024.03 ~ 2024.08)</sub>
- 홍익대<a href="https://github.com/HIUMC"> UMC</a> - 7기 BE 파트장 <sub>(2024.08 ~ 2025.01)</sub>
- KISIA 주관 AI보안 기술개발 개인정보반 교육 참여 <sub>(2024.07.22 ~ 2024.08.20) ✨AI보안 기술개발 교육과정 우수상 수여✨</sub>

## Experience
- <a href="https://github.com/fitness-bro">1:1 PT 매칭 서비스</a>: "더이상 PT말고 동네형에게 헬스 과외 받자, 동네형" FE 참여 <sub>(2023.12~2024.04)</sub>
- <a href="https://github.com/UMC-ShowHoo">공연 준비 및 공연 예매 서비스</a>: "당신을 위한 공연 플랫폼, ShowHoo" BE 참여 <sub>(2024.07~2024.08)</sub>
<details><summary><a href="https://github.com/5i5i">AI보안 프로젝트</a>: "일상 블로그 속 개인정보 결합을 통한 개인식별 위험도 예측 서비스" BE, AI 참여 <sub>(2024.08.20 ~2024.11.20)</sub></summary> <div markdown="1">
# 일상 블로그 속  개인정보 결합을 통한 개인식별 위험도 예측 확장 프로그램 개발

---

### 1. **프로젝트 개요**

- **프로젝트 제목**: 블로그 게시글 속 개인정보 결합을 통한 개인식별 위험도 예측 확장 프로그램 개발
- **프로젝트 기간**: 2024년 8월 20일 - 2024년 11월 8일 (12주)
- **주요 목표**: 블로그 게시글을 게시 전에 개인정보를 자동으로 탐지하고, 이전 게시글들에서의 개인정보들의 카테고리 간의 결합 정보로 개인식별 위험도를 판단하여 경고를 해주는 웹 브라우저 확장 프로그램을 개발
    
    ⇒ 개인 정보 노출 경보
    


### 2. **문제 정의**

- **주제**: 일상 블로그 게시글에서 개인정보가 무분별하게 공개되어 발생할 수 있는 개인식별 위험을 예측하고 경고하는 시스템 개발.
- **근거**
    - **블로그의 보편성**: 블로그는 많은 사용자가 일상생활과 생각을 공유하는 주요 플랫폼 중 하나로, 전 세계 수백만 명이 개인적인 이야기를 블로그에 게시하고 있습니다. 이러한 글에는 종종 민감한 개인정보가 포함될 수 있으며, 사용자가 의도하지 않더라도 정보가 노출될 위험이 존재합니다.
    
    - **정보의 조각화와 결합 가능성**: 사용자는 종종 여러 개의 블로그 게시글에 걸쳐 다양한 정보를 게시합니다. 각각의 게시글에서는 개별적으로 큰 의미가 없는 정보일 수 있지만, 여러 게시글의 정보를 결합하면 개인을 식별할 수 있는 단서가 될 수 있습니다.
        
        **ex**) 한 게시글에 이름이 포함되고, 다른 게시글에 이메일 주소가 포함될 경우, 이 두 정보가 결합되어 개인 식별 가능성이 높아짐
        
    - **정보 유출 사례 증가**: 최근 몇 년간, 블로그 및 SNS에서 개인정보가 무단으로 수집되거나 유출되는 사례가 증가하고 있습니다. 이러한 사례는 사용자가 무심코 올린 정보들이 결합되어 악용될 수 있다는 위험성을 보여줍니다. (밑에 기사 참고)
    
    - **사용자 인식 부족**: 많은 블로그 사용자들은 자신의 게시글에 포함된 정보가 어떻게 결합될 수 있는지, 그리고 그로 인해 발생할 수 있는 위험에 대해 충분히 인지하지 못하고 있습니다. 따라서 사용자에게 이러한 결합 위험성을 경고하고, 개인정보 보호를 강화할 수 있는 도구가 필요합니다.
- **관련 기사**
    - “네이버 블로그 광고 이용자 2,200명 개인정보 유출**”** [https://www.yna.co.kr/view/MYH20190502002300038](https://www.yna.co.kr/view/MYH20190502002300038)
    - “네이버, 블로그 서비스 오픈 20주년 “3,300만 블로그서 28억 건 글 창작됐다” [https://www.itworld.co.kr/news/310009](https://www.itworld.co.kr/news/310009)
    - “카카오, ‘오픈채팅 개인정보 유출’ 과징금 151억”
        
        [https://www.sisajournal-e.com/news/articleView.html?idxno=403028](https://www.sisajournal-e.com/news/articleView.html?idxno=403028)
        
        **카카오 ‘오픈채팅방 개인정보 유출’, 과징금 151억원 ‘철퇴’**
        
        [https://www.hani.co.kr/arti/economy/it/1141740.html](https://www.hani.co.kr/arti/economy/it/1141740.html)
        
        주차장 CCTV
        
    

---

### 3. **개인정보 보호 효과**

- **예측**: 동일 사용자가 작성한 여러 게시글 간의 정보 결합 가능성을 분석하고, 결합으로 인해 발생할 수 있는 개인식별 위험도를 예측합니다.
- **탐지**: OCR, NLP 기술을 활용하여 이름, 이메일, 전화번호 등의 개인정보를 탐지하고, 이를 기반으로 개인식별 가능성을 탐지합니다.

---

### 4. **데이터 수집 및 EDA**

- **수집 출처**:
    - **공공 데이터셋** : AI-Hub, Kaggle, UCI 머신러닝 레포지토리 등에서 제공하는 블로그 게시글 데이터셋.
        - AI-hub : 야외 실제 한글 이미지(간판) [https://aihub.or.kr/aihubdata/data/view.do?dataSetSn=105](https://aihub.or.kr/aihubdata/data/view.do?dataSetSn=105)
        - 도로안내판 데이터 [https://www.data.go.kr/data/15028193/standard.do?recommendDataYn=Y](https://www.data.go.kr/data/15028193/standard.do?recommendDataYn=Y)
        - 
    - [**네이버 오픈 API**](https://zephy2.tistory.com/21)를 통한 블로그 데이터 요청
    - **크롤링 데이터**: 실제 블로그 플랫폼에서 수집한 게시글 데이터 (법적 동의 받은 가상 사용자 데이터).
    - **Synthetic Data 생성** : 개인정보 패턴을 반영한 인공 데이터 생성 (ChatGPT 기반).
    - **GitHub** : 연구 목적으로 공개된 이미지 데이터셋
    - GANs을 사용해 신분증이나 문서 이미지와 같은 특정 유형의 이미지를 생성
- **형식**: 텍스트 데이터(블로그 게시글), 메타데이터(게시글 작성일, 작성자 등), 이미지에서 텍스트 추출
- **관련 기술 도구**:
    - **NLP**: NLTK, SpaCy, Transformers(BERT) 등 텍스트 분석 도구.
    - **데이터 수집 및 처리**: Python, BeautifulSoup, Scrapy, Pandas.
    - **EDA 시각화**: Matplotlib, Seaborn, Plotly.
    - **확률 예측:**
    - **개인정보 위험도? 예측: ex) LSTM**
    

---

### 5. **AI 가드레일 설정**

- **데이터 익명화**: 실제 사용자 데이터를 수집할 때, 모든 데이터는 익명화 처리하여 개인정보 보호를 우선합니다.
- **모델 공정성**: 개인식별 위험도를 예측하는 모델이 특정 개인이나 그룹에 편향되지 않도록 공정성 테스트를 수행합니다.
- **데이터 보안**: 데이터 수집, 처리 및 저장 시 강력한 암호화 기법을 사용하여 데이터 유출 위험을 최소화합니다.
- **사용자 프라이버시 보호**: 사용자의 동의 없이 어떠한 개인 정보도 저장하거나 공유하지 않습니다.
- **성능 지연 문제:** 프로세서 바(진행상황)를 보여주기
- 큐알, 이미지 어디까지 인식할 것인지?? → 범위 정하기
- 첨부파일, 링크는 확인하지 않음
- 성능문제로 확장 프로그램으로 구현 실패. 대신 웹 서비스로 구현
- 다른 플랫폼과 호환 안됨!!!

</div>
</details>
- <a href="https://github.com/ChungBazi">청년 정책 맞춤 서비스</a>: "정책도 쉽고 간편하게, 청바지" BE 참여 <sub>(2025.01~)</sub>

## Others

<div>
    <a href="mailto:pololydotoly@naver.com">
        <img src="https://img.shields.io/badge/
        Email-#03C75A?style=for-the-badge&logo=Naver&logoColor=white"> 
    </a>
    <a href="https://velog.io/@yeonho03/posts">
        <img src="https://img.shields.io/badge/
        Velog-#20C997?style=for-the-badge&logo=Velog&logoColor=white"> 
    </a>


![LeeYatHo's GitHub stats](https://github-readme-stats.vercel.app/api?username=dldusgh318&show_icons=true&bg_color=00000000)


