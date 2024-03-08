# JSON-Übung

Ich möchte meinen privaten Bibliothekskatalog von XML zu JSON konvertieren. Kannst du mir dabei helfen?

## 1. Fork erstellen

Forke dieses Repository mit dem `Fork`-Button oben rechts. Dafür musst du eingeloggt sein.

## 2. Buch auswählen

**In deinem geforkten Repository**, wähle ein Buch aus dem Ordner `library` aus und sieh dir die **XML-Datei** an (z.B. `kafka-urteil.xml`).

## 3. JSON-Datei ergänzen

Öffne die zugehörige **JSON-Datei** (z.B. `kafka-urteil.json`) in einem zweiten Browser-Fenster. Konvertiere das XML-Dokument in ein JSON-Objekt nach dem folgenden Muster:

```json
{
    "author": {
        "firstName": "Franz",
        "lastName": "Kafka"
    },
    "title": "Das Urteil",
    "publicationYear": 1913,
    "hardcover": true,
    "keywords": ["Vater", "Sohn", "Konflikt"]
}
```

## 4. Pull Request erstellen

Erstelle einen Pull Request auf den `main`-Branch des ursprünglichen Repositorys.
