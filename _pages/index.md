<style>
  /* 본문 전체 폭 확장 */
  .archive, .page {
    width: 100% !important;
    max-width: 1200px !important; /* 기본값(약 800px)보다 넓게 설정 */
  }

  /* 사이드바와 본문 사이의 간격 및 비율 조정 */
  @media (min-width: 64em) {
    .archive, .page {
      padding-right: 0 !important;
    }
  }
</style>

---
layout: single
permalink: /
author_profile: true
---

# About Me
{% include about.md %}

---

# Researches
{% include research.md %}

---

# Education
{% include education.md %}

---

# Experiences
{% include experiences.md %}
