# sibur2020-matching-baseline
Slightly changed baseline with improve performance and corrected regular expressions

Changes:
1. Fully used RE capabilities to substitute strings.
2. Escaping added in RE for legal entities.
3. Multithreaded Levenshtein distance calculation.

---------------

# Collection of approved external data:

| Approve | Link    | Comment |
|---------|---------|---------|
| | [gleif.org](https://www.gleif.org/en/about-lei/code-lists/iso-20275-entity-legal-forms-code-list "https://www.gleif.org/en/about-lei/code-lists/iso-20275-entity-legal-forms-code-list") | |
| ✅ | [rusvectores.org models](https://rusvectores.org/ru/models/ "https://rusvectores.org/ru/models/") | |
| ✅ | [natasha ner](http://natasha.github.io/ner "http://natasha.github.io/ner") | | 
| ❌ | [API dictionary.cambridge](https://dictionary.cambridge.org/ru/%D0%BF%D1%80%D0%BE%D1%81%D0%BC%D0%B0%D1%82%D1%80%D0%B8%D0%B2%D0%B0%D1%82%D1%8C/english/a/ "https://dictionary.cambridge.org/ru/%D0%BF%D1%80%D0%BE%D1%81%D0%BC%D0%B0%D1%82%D1%80%D0%B8%D0%B2%D0%B0%D1%82%D1%8C/english/a/") | not free |
| ✅ | [wiki legal entities](https://en.wikipedia.org/wiki/List_of_legal_entity_types_by_country "https://en.wikipedia.org/wiki/List_of_legal_entity_types_by_country") | |
| ✅ | [wiki dumps](https://dumps.wikimedia.org/ "https://dumps.wikimedia.org/") | | 
| ❌ | [YaTranslate API](https://translate.yandex.com "https://translate.yandex.com") | Limits are too tight (10,000,000 characters / month) |
