---
layout: archive
title: "Contact"
permalink: /contact/
author_profile: false
---

<style>
.contact-container {
  display: flex;
  align-items: flex-start;
  justify-content: center;
  flex-wrap: wrap;
  gap: 40px;
  margin-top: 30px;
}
.contact-map iframe {
  border: 0;
  border-radius: 10px;
  width: 400px;   /* 필요시 100%로 변경 */
  height: 300px;
  display: block;
}
.contact-map .map-link {
  display: inline-block;
  margin-top: 8px;
  text-align: center;
}
.contact-info {
  max-width: 420px;
  font-size: 15px;
  line-height: 1.7;
}
.contact-info a {
  color: #1a0dab;
  text-decoration: none;
}
.contact-info a:hover { text-decoration: underline; }
@media (max-width: 720px) {
  .contact-map iframe { width: 100%; height: 260px; }
}
</style>

<div class="contact-container">

  <!-- 왼쪽: 지도 -->
  <div class="contact-map">
    <iframe
      src="https://www.google.com/maps?q=%EC%84%B1%EA%B7%A0%EA%B4%80%EB%8C%80%ED%95%99%EA%B5%90%20%EC%9E%90%EC%97%B0%EA%B3%BC%ED%95%99%EC%BA%A0%ED%8D%BC%EC%8A%A4&hl=ko&z=16&output=embed"
      allowfullscreen="" loading="lazy">
    </iframe>
    <div class="map-link">
      <a href="https://www.google.com/maps/place/%EC%84%B1%EA%B7%A0%EA%B4%80%EB%8C%80%ED%95%99%EA%B5%90+%EC%9E%90%EC%97%B0%EA%B3%BC%ED%95%99%EC%BA%A0%ED%8D%BC%EC%8A%A4/@37.2937619,126.9752556,17z"
         target="_blank" rel="noopener">큰 지도 보기</a>
    </div>
  </div>

  <!-- 오른쪽: 연락처 -->
  <div class="contact-info">
    <p><strong>Email:</strong> <a href="mailto:pebble3@skku.edu">pebble3@skku.edu</a></p>
    <p><strong>Phone:</strong> +82-10-7724-4279</p>
    <p style="margin-top:20px; font-weight:600;">
      I am seeking a postdoctoral position in the field of bioelectronics.<br>
      Please feel free to contact me.
    </p>
  </div>

</div>
