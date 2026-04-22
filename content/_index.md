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
