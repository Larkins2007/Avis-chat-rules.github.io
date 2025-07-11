<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Правила чата</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      line-height: 1.5;
      color: #222;
      background: #fff;
    }
    h1 {
      font-size: 2em;
      margin-bottom: 0.5em;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    h1 svg {
      width: 36px;
      height: 36px;
      fill: #007acc;
      flex-shrink: 0;
    }
    h2 {
      margin-top: 40px;
      margin-bottom: 10px;
      border-bottom: 2px solid #007acc;
      padding-bottom: 5px;
      color: #333;
      display: flex;
      align-items: center;
      gap: 8px;
    }
    h2 svg {
      width: 24px;
      height: 24px;
      fill: #007acc;
      flex-shrink: 0;
      transition: transform 0.3s ease;
    }
    h2:hover svg {
      transform: rotate(15deg);
      fill: #005fa3;
    }
    h3 {
      margin-top: 20px;
      margin-bottom: 6px;
      color: #444;
      display: flex;
      align-items: center;
      gap: 6px;
    }
    h3 svg {
      width: 16px;
      height: 16px;
      fill: #007acc;
      flex-shrink: 0;
      transition: fill 0.3s ease;
    }
    h3:hover svg {
      fill: #005fa3;
    }
    p {
      margin-bottom: 1em;
    }
    ul {
      padding-left: 1.2em;
      margin-bottom: 1em;
    }
    nav {
      background: #f0f0f0;
      padding: 15px;
      border-radius: 8px;
      margin-bottom: 30px;
    }
    nav ul {
      padding-left: 0;
      list-style: none;
    }
    nav ul li {
      margin-bottom: 8px;
      display: flex;
      align-items: center;
      gap: 6px;
    }
    nav ul li svg {
      width: 14px;
      height: 14px;
      fill: #007acc;
      flex-shrink: 0;
      transition: fill 0.3s ease;
    }
    nav ul li a {
      text-decoration: none;
      color: #007acc;
      transition: color 0.3s;
      flex-grow: 1;
    }
    nav ul li a:hover,
    nav ul li a:focus {
      color: #005fa3;
      outline: none;
      text-decoration: underline;
    }
    strong {
      color: #000;
    }
    em {
      color: #555;
    }
    html {
      scroll-behavior: smooth;
    }
    @media (max-width: 600px) {
      body {
        margin: 10px;
        font-size: 16px;
      }
      nav {
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <h1>
    <!-- Иконка правил (щит с галочкой) -->
    <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
      <path d="M12 2L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-3zM10 16l-4-4 1.41-1.41L10 13.17l6.59-6.59L18 8l-8 8z"/>
    </svg>
    Правила чата
  </h1>

  <p>Каждый вошедший пользователь добровольно принимает правила нашего чата и обязуется их соблюдать.</p>

  <nav aria-label="Оглавление">
    <h2>
      Содержание
      <!-- Иконка списка -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M4 10h16v2H4zm0-4h16v2H4zm0 8h10v2H4z"/>
      </svg>
    </h2>
    <ul>
      <li>
        <!-- Иконка стрелки вправо -->
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
          <path d="M10 17l5-5-5-5v10z"/>
        </svg>
        <a href="#ne-zhelatelno">Не желательно</a>
      </li>
      <li>
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
          <path d="M10 17l5-5-5-5v10z"/>
        </svg>
        <a href="#zapreshchaetsya">Запрещается</a>
      </li>
      <li>
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
          <path d="M10 17l5-5-5-5v10z"/>
        </svg>
        <a href="#dopolneniya-po-moderatoram">Важные дополнения по работе модераторов и контролю качества их действий</a>
      </li>
      <li>
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
          <path d="M10 17l5-5-5-5v10z"/>
        </svg>
        <a href="#nakazaniya">Наказания</a>
      </li>
      <li>
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
          <path d="M10 17l5-5-5-5v10z"/>
        </svg>
        <a href="#politika">Политика модераторов</a>
      </li>
    </ul>
  </nav>

  <section id="samoe-vazhnoe">
    <h2>
      Самое важное
      <!-- Иконка звезды -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 17.27L18.18 21l-1.64-7.03L22 9.24l-7.19-.61L12 2 9.19 8.63 2 9.24l5.46 4.73L5.82 21z"/>
      </svg>
    </h2>
    <p><strong>Каждый участник чата обязан уважать других, соблюдать правила и поддерживать дружелюбную атмосферу.</strong></p>
    <p>Нарушение этого принципа ведёт к предупреждениям и, при повторении — к более строгим мерам вплоть до бана.</p>
  </section>

  <section id="ne-zhelatelno">
    <h2>
      Не желательно
      <!-- Иконка предупреждения -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M1 21h22L12 2 1 21zm12-3h-2v-2h2v2zm0-4h-2v-4h2v4z"/>
      </svg>
    </h2>
    <h3>
      1. Использование большого количества ненормативной лексики
      <!-- Иконка "звук" -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M3 9v6h4l5 5V4L7 9H3z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Предупреждение</p>
    <p><strong>Пояснение:</strong> Мы понимаем, что иногда эмоции берут верх, но старайтесь не злоупотреблять матом. Если вы используете ненормативную лексику редко и без оскорблений — это не проблема.</p>
    <p><strong>Пример:</strong> «Вот это классно!» — нормально; «Ты полный [нецензурное слово]» — повод для предупреждения.</p>

    <h3>
      2. Рекламировать другие группы/каналы
      <!-- Иконка "реклама" -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M3 10h2v4H3v-4zm16-2h2v8h-2v-8zm-6 0h2v8h-2v-8zM5 7h14v2H5V7z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Предупреждение</p>
    <p><strong>Пояснение:</strong> Реклама чужих ресурсов без согласия администрации мешает общению. Если хотите поделиться полезным каналом — сначала свяжитесь с администратором (@lia_os).</p>
    <p><strong>Пример:</strong> «Подпишитесь на мой канал!» — запрещено без разрешения.</p>

    <h3>
      3. Начинать ссоры, старайтесь поддерживать комфорт в чате
      <!-- Иконка "конфликт" -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M7 14l5-5 5 5H7z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Предупреждение или мут (в зависимости от интенсивности)</p>
    <p><strong>Пояснение:</strong> Споры бывают, но если они переходят в оскорбления или мешают другим — сначала предупредим, а при повторе временно ограничим возможность писать (мут).</p>
    <p><strong>Пример:</strong> «Ты неправ!» — нормально, «Ты идиот!» — повод для наказания.</p>

    <h3>
      4. Flash — видео/голосовые (редкие громкие звуки, резко мерцающие видео)
      <!-- Иконка "звук мут" -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M16.5 12c0-1.77-1.02-3.29-2.5-4.03v8.06c1.48-.74 2.5-2.26 2.5-4.03zM19 12c0 2.89-2.39 5.24-5.5 5.24S8 14.89 8 12s2.39-5.24 5.5-5.24S19 9.11 19 12z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Мут</p>
    <p><strong>Пояснение:</strong> Такие материалы могут раздражать или вредить здоровью участников (например, вызывать головную боль). Поэтому за их публикацию временно ограничивается возможность писать.</p>

    <h3>
      5. Оскорбление персонажей, уважайте чувства и вкусы других
      <!-- Иконка "сердце" -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41 1.01 4.5 2.09C13.09 4.01 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Предупреждение или мут</p>
    <p><strong>Пояснение:</strong> Критика — нормально, а личные оскорбления — нет.</p>
    <p><strong>Пример:</strong> «Мне не нравится этот персонаж» — допустимо, «Этот персонаж — дурак» — нарушение.</p>

    <h3>
      6. Пересылка личных сообщений другого человека в беседу
      <!-- Иконка "конфиденциальность" -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Предупреждение</p>
    <p><strong>Пояснение:</strong> Личные сообщения другого участника нельзя пересылать в общий чат без согласия обеих сторон. Если оба участника переписки являются членами группы, часть переписки пересылается только с одобрения обеих сторон. Это помогает сохранять приватность и уважать личное пространство.</p>
    <p><strong>Пример:</strong> Пересылать скриншоты или сообщения из личных диалогов без разрешения — запрещено.</p>
  </section>

  <section id="zapreshchaetsya">
    <h2>
      Запрещается
      <!-- Иконка запрета -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm5 13.59L13.59 17 12 15.41 10.41 17 7 13.59 8.59 12 7 10.41 10.41 7 12 8.59 13.59 7 17 10.41 15.41 12 17 13.59z"/>
      </svg>
    </h2>

    <!-- Для каждого пункта добавим иконки в заголовках -->
    <h3>
      1. Обсуждение политики и публикация любого контента, связанного с политикой
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M7 10h2v4H7zM15 10h2v4h-2z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Бан</p>
    <p><strong>Пояснение:</strong> Политика часто вызывает конфликты и разделение. Чтобы сохранить дружелюбную атмосферу, такие темы запрещены.</p>
    <p><strong>Пример:</strong> обсуждение выборов, политических лидеров и т.п.</p>

    <h3>
      2. Оскорбления
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 4a8 8 0 1 0 0 16 8 8 0 0 0 0-16zm1 11h-2v-2h2v2zm0-4h-2V7h2v4z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Предупреждение, при повторе — мут или бан</p>
    <p><strong>Пояснение:</strong> Шутки — хорошо, но если кому-то неприятно — защитим его.</p>
    <p><strong>Пример:</strong> «Ты такой смешной дурачок» — шутка, но если это обидело — последует предупреждение.</p>

    <h3>
      3. Публикация порнографического и околопорнографического контента
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 2a10 10 0 1 0 0 20 10 10 0 0 0 0-20zm-1 14h2v2h-2v-2zm0-8h2v6h-2V8z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Бан</p>
    <p><strong>Пояснение:</strong> Нарушает правила приличия и закон.</p>
    <p><strong>Пример:</strong> откровенные фото, видео или ссылки.</p>

    <h3>
      4. Публикация треш-контента (стикеры/видео/гиф с расчлененкой и тому подобное)
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M4 4h16v16H4zM9 9h6v6H9z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Бан</p>
    <p><strong>Пояснение:</strong> Шокирующие материалы могут травмировать участников.</p>
    <p><strong>Пример:</strong> видео с насилием или жестокостью.</p>

    <h3>
      5. Поднятие тем, нарушающих законы РФ (экстремизм, терроризм, пропаганда наркотиков, оскорбление чувств верующих и др.)
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 4a8 8 0 0 1 8 8c0 4.42-3.58 8-8 8s-8-3.58-8-8a8 8 0 0 1 8-8zm0 14a6 6 0 0 0 6-6 6 6 0 0 0-6-6 6 6 0 0 0-6 6 6 6 0 0 0 6 6z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Бан</p>
    <p><strong>Пояснение:</strong> Такие темы запрещены законом и чатом.</p>
    <p><strong>Пример:</strong> призывы к насилию, обсуждение запрещённых веществ.</p>

    <h3>
      6. Спам / флуд (часто повторяющиеся сообщения, сообщения без смысла)
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M3 12h18M3 6h18M3 18h18"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Мут</p>
    <p><strong>Пояснение:</strong> Чтобы чат был удобен для всех, не стоит засорять его бессмысленными сообщениями.</p>
    <p><strong>Пример:</strong> повторять одну и ту же фразу много раз подряд.</p>

    <h3>
      7. Публичное осуждение действий администрации / провокация администрации типа «ну давай бань меня»
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 2a10 10 0 1 1 0 20 10 10 0 0 1 0-20zm1 14h-2v-2h2v2zm0-4h-2V7h2v5z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Предупреждение или мут</p>
    <p><strong>Пояснение:</strong> Если есть вопросы к администрации — лучше написать в личку, а не провоцировать конфликт в общем чате.</p>

    <h3>
      8. Любая дискриминация по расовому/национальному/половому/религиозному признаку
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 2C6.48 2 2 6.48 2 12c0 4.42 3.58 8 8 8 1.85 0 3.55-.63 4.9-1.69l4.39 1.16-1.16-4.39A7.96 7.96 0 0 0 20 12c0-5.52-4.48-10-10-10z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Бан</p>
    <p><strong>Пояснение:</strong> Мы за равенство и уважение ко всем.</p>
    <p><strong>Пример:</strong> оскорбления по национальному признаку недопустимы.</p>

    <h3>
      9. Просьбы перейти по ссылкам/зарегистрироваться на вредоносном сайте
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M10 17l5-5-5-5v10z"/>
      </svg>
    </h3>
    <p><strong>Наказание:</strong> Бан</p>
    <p><strong>Пояснение:</strong> Безопасность участников — наш приоритет.</p>
    <p><strong>Пример:</strong> ссылки на мошеннические сайты.</p>
  </section>

  <section id="dopolneniya-po-moderatoram">
    <h2>
      Важные дополнения по работе модераторов и контролю качества их действий
      <!-- Иконка щита -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 2L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-3z"/>
      </svg>
    </h2>
    <h3>
      10. Модераторы обязаны действовать в соответствии с правилами чата и не использовать свои полномочия в личных интересах
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 12c2.21 0 4-1.79 4-4S14.21 4 12 4 8 5.79 8 8s1.79 4 4 4zM6 20v-2c0-2.21 3.58-4 6-4s6 1.79 6 4v2H6z"/>
      </svg>
    </h3>
    <p><strong>Пояснение:</strong> Если заметили нарушение или злоупотребление полномочиями (например, необоснованно мутит или банит, игнорирует правила), обратитесь к высшим администраторам или создателю чата (@lia_os). Жалобы рассматриваются, и мы защищаем от несправедливого обращения.</p>

    <h3>
      11. Перед применением наказания модератор должен дать словесное предупреждение участнику
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 2a10 10 0 1 1 0 20 10 10 0 0 1 0-20zm1 15h-2v-2h2v2zm0-4h-2V7h2v6z"/>
      </svg>
    </h3>
    <p><strong>Пояснение:</strong> Если поведение начинает нарушать правила или мешать комфорту, модератор предупреждает: «Пожалуйста, прекратите, иначе последуют меры». Если предупреждение игнорируется — применяется наказание (мут, бан и т.п.). Это помогает избежать конфликтов и даёт шанс исправиться.</p>
  </section>

  <section id="nakazaniya">
    <h2>
      Наказания
      <!-- Иконка молотка -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M14.7 9.3l-4.4 4.4-1.4-1.4 4.4-4.4 1.4 1.4zM3 17h18v2H3v-2z"/>
      </svg>
    </h2>
    <ul>
      <li><strong>Предупреждение</strong> — первое и мягкое наказание. Сообщаем, что поведение не соответствует правилам с объяснением.</li>
      <li><strong>Мут</strong> — временное ограничение возможности писать (несколько минут или часов). Используется при повторных нарушениях или серьёзных проступках. Перед мутом обязательно словесное предупреждение.</li>
      <li><strong>Бан</strong> — удаление из чата с запретом на повторный вход. За серьёзные или неоднократные нарушения.</li>
    </ul>
  </section>

  <section id="politika">
    <h2>
      Политика модераторов
      <!-- Иконка политика -->
      <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false" role="img">
        <path d="M12 12c2.21 0 4-1.79 4-4S14.21 4 12 4 8 5.79 8 8s1.79 4 4 4zm-6 8v-2c0-2.21 3.58-4 6-4s6 1.79 6 4v2H6z"/>
      </svg>
    </h2>
    <ul>
      <li>Всегда сначала предупреждайте участников, чтобы дать им шанс исправиться.</li>
      <li>Действуйте объективно и справедливо, руководствуясь правилами, а не личными симпатиями.</li>
      <li>При сомнениях или спорных ситуациях обращайтесь к высшему администратору для консультации.</li>
      <li>Помните, что ваша задача — поддерживать комфорт и безопасность в чате, а не «наказывать» ради наказания.</li>
    </ul>
  </section>

  <section>
    <p>Если у вас есть вопросы или нужна помощь — обращайтесь к администрации (<strong>@lia_os</strong>).</p>
    <p>Спасибо, что соблюдаете правила и делаете чат приятным для всех!</p>
  </section>
</body>
</html>
