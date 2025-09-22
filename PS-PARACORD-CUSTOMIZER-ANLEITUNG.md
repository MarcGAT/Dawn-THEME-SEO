# PS Paracord Customizer - Integrationsanleitung

## Übersicht
Der PS Paracord Customizer ermöglicht es Kunden, ihre Paracord-Leinen und Halsbänder zu konfigurieren. Die ausgewählten Optionen werden als Line Item Properties an Shopify übermittelt und im Warenkorb angezeigt.

## Dateien
- `snippets/ps-paracord-customizer.liquid` - Hauptcustomizer
- `snippets/ps-cart-item-properties.liquid` - Verbesserte Warenkorb-Anzeige

## Integration in Product Template

### Option 1: Als Custom Liquid Block
1. Gehe zu deinem Product Template
2. Füge einen "Custom Liquid" Block hinzu
3. Füge folgenden Code ein:

```liquid
{% render 'ps-paracord-customizer' %}
```

### Option 2: Direkt in main-product.liquid
Füge den Render-Aufruf vor den Buy Buttons ein:

```liquid
{%- when 'paracord_customizer' -%}
  {% render 'ps-paracord-customizer' %}
```

## Funktionsweise

### Customizer Features
- **Längenauswahl**: 1,5m, 2,0m, 3,0m
- **Karabiner**: Schwarz-Stahl, Silber-Stahl, Gold-Messing
- **Farbschema**: Jasmin (Standard), Jasmin dunkel, Eigenes Schema
- **Halsband-Größen**: XS bis XL
- **Gravur**: Name und Telefon (optional)
- **Hinweise**: Freitext für Sonderwünsche

### Warenkorb-Integration
Die ausgewählten Optionen werden automatisch als Line Item Properties übermittelt:
- `properties[Leinenlänge]`
- `properties[Karabiner]`
- `properties[Farbschema]`
- `properties[Halsband-Größe]`
- `properties[Gravur Name]`
- `properties[Gravur Telefon]`
- `properties[Hinweise]`

### Verbesserte Warenkorb-Anzeige
Das neue `ps-cart-item-properties.liquid` Snippet zeigt die Customizer-Optionen mit:
- Emojis für bessere Erkennbarkeit
- Strukturierte Darstellung
- Spezielle Formatierung für Hinweise

## Automatische Integration
Der Customizer wird automatisch in das Add-to-Cart-Formular integriert und:
- Funktioniert mit Dawn Theme's `<product-form>` Struktur
- Reagiert auf Shopify Section Updates
- Zeigt Live-Preview der Auswahl
- Übermittelt Daten korrekt an Shopify

## CSS-Styling
Der Customizer enthält eingebettete Styles für:
- Moderne Card-Darstellung
- Responsive Grid-Layout
- Konsistente Formular-Elemente
- Mobile Optimierung

## Browser-Kompatibilität
- Moderne Browser (Chrome, Firefox, Safari, Edge)
- ES6+ Features (Optional Chaining)
- Graceful Degradation für ältere Browser

## Troubleshooting

### Customizer erscheint nicht
1. Stelle sicher, dass das Snippet korrekt gerendert wird
2. Überprüfe die Browser-Konsole auf JavaScript-Fehler
3. Teste mit verschiedenen Product Templates

### Optionen werden nicht übertragen
1. Überprüfe, ob der Customizer im `<form>` Element steht
2. Teste die Form-Submission in den Entwicklertools
3. Überprüfe die Network-Tab für Cart-API-Calls

### Warenkorb zeigt keine Optionen
1. Stelle sicher, dass `ps-cart-item-properties.liquid` verwendet wird
2. Überprüfe, ob Line Item Properties korrekt übermittelt werden
3. Teste mit verschiedenen Cart-Templates

## Anpassungen

### Neue Optionen hinzufügen
1. Füge das HTML-Element im Customizer hinzu
2. Erweitere die JavaScript-Event-Listener
3. Füge die Property-Anzeige im Cart-Snippet hinzu

### Styling anpassen
- Ändere die CSS-Regeln im Customizer
- Passe das `ps-cart-item-properties.liquid` Styling an
- Nutze CSS-Variablen für konsistente Farben

## Support
Bei Problemen oder Fragen zur Integration, überprüfe:
1. Browser-Konsole auf Fehler
2. Shopify Theme-Editor Logs
3. Cart API Responses in den Entwicklertools




