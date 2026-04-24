---
title: "학술 발표"
summary: "국내외 학술대회 발표 및 연구 성과 공유"
show_breadcrumb: false
share: false
profile: false
toc: false
reading_time: false   # 👈 이 줄을 추가하세요! (일반 게시물용 읽기 시간 숨김)
authors: []
---

<style>
h1, .article-metadata { display: none !important; }
.center-container { max-width: 1000px; margin: 0 auto; text-align: center; padding: 2rem 0; }
.slider-wrapper { position: relative; width: 100%; max-width: 800px; margin: 2rem auto; background-color: transparent !important; }
.slider-container { width: 100%; overflow: hidden; border-radius: 12px; background-color: transparent !important; }
.slider-track { display: flex; transition: transform 0.6s ease-in-out; background-color: transparent !important; }
.slider-track img { width: 100%; flex-shrink: 0; object-fit: contain; background-color: transparent !important; border: none !important; }
.nav-arrow { position: absolute; top: 50%; transform: translateY(-50%); background-color: rgba(0, 0, 0, 0.3); color: white; border: none; font-size: 2rem; padding: 10px 15px; cursor: pointer; border-radius: 50%; z-index: 10; transition: background-color 0.3s ease; }
.nav-arrow:hover { background-color: rgba(0, 0, 0, 0.7); }
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

if (totalSlides <= 1) {
prevBtn.style.display = 'none';
nextBtn.style.display = 'none';
return;
}

function updateSlide() { track.style.transform = `translateX(-${currentIndex * 100}%)`; }
function nextSlide() { currentIndex++; if (currentIndex >= totalSlides) currentIndex = 0; updateSlide(); }
function prevSlide() { currentIndex--; if (currentIndex < 0) currentIndex = totalSlides - 1; updateSlide(); }
function startAutoSlide() { slideInterval = setInterval(nextSlide, 3500); }
function resetAutoSlide() { clearInterval(slideInterval); startAutoSlide(); }

nextBtn.addEventListener('click', () => { nextSlide(); resetAutoSlide(); });
prevBtn.addEventListener('click', () => { prevSlide(); resetAutoSlide(); });
startAutoSlide();
});
</script>

---
## 국제 학술대회

**2025**

1. 한상환, 조은선, 홍민국. *Cyclic Performance of Steel Beam-Column Connections with Weak Panel Zones: Experimental and Numerical Study.* **ISSS-PSSC**. (2025.10)

2. 이건찬, 이창석, 전종수. *Shape memory alloy jacket repair of reinforced concrete column for aftershock demand reduction.* **ISSS-PSSC**. (2025.11)
