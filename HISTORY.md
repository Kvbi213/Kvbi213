# 📜 Rejestr Wersji — GitHub Profile OS

Wszystkie wydania podlegają zasadom Semantic Versioning (SemVer) oraz standardowi Antigravity v3.0.

---

## v 1.0.0 — 2026-09-08

**Typ:** MAJOR  
**Zakres:** Gruntowny redesign profilu GitHub (Kvbi213) od zera w oparciu o estetykę portfolio `kvbi-portfolio.web.app`.

### Zmiany
- [+] Dodano: Nowy, minimalistyczny banner hero o wysokim kontraście (`#000000` / `#FFFFFF`).
- [+] Dodano: Sekcję głównych wdrożeń (Core Deploys) z wyróżnieniem `ai-system-dashboard` (OmniDash) oraz oficjalnego portfolio `kvbi-portfolio.web.app`.
- [+] Dodano: Reorganizację stosu technologicznego na 4 klarowne filary (Frontend, Backend, Cloud & DevOps, AI & Security).
- [+] Dodano: Spójną paletę barw dla GitHub Streak, GitHub Stats i Top Languages w stylu brutalistycznym / dark monochrome.
- [+] Dodano: Kopię zapasową pierwotnego profilu w `README_OLD_BACKUP.md`.
- [+] Dodano: Narzędzie podglądu lokalnego `preview.html`.
- [*] Zmodyfikowano: Usunięto niejednorodne, mdłe brązowo-złote tła i zbędne separatory waving na rzecz czystej, inżynieryjnej geometrii.

### Audyt
Status: ZGODNY Z PROTOKOŁEM ANTIGRAVITY v3.0

---

## v 1.1.0 — 2026-09-08

**Typ:** MINOR  
**Zakres:** Chirurgiczna redukcja projektów (usunięcie Home-OS i WhiteHat-Hack), zamiana wszystkich emotek na wektory SVG Lucide/SimpleIcons, wdrożenie bibliotek Readme-Typing SVG oraz GitHub Stats Repo Pin API.

### Zmiany
- [+] Dodano: Dedykowaną, dynamiczną kartę GitHub Repo Pin dla `ai-system-dashboard`.
- [+] Dodano: Autorski baner wektorowy SVG (`assets/header.svg`) z siatką inżynierską i pulsem telemetrycznym.
- [+] Dodano: Animowaną bibliotekę `Readme-Typing-SVG` w terminalu nagłówkowym.
- [+] Dodano: Wektorowe odznaki techniczne Flat-Square z oficjalnymi wektorami SimpleIcons.
- [*] Zmodyfikowano: Wyeliminowano w 100% emotikony, wprowadzając ostre wektory SVG Lucide & Octicons via Iconify API.
- [-] Usunięto: Projekty `Home-OS-2035` oraz `WhiteHat-Hack` z sekcji wdrożeń ("Chirurgiczna Redukcja" na polecenie operatora).

### Audyt
Status: ZGODNY Z PROTOKOŁEM ANTIGRAVITY v3.0

---

## v 1.1.1 — 2026-09-08

**Typ:** PATCH  
**Zakres:** Naprawa ładowania OmniDash Repo Card, Overall Stats, Top Languages (przełączenie na instancję eight-theta) oraz wdrożenie lokalnych ikon SVG z wymiarami 24x24 px.

### Zmiany
- [!] Naprawiono: Błąd rate-limitu (Maximum retries exceeded) na kartach GitHub Stats i Repo Pin poprzez przekierowanie do stabilnej instancji `eight-theta`.
- [!] Naprawiono: Niewidoczne ikony spowodowane zapadaniem się jednostki `1em` w tagach `<img>` — utworzono i zintegrowano pliki SVG w `assets/icons/` ze sztywnymi wymiarami `24x24`.
- [*] Zmodyfikowano: Plik `preview.html` ładuje bezpośrednio treść bez konfliktów polityki CORS w protokole `file://`.

### Audyt
Status: ZGODNY Z PROTOKOŁEM ANTIGRAVITY v3.0

---


