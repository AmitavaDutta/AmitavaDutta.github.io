---

layout: page
title: Gallery
icon: fas fa-images
order: 3
--------

A collection of photographs, memories, places, and moments from different parts of my journey.

---

## Know Me: My Interests

Beyond my work in geodynamics, I have a few interests that have stayed with me over the years. I enjoy photography, exploring places, following football, and occasionally getting lost in fictional worlds. This section is a small glimpse of some of the things I enjoy outside research.

<div class="gallery-static gallery-two">

  <img src="/assets/img/gallery/brazil-2002.jpg" alt="Brazil 2002">

  <img src="/assets/img/gallery/one-piece.png" alt="One Piece">

</div>

---

## Photography

<div class="gallery-static gallery-two">

  <img src="/assets/img/gallery/photography1.jpg" alt="Photography 1">

  <img src="/assets/img/gallery/photography2.jpg" alt="Photography 2">

  <img src="/assets/img/gallery/photography3.jpg" alt="Photography 3">

  <img src="/assets/img/gallery/photography4.jpg" alt="Photography 4">

</div>

---

## Family

<div class="gallery-static gallery-two">

  <img src="/assets/img/gallery/family1.jpg" alt="Family">

</div>

---

## School

<div class="gallery-carousel" data-interval="4500">

  <div class="gallery-slide">
    <img src="/assets/img/gallery/school1.jpg" alt="School 1">
  </div>

  <div class="gallery-slide">
    <img src="/assets/img/gallery/school2.jpg" alt="School 2">
  </div>

  <div class="gallery-slide">
    <img src="/assets/img/gallery/school3.jpg" alt="School 3">
  </div>

  <div class="gallery-slide">
    <img src="/assets/img/gallery/school4.jpg" alt="School 4">
  </div>

  <div class="gallery-slide">
    <img src="/assets/img/gallery/school5.jpg" alt="School 5">
  </div>

  <div class="gallery-slide">
    <img src="/assets/img/gallery/school6.jpg" alt="School 6">
  </div>

</div>

---

## Convocation 2024

<div class="gallery-carousel" data-interval="4500">

  <div class="gallery-slide">
    <img src="/assets/img/gallery/convocation1.jpg" alt="Convocation 2024 - 1">
  </div>

  <div class="gallery-slide">
    <img src="/assets/img/gallery/convocation2.jpg" alt="Convocation 2024 - 2">
  </div>

  <div class="gallery-slide">
    <img src="/assets/img/gallery/convocation3.jpg" alt="Convocation 2024 - 3">
  </div>

  <div class="gallery-slide">
    <img src="/assets/img/gallery/convocation4.jpg" alt="Convocation 2024 - 4">
  </div>

</div>

---

## Cultural, IISERK

<div class="gallery-carousel" data-interval="4500">

  <!-- Add Cultural, IISERK images here -->

</div>

---

## Field DES, IISERK

<div class="gallery-carousel" data-interval="4500">

  <!-- Add Field DES, IISERK images here -->

</div>

---

## FCIK 19MS, IISERK

<div class="gallery-carousel" data-interval="4500">

  <!-- Add FCIK 19MS, IISERK images here -->

</div>

---

## Outreach DES, IISERK

<div class="gallery-carousel" data-interval="4500">

  <!-- Add Outreach DES, IISERK images here -->

</div>

<style>
.gallery-static {
  display: grid;
  gap: 1rem;
  margin: 1.5rem 0 2rem;
}

.gallery-two {
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.gallery-static img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 8px;
}

.gallery-carousel {
  position: relative;
  width: 100%;
  margin: 1.5rem 0 2.5rem;
  overflow: hidden;
  border-radius: 8px;
  background: #f5f5f5;
}

.gallery-slide {
  display: none;
  width: 100%;
}

.gallery-slide.active {
  display: block;
}

.gallery-slide img {
  display: block;
  width: 100%;
  height: auto;
  max-height: 75vh;
  object-fit: contain;
  margin: 0 auto;
}

@media (max-width: 768px) {
  .gallery-two {
    grid-template-columns: 1fr;
  }
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {

  document.querySelectorAll(".gallery-carousel").forEach(function (carousel) {

    const slides = carousel.querySelectorAll(".gallery-slide");

    if (slides.length === 0) {
      return;
    }

    let current = 0;

    slides[current].classList.add("active");

    if (slides.length > 1) {

      setInterval(function () {

        slides[current].classList.remove("active");

        current = (current + 1) % slides.length;

        slides[current].classList.add("active");

      }, Number(carousel.dataset.interval) || 4500);

    }

  });

});
</script>
