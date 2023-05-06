# regex

Für Automatisierung oder anything else

- Dokument wurde per OCR zerlegt, Textinhalt liegt nun vor 
- Metadaten identifizieren extrahieren

bspw. Datum
```js copy
(?<!\d)(\d|0\d|1\d|2\d|3\d)[\.,]\s{0,3}(\d|0\d|1[012]|Januar|Februar|März|April|Mai|Juni|Juli|August|September|Oktober|November|Dezember)[\.,]?\s{0,3}(19\d{2}|20\d{2}|\d{2}(?!\d))
```
