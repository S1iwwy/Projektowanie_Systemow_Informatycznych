GymOS - System Zarządzania Autonomiczną Siłownią 🏋️‍♂️💻
Rola: Analityk Biznesowy / Projektant Systemu
Autor: Bartosz Rosmanowski

📖 O projekcie

GymOS to kompleksowy projekt analityczny systemu informatycznego przeznaczonego do obsługi w pełni autonomicznych klubów fitness. System ma na celu automatyzację kluczowych procesów operacyjnych, odciążenie personelu oraz znaczącą poprawę doświadczeń użytkownika końcowego (UX).  

Projekt powstał w oparciu o dogłębną analizę dziedziny problemowej i modelowanie procesów biznesowych, weryfikując ograniczenia tradycyjnego modelu zarządzania placówkami sportowymi. Wzorowano się na globalnych i lokalnych liderach rynku (np. CityFit, Just Gym), identyfikując obszary do budowania przewagi konkurencyjnej.

🎯 Dziedzina problemowa i uzasadnienie biznesowe

Analiza tradycyjnych siłowni wykazała szereg nieoptymalnych procesów generujących wysokie koszty i utrudniających skalowanie biznesu:
  Wąskie gardło w postaci recepcji: Proces rejestracji, sprzedaży, płatności i wydawania kluczyków jest manualny i czasochłonny.  
  Wysokie koszty operacyjne: Model tradycyjny wymusza utrzymanie rozbudowanej kadry (recepcjoniści, trenerzy dyżurni, managerowie).  
  Reaktywne zarządzanie infrastrukturą: Zgłaszanie usterek maszyn odbywa się "na papierze" lub słownie, co wydłuża czas reakcji serwisów i obniża satysfakcję klientów.  

💡 Proponowane rozwiązanie
GymOS dzieli się na dwa główne moduły operacyjne:

Aplikacja Mobilna (Dla Klienta):
  Rejestracja, zakup karnetów i podpinanie kart do płatności subskrypcyjnych.  
  Autonomiczny dostęp do obiektu za pomocą generowanego dynamicznie kodu QR.  
  Przeglądanie harmonogramu zajęć, zapisy na zajęcia grupowe i śledzenie postępów treningowych.  

Panel Zarządzania (Dla Administracji/Menedżera):
  Zaawansowany system CRM i automatyzacja komunikacji.  
  Integracja z fizycznymi bramkami turnikietowymi (audyt wejść i kontrola dostępu w czasie rzeczywistym).  
  Zautomatyzowany obieg zgłoszeń (ticketów) dla firm serwisowych i sprzątających.  
  
📂 Artefakty analityczne w repozytorium

Poniższe elementy dokumentacji (dostępne w repozytorium) demonstrują warsztat inżynierii wymagań oraz modelowania systemów:
  Analiza Wymagań i Słownik Pojęć: Zdefiniowanie aktorów systemu oraz ujednolicenie terminologii biznesowej (m.in. Karnet, CRM, Weryfikacja dostępu).  
  Diagramy Przypadków Użycia (Use Case Diagrams - UML): Mapowanie interakcji pomiędzy aktorami (Klient, Pracownik, Menedżer, Trener, System Bankowy) a systemem.  
  Szczegółowe Scenariusze Przypadków Użycia: Dokumentacja kluczowych procesów (Main Flow, Alternative Flows, Exceptions) takich jak "Zarządzaj karnetem", "Realizuj płatność" czy "Kontroluj dostęp".  
  Diagramy Przepływów / Aktywności: Wizualizacja algorytmów decyzyjnych m.in. dla modułu bramki płatniczej (autoryzacja, odrzucenie transakcji, płatność 1-Click) oraz kontroli QR na bramce wejściowej.  
  Diagramy Klas i Obiektów (UML): Struktura danych oraz relacje pomiędzy encjami w systemie. Udokumentowano "typową" ścieżkę klienta oraz sytuacje wyjątkowe (np. nagłe zastępstwo trenera).  
  Prototypy Interfejsów (Wireframes / UI): Wizualizacje kluczowych ekranów systemu z perspektywy Menedżera (Dashboard GymOS) obrazujące m.in. zdalną kontrolę dostępu, kreator grafiku metodą "Drag & Drop" oraz zarządzanie zgłoszeniami serwisowymi.  
  
🛠 Wykorzystane techniki i metodyki
  Modelowanie w notacji UML (Use Case, Class, Object diagrams).Analiza biznesowa (Business Case, As-Is / To-Be, Identifikacja wąskich gardeł).User Experience (UX) & User Interface (UI) Design (tworzenie makiet).Inżynieria wymagań (Specyfikacja funkcjonalna, Scenariusze i ścieżki alternatywne).
  
Status projektu: Analiza ukończona / Dokumentacja kompletna.
