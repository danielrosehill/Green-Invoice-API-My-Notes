# Green Invoice API - Document Types

![Added](https://img.shields.io/badge/Added-26--May--2025-blue)



| ID  | Hebrew                   | Transliteration           |
|-----|--------------------------|---------------------------|
| 10  | הצעת מחיר               | Hatz'at Mechir            |
| 100 | הזמנה                   | Hazmana                   |
| 200 | תעודת משלוח             | Te'udat Mishloach         |
| 210 | תעודת החזרה             | Te'udat Hachzara          |
| 300 | חשבון עסקה              | Cheshbon Iska             |
| 305 | חשבונית מס              | Cheshbonit Mas            |
| 320 | חשבונית מס / קבלה      | Cheshbonit Mas / Kabala   |
| 330 | חשבונית זיכוי           | Cheshbonit Zikui          |
| 400 | קבלה                    | Kabala                    |
| 405 | קבלה על תרומה           | Kabala al Truma           |
| 500 | הזמנת רכש               | Hazmanat Rechash          |
| 600 | קבלת פיקדון             | Kabalat Pikadon           |
| 610 | משיכת פיקדון            | Meshichat Pikadon         |

---

## IDs For The Most Common Documents

### Invoices

Heshbon Iska - 300

### Receipts - Israeli Clients

Heshbonit Mas / Kabala - 320

### Receipts - ROW Clients

Kabala - 400

---

## Filtering Syntax For Automations (By Document Type)

### Client Invoices

Filter on ID = 300

### Client Receipts

Filter on ID = 320, 400