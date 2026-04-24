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
    max-width: 1000px;
    margin: 0 auto;
    text-align: center;
    padding: 2rem 0;
  }

  /* 3. 슬라이더 전체를 감싸는 래퍼 (화살표 위치 기준점) */
  .slider-wrapper {
    position: relative;
    width: 100%;
    max-width: 800px;
    margin: 2rem auto;
    background-color: transparent !important; /* 배경 완전히 투명하게 */
  }

  /* 4. 자동 슬라이더 컨테이너 설정 */
  .slider-container {
    width: 100%;
    overflow: hidden; /* 프레임 밖으로 나가는 이미지 숨김 */
    border-radius: 12px;
    background-color: transparent !important; /* 배경 투명 */
    /* 기존에 있던 그림자(box-shadow)와 테두리 제거하여 흰 배경 원인 차단 */
  }

  /* 5. 슬라이드 트랙 */
  .slider-track {
    display: flex;
    transition: transform 0.6s ease-in-out;
    background-color: transparent !important;
  }

  /* 6. 개별 슬라이드 이미지 세팅 */
  .slider-track img {
    width: 100%;
    flex-shrink: 0;
    object-fit: contain; /* cover 대신 contain을 써서 이미지 짤림을 방지 (필요시 변경 가능) */
    background-color: transparent !important;
    border: none !important; /* 테두리 제거 */
  }

  /* 7. 좌우 화살표 버튼 스타일 */
  .nav-arrow {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0, 0, 0, 0.3); /* 반투명 검은색 배경 */
    color: white;
    border: none;
    font-size: 2rem;
    padding: 10px 15px;
    cursor: pointer;
    border-radius: 50%;
    z-index: 10;
    transition: background-color 0.3s ease;
  }

  .nav-arrow:hover {
    background-color: rgba(0, 0, 0, 0.7); /* 마우스 올렸을 때 더 진해짐 */
  }

  .left-arrow { left: 10px; }
  .right-arrow { right: 10px; }
</style>

<div class="center-container">
  <h2>학술대회 발표 및 연구성과 정리 내용</h2>

  <div class="slider-wrapper">
    <div class="slider-container">
      <div class="slider-track" id="imageSlider">
        <img src="/uploads/학1.png" alt="학술발표 사진 1" onerror="this.src='https://via.placeholder.com/800x600?text=이미지1을+찾을수없음'">
        <img src="/uploads/학2.png" alt="학술발표 사진 2" onerror="this.src='https://via.placeholder.com/800x600?text=이미지2을+찾을수없음'">
        <img src="/uploads/학3.png" alt="학술발표 사진 3" onerror="this.src='https://via.placeholder.com/800x600?text=이미지2을+찾을수없음'">
        </div>
    </div>
    
    <button class="nav-arrow left-arrow" id="prevBtn">&#10094;</button>
    <button class="nav-arrow right-arrow" id="nextBtn">&#10095;</button>
  </div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const track = document.getElementById('imageSlider');
    const slides = track.children;
    const prevBtn = document.getElementById('prevBtn');
    const nextBtn = document.getElementById('nextBtn');
    
    let currentIndex = 0;
    const totalSlides = slides.length;
    let slideInterval;

    // 이미지가 1장뿐이면 화살표를 숨깁니다.
    if (totalSlides <= 1) {
      prevBtn.style.display = 'none';
      nextBtn.style.display = 'none';
      return;
    }

    // 슬라이드 이동 함수
    function updateSlide() {
      track.style.transform = `translateX(-${currentIndex * 100}%)`;
    }

    // 다음 슬라이드로
    function nextSlide() {
      currentIndex++;
      if (currentIndex >= totalSlides) currentIndex = 0;
      updateSlide();
    }

    // 이전 슬라이드로
    function prevSlide() {
      currentIndex--;
      if (currentIndex < 0) currentIndex = totalSlides - 1;
      updateSlide();
    }

    // 자동 슬라이드 시작
    function startAutoSlide() {
      slideInterval = setInterval(nextSlide, 3500); // 3.5초마다 다음으로
    }

    // 사용자가 버튼을 누르면 자동 넘김 타이머를 리셋 (겹침 방지)
    function resetAutoSlide() {
      clearInterval(slideInterval);
      startAutoSlide();
    }

    // 버튼 클릭 이벤트 연결
    nextBtn.addEventListener('click', () => {
      nextSlide();
      resetAutoSlide();
    });

    prevBtn.addEventListener('click', () => {
      prevSlide();
      resetAutoSlide();
    });

    // 최초 자동 슬라이드 실행
    startAutoSlide();
  });
</script>

---
## 국제 학술대회

**2025**

1. 한상환, 조은선, 홍민국. *Cyclic Performance of Steel Beam-Column Connections with Weak Panel Zones: Experimental and Numerical Study.* **ISSS-PSSC**. (2025.10)

2. 이건찬, 이창석, 전종수. *Shape memory alloy jacket repair of reinforced concrete column for aftershock demand reduction.* **ISSS-PSSC**. (20
