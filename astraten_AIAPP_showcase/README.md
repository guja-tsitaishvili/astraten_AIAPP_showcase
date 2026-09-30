# astraten_AIAPP_showcase
i built AI zodiac app astraten, this is first public project for poeple to use and it was quite successfull, it become popular in my country. people started asking questions look for answers and has big satisfaction rate. it spread with power of "word of mouth" and has growing users.  2200 and counting. 

# 🌌 astraten — Astrological Intelligence & Compatibility Platform

> **Showcase Repository**: This public repository serves as a portfolio demonstration of the architecture, UI system, and technical patterns behind **astraten**. Proprietary system prompts, production secrets, and direct payment Webhooks have been sanitized and mocked for public viewing.

---

## 🛠️ Tech Stack & Badges

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![TailwindCSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Dodo Payments](https://img.shields.io/badge/Dodo_Payments-FF6B6B?style=for-the-badge&logo=card&logoColor=white)

---

## 🚀 Architectural Overview

astraten combines high-precision astronomical mechanics with generative AI to calculate natal charts, interpret planetary aspects, and compute synastry compatibility models.

```mermaid
flowchart TD
    A[Client UI / User Input] -->|Birth Details & Time| B[Next.js App Router Server Action]
    B -->|Calculate Ephemeris| C[Astronomy Engine & Chart JS]
    C -->|Structured Celestial Data| B
    B -->|Query Entitlements| D[Supabase SSR Session]
    D -->|Valid Session & Credits| E[AI Generation Core]
    E -->|Structured Reading| B
    B -->|Render UI & Export Canvas| A
    
    A -->|Checkout Request| F[Dodo Payments API]
    F -->|Webhook Success Event| D

```
## 📱 Product Showcase

| 💬 AI Chat & Interpretations | 👤 Saved Profiles & Charts |
| :---: | :---: |
| ![AI Chat Feature](.github/assets/AIchat.png) | ![Profiles Page](.github/assets/profilespage.png) |
| *Real-time AI astrology assistant & reading output* | *User natal chart storage & profile management* |

---

### 🔮 Compatibility & Readings Overview

<p align="center">
  <img src=".github/assets/readingspage.png" alt="Readings Page Showcase" width="100%">
  <br>
  <em>Synastry compatibility scoring and detailed astrological analysis dashboard</em>
</p>
