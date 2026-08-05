<h1 align="center">Дмитрий Власенко</h1>

<p align="center">
  <b>Frontend-разработчик</b> · Vue 3 + TypeScript · 7 лет в продакшене<br>
  Москва · удалённая работа
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue.js">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=white" alt="Nuxt">
  <img src="https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logo=vuedotjs&logoColor=black" alt="Pinia">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" alt="GitLab CI">
</p>

---

## О себе

Пишу фронтенд для больших SPA — тех, где счёт идёт на тысячи файлов и сотни компонентов, а не на пару экранов. Последние четыре года веду образовательную LMS-платформу: **2100+ файлов, 550+ компонентов**, продакшен на шести репликах Kubernetes.

Люблю задачи на стыке архитектуры и инструментов: собрать UI-kit, чтобы команда перестала копипастить кнопки; написать свой ESLint-плагин, чтобы договорённости соблюдались автоматически; перевести проект с Vue 2 на Vue 3 так, чтобы пользователи ничего не заметили.

Помимо кода — координирую фронтенд-команду (2–3 человека), провожу код-ревью, менторю новичков и участвую в технических собеседованиях.

## Что успел сделать

**Библиотеки и инструменты**
- UI-kit `@umax/umax-ui` — единые компоненты для нескольких проектов, документация в Storybook
- npm-пакет для Яндекс.Метрики с type-safe TypeScript API
- Кастомный ESLint-плагин под командные code standards

**Миграции и рефакторинг**
- Три крупных продакшен-проекта переведены с Vue 2 на Vue 3 без даунтайма
- Options API (Class) → Composition API, Vuex → Pinia, серверный стейт на Tanstack Vue Query

**Сборка и инфраструктура**
- CI/CD на GitLab с автодеплоем в Kubernetes
- Время сборки сокращено на **40 %** — SWC, code splitting, tree shaking
- Мониторинг на Sentry с автоматической выгрузкой source maps

**Нестандартные интеграции**
- Monaco Editor прямо в браузере — редактирование кода с подсветкой синтаксиса
- Плагин LaTeX-формул для TinyMCE — самописная замена платному решению
- Генерация PNG из Vue-компонентов и в браузере, и на Node.js
- Документы DOCX и PDF по шаблонам, real-time через WebSocket / Pusher.js

## Open Source

**[formkit/drag-and-drop](https://github.com/formkit/drag-and-drop)** &nbsp;·&nbsp; ⭐ 1.9k

Нашёл критический баг во вложенных drag-группах ([issue #83](https://github.com/formkit/drag-and-drop/issues/83)), собрал воспроизводимый пример на CodeSandbox и прислал PR с фиксом. Изменения вошли в [релиз v0.4.1](https://github.com/formkit/drag-and-drop/releases/tag/v0.4.1).

## Стек

| | |
|---|---|
| **Основное** | Vue 3 / 2, TypeScript, JavaScript ES6+, HTML5, SCSS |
| **Состояние** | Pinia, Vuex, Tanstack Vue Query |
| **Сборка** | Vite, Webpack 5, SWC |
| **UI** | Naive UI, Vuetify, Storybook |
| **Качество** | ESLint (в т. ч. свои плагины), Prettier, Husky, TS strict mode |
| **DevOps** | Docker, GitLab CI/CD, Kubernetes, Sentry |
| **Архитектура** | Feature-based, Feature-Sliced Design, монорепозитории, hygen |
| **Прочее** | Vee-validate, Vue i18n, WebSocket, Pusher.js, Monaco Editor |

## Опыт

| Компания | Роль | Период |
|---|---|---|
| **MAXIMUM EDUCATION** | Frontend-разработчик | июль 2022 — н. в. |
| **LeadHit** | Веб-разработчик | окт. 2020 — июль 2022 |
| **Gridnine Systems** | Инженер-программист | июль 2020 — авг. 2020 |
| **Воркл** | Frontend-разработчик | июнь 2019 — апр. 2020 |

## Связь

Открыт к предложениям: **Frontend / Vue**, удалённо, полная занятость. Готов при необходимости перейти на React или Angular.

[![Email](https://img.shields.io/badge/vlasenko@live.ru-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vlasenko@live.ru)

---

<details>
<summary><b>🇬🇧 English version</b></summary>

<br>

## About

I build front-ends for large SPAs — the kind measured in thousands of files and hundreds of components, not a couple of screens. For the past four years I have been working on an educational LMS platform: **2,100+ files, 550+ components**, running in production across six Kubernetes replicas.

I enjoy work where architecture meets tooling: building a UI kit so the team stops copy-pasting buttons, writing a custom ESLint plugin so conventions enforce themselves, migrating a project from Vue 2 to Vue 3 without users noticing a thing.

Beyond code, I coordinate a front-end team of 2–3 developers, run code reviews, mentor newcomers and take part in technical interviews.

## Highlights

**Libraries and tooling**
- `@umax/umax-ui` UI kit — shared components across projects, documented in Storybook
- npm package for Yandex.Metrica with a type-safe TypeScript API
- Custom ESLint plugin enforcing team-wide code standards

**Migrations and refactoring**
- Three large production projects migrated from Vue 2 to Vue 3 with zero downtime
- Options API (Class) → Composition API, Vuex → Pinia, server state on Tanstack Vue Query

**Build and infrastructure**
- GitLab CI/CD pipeline with automated deployment to Kubernetes
- Build time cut by **40 %** via SWC, code splitting and tree shaking
- Sentry monitoring with automatic source map uploads

**Non-trivial integrations**
- Monaco Editor embedded in the browser for in-app code editing
- LaTeX formula plugin for TinyMCE — an in-house alternative to a paid product
- PNG generation from Vue components, both in-browser and server-side on Node.js
- DOCX and PDF generation from templates, real-time features over WebSocket / Pusher.js

## Open Source

**[formkit/drag-and-drop](https://github.com/formkit/drag-and-drop)** &nbsp;·&nbsp; ⭐ 1.9k

Found a critical bug in nested drag groups ([issue #83](https://github.com/formkit/drag-and-drop/issues/83)), put together a reproducible CodeSandbox case and submitted a fix. The patch shipped in [release v0.4.1](https://github.com/formkit/drag-and-drop/releases/tag/v0.4.1).

## Stack

| | |
|---|---|
| **Core** | Vue 3 / 2, TypeScript, JavaScript ES6+, HTML5, SCSS |
| **State** | Pinia, Vuex, Tanstack Vue Query |
| **Build** | Vite, Webpack 5, SWC |
| **UI** | Naive UI, Vuetify, Storybook |
| **Quality** | ESLint (incl. custom plugins), Prettier, Husky, TS strict mode |
| **DevOps** | Docker, GitLab CI/CD, Kubernetes, Sentry |
| **Architecture** | Feature-based, Feature-Sliced Design, monorepos, hygen |
| **Also** | Vee-validate, Vue i18n, WebSocket, Pusher.js, Monaco Editor |

## Experience

| Company | Role | Period |
|---|---|---|
| **MAXIMUM EDUCATION** | Frontend Developer | Jul 2022 — present |
| **LeadHit** | Web Developer | Oct 2020 — Jul 2022 |
| **Gridnine Systems** | Software Engineer | Jul 2020 — Aug 2020 |
| **Workle** | Frontend Developer | Jun 2019 — Apr 2020 |

## Contact

Open to **Frontend / Vue** roles — remote, full-time. Happy to move to React or Angular if the role calls for it.

[![Email](https://img.shields.io/badge/vlasenko@live.ru-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vlasenko@live.ru)

</details>

