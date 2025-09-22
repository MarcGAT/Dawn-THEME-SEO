# 🎨 Marquee Ankündigungsleiste - Anleitung

## Übersicht
Die Ankündigungsleiste wurde mit einem modernen Marquee-Style (Laufschrift) verbessert und ist vollständig im Shopify Live Editor bearbeitbar.

## ✨ Neue Features

### 🎯 Marquee-Style
- **Laufschrift-Animation**: Nahtlose Endlosschleife
- **Hover-Pause**: Animation stoppt beim Überfahren mit der Maus
- **Responsive**: Angepasste Einstellungen für Desktop und Mobile
- **Barrierefreiheit**: Respektiert `prefers-reduced-motion`

### 🎨 Vollständig anpassbar
- **Hintergrundfarbe**: Beliebig änderbar
- **Textfarbe**: Kontrastierend einstellbar
- **Schriftgröße**: Separate Einstellungen für Desktop/Mobile
- **Laufgeschwindigkeit**: Von 15s bis 60s einstellbar
- **Abstände**: Zwischen Items und vertikal anpassbar

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

### 4. Ankündigungen hinzufügen/bearbeiten
- Klicke auf **"Ankündigung hinzufügen"**
- **Text eingeben**: Emojis funktionieren direkt: 🐾 🎨 🤲 🚚 ⚡ 🔄
- **Link hinzufügen** (optional): Macht den Text anklickbar
- **Text-Stil wählen**: Normal, Fett oder Hervorhebung

## 📝 Vorgefertigte Ankündigungen

Das Preset enthält bereits optimierte Ankündigungen:

1. **🐾 Hundehalsbänder nach Maß aus Paracord** (mit Link)
2. **🎨 Viele Farben & Größen – passend zu Leinen**
3. **🤲 Handgemacht in der Schweiz**
4. **🚚 Gratis Versand ab 130 CHF**
5. **⚡ Lieferung in 2–3 Werktagen**
6. **🔄 30 Tage Geld-zurück-Garantie**

## 🎯 Tipps für optimale Ergebnisse

### Emojis verwenden
- 🐾 für Hundeprodukte
- 🎨 für Farben/Design
- 🤲 für Handarbeit
- 🚚 für Versand
- ⚡ für Schnelligkeit
- 🔄 für Garantie/Service

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

