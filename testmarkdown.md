# 🗂 Backlog Projektu (User Stories)

Ten plik zawiera wysokopoziomową listę wymagań biznesowych. Przed rozpoczęciem implementacji, wybrane zlecenia są przenoszone do GitHub Issues, gdzie toczy się dyskusja i śledzenie postępów.

## 📌 Legenda Statusów
- [x] **Zrobione** (Zaimplementowane i przetestowane)
- [~] **W trakcie** (Przeniesione do GitHub Issues / W developmencie)
- [ ] **Do zrobienia** (Oczekuje w kolejce)

---

## 🚀 Wersja 1.0 (MVP)

### 🔐 Epic: Autoryzacja i Profil Użytkownika
- [x] **[AUTH-01]** Jako nowy użytkownik, chcę móc założyć konto używając adresu e-mail i hasła, aby uzyskać dostęp do systemu.
  - *Kryteria akceptacji:*
    - Wymuszenie silnego hasła (min. 8 znaków, cyfra, znak specjalny).
    - Wysłanie e-maila weryfikacyjnego po rejestracji.
- [~] **[AUTH-02]** Jako zarejestrowany użytkownik, chcę logować się przez konto Google, aby przyspieszyć proces wejścia do aplikacji. *(Issue: #12)*
- [ ] **[AUTH-03]** Jako zalogowany użytkownik, chcę móc zresetować zapomniane hasło, aby odzyskać dostęp do konta.

### 🛒 Epic: Zarządzanie Koszykiem
- [x] **[CART-01]** Jako klient, chcę dodać produkt do koszyka z poziomu listy produktów, aby móc kupić kilka rzeczy na raz.
- [ ] **[CART-02]** Jako klient, chcę widzieć sumaryczną wartość mojego koszyka w czasie rzeczywistym, aby kontrolować swoje wydatki.
  - *Kryteria akceptacji:*
    - Kwota aktualizuje się bez przeładowania strony.
    - Kwota uwzględnia koszty wysyłki po przekroczeniu progu 150 PLN (darmowa dostawa).
- [ ] **[CART-03]** Jako klient, chcę móc zmienić ilość sztuk danego produktu w koszyku, aby dostosować zamówienie przed płatnością.

---

## 🌅 Wersja 2.0 (Planowane)

### 💳 Epic: Płatności i Subskrypcje
- [ ] **[PAY-01]** Jako użytkownik, chcę podpiąć kartę płatniczą, aby opłacać subskrypcję w modelu miesięcznym.
- [ ] **[PAY-02]** Jako księgowy, chcę aby system automatycznie generował i wysyłał faktury VAT po udanej płatności, aby zminimalizować pracę ręczną.

---

## 🧊 Lodówka (Pomysły na przyszłość / Odrzucone)
*Zebrane pomysły, które nie mają jeszcze priorytetu ani przypisanego wydania.*

- [ ] Jako użytkownik, chcę mieć tryb ciemny (Dark Mode), aby mniej męczyć wzrok w nocy.
- [ ] Jako administrator, chcę widzieć mapę ciepła (heatmap) kliknięć użytkowników na stronie głównej.