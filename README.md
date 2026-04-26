# Mail – klient poczty (SPA)

Jednostronicowa aplikacja (SPA) imitująca klienta poczty elektronicznej. Umożliwia wysyłanie, odbieranie, archiwizowanie oraz odpowiadanie na wiadomości e-mail.

Aplikacja działa w oparciu o REST API i w pełni zarządzana jest po stronie JavaScript bez przeładowywania strony.

---

## 📌 Funkcjonalności

- Wysyłanie wiadomości e-mail
- Skrzynka odbiorcza (Inbox)
- Wysłane wiadomości (Sent)
- Archiwum (Archive / Unarchive)
- Wyświetlanie szczegółów wiadomości
- Oznaczanie wiadomości jako przeczytane
- Archiwizacja i przywracanie wiadomości
- Odpowiadanie na wiadomości (pre-fill formularza)

---

## 🧩 Jak działa aplikacja

- Aplikacja działa jako Single Page Application (SPA)
- Dane pobierane są z API przy użyciu `fetch`
- Widoki są dynamicznie przełączane w JavaScript (bez przeładowania strony)
- Wiadomości są renderowane dynamicznie w DOM
- Operacje CRUD wykonywane są przez REST API (GET / POST / PUT)

---

## 🛠️ Technologie

- JavaScript (ES6)
- HTML
- CSS
- REST API
- Django (backend API – gotowy)

---

## 📁 Główne elementy

- `inbox.js` – logika całej aplikacji (frontend)
- `inbox.html` – struktura interfejsu
- `styles.css` – stylizacja widoków

---

## 🚀 Architektura

- SPA (Single Page Application)
- Komunikacja z backendem przez `fetch API`
- Dynamiczne renderowanie widoków (Inbox / Compose / Email view)
