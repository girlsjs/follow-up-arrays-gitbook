## Tablice w obiektach
```javascript
let book = {
  name: 'Harry Potter',
  languages: ['en', 'ge', 'pl', 'fr', 'it']
}
```

Dobieramy się do wartości:
```javascript
book.languages[2] // 'pl'
```

### Poruszanie się
Pamiętajcie, że po tablicach wewnątrz obiektów najczęściej poruszamy się przy użyciu pętli.

Mając bardzo skomplikowane obiekty mogą powstać takie oto potworki:
```javascript
author.books.novels[17].translations[3].title
```

Dlatego czasem warto używać zmiennych po drodze:

```javascript
let novels = author.books.novels
let title = novels[17].translations[3].title
```
