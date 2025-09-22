# 🎨 Paracord Customizer - Produkt-spezifische Anleitung

## Übersicht
Der Paracord Customizer kann jetzt intelligent gesteuert werden und erscheint nur bei den Produkten, die du auswählst. Du hast mehrere Möglichkeiten, zu kontrollieren, bei welchen Produkten der Customizer angezeigt wird.

## 🚀 So aktivierst du den Customizer

### Methode 1: Als Block im Live Editor
1. Gehe zu **Online Store > Themes > Customize**
2. Wähle ein **Product Template** aus
3. Klicke **"Add block"**
4. Wähle **"Paracord Customizer"** aus
5. Konfiguriere die Einstellungen

### Methode 2: Direkt im Template
```liquid
{% render 'ps-paracord-customizer', product: product %}
```

## ⚙️ Anzeige-Methoden

### 1. **Automatisch** (Empfohlen)
Der Customizer wird automatisch angezeigt bei Produkten, die:
- **Metafield** `enable_paracord_customizer` auf `true` haben
- **Tag** `paracord-customizer` haben
- **Typ** `paracord`, `leash` oder `collar` enthalten
- **Collection** `paracord`, `hundehalsbaender` oder `leinen` enthalten

### 2. **Manuell**
Der Customizer wird immer angezeigt, wenn der Block aktiviert ist.

### 3. **Nur bei bestimmten Tags**
Gebe die gewünschten Tags ein (kommagetrennt):
```
paracord, customizer, leash, halsband
```

### 4. **Nur bei bestimmten Collections**
Gebe die Collection-Handles ein (kommagetrennt):
```
hundehalsbaender, leinen, paracord-produkte
```

## 🏷️ Produkt-Tags verwenden

### Empfohlene Tags:
- `paracord-customizer` - Aktiviert den Customizer
- `paracord` - Für alle Paracord-Produkte
- `leash` - Für Leinen
- `collar` - Für Halsbänder
- `custom` - Für maßgeschneiderte Produkte

### So fügst du Tags hinzu:
1. Gehe zu **Products** im Shopify Admin
2. Wähle ein Produkt aus
3. Scrolle zu **Search engine listing preview**
4. Füge Tags hinzu: `paracord-customizer`

## 📦 Collection-basierte Steuerung

### Empfohlene Collections:
- `hundehalsbaender` - Für Halsbänder
- `leinen` - Für Leinen
- `paracord-produkte` - Für alle Paracord-Artikel

### So erstellst du Collections:
1. Gehe zu **Products > Collections**
2. Klicke **"Create collection"**
3. Verwende einen der empfohlenen Handles

## 🎯 Metafields verwenden (Für Entwickler)

### Metafield einrichten:
1. Gehe zu **Settings > Metafields**
2. Erstelle ein neues Metafield:
   - **Namespace**: `custom`
   - **Key**: `enable_paracord_customizer`
   - **Type**: `Boolean`

### Produkt-Metafield setzen:
```liquid
{% if product.metafields.custom.enable_paracord_customizer == true %}
  <!-- Customizer wird angezeigt -->
{% endif %}
```

## 🔧 Block-Einstellungen

### Im Live Editor konfigurierbar:
- **✅ Paracord Customizer aktivieren** - Ein/Aus-Schalter
- **📝 Titel des Customizers** - Benutzerdefinierter Titel
- **🎯 Anzeige-Methode** - Wie der Customizer erkannt wird
- **🏷️ Erforderliche Tags** - Bei Tag-basierter Anzeige
- **📦 Erforderliche Collections** - Bei Collection-basierter Anzeige

## 💡 Praktische Beispiele

### Beispiel 1: Alle Paracord-Produkte
```
Anzeige-Methode: Automatisch
Produkt-Typ: "Paracord Leine"
Tag: "paracord-customizer"
```

### Beispiel 2: Nur bestimmte Collection
```
Anzeige-Methode: Nur bei bestimmten Collections
Collections: "hundehalsbaender, premium-leinen"
```

### Beispiel 3: Spezifische Tags
```
Anzeige-Methode: Nur bei bestimmten Tags
Tags: "custom, handgemacht, paracord"
```

## 🎨 Customizer anpassen

### Titel ändern:
- Im Block-Settings: "Titel des Customizers"
- Standard: "🎨 Dein Jasmin-Set konfigurieren"
- Beispiel: "🎨 Dein individuelles Paracord-Set"

### Farben anpassen:
```css
.ps-cust {
  background: #deine-farbe;
  border-color: #deine-farbe;
}
```

## 🚀 Schnellstart

### Für alle Paracord-Produkte:
1. Füge den **"Paracord Customizer"** Block hinzu
2. Setze **Anzeige-Methode** auf **"Automatisch"**
3. Füge das Tag **`paracord-customizer`** zu deinen Produkten hinzu

### Für spezifische Produkte:
1. Füge den **"Paracord Customizer"** Block hinzu
2. Setze **Anzeige-Methode** auf **"Manuell"**
3. Aktiviere den Block nur bei gewünschten Produkten

## 🔍 Debugging

### Customizer erscheint nicht:
1. Überprüfe, ob der Block aktiviert ist
2. Kontrolliere die Anzeige-Methode
3. Überprüfe Tags/Collections
4. Schaue in die Browser-Konsole auf Fehler

### Customizer erscheint bei falschen Produkten:
1. Überprüfe die Anzeige-Methode
2. Kontrolliere Tags und Collections
3. Verwende spezifischere Tags

## 📱 Mobile Optimierung

Der Customizer ist automatisch für mobile Geräte optimiert:
- **Responsive Layout** - Passt sich der Bildschirmgröße an
- **Touch-freundlich** - Große Buttons und Eingabefelder
- **Vereinfachte Ansicht** - Weniger Spalten auf kleinen Bildschirmen

## 🎯 Best Practices

1. **Konsistente Tags** - Verwende einheitliche Tag-Struktur
2. **Klare Collections** - Organisiere Produkte logisch
3. **Testen** - Überprüfe verschiedene Produkttypen
4. **Performance** - Vermeide zu viele automatische Regeln

Der Customizer ist jetzt vollständig steuerbar und erscheint nur bei den Produkten, die du auswählst! 🎉
