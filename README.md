<div align="center">
  <h1>💎 GetGems | Premium NFT Landing Page</h1>
  <p><b>Высокопроизводительный и визуально потрясающий Web3-лендинг, построенный на нативных веб-технологиях для достижения идеальных 60 FPS.</b></p>

  <div>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/GSAP_3-88CE02?style=for-the-badge&logo=greensock&logoColor=white" alt="GSAP" />
  </div>
</div>

---

## 💻 Демонстрация интерфейса

<div align="center">
  <b>🖥 Десктопная версия (macOS)</b><br><br>
  <img src="https://github.com/user-attachments/assets/d9a01c9c-5fa6-4356-8d63-8b475b66b89a" width="800" />
</div>

<br>

<table align="center">
  <tr>
    <td align="center">
      <b>📲 Планшет (iPad)</b><br>
      <img src="https://github.com/user-attachments/assets/2659bd84-42e8-41c7-aa76-e10a4a724684" width="350" />
    </td>
    <td align="center">
      <b>📱 Смартфон (iPhone)</b><br>
      <img src="https://github.com/user-attachments/assets/d7107a7b-3708-4c3e-ad82-f56f5faf4ae0" width="350" />
    </td>
  </tr>
</table>

<br>

<div align="center">
  <h3>✨ Плавность анимаций GSAP (Видео-демо)</h3>
  <video src="https://github.com/user-attachments/assets/2df72ab8-a1a3-4fe1-bdb4-0435db2b897b" width="600" autoplay loop muted playsinline style="border-radius: 20px;"></video>
</div>

---

## 🚀 Ключевые особенности (Key Features)

Проект спроектирован с упором на премиальный пользовательский опыт и бесшовные микродвижения.

* 🎬 **Продвинутые анимации GSAP:** Многоуровневые параллакс-эффекты, сложные секвенции появления и скролл-анимации.
* ⚡ **Экстремальная оптимизация:** Использование исключительно `transform` и `opacity` для полного аппаратного ускорения (GPU) и предотвращения скачков верстки (Reflow/Layout Shifts).
* 🔮 **Glassmorphism UI:** Современный темный дизайн (Dark Web3) с яркими неоновыми акцентами и эффектом матового стекла.
* 🔠 **Кастомный SplitText:** Легковесная реализация посимвольной анимации текста без использования платных тяжелых зависимостей.
* 🧲 **Магнитные интеракции:** Интерактивные UI-элементы, плавно реагирующие на движения курсора и касания.

---

## 🛠 Технологический стек

* **Базовый слой:** Semantic HTML5, Vanilla CSS3 (Custom Properties), JavaScript (ES6+).
* **Анимационный движок:** [GSAP 3](https://gsap.com/) (GreenSock Animation Platform).
* **Плагины:** `ScrollTrigger`, `Observer` (для нормализации touch-событий).
* **Инструментарий:** `Browser-sync` для быстрой разработки и локального сервера с Hot Reload.

---

## 🏗 Архитектура: Performance First

Проект следует строгой философии «Производительность прежде всего», что критически важно для мобильных браузеров:

1. **Zero Framework Bloat:** Никакого оверхеда от React или Vue — только чистый, быстро парсящийся код для мгновенной отрисовки (Largest Contentful Paint).
2. **GPU Compositing:** Агрессивное использование свойства `will-change: transform, opacity` для рендеринга слоев на стороне видеокарты.
3. **Event Normalization:** Внедрение плагина GSAP `Observer` для консистентной обработки сложных свайпов и тапов на всех устройствах (Android/iOS).

---

## 📦 Быстрый старт (Local Setup)

Для запуска проекта локально убедитесь, что у вас установлен [Node.js](https://nodejs.org/), и выполните следующие шаги:

1. **Клонируйте репозиторий:**
   ```bash
   git clone [https://github.com/m1sstak3/getgems-nft-landing.git](https://github.com/m1sstak3/getgems-nft-landing.git)
   cd getgems-nft-landing
   ```

2. **Установите зависимости (для локального сервера):**
   ```bash
   npm install
   ```

3. **Запустите development-сервер:**
   ```bash
   npm run dev
   ```
   *(Проект автоматически откроется в вашем браузере по адресу `http://localhost:3000`)*

---

<div align="center">
  <p>Проект является открытым и распространяется под лицензией <a href="LICENSE">MIT</a>.</p>
  <b>Developed with ❤️ by m1sstak3</b>
</div>
