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
| | https://www.gleif.org/en/about-lei/code-lists/iso-20275-entity-legal-forms-code-list | |
| ✅ | https://rusvectores.org/ru/models/ | |
| ✅ | http://natasha.github.io/ner | | 
| ❌ | API https://dictionary.cambridge.org/ru/%D0%BF%D1%80%D0%BE%D1%81%D0%BC%D0%B0%D1%82%D1%80%D0%B8%D0%B2%D0%B0%D1%82%D1%8C/english/a/ | not free |
| ✅ | https://en.wikipedia.org/wiki/List_of_legal_entity_types_by_country | |
| ✅ | https://dumps.wikimedia.org/ | | 
| ❌ | API https://translate.yandex.com | Limits are too tight (10,000,000 characters / month) |
