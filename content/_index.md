---
title: "Home"
type: landing

sections:
  # 1. 메인 배너 (대표 사진과 슬로건)
  - block: hero
    content:
      title: "한양대학교 지진방재 인력양성 사업단"
      text: "미래 사회의 안전을 책임지는 지진방재 전문인력 양성"
    design:
      background:
        # assets/media/ 폴더에 넣을 사진 이름
        image: 
          filename: "main-bg.jpg"
          filters:
            brightness: 0.4 # 흰색 글씨가 확 돋보이도록 사진 밝기를 살짝 더 낮춤
      spacing:
        padding: ["100px", "0", "100px", "0"]

  # 2. 사업단장 인사말 (텍스트 영역)
  - block: markdown
    content:
      title: "사업단장 인사말"
      text: |
        안녕하십니까, 한양대학교 지진방재 인력양성 사업단장입니다.
        
        최근 기후 변화와 지각 변동으로 인해 재난 대비의 중요성이 그 어느 때보다 강조되고 있습니다. 우리 사업단은... (여기에 원하시는 인사말을 쭉 적어주세요)
        
        감사합니다.
    design:
      spacing:
        padding: ["80px", "0", "80px", "0"]
---
