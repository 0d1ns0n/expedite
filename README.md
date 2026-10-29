<div align="center">
  <img src="assets/logo.svg" width="96" height="96" alt="Expedite" />
  <h1>Expedite ⚡</h1>
  <p><strong>Прискорення посилки за ініціативою отримувача.</strong></p>
  <p>
    <img alt="status" src="https://img.shields.io/badge/status-concept-blue" />
    <img alt="license" src="https://img.shields.io/badge/license-All%20Rights%20Reserved-red" />
    <img alt="prior art" src="https://img.shields.io/badge/prior%20art-public%20disclosure-informational" />
  </p>
</div>

> **🔒 Публічне розкриття концепції. Усі права захищено (All Rights Reserved).**
> Цей репозиторій — вітрина ідеї, а не відкритий код. Він опублікований, щоб
> зафіксувати **авторство і дату** концепції. Дозволу на використання,
> копіювання чи реалізацію ідеї **не надається**. Деталі — у [`LICENSE`](LICENSE).

---

## Проблема

Сьогодні швидкість посилки задає **відправник** у момент створення ТТН.
Отримувач на останньому відрізку (термінал → відділення → руки) не обирає нічого —
навіть коли посилка вже лежить у відділенні за 500 метрів, а потрібна **зараз**.

- Перевізник продає швидкість при **відправленні**, але не продає прискорення
  **вже прибулої** посилки за ініціативою отримувача.
- У покупця немає кнопки «отримати сьогодні / до потрібного часу».
- Виконавець останньої милі вже існує — його треба лише підключити в правильний момент.

## Ідея

**Expedite** за номером ТТН показує отримувачу, де його посилка і скільки вона
вже лежить, і — **лише коли це справді має сенс** — пропонує привезти її швидше
або забрати без черги за прозору доплату.

Монетизація не нової інфраструктури, а **посилок, які вже їдуть**: дохід для
перевізника/маркетплейсу та економія часу для людини — у момент, коли час коштує
найдорожче.

## Чому це не «ще один чат-бот»

Ключовий принцип (і головна гарантія довіри):

> **Рішення «пропонувати чи ні» та ціну рахує детермінований код. LLM лише
> пояснює це рішення людською мовою — він нічого не вигадує і не може вигадати ціну.**

Завдяки цьому пропозиція передбачувана, пояснювана й безпечна: кожен крок
логується, а ціну неможливо «нагалюцинувати». *Конкретні сигнали, ваги, пороги
та формула ціни є частиною рішення й у цьому репозиторії не розкриваються.*

## Демо

Робочий прототип живий у Telegram: **[@Vip_fastDelivery_bot](https://t.me/Vip_fastDelivery_bot)**
(трекінг — на реальному публічному API Нової Пошти; оплата й курʼєр — демо-режим).

## Статус

Концепцію та робочий прототип створено у **вересні 2025 року**. Повний вихідний
код із детермінованим рушієм рішень — у **приватному репозиторії**; доступ та
формат співпраці — за запитом.

---

## 🔒 Права та резервування

© 2026 **0d1ns0n**. Усі права захищено.

Ідея, назва «Expedite» (у цьому контексті), дизайн продукту та логотип належать
автору. Ця публікація є **захисним розкриттям (defensive publication)**: вона
публічно й із відміткою часу фіксує авторство та дату створення концепції, щоб
слугувати підтвердженням першості (prior art).

Жодної ліцензії на використання, копіювання, адаптацію чи реалізацію описаної
концепції **не надано**. Умови — у файлі [`LICENSE`](LICENSE).

**Запити щодо партнерства чи ліцензування:** через профіль
[github.com/0d1ns0n](https://github.com/0d1ns0n) (issue або контакти у профілі).

---

<details>
<summary><strong>English summary</strong></summary>

**Expedite** is a receiver-initiated last-mile speed-up for parcels. Today the
*sender* fixes a parcel's speed at creation; the receiver chooses nothing on the
final leg — even when the parcel already sits in a branch 500 m away and is
needed *now*. Expedite reads a tracking number, shows where the parcel is and how
long it has been waiting, and — **only when it makes sense** — offers to bring it
faster or skip the queue for a transparent fee.

Core principle: **a deterministic engine decides whether to offer and at what
price; the LLM only explains that decision in plain language — it cannot invent a
price.** Every step is logged. *The specific signals, weights, thresholds and
pricing formula are part of the invention and are not disclosed here.*

Live prototype: **[@Vip_fastDelivery_bot](https://t.me/Vip_fastDelivery_bot)**.
Concept and working prototype built in **September 2025**; full source is private.

**🔒 All rights reserved.** This repository is a public, timestamped disclosure to
establish authorship and prior art. No license is granted — see [`LICENSE`](LICENSE).
Partnership / licensing inquiries via [github.com/0d1ns0n](https://github.com/0d1ns0n).

</details>
