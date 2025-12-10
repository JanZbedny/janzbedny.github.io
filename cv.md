---
title: CV
layout: default
---

# 📄 Curriculum Vitae

## 👤 Dane osobowe

| **Informacja**        | **Wartość** |
|----------------------|-------------|
| 🧑 Imię i nazwisko    | **Tomasz Kowalczyk** |
| 🎂 Data urodzenia     | DD-MM-YYYY|
| 📍 Miejsce zamieszkania | Olsztyn |
| 📞 Telefon            | 000 000 000 |
| ✉️ E-mail             | vvvvJan@protonmail.com |

## 🎓 Wykształcenie — Oś czasu

<div class="timeline">
  {% for item in site.data.education %}
  <div class="timeline-item">
    <span class="timeline-year">{{ item.year }}</span>
    <span class="timeline-detail">{{ item.school }} — {{ item.degree }}</span>
  </div>
  {% endfor %}
</div>

</div>

---

## 💼 Doświadczenie zawodowe — Oś czasu

<div class="timeline">
  {% for item in site.data.experience %}
  <div class="timeline-item">
    <span class="timeline-year">{{ item.year }}</span>
    <span class="timeline-detail">{{ item.company }} — {{ item.position }}</span>
  </div>
  {% endfor %}
</div>
</div>

<div class="entry">
  <div class="year">2021 – 2023</div>
  <div class="detail">
    <strong>Software House XYZ</strong><br>
    Junior Developer<br>
    • Tworzenie aplikacji webowych<br>
    • Praca z JavaScript i Pythonem
  </div>
</div>

</div>

---

## 🛠️ Umiejętności

### 🔧 Techniczne
- Linux, Windows Server  
- Git, GitHub  
- HTML / CSS / Jekyll  
- Python (podstawy)  
- Automatyzacje IT  
- Sieci komputerowe  

### 🤝 Miękkie
- Komunikacja  
- Praca zespołowa  
- Analityczne myślenie  
- Organizacja czasu  

---

## 🌐 Języki
- 🇵🇱 Polski – ojczysty  
- 🇬🇧 Angielski – B2  

---

## 📎 Dokument do pobrania

➡️ [**Pobierz pełne CV (PDF)**](assets/cv.pdf)

---

