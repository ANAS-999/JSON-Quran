# Quran in JSON Format

![Project Banner](https://al-dirassa.com/en/wp-content/uploads/2024/11/quran-6862296_1280.jpg) <!-- Optional -->

A complete, well-structured JSON dataset of the Holy Quran with:
- Full Arabic text (Uthmani script)
- Surah names in Arabic and English
- Makki/Madani classification
- Verse-by-verse organization

## Features

- Clean JSON structure
- Uthmani script text
- Surah metadata (name, type, verse count)
- Verse-by-verse organization
- Lightweight and easy to parse

## Sample Structure

```json
[
  {
    "id": 1,
    "name": "الفاتحة",
    "name_en": "Al-Fatihah",
    "type": "meccan",
    "total_verses": 7,
    "verses": [
      "بِسۡمِ ٱللَّهِ ٱلرَّحۡمَٰنِ ٱلرَّحِيمِ",
      "ٱلۡحَمۡدُ لِلَّهِ رَبِّ ٱلۡعَٰلَمِينَ",
      "..."
    ]
  },
  ...
]
