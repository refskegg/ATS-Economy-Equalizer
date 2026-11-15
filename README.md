# ATS Economy Equalizer (ATSEE)

🌍 **[🇬🇧 English](#-english-version)** | **[🇩🇪 Deutsch](#-deutsche-version)**

---

## 🇬🇧 English Version

A lightweight, powerful open-source tool for **American Truck Simulator (1.62+)** to customize the entire in-game economy without manually editing text files, and export your setup directly as a ready-to-play `.scs` mod with a single click.

> ### 🎮 Compatibility & Game Versions
> - **Main Version (`ATSEE_v1.0.0.exe`):** Built for **American Truck Simulator 1.62 and newer**.
> - **Note:** `manifest.sii` is configured with `compatible_versions[]: "1.62.*"`.

---

### 🚚 Features (Version 1.0)

- **All 8 Economy Areas in One Place:**
  1. 🏦 **Bank & Loans (`bank_data.sii`):** Loan amounts, interest rates, durations (4, 6, 8, 10 weeks), overdraft grace periods, and warning emails.
  2. 💥 **Damage & Wear (`damage_data.sii`):** Collision multipliers, component damage distribution, and ongoing wear (both fixable & permanent unfixable wear) on long hauls.
  3. 📈 **Economy & Cargo (`economy_data.sii`):** Base revenue, garage prices, fuel discounts, US DOT driving & sleeping hours (14h / 10h), F7 emergency services (15 gal refuel), AI driver margins, and XP bonuses.
  4. 🚓 **Police & Fines (`police_data.sii`):** Fine amounts for every traffic offence, progressive speed camera multipliers, check delays, and offence probabilities (with/without a police patrol car nearby).
  5. 🔧 **Service & Restoration (`service_data.sii`):** Base fees and part price factors for complete restoration of trucks and owned trailers.
  6. ⭐ **Driver Skills (`skill_data.sii`):** XP bonuses, revenue increases, and maximum route distances per rank (250 – 2500 miles) across all 6 truck driver skills (Long Distance, High Value, Fragile, Just-In-Time, Eco-Driving, Hazmat).
  7. 🔓 **Events & Unlocks (`special_event_data.sii`):** Unlock thresholds for bank loans, truck dealers, and trailer ownership, plus maximum total credit limits.
  8. 🚛 **Used Truck Market (`used_vehicle_config.sii`):** Offer counts, refresh times, mileage limits, pre-existing wear, and price discounts at the used truck dealer.
- **6 Built-in Quick Presets:** Load directly via dropdown and customize further as you like:
  - ⚙️ *Default (Vanilla)* – Unmodified original SCS Software values ($15 base rate, 14h US DOT shift)
  - ⚖️ *Realism Lite (Balanced)* – Fair loans, $9 base rate, 11h US DOT driving time, reduced passive AI driver profits
  - 💀 *Hardcore Real Economy* – True US haulage simulation ($2.20 rate, 0.5 XP factor, 11h drive / 10h rest, tight real-world margins)
  - 🚛 *Used Truck Career* – Large & affordable used truck assortment from Level 0 and cheaper workshop restoration
  - 🛡️ *Relaxed (No Damage/Police)* – Stress-free cruising with 0% vehicle/cargo damage and no police fines
  - ⚡ *Fast Money & XP (Arcade)* – Fast progression ($35 base rate, 2.5x XP, 0% permanent wear, instant unlocks)
- **Collapsible Parameter Explanations (`ⓘ Details`):** Every single setting includes a clear explanation with its original default value, unit conversions (miles/gallons/USD), and practical tips.
- **Live Search & Dashboard Overview:** Instantly find any parameter via the search bar (e.g., *"Loan"*, *"Speed"*, *"XP"*, *"Hazmat"*).
- **Mod Import & Direct Export:**
  - Exports a ready-to-use `.scs` mod archive (including `manifest.sii`, bilingual description, and icon) **directly into your `Documents\American Truck Simulator\mod` folder** if desired.
  - Existing `.scs` or `.zip` economy mods can be imported at any time for further editing.
- **Bilingual UI (German & English):** Switch the entire interface and all parameter explanations between **🇩🇪 DE** and **🇬🇧 EN** at any time with a single click.
- **No Installation Required:** Portable single-file application (`ATSEE_v1.0.0.exe`) that runs out of the box without an installer or extra runtime dependencies.

---

### 📥 Download & Getting Started

> ⚠️ **Important: Back Up Your Profile / Savegame First!**  
> Before testing custom economy values (especially extreme settings for loans, XP, or job generation), **always create a backup of your ATS profile** or test your mod on a separate profile first.  
> You can find your profiles under `Documents\American Truck Simulator\profiles` (or `steam_profiles` if Steam Cloud is enabled). Use at your own risk!

1. Download **`ATSEE_v1.0.0.exe`** (or build from source using `dotnet publish ATSEE.csproj -c Release`).
2. Double-click the file to launch it.
   > **Note on Windows SmartScreen:**  
   > Since this is a private, unsigned open-source tool without a paid code-signing certificate, Windows may show a one-time warning on first launch. Simply click **"More info"** $\rightarrow$ **"Run anyway"**.
3. Pick a preset or customize your desired economy parameters.
4. Click **"📁 Direct to ATS Mod Folder"** (or **"🚀 Export Mod (.scs)"**) in the bottom right corner and activate the mod in the ATS Mod Manager.

---

### 💡 About the Project & AI Transparency

I created this tool because the vanilla economy in ATS often generates too much money too quickly for my taste, and manually editing game files becomes tedious over time.

Existing tools in this space didn't offer enough configuration options for me, which meant I still had to piece my own mods together manually.

The goal of **ATSEE** is to provide an all-in-one solution: maximum freedom in tweaking parameters, paired with a user interface designed to be as clean and intuitive as possible.

Since I don't have a professional background in C# development, this tool was built with the help of **AI as a coding partner**. The entire source code is openly available here – feel free to take a look or contribute!

---

### 💬 Feedback & Contributions

If you find bugs, have requests for additional parameters, or want to leave feedback:
- Feel free to open a GitHub Issue.
- I am a hobbyist doing this for fun in my spare time.  
  Please bear with me if replies or bug fixes sometimes take a little while.

---
---

## 🇩🇪 Deutsche Version

Ein schlankes, leistungsstarkes Open-Source-Tool für **American Truck Simulator (1.62+)**, um die gesamte Spielwirtschaft ohne manuelles Bearbeiten von Textdateien individuell anzupassen und mit einem Klick als spielfertige `.scs`-Mod zu exportieren.

> ### 🎮 Kompatibilität & Spielversionen
> - **Hauptversion (`ATSEE_v1.0.0.exe`):** Entwickelt für **American Truck Simulator 1.62 und neuer**.
> - **Hinweis:** Die `manifest.sii` ist auf `compatible_versions[]: "1.62.*"` ausgelegt.

---

### 🚚 Features (Version 1.0)

- **Alle 8 Wirtschaftsbereiche an einem Ort:**
  1. 🏦 **Bank & Kredite (`bank_data.sii`):** Kredithöhen, Zinssätze, Laufzeiten (4, 6, 8, 10 Wochen), Dispo-Tage und Mahnungen.
  2. 💥 **Schaden & Verschleiß (`damage_data.sii`):** Kollisionsfaktoren, Bauteil-Schadensverteilung und laufender Verschleiß (reparierbar & permanenter Dauerschaden) auf Langstrecken.
  3. 📈 **Wirtschaft & Fracht (`economy_data.sii`):** Basisvergütung, Garagenpreise, Tankrabatte, US-DOT Lenk- und Ruhezeiten (14h / 10h), F7-Notdienst (15 Gallonen Notbetankung), KI-Fahrer-Margen und XP-Boni.
  4. 🚓 **Polizei & Bußgelder (`police_data.sii`):** Strafbeträge für jedes Delikt, Blitzer-Progression, Kontrollverzögerungen und Wahrscheinlichkeiten (mit/ohne Polizeistreife vor Ort).
  5. 🔧 **Werkstatt & Service (`service_data.sii`):** Kosten und Teilefaktoren für die Gesamtwiederherstellung von Trucks und eigenen Anhängern.
  6. ⭐ **Fähigkeiten / Skills (`skill_data.sii`):** XP-Boni, Umsatzsteigerungen und Maximaldistanzen je Rang (250 – 2500 Meilen) für alle 6 Fahrer-Fähigkeiten (Fernfahrt, Wertvolle Fracht, Zerbrechliche Fracht, Eillieferung, Sparsame Fahrweise, Gefahrgut / Hazmat).
  7. 🔓 **Events & Freischaltungen (`special_event_data.sii`):** Wann Bankkredite, Truck-Händler und der eigene Anhängerkauf freigeschaltet werden, sowie das maximale Gesamtkreditlimit.
  8. 🚛 **Gebrauchtfahrzeuge (`used_vehicle_config.sii`):** Angebotsgröße, Erneuerungszeiten, Laufleistungen (Mileage), Vorschäden und Preisrabatte beim Gebrauchtwagenhändler.
- **6 integrierte Schnell-Presets:** Direkt per Dropdown laden und nach Belieben weiter verfeinern:
  - ⚙️ *Standard (Vanilla)* – Unveränderte Originalwerte von SCS Software (15 $ Basisrate, 14h US-DOT Schicht)
  - ⚖️ *Realismus Light (Ausgewogen)* – Faire Kredite, 9 $ Basisrate, 11h US-DOT Lenkzeit, reduzierter passiver KI-Fahrer-Gewinn
  - 💀 *Hardcore Real Economy* – Echte US-Speditions-Simulation (2,20 $ Rate, 0,5 XP Faktor, 11h Lenk- / 10h Ruhezeit, knappe Margen)
  - 🚛 *Gebrauchtwagen-Karriere* – Großes & günstiges Gebraucht-Angebot ab Level 0 und günstigere Restauration
  - 🛡️ *Entspannt (Kein Schaden/Polizei)* – Stressfreies Cruisen ohne Fahrzeug-/Frachtschaden und ohne Bußgelder
  - ⚡ *Schnelles Geld & XP (Arcade)* – Schneller Aufstieg (35 $ Basisrate, 2,5x XP, 0 % Dauerschaden, Sofort-Unlocks)
- **Ausklappbare Parameter-Erklärungen (`ⓘ Erklärung`):** Zu jedem einzelnen Wert gibt es eine verständliche Erklärung inklusive Original-Standardwert, Einheiten-Umrechnungen (Meilen / Gallonen / US-Dollar) und Praxis-Tipps.
- **Live-Suche & Dashboard-Übersicht:** Finde jeden Parameter sofort per Suchfeld (z. B. *„Kredit“*, *„Blitzer“*, *„XP“*, *„Hazmat“*).
- **Mod-Import & Direkt-Export:**
  - Exportiert eine fertig gepackte `.scs`-Mod (inkl. `manifest.sii`, zweisprachiger Beschreibung und Icon) auf Wunsch **direkt in deinen `Dokumente\American Truck Simulator\mod`-Ordner**.
  - Bestehende `.scs`- oder `.zip`-Wirtschaftsmods können jederzeit wieder importiert und weiterbearbeitet werden.
- **Zweisprachig (Deutsch & Englisch):** Komplette Oberfläche und alle Parameter-Erklärungen lassen sich jederzeit per Klick zwischen **🇩🇪 DE** und **🇬🇧 EN** umschalten.
- **Keine Installation nötig:** Portable Single-File-Anwendung (`ATSEE_v1.0.0.exe`), die ohne Installer oder zusätzliche Laufzeitumgebung sofort startet.

---

### 📥 Download & Erste Schritte

> ⚠️ **Wichtiger Hinweis: Vorher Profil / Savegame sichern!**  
> Bevor du eigene Wirtschaftswerte ausprobierst (insbesondere bei extremen Werten für Kredite, XP oder Auftragsgenerierung), **erstelle bitte unbedingt ein Backup deines ATS-Profils** oder teste die Mod zuerst mit einem separaten Testprofil.  
> Deine Profile findest du unter `Dokumente\American Truck Simulator\profiles` (bzw. `steam_profiles` bei aktiver Steam Cloud). Die Nutzung erfolgt auf eigene Gefahr!

1. Lade dir **`ATSEE_v1.0.0.exe`** herunter (oder baue das Projekt selbst per `dotnet publish ATSEE.csproj -c Release`).
2. Starte die Datei per Doppelklick.
   > **Hinweis zu Windows SmartScreen:**  
   > Da es sich um ein privates, nicht kostenpflichtig signiertes Open-Source-Tool handelt, warnt Windows beim ersten Start einmalig. Einfach auf **„Weitere Informationen“** $\rightarrow$ **„Trotzdem ausführen“** klicken.
3. Wähle ein Preset oder passe die gewünschten Wirtschafts-Parameter frei an.
4. Klicke unten rechts auf **„📁 Direkt in ATS Mod-Ordner“** (oder **„🚀 Mod (.scs) exportieren“**) und aktiviere die Mod im ATS Mod-Manager.

---

### 💡 Über das Projekt & KI-Transparenz

Ich habe das Tool entwickelt, weil mir das originale Wirtschaftssystem in ATS oft zu schnell zu viel Geld abgeworfen hat und manuelles Bearbeiten der Spieldateien auf Dauer umständlich ist.

Die bereits existierenden Tools in dem Bereich hatten mir jeweils zu wenige Einstellungsmöglichkeiten, sodass ich mir die Mods dennoch selbst zusammenbasteln musste.

Das Ziel des **ATSEE** ist es, alles aus einer Hand zu haben: maximale Freiheit bei der Parameterwahl, gepaart mit einer so einfach und übersichtlich wie möglich gestalteten Benutzeroberfläche.

Da ich selbst keinen professionellen Hintergrund in der C#-Entwicklung habe, ist dieses Tool mit Unterstützung von **KI als Coding-Partner** entstanden. Der gesamte Quellcode ist hier transparent einsehbar – schaut gerne rein oder helft mit!

---

### 💬 Feedback & Mithilfe

Wenn ihr Fehler findet, Wünsche für Parameter habt oder Feedback dalassen wollt:
- Erstellt einfach ein GitHub Issue.
- Ich bin kompletter Laie und mache das aus Spaß in meiner Freizeit.  
  Bitte verzeiht, wenn ich mal nicht schnell antworten sollte oder Fehlerbehebungen länger auf sich warten lassen.
