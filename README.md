# Vision Language Modelle (VLM)

## Überblick
Vision Language Modelle (VLMs) verbinden visuelle Daten (Bilder oder Videos) mit sprachlichen Informationen (Text). Sie nutzen multimodale Daten, um automatisierte Beschreibungen zu generieren, z. B. für Bilder oder Karten. Dies kann die Barrierefreiheit erhöhen, indem Bild- und Kartenelemente für Menschen mit Sehbehinderungen zugänglicher gemacht werden.

## Motivation
Trotz Fortschritten in der Kartenerstellung bleibt die Zugänglichkeit von Kartenmaterial für blinde und sehbehinderte Menschen oft unzureichend. VLMs könnten durch automatisierte Bildbeschreibungen eine Lösung bieten, doch ihre Ergebnisse hängen von sorgfältigen Eingaben (Prompts) und der Nachvollziehbarkeit der Modelle ab. Letztere ist entscheidend für die Akzeptanz und das Vertrauen in diese Modelle.

## Beispiele

### Einfluss von Kartenbeschriftungen
![london_labelnolabel](https://github.com/user-attachments/assets/d001c837-2fd0-4140-aab8-f159ea9a497f)
Untersuchungen zeigen, dass VLMs Karten auch ohne Beschriftungen erkennen können. Zum Beispiel eine Karte von London im Maßstab 1:50.000, welche mit und ohne Beschriftungen und dem Prompt "What do you see?" einem VLM übergeben wurde:
- **Mit Beschriftungen:** "The image is a detailed map of London, England, showing the city's streets, landmarks, and surrounding areas."
- **Ohne Beschriftungen:** "The image displays a detailed map of London, England, showing the city's streets, landmarks, and waterways."

### Auswirkungen des Kartenmaßstabs
![scales](https://github.com/user-attachments/assets/c541a962-9be3-4ec0-a99c-924d79a97d9e)
Der Maßstab beeinflusst die Fähigkeit von VLMs, Orte zu erkennen. Beispiel: New York in verschiedenen Maßstäben:
- Maßstäbe 1:200.000 bis 1:50.000: Der Ortsname "New York" ist Teil der Beschreibungsgenerierung.
- Maßstab 1:10.000: Die Beschreibung enthält nur „a city“, ohne New York explizit zu nennen.

## Offene Fragen und Zukunftsperspektiven
Die Arbeit mit VLMs im Kontext der Kartographie wirft grundlegende Fragen auf:
- Was ist eine „gute“ Kartenbeschreibung?
- Wie kann Explainable AI die Generierung und Interpretation von VLM-Beschreibungen verbessern?
- Welche Rolle spielen Kartenlabels, Maßstab und Nutzereingaben auf die Ergebnisse?

## Weitere Informationen
Die präsentierten Daten und weitere Informationen sind (hier) auf GitHub verfügbar: [GitHub Repository](https://github.com/grndng/NIAM2025).

## Über uns
Wir sind das Labor für Geoinformatik und Geovisualisierung, **g2lab** ([g2lab.net](http://www.geomatik-hamburg.de/g2lab/), der HafenCity Universität Hamburg. Unsere Arbeit konzentriert sich auf die Visualisierung spatiotemporaler Daten, um Entscheidungsprozesse zu unterstützen. Darüber hinaus beschäftigen wir uns damit, Unsicherheiten mit dem zu modellieren, Nutzer:innen bessere Entscheidungsgrundlagen zur Verfügung zu stellen. Darüber beschäftigt sich die [CartoAI Kommission der DGfK](https://dgfk.net/kommission/commission-on-cartography-and-artificial-intelligence/) ausgiebig mit dem Thema "Karten und KI".
