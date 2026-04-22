---
title: "Home"
type: landing

sections:
  # 1. 메인 배너 (대표 사진과 슬로건)
  - block: hero
    content:
      title: "한양대학교 지진방재<br>인력양성 사업단"
      text: "미래 사회의 안전을 책임지는 지진방재 전문인력 양성"
    design:
      background:
        text_color_light: true # ★ 글씨를 자동으로 하얗게 만들어주는 테마 전용 치트키입니다!
        image:
          filename: "main-bg.jpg"
          filters:
            brightness: 0.4 # 배경을 원하시는 느낌으로 묵직하게(0.4) 눌러줍니다.
      spacing:
        padding: ["120px", "0", "120px", "0"] # 위아래 여백을 조금 더 주어 시원하게 배치

  # 2. 사업단장 인사말 (텍스트 영역)
  - block: markdown
    content:
      title: "사업단장 인사말"
      text: |
        안녕하십니까, 한양대학교 지진방재 인력양성 사업단장입니다.
        
        최근 기후 변화와 지각 변동으로 인해 재난 대비의 중요성이 그 어느 때보다 강조되고 있습니다. 우리 사업단은 지진 재난으로부터 안전한 사회를 만들기 위해 현장 중심의 실무 능력을 갖춘 전문 인력을 양성하고 있습니다.
        
        본 사업단을 통해 배출된 인재들이 대한민국 지진 방재의 핵심적인 역할을 수행할 수 있도록 최선을 다하겠습니다.
        
        감사합니다.
    design:
      spacing:
        padding: ["80px", "0", "80px", "0"]
---
# 1. 사업 소개 상세 글 부분
  - block: markdown
    content:
      title: "사업 소개"
      subtitle: "미래 사회의 안전을 책임지는 실무형 내진 전문인력 양성"
      text: |
        <div id="introduction"></div>
        **한반도는 더 이상 지진의 안전지대가 아닙니다.**
        최근 경주와 포항 지진은 우리 사회에 큰 경종을 울렸습니다. '한양대학교 지진방재 인력양성 사업단'은 이러한 국가적 위기에 대응하고 국민의 안전을 책임질 최고 수준의 내진 전문가를 양성하기 위해 출범하였습니다. 
        
        단순한 이론 교육을 넘어 현장 맞춤형 IC-PBL 교육과 첨단 실험 인프라를 통해 대한민국 지진방재의 미래를 이끌어갈 글로벌 인재를 키워냅니다.
    design:
      spacing:
        padding: ["80px", "0", "20px", "0"]

  # 2. 사업의 4가지 핵심 강점
  - block: features
    content:
      items:
        - name: "최우수 전문인력 양성"
          description: "국가 정책에 기여하는 실무형 인재 양성"
          icon: "fas fa-user-graduate"
        - name: "맞춤형 학위과정"
          description: "내진설계 심화 및 4차 산업 기술 융합 교육"
          icon: "fas fa-book-open"
        - name: "현장 연계 산학협력"
          description: "산업체 수요를 반영한 문제 해결 능력 배양"
          icon: "fas fa-handshake"
        - name: "첨단 교육 시설"
          description: "세계적 수준의 진동대 및 실험실 지원"
          icon: "fas fa-flask"
    design:
      columns: "2"
      spacing:
        padding: ["0", "0", "80px", "0"]
    ---
- block: markdown
    id: research  # 메뉴의 /#research 와 연결되는 이름표
    content:
      title: "연구 | RESEARCH"
      subtitle: "미래 사회 안전을 위한 첨단 지진방재 및 내진공학 연구"
      text: |
        **한양대학교 지진방재 인력양성 사업단**은 건축 구조물의 안전성과 회복탄력성(Resilience)을 극대화하기 위해 내진공학 전반에 걸친 심도 있는 연구를 수행합니다. 재료 및 부재 단위부터 전체 구조 시스템에 이르기까지 다각적인 수준에서 거동을 분석하며, 탄탄한 이론을 바탕으로 고도화된 전산 해석과 실증적 실험(진동대 실험 등)을 병행하고 있습니다.
        
        우리의 주요 연구 관심사는 전통적인 내진공학을 넘어 미래 핵심 기술과 융합하는 데 있습니다.
        
        * **고도화된 내진설계 및 성능평가 (Advanced Seismic Design & Evaluation)**
        * **지반-구조물 상호작용 및 방재안전 (Soil-Structure Interaction & Disaster Safety)**
        * **기존 구조물의 첨단 내진보강 기법 (Seismic Retrofit for Existing Structures)**
        * **4차 산업혁명 융합 기술 (Smart Disaster Prevention):** AI, 데이터 기반 손상 식별 및 구조 건전성 모니터링
        
        사업단의 궁극적인 목표는 국가 지진방재 인프라를 고도화하여 국민의 안전하고 지속 가능한 삶에 기여하고, 나아가 세계적 수준의 연구 역량으로 학계와 산업계를 이끌어갈 미래의 리더를 양성하는 것입니다.
    design:
      spacing:
        padding: ["100px", "0", "100px", "0"] # 텍스트에 집중할 수 있도록 위아래 여백을 넉넉히 줍니다.
