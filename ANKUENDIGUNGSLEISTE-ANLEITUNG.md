# 🎨 Marquee Ankündigungsleiste - Anleitung

## Übersicht
Die Ankündigungsleiste wurde mit einem modernen Marquee-Style (Laufschrift) verbessert und ist vollständig im Shopify Live Editor bearbeitbar.

## ✨ Neue Features

### 🎯 Marquee-Style
- **Laufschrift-Animation**: Nahtlose Endlosschleife
- **Hover-Pause**: Animation stoppt beim Überfahren mit der Maus
- **Responsive**: Angepasste Einstellungen für Desktop und Mobile
- **Barrierefreiheit**: Respektiert `prefers-reduced-motion`
- **Richtung umkehrbar**: Von links nach rechts oder umgekehrt

### 🎨 Vollständig anpassbar
- **Hintergrundfarbe**: Beliebig änderbar
- **Gradient-Hintergrund**: Zweifarbige Verläufe möglich
- **Textfarbe**: Kontrastierend einstellbar
- **Schriftgröße**: Separate Einstellungen für Desktop/Mobile
- **Laufgeschwindigkeit**: Von 15s bis 60s einstellbar
- **Abstände**: Zwischen Items und vertikal anpassbar
- **Schatten-Effekt**: Subtiler Schatten für Tiefe
- **Glow-Effekt**: Leuchtender Text für Aufmerksamkeit

### 🎭 Erweiterte Emoji-Features
- **Intelligente Emoji-Erkennung**: Automatische Extraktion und Styling
- **Bounce-Animation**: Emojis hüpfen sanft
- **Anpassbare Größe**: Emojis können größer/kleiner gemacht werden
- **Separate Mobile-Größe**: Optimiert für verschiedene Bildschirmgrößen

### 🎪 Text-Styling-Optionen
- **Normal**: Standard-Darstellung
- **Fett & Großbuchstaben**: Für wichtige Botschaften
- **Hervorhebung**: Mit transparentem Hintergrund
- **Pulse-Effekt**: Für besonders wichtige Ankündigungen

## 🚀 So verwendest du es

### 1. Im Shopify Live Editor
1. Gehe zu **Online Store > Themes**
2. Klicke auf **Customize** bei deinem Dawn Theme
3. Wähle **Header** aus
4. Scrolle zur **Ankündigungsleiste**

### 2. Marquee-Style aktivieren
- ✅ **"Marquee-Style aktivieren"** anklicken
- Die neue Laufschrift-Ankündigungsleiste wird aktiviert

