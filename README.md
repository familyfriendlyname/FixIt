# 🔧 NaprawTo – AI Assistant for Troubleshooting

**NaprawTo** to aplikacja wykorzystująca sztuczną inteligencję do diagnozowania usterek urządzeń domowych. Pomaga użytkownikom znaleźć możliwe przyczyny problemów oraz wskazuje, co można bezpiecznie sprawdzić samodzielnie.

## 🎯 Cel projektu

Celem projektu jest stworzenie asystenta AI, który wspiera użytkownika w diagnozowaniu awarii urządzeń domowych na podstawie opisu problemu i dokumentacji technicznej.

## ❓ Problem

Znalezienie przyczyny awarii urządzenia domowego bywa trudne, szczególnie bez specjalistycznej wiedzy technicznej. Użytkownicy często nie wiedzą, od czego rozpocząć diagnozę ani jakie czynności mogą bezpiecznie wykonać samodzielnie.

## 👥 Grupa docelowa

Aplikacja jest przeznaczona dla osób, które chcą samodzielnie zidentyfikować możliwe przyczyny usterek urządzeń domowych i dowiedzieć się, jakie kroki diagnostyczne warto podjąć.

## ⚙️ Jak to działa?

1. **Opis problemu** – użytkownik opisuje objawy usterki.
2. **Analiza** – agent AI zadaje pytania uzupełniające i analizuje dostępne informacje.
3. **Wyszukiwanie wiedzy** – aplikacja korzysta z instrukcji obsługi i dokumentacji technicznej.
4. **Diagnoza** – agent wskazuje najbardziej prawdopodobne przyczyny problemu.
5. **Zalecenia** – użytkownik otrzymuje propozycje bezpiecznych czynności diagnostycznych i dalszych kroków.

## 🤖 Rola agenta AI

Agent AI pełni funkcję inteligentnego asystenta diagnostycznego. Jego zadania obejmują:

- Prowadzenie rozmowy z użytkownikiem i zadawanie pytań doprecyzowujących.
- Analizowanie objawów i identyfikowanie możliwych przyczyn awarii.
- Wykorzystywanie instrukcji obsługi i dokumentacji technicznej.
- Dobieranie odpowiednich narzędzi za pomocą mechanizmu **Tool Calling**.
- Formułowanie zaleceń dotyczących bezpiecznej diagnostyki.

## 🛠️ Technologie

- **.NET** – platforma do budowy aplikacji.
- **AI Agent** – agent odpowiedzialny za prowadzenie procesu diagnostycznego.
- **Tool Calling** – umożliwia agentowi wywoływanie funkcji i korzystanie z narzędzi.
- **MCP (Model Context Protocol)** – standard komunikacji modelu AI z narzędziami i źródłami danych.
- **RAG (Retrieval-Augmented Generation)** – umożliwia wykorzystanie dokumentacji podczas generowania odpowiedzi.

## 🧪 Zakres projektu

W ramach projektu powstanie prosta aplikacja demonstracyjna obejmująca:

- Przyjmowanie opisów usterek od użytkownika.
- Prowadzenie interaktywnej rozmowy diagnostycznej.
- Wyszukiwanie informacji w dokumentacji z wykorzystaniem RAG.
- Wywoływanie narzędzi przez agenta AI.
- Generowanie propozycji diagnozy i zaleceń.
- Testowanie działania na zestawie przykładowych usterek urządzeń domowych.

## 🛡️ Bezpieczeństwo

NaprawTo ma wspierać użytkownika w wykonywaniu wyłącznie bezpiecznych czynności diagnostycznych. W przypadku usterek wymagających specjalistycznej wiedzy aplikacja powinna zalecać kontakt z wykwalifikowanym serwisem.

> **Uwaga:** Aplikacja ma charakter pomocniczy. Wygenerowana diagnoza jest jedynie sugestią i nie zastępuje profesjonalnej oceny technicznej.

## 🚀 Status projektu

**Status:** W fazie rozwoju.

Celem jest stworzenie prototypu prezentującego możliwości wykorzystania agentów AI, Tool Calling, MCP i RAG w praktycznym zastosowaniu.