# EasyTopup — Mobile Recharge & Top-up Platform

<p align="left">
  <a href="https://play.google.com/store/apps/details?id=easytopup.easytopupapp.EasyTopup">
    <img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" alt="Google Play" />
  </a>
  <a href="https://apps.apple.com/ng/app/easy-topup-mobile-recharge/id6633411365">
    <img src="https://img.shields.io/badge/App_Store-000000?style=for-the-badge&logo=apple&logoColor=white" alt="App Store" />
  </a>
  <a href="https://easytopup.pk">
    <img src="https://img.shields.io/badge/Website-0052FF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" />
  </a>
</p>

A live, production mobile recharge and utility top-up platform — available on iOS, Android, and web. The entire backend was designed, built, and deployed to a VPS by me solo in 3.5 months. It powers high-volume transactions, integrates multiple telecom APIs, and processes payments across five distinct payment gateways including Apple Pay and Google Pay.

---

## 🚀 Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel 10" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP 8.1+" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Laravel_Passport-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel Passport" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Pusher-300D4F?style=for-the-badge&logo=pusher&logoColor=white" alt="Pusher" />
</p>

---

## ✨ Key Features

- **Mobile Top-ups** — Query telecom catalogs and process instant recharges via Ding API and Swich API
- **Multi-Gateway Payments** — Unified checkout supporting JazzCash, EasyPaisa, MyPay, Bank Alfalah, and Tap Payments
- **Apple Pay & Google Pay** — Native wallet support via the Tap payment gateway
- **Real-Time Support Chat** — In-app live chat using Laravel Reverb and Pusher with a built-in ticketing system
- **Automated Order Fulfillment** — Async fulfillment queues handle payment callbacks, retries, and failure rollbacks automatically
- **Push Notifications** — Transaction updates delivered instantly via Firebase Cloud Messaging
- **Device Binding & Fraud Prevention** — Custom service enforcing strict session limits per device

---

## 🔌 Integrations

| Category | Services |
|---|---|
| Telecom APIs | Ding API, Swich API |
| Payment Gateways | JazzCash, EasyPaisa, MyPay, Bank Alfalah, Tap (Apple Pay, Google Pay) |
| Real-Time | Laravel Reverb, Pusher |
| Notifications | Firebase Cloud Messaging (FCM) |
| Auth | Laravel Passport (OAuth2), Laravel Sanctum |

---

## 🛠️ My Contributions

I worked as the backend developer and architect on this project, responsible for the API, payment infrastructure, and third-party integrations.

**Admin Panel**
- Built a full-featured admin dashboard covering complete CRUD operations 
  for users, transactions, orders, and platform configuration — giving the 
  business team full control over the platform without touching the codebase
**Payment Infrastructure**
- Designed the `PaymentService` using the Strategy pattern to normalize responses, handle webhooks, and process payment inquiries across all 5 gateways into a single standardized transaction flow — regardless of which provider the user pays through

**Telecom Integrations**
- Implemented full product catalog mapping, promotions, and real-time recharge processing using both Ding and Swich APIs

**Fulfillment & Reconciliation**
- Built the `FulfillmentService` — handles automated order retrieval, manual reconciliation for edge cases (money deducted but telecom delivery fails), and accurate ledger updates to protect users and the business

**Real-Time Infrastructure**
- Integrated Laravel Reverb and Pusher for live customer support chat, and Firebase FCM for instant push notifications on every transaction event

**Security**
- Implemented OAuth2 authentication via Laravel Passport and built a custom Device Binding service to prevent session abuse and unauthorized access

---

## 💡 Skills This Project Demonstrates

- RESTful API design for mobile (iOS + Android) and web consumption
- Unifying multiple third-party payment and telecom APIs into clean internal interfaces
- Financial workflow handling — race conditions, background queues, webhook processing, ledger reconciliation
- Real-time systems with WebSockets and push notifications
- Security-first API design with OAuth2, device binding, and fraud prevention

---

## 🌐 Live Project

- **Android:** [Google Play Store](https://play.google.com/store/apps/details?id=easytopup.easytopupapp.EasyTopup)
- **iOS:** [Apple App Store](https://apps.apple.com/ng/app/easy-topup-mobile-recharge/id6633411365)
- **Web:** [easytopup.pk](https://easytopup.pk)

---

## 📫 Contact

Open to freelance projects and remote opportunities.

- **GitHub:** [github.com/abubakaramin](https://github.com/abubakaramin)
- **Email:** [abubakarmain100@gmail.com](mailto:abubakarmain100@gmail.com)
