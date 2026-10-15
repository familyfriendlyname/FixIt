
# 🔧 NaprawTo – Evidence-Based AI Troubleshooting

NaprawTo to prototyp asystenta AI wspierającego diagnostykę usterek urządzeń domowych. Zamiast generować pojedynczą odpowiedź na podstawie opisu problemu, system prowadzi użytkownika przez uporządkowany proces diagnostyczny, wykorzystując dokumentację techniczną, pytania uzupełniające i dostępne narzędzia.

## 🎯 Cel projektu

Celem projektu jest opracowanie agenta diagnostycznego, który potrafi analizować objawy usterek, porównywać możliwe przyczyny oraz uzasadniać proponowane działania na podstawie dostępnych źródeł wiedzy.

Projekt koncentruje się na połączeniu agentów AI, RAG, Tool Calling i MCP w jednym procesie diagnostycznym, ze szczególnym uwzględnieniem wiarygodności odpowiedzi i bezpieczeństwa użytkownika.

## 💡 Co wyróżnia NaprawTo?

- **Diagnostyka iteracyjna** – agent zadaje pytania uzupełniające i aktualizuje hipotezy na podstawie uzyskanych informacji.
- **Odpowiedzi oparte na źródłach** – system wykorzystuje dokumentację techniczną i wskazuje materiały wspierające proponowaną diagnozę.
- **Porównywanie możliwych przyczyn** – agent rozważa alternatywne wyjaśnienia objawów, zamiast bezwarunkowo wskazywać jedną przyczynę.
- **Bezpieczeństwo diagnostyki** – proponowane czynności uwzględniają ryzyko, a sytuacje wymagające specjalistycznej wiedzy skutkują rekomendacją kontaktu z serwisem.
- **Jawne wykorzystanie narzędzi** – Tool Calling i MCP umożliwiają agentowi korzystanie z funkcji i źródeł danych wspierających proces diagnostyczny.

## ⚙️ Jak to działa?

1. **Opis usterki** – użytkownik przedstawia objawy i, jeśli to możliwe, podaje markę oraz model urządzenia.
2. **Doprecyzowanie problemu** – agent zadaje pytania pozwalające zawęzić listę potencjalnych przyczyn.
3. **Wyszukiwanie wiedzy** – mechanizm RAG wyszukuje odpowiednie fragmenty instrukcji i dokumentacji technicznej.
4. **Analiza hipotez** – agent porównuje objawy z odnalezionymi informacjami i identyfikuje możliwe przyczyny.
5. **Dobór kolejnych kroków** – agent wybiera pytania lub bezpieczne czynności diagnostyczne, które mogą pomóc rozróżnić hipotezy.
6. **Prezentacja wyniku** – użytkownik otrzymuje możliwe wyjaśnienia, uzasadnienie, źródła i zalecane dalsze działania.

## 🤖 Rola agenta AI

Agent pełni funkcję koordynatora procesu diagnostycznego. Jego zadania obejmują:

- Prowadzenie rozmowy z użytkownikiem i zadawanie pytań uzupełniających.
- Analizowanie objawów i porównywanie możliwych przyczyn.
- Wykorzystywanie dokumentacji technicznej za pomocą RAG.
- Dobieranie narzędzi i wywoływanie funkcji za pomocą Tool Calling.
- Korzystanie z integracji udostępnianych przez MCP.
- Formułowanie zaleceń z uwzględnieniem niepewności i bezpieczeństwa.

## 🛠️ Technologie

- **.NET** – platforma do budowy aplikacji.
- **AI Agent** – koordynacja rozmowy i procesu diagnostycznego.
- **Tool Calling** – wywoływanie funkcji wspierających diagnozę.
- **MCP (Model Context Protocol)** – integracja agenta z narzędziami i źródłami danych.
- **RAG (Retrieval-Augmented Generation)** – wyszukiwanie wiedzy w dokumentacji technicznej przed wygenerowaniem odpowiedzi.

## 🔍 Przykładowy scenariusz

**Problem:** Pralka nie odprowadza wody po zakończeniu programu.

1. Użytkownik opisuje objawy usterki.
2. Agent pyta, czy urządzenie wyświetla kod błędu i czy słychać pracę pompy.
3. RAG wyszukuje odpowiednie procedury diagnostyczne w instrukcji obsługi.
4. Agent porównuje możliwe przyczyny, np. niedrożność odpływu lub problem z pompą.
5. System proponuje odpowiednie, bezpieczne kroki diagnostyczne.
6. Jeśli problem wymaga specjalistycznej interwencji, agent zaleca kontakt z serwisem.

## 🛡️ Bezpieczeństwo i ograniczenia

NaprawTo ma wspierać wstępną diagnostykę, a nie zastępować profesjonalny serwis.

System powinien:

- Jasno komunikować niepewność diagnozy.
- Opierać zalecenia na dostępnych źródłach i informacjach o urządzeniu.
- Unikać instrukcji mogących narazić użytkownika na niebezpieczeństwo.
- Rozpoznawać sytuacje wymagające przerwania diagnostyki i kontaktu ze specjalistą.
- Zalecać kontakt z odpowiednimi służbami w sytuacjach bezpośredniego zagrożenia.

> **Uwaga:** Wynik generowany przez AI jest sugestią, a nie potwierdzoną diagnozą techniczną. Nie zastępuje profesjonalnej oceny ani naprawy wykonanej przez wykwalifikowany serwis.

## 🧪 Weryfikacja działania

Projekt zakłada testowanie na zestawie przykładowych usterek urządzeń domowych.

Ocena działania systemu powinna obejmować:

- **Trafność diagnozy** – czy wskazane przyczyny odpowiadają rzeczywistym usterkom.
- **Jakość źródeł** – czy odpowiedzi są zgodne z dokumentacją techniczną.
- **Jakość pytań** – czy pytania agenta pomagają zawęzić możliwe przyczyny.
- **Wykorzystanie narzędzi** – czy agent prawidłowo dobiera i wywołuje dostępne funkcje.
- **Bezpieczeństwo** – czy zalecenia nie zachęcają do wykonywania niebezpiecznych czynności.

## 🚀 Zakres projektu

W ramach prototypu planowane jest:

- Przyjmowanie opisów usterek od użytkownika.
- Prowadzenie interaktywnej rozmowy diagnostycznej.
- Wyszukiwanie informacji w dokumentacji z wykorzystaniem RAG.
- Wywoływanie narzędzi przez agenta AI.
- Generowanie diagnoz z uzasadnieniem i propozycjami dalszych kroków.
- Testowanie działania na zestawie przykładowych usterek.

## 📌 Status projektu

**Status:** W fazie rozwoju.

Celem jest stworzenie prototypu i zweryfikowanie, czy połączenie interaktywnej diagnostyki, dokumentacji technicznej oraz mechanizmów kontroli bezpieczeństwa pozwala uzyskać bardziej uzasadnione i użyteczne odpowiedzi.

Projekt stanowi praktyczną demonstrację zastosowania agentów AI, Tool Calling, MCP i RAG w procesie diagnostyki usterek urządzeń domowych.