### 3. Design anpassen
Unter **"🎨 Marquee-Style Ankündigungsleiste"**:
- **Hintergrundfarbe**: Wähle deine Markenfarbe (Standard: Blau #1e3a8a)
- **Textfarbe**: Meist Weiß für guten Kontrast (Standard: #ffffff)
- **Schriftgröße Desktop**: 12-24px (Standard: 16px)
- **Schriftgröße Mobile**: 10-20px (Standard: 14px)
- **Laufgeschwindigkeit**: 15-60 Sekunden (Standard: 30s)
- **Abstände**: Zwischen Items und vertikal einstellbar

Unter **"🎨 Erweiterte Design-Optionen"**:
- **Gradient-Hintergrund aktivieren**: Für moderne Verläufe
- **Gradient Start-/Endfarbe**: Zwei Farben für den Verlauf
- **Schatten-Effekt**: Subtiler Schatten für Tiefe
- **Glow-Effekt**: Leuchtender Text für Aufmerksamkeit
- **Bounce-Animation**: Emojis hüpfen sanft (Standard: aktiviert)
- **Laufrichtung umkehren**: Von rechts nach links
- **Emoji-Größe**: Multiplikator für Emoji-Größe (Standard: 1.2x)
- **Emoji-Größe mobil**: Separate Einstellung für Mobile (Standard: 1.1x)

### 4. Ankündigungen hinzufügen/bearbeiten
- Klicke auf **"Ankündigung hinzufügen"**
- **Text eingeben**: Emojis funktionieren direkt: 🐾 🎨 🤲 🚚 ⚡ 🔄 💎 🌟 🎯 🏆 💫 🔥
- **Link hinzufügen** (optional): Macht den Text anklickbar
- **Text-Stil wählen**: 
  - **Normal**: Standard-Darstellung
  - **Fett & Großbuchstaben**: Für wichtige Botschaften
  - **Hervorhebung**: Mit transparentem Hintergrund
  - **Pulse-Effekt**: Für besonders wichtige Ankündigungen

## 📝 Vorgefertigte Ankündigungen

Das Preset enthält bereits optimierte Ankündigungen mit verschiedenen Styling-Optionen:

1. **🐾 Hundehalsbänder nach Maß aus Paracord** (Normal, mit Link)
2. **🎨 Viele Farben & Größen – passend zu Leinen** (Hervorhebung)
3. **🤲 Handgemacht in der Schweiz** (Fett & Großbuchstaben)
4. **🚚 Gratis Versand ab 130 CHF** (Pulse-Effekt)
5. **⚡ Lieferung in 2–3 Werktagen** (Normal)
6. **🔄 30 Tage Geld-zurück-Garantie** (Fett & Großbuchstaben)
7. **💎 Premium Qualität für Ihren Liebling** (Hervorhebung)
8. **🌟 Neu: Personalisierte Gravur verfügbar** (Pulse-Effekt)

## 🎯 Tipps für optimale Ergebnisse

### Emojis verwenden
- 🐾 für Hundeprodukte
- 🎨 für Farben/Design
- 🤲 für Handarbeit
- 🚚 für Versand
- ⚡ für Schnelligkeit
- 🔄 für Garantie/Service
- 💎 für Premium-Produkte
- 🌟 für Highlights/Neuigkeiten
- 🎯 für Angebote/Aktionen
- 🏆 für Qualität/Auszeichnungen
- 💫 für Magie/Besonderes
- 🔥 für Sale/Hot-Deals

### Text-Länge
- **Kurz halten**: 3-8 Wörter pro Ankündigung
- **Aussagekräftig**: Wichtigste Vorteile hervorheben
- **Call-to-Action**: Bei Bedarf Links hinzufügen

### Geschwindigkeit
- **Langsam (45-60s)**: Für längere Texte
- **Mittel (30s)**: Standard für die meisten Fälle
- **Schnell (15-25s)**: Für kurze, prägnante Botschaften

## 🔧 Technische Details

### CSS-Variablen
```css
--ps-bg: Hintergrundfarbe
--ps-fg: Textfarbe
--ps-size: Schriftgröße Desktop
--ps-speed: Laufgeschwindigkeit
--ps-gap: Abstand zwischen Items
--ps-pad: Vertikaler Abstand
```

### Responsive Verhalten
- **Desktop**: Vollständige Funktionalität
- **Mobile**: Reduzierte Schriftgröße und Abstände
- **Barrierefreiheit**: Animation stoppt bei `prefers-reduced-motion`

### Browser-Kompatibilität
- ✅ Chrome, Firefox, Safari, Edge
- ✅ Mobile Browser (iOS Safari, Chrome Mobile)
- ✅ Graceful Degradation für ältere Browser

## 🎨 Design-Beispiele

### Minimalistisch
- Hintergrund: Weiß (#ffffff)
- Text: Dunkelblau (#1e3a8a)
- Geschwindigkeit: 40s
- Wenige, prägnante Ankündigungen

### Markenkonform
- Hintergrund: Markenfarbe
- Text: Kontrastierend
- Geschwindigkeit: 30s
- Emojis für visuelle Attraktivität

### Auffällig
- Hintergrund: Lebendige Farbe
- Text: Weiß oder Gelb
- Geschwindigkeit: 25s
- Viele kurze, dynamische Ankündigungen

## 🐛 Troubleshooting

### Marquee läuft nicht
1. Überprüfe, ob "Marquee-Style aktivieren" aktiviert ist
2. Stelle sicher, dass mindestens eine Ankündigung vorhanden ist
3. Browser-Cache leeren

### Text zu schnell/langsam
- Passe die "Laufgeschwindigkeit" in den Einstellungen an
- Niedrigere Werte = schneller
- Höhere Werte = langsamer

### Mobile Darstellung
- Überprüfe die "Schriftgröße (Mobile)" Einstellung
- Teste auf verschiedenen Geräten

### Links funktionieren nicht
- Überprüfe die URL-Formatierung
- Verwende absolute URLs (https://...)
- Teste die Links in einem neuen Tab

## 📱 Mobile Optimierung

Die Ankündigungsleiste ist automatisch für mobile Geräte optimiert:
- Reduzierte Schriftgröße
- Angepasste Abstände
- Touch-freundliche Interaktion
- Responsive Animation

## 🎯 Best Practices

1. **Konsistenz**: Verwende einheitliche Emojis und Stil
2. **Relevanz**: Zeige wichtige Vorteile und Angebote
3. **Aktualität**: Passe Ankündigungen saisonal an
4. **Testen**: Überprüfe auf verschiedenen Geräten
5. **Performance**: Begrenze die Anzahl der Ankündigungen (max. 8-10)

Die neue Marquee-Ankündigungsleiste macht deinen Shop moderner und auffälliger! 🚀





