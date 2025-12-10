---
title: Curriculum Vitae
layout: default
---

# Curriculum Vitae

## 🧑‍💼 Dane osobowe
- **Imię i nazwisko:** {{ site.title }}
- **Email:** example@example.com
- **Telefon:** +48 123 456 789
- **Adres:** Twoje miasto

---

## 🎓 Wykształcenie — Oś czasu

<div class="timeline cv-timeline">
  {% for item in site.data.education %}
  <div class="timeline-item">
    <div class="timeline-icon"><i class="fa-solid fa-graduation-cap"></i></div>
    <div class="timeline-line"></div>
    <div class="timeline-content">
      <span class="timeline-year">{{ item.year }}</span>
      <h3>{{ item.school }}</h3>
      <p>{{ item.degree }}</p>
    </div>
  </div>
  {% endfor %}
</div>

---

## 💼 Doświadczenie zawodowe — Oś czasu

<div class="timeline cv-timeline">
  {% for item in site.data.experience %}
  <div class="timeline-item">
    <div class="timeline-icon"><i class="fa-solid fa-briefcase"></i></div>
    <div class="timeline-line"></div>
    <div class="timeline-content">
      <span class="timeline-year">{{ item.year }}</span>
      <h3>{{ item.company }}</h3>
      <p>{{ item.position }}</p>
    </div>
  </div>
  {% endfor %}
</div>

---

## 🧠 Umiejętności

- Programowanie: Python, Java, C#
- HTML, CSS, Jekyll, GitHub Pages
- Systemy Windows & Linux
- Obsługa sprzętu i diagnostyka IT

---

## 📄 Pobierz pełne CV (PDF)

👉 _Prześlij mi PDF, a przygotuję automatyczne pobieranie tutaj._

---


---

