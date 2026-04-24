---
title: "학술 발표"
summary: "국내외 학술대회 발표 및 연구 성과 공유"
show_breadcrumb: false
share: false
profile: false
toc: false  # 우측 사이드바를 제거하여 중앙 집중도를 높입니다.
authors: []
---

<style>
  /* 1. 상단 자동 생성 제목 및 메타데이터 숨김 */
  h1, .article-metadata { display: none !important; }

  /* 2. 전체 컨텐츠 중앙 정렬 레이아웃 */
  .center-container {
    max-width: 1000px;     /* 전체적인 가로 폭 제한 */
    margin: 0 auto;        /* 페이지 중앙 배치 */
    text-align: center;    /* 텍스트 중앙 정렬 */
    padding: 2rem 0;
  }

  /* 3. 자동 슬라이더 컨테이너 설정 */
  .slider-container {
    width: 100%;
    max-width: 800px;      /* 슬라이더의 최대 너비 지정 */
    margin: 2rem auto;     /* 위아래 여백 및 가운데 정렬 */
    overflow: hidden;      /* 프레임 밖으로 나가는 이미지 숨김 (핵심) */
    border-radius: 12px;   /* 모서리 곡선 처리 */
    box-shadow: 0 10px 30px rgba(0,0,0,0.1); /* 부드러운 그림자 효과 */
  }

  /* 4. 슬라이드 트랙 (이미지들이 가로로 길게 이어지는 공간) */
  .slider-track {
    display: flex;
    transition: transform 0.8s ease-in-out; /* 부드럽게 미끄러지는 애니메이션 속도 */
  }

  /* 5. 개별 슬라이드 이미지 세팅 */
  .slider-track img {
    width: 100%;           /* 컨테이너 너비에 꽉 차게 설정 */
    flex-shrink: 0;        /* 이미지 영역이 찌그러지지 않도록 방지 */
    object-fit: cover;     /* 비율을 유지하며 영역 채우기 */
  }
</style>

<div class="center-container">
  <h2>학술대회 발표 및 연구성과 정리 내용</h2>

  <div class="slider-container">
    <div class="slider-track" id="imageSlider">
      <img src="/uploads/학1.png" alt="학술발표 사진 1" onerror="this.src='https://via.placeholder.com/800x600?text=이미지1을+찾을수없음'">
      <img src="/uploads/학2.png" alt="학술발표 사진 2" onerror="this.src='https://via.placeholder.com/800x600?text=이미지2을+찾을수없음'">
      <img src="/uploads/학3.png" alt="학술발표 사진 2" onerror="this.src='https://via.placeholder.com/800x600?text=이미지2을+찾을수없음'">
      </div>
  </div>
</div>

<script>
  // 마크다운 내부에서 작동하는 자동 슬라이드 스크립트
  document.addEventListener('DOMContentLoaded', function() {
    const track = document.getElementById('imageSlider');
    const slides = track.children;
    let currentIndex = 0;
    const totalSlides = slides.length;

    // 사진이 2장 이상일 때만 슬라이드 애니메이션 작동
    if (totalSlides > 1) {
      setInterval(() => {
        currentIndex++;
        // 마지막 사진에 도달하면 다시 첫 번째 사진으로 되돌아감
        if (currentIndex >= totalSlides) {
          currentIndex = 0; 
        }
        // 왼쪽으로 100%씩 이동하여 다음 사진을 보여줌
        track.style.transform = `translateX(-${currentIndex * 100}%)`;
      }, 3500); // 현재 3.5초(3500ms)마다 넘어갑니다. 속도를 조절하고 싶다면 이 숫자를 변경하세요.
    }
  });
</script>

---
## 국제 학술대회

**2025**

1. 한상환, 조은선, 홍민국. *Cyclic Performance of Steel Beam-Column Connections with Weak Panel Zones: Experimental and Numerical Study.* **ISSS-PSSC**. (2025.10)

2. 이건찬, 이창석, 전종수. *Shape memory alloy jacket repair of reinforced concrete column for aftershock demand reduction.* **ISSS-PSSC**. (2025.11)
