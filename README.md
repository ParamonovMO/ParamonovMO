<!-- Стили для экрана iPhone -->
<style>
  .iphone-frame {
    max-width: 400px;
    margin: 0 auto 20px auto;
    background: #000;
    border-radius: 48px;
    padding: 16px 8px 24px 8px;
    box-shadow: 0 20px 40px rgba(0,0,0,0.3), 0 0 0 8px #3a3a3a;
    position: relative;
  }
  .iphone-screen {
    background: #ffffff;
    border-radius: 36px;
    padding: 24px 20px 20px 20px;
    position: relative;
    overflow: hidden;
    box-shadow: inset 0 0 0 1px rgba(255,255,255,0.1);
  }
  /* Dynamic Island */
  .dynamic-island {
    width: 110px;
    height: 34px;
    background: #111;
    margin: -34px auto 12px auto;
    border-radius: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .camera-dot {
    width: 12px;
    height: 12px;
    background: #1a1a1a;
    border-radius: 50%;
    margin: 0 4px;
    border: 1px solid #333;
  }
  .avatar-img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    object-fit: cover;
    margin: 0 auto 12px;
    display: block;
    border: 3px solid #007aff;
  }
  .iphone-screen h1, .iphone-screen h3, .iphone-screen p {
    margin: 8px 0;
    text-align: center;
    color: #1c1c1e;
  }
  .iphone-screen h1 {
    font-size: 24px;
    font-weight: 700;
  }
  .iphone-screen h3 {
    font-size: 16px;
    font-weight: 500;
    color: #8e8e93;
  }
  .contact-buttons {
    display: flex;
    justify-content: center;
    gap: 12px;
    margin: 16px 0;
  }
  .contact-buttons a {
    text-decoration: none;
    background: #007aff;
    color: white;
    padding: 8px 16px;
    border-radius: 30px;
    font-weight: 500;
    font-size: 14px;
    display: inline-flex;
    align-items: center;
    gap: 6px;
  }
  .contact-buttons a.telegram { background: #26A5E4; }
  .contact-buttons a.email { background: #EA4335; }
  .contact-buttons a.resume { background: #34C759; }
  .status-badge {
    background: #e5e5ea;
    padding: 6px 12px;
    border-radius: 30px;
    font-size: 14px;
    color: #1c1c1e;
    display: inline-block;
    margin: 4px auto;
    text-align: center;
  }
  .divider {
    height: 1px;
    background: #c6c6c8;
    margin: 16px 0;
  }
  .skills-icons {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 16px;
  }
  .skills-icons img {
    width: 32px;
    height: 32px;
  }
  /* Адаптация для тёмной темы GitHub */
  @media (prefers-color-scheme: dark) {
    .iphone-screen {
      background: #1c1c1e;
    }
    .iphone-screen h1, .iphone-screen h3, .iphone-screen p {
      color: #ffffff;
    }
    .iphone-screen h3 {
      color: #98989e;
    }
    .status-badge {
      background: #2c2c2e;
      color: #ffffff;
    }
    .divider {
      background: #38383a;
    }
  }
</style>

<div align="center">
  <div class="iphone-frame">
    <div class="iphone-screen">
      <!-- Dynamic Island -->
      <div class="dynamic-island">
        <div class="camera-dot"></div>
        <div class="camera-dot" style="background: #2c2c2c;"></div>
      </div>
      
      <!-- Аватарка (замените src на свою) -->
      <img class="avatar-img" src="https://avatars.githubusercontent.com/u/ваш-id?v=4" alt="Максим Парамонов" />
      
      <h1>👋 Максим Парамонов</h1>
      <h3>🧪 QA Engineer | 🐍 Python AQA</h3>
      
      <div align="center">
        <span class="status-badge">🔍 В поиске работы</span>
      </div>
      
      <div class="contact-buttons">
        <a href="https://t.me/ParamonovMO" class="telegram" target="_blank">
          <img src="https://cdn.simpleicons.org/telegram/white" width="16" height="16" style="filter: brightness(0) invert(1);"> Telegram
        </a>
        <a href="mailto:paramonov.maxim@vk.com" class="email" target="_blank">
          <img src="https://cdn.simpleicons.org/gmail/white" width="16" height="16" style="filter: brightness(0) invert(1);"> Email
        </a>
        <a href="#" class="resume" target="_blank">
          <img src="https://cdn.simpleicons.org/readthedocs/white" width="16" height="16" style="filter: brightness(0) invert(1);"> Резюме
        </a>
      </div>
      
      <div class="divider"></div>
      
      <p style="font-size: 14px; margin-bottom: 8px;">
        🎓 Выпускник <strong>Яндекс Практикума</strong><br>
        «Инженер по тестированию»<br>
        «Автоматизатор на Python»
      </p>
      
      <div class="skills-icons">
        <img src="https://cdn.simpleicons.org/python/3776AB" alt="Python" title="Python"/>
        <img src="https://cdn.simpleicons.org/selenium/43B02A" alt="Selenium" title="Selenium"/>
        <img src="https://cdn.simpleicons.org/pytest/0A9EDC" alt="Pytest" title="Pytest"/>
        <img src="https://cdn.simpleicons.org/postman/FF6C37" alt="Postman" title="Postman"/>
        <img src="https://cdn.simpleicons.org/git/F05032" alt="Git" title="Git"/>
        <img src="https://cdn.simpleicons.org/pycharm/000000" alt="PyCharm" title="PyCharm" style="filter: invert(1);"/>
        <img src="https://cdn.simpleicons.org/figma/F24E1E" alt="Figma" title="Figma"/>
      </div>
      
      <p style="font-size: 13px; margin-top: 16px;">
        <img src="https://komarev.com/ghpvc/?username=ParamonovMO&style=flat-square&color=007aff" alt=""/>
      </p>
    </div>
  </div>
</div>

<br>

<!-- Остальная информация остаётся за пределами "экрана" -->
---

### 🚀 Мои проекты (автотесты)

| Название | Описание | Стек |
|----------|----------|------|
| **[Web‑приложение Яндекс.Самокат](https://github.com/ParamonovMO/scooter-tests)** | UI‑автотесты на Selenium + Pytest, Allure‑отчёты | Python, Selenium, Pytest, Allure |
| **[API‑тесты для учебного сервиса](https://github.com/ParamonovMO/api-tests)** | Проверка REST API с помощью Requests и Pytest | Python, Requests, Pytest |
| **[Мобильное тестирование (Android)](https://github.com/ParamonovMO/mobile-tests)** | Автотесты для мобильного приложения через Appium | Python, Appium, Pytest |

*Ссылки примерные — замените на свои репозитории.*

---

### 📫 Контакты

<div align="center">
  <a href="https://t.me/ParamonovMO"><img src="https://img.shields.io/badge/Telegram-@ParamonovMO-blue?style=flat-square&logo=telegram" alt="Telegram"/></a>
  <a href="mailto:paramonov.maxim@vk.com"><img src="https://img.shields.io/badge/Email-paramonov.maxim@vk.com-red?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/ParamonovMO"><img src="https://img.shields.io/badge/GitHub-ParamonovMO-181717?style=flat-square&logo=github" alt="GitHub"/></a>
</div>

<br>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,100:92FE9D&height=100&section=footer" alt="footer"/>
</div>